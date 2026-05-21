---
permalink: /projects/bitcoin-prediction/
title: "Predicting Bitcoin Price Volatility"
excerpt: "A machine learning project using order-book features to predict Bitcoin price volatility."
author_profile: true
---

{% include project-styles.html %}

<main class="project-detail-page">
  <p class="project-back"><a href="/projects/">← Projects</a></p>
  <header class="project-hero">
    <p class="project-kicker">Data Science · 2022</p>
    <h1>Predicting Bitcoin Price Volatility</h1>
    <p class="project-summary">A machine learning project using order-book features to predict Bitcoin price volatility.</p>
  </header>

  <div class="project-body">
<section class="project-section">
<p>Bitcoin and cryptocurrency have been hot topics these years due to the rapid growth of the market value. Due to the lack of regulation, the market of cryptocurrency is very volatile and risky for investors. This project aims to construct a systematic way to <strong>predict the volatility of the Bitcoin market through the microstructure of the market.</strong> The data source is a high-frequency orderbook, which is a snapshot of all the orders listed on the exchange, and they're collected from Tardis, a major cryptocurrency data collector. Various machine learning models and features will be investigated and their performance will be evaluated by different metrics as well.</p>
</section>

<section class="project-section">
<p><strong>Team</strong></p><p>Xin Ye, Chongdan Pan, Fangzhe Li</p><p><strong>Exhibition</strong></p><p>@ Umich 2022 School of Information Design Expo</p>
</section>

<section class="project-section">
<p><strong>Duration</strong></p><p>Nov 2022 - Dec 2020 (2 mo)</p><p><strong>Methods</strong></p><p>Garch model; Ridge regression; Feature engineering; PCA; XGBoost; LSTM</p>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-01.jpg" alt="Predicting Bitcoin Price Volatility project visual 1">
</figure>

<section class="project-section">
<h3><strong>Objective</strong></h3><h3>This project aims to use the bid price and ask price provided in orderbook, explored new predictors with feature engineering, applied different models to predict the volatility of Bitcoin.</h3><h3><strong>Introduction</strong></h3><h2><strong>Order book</strong></h2>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-02.png" alt="Predicting Bitcoin Price Volatility project visual 2">
</figure>

<section class="project-section">
<h3><strong>Datasets</strong></h3><h2><strong>The orderbook data from Tardis.&nbsp;</strong></h2><h3>Training set:&nbsp; every 30 seconds from August 1st, 2022 to October 8th, 2022.&nbsp;</h3><h3>Testing set: every 30 seconds from October 9th, 2022 to October 31st, 2022.&nbsp;</h3><ul><li><p><strong>our train and test data have gone through different market conditions such as an extremely high peak in volatility.</strong></p></li></ul><h3>21 fields as raw features: Timestamp, Ask price, Ask volume, Bid price, Bid volume</h3>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-03.png" alt="Predicting Bitcoin Price Volatility project visual 3">
</figure>

<section class="project-section">
<h3><strong>Preprocessing</strong></h3><h2><strong><em>A.</em>Resample the orderbook and chose 30 seconds as length.</strong></h2><p><strong>Orderbook is not aligned with a specific frequency since people may post trade at any time.</strong></p><h2><strong><em>B.</em>Build volatility: the standard deviation of return within a specific time interval.</strong></h2><p><strong>The volatility is calculated in different time horizons because the return within 30 seconds is too noisy and they usually follow a random walk. We cut the price of Bitcoin by every minute and calculate the return. we scale it by 100 times and group the return by every 30 minutes and calculate the standard deviation as our label.</strong></p><h2><strong><em>C.</em>EDA of volatility</strong></h2>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-04.png" alt="Predicting Bitcoin Price Volatility project visual 4">
</figure>

<section class="project-section">
<h3><strong>Results</strong></h3>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-05.png" alt="Predicting Bitcoin Price Volatility project visual 5">
</figure>

<section class="project-section">
<h2><strong>Baseline: Garch model</strong></h2><p>Generalized AutoRegressive Conditional Heteroskedasticity(GARCH) is a statistical model which typically used to predicate the volatility based on the historical return. </p>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-06.jpg" alt="Predicting Bitcoin Price Volatility project visual 6">
</figure>

<section class="project-section">
<ul><li><pre><code>Good at predicting the peak of the volatility thanks to its assumption of volatility clustering;</code></pre></li><li><pre><code>Lower bound is too high, leading to a high error.</code></pre></li></ul><h2><strong>Ridge with raw order book feature</strong></h2>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-07.png" alt="Predicting Bitcoin Price Volatility project visual 7">
</figure>

<section class="project-section">
<ul><li><pre><code>Achieve a better result than Garch even though it can’t capture the high volatility.&nbsp;</code></pre></li></ul><ul><li><pre><code>Its supremacy implies that the orderbook’s features contain a lot of information for prediction.</code></pre><h2></h2></li></ul><h2><strong>Ridge with PCA and new features</strong></h2><p><strong>Feature Construction</strong></p><ul><li><p><strong>Mid price: The average between the ask price 1 and bid price 1.&nbsp;</strong></p></li></ul><ul><li><p><strong>Spread: The difference between the ask price and bid price and normalized by the mid price.&nbsp;</strong></p></li><li><p><strong>Weighted Spread: Use the volume of each price as the weight to price to get the weighted difference between the ask price and bid price and normalized by the mid price.&nbsp;</strong></p></li><li><p><strong>Volume Spread: The difference between the ask volume 1 and bid volume 1 and normalized by the sum of ask volume 1 and bid volume 1.&nbsp;</strong></p></li><li><p><strong>Weighted Mid price: the weighted average ask prices and bid prices.&nbsp;</strong></p></li></ul><p><strong>Also,</strong></p><ul><li><p><strong>Dimension reduction through PCA to prevent overfitting;</strong></p></li><li><p><strong>Feature Normalization;</strong></p></li></ul>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-08.png" alt="Predicting Bitcoin Price Volatility project visual 8">
</figure>

<section class="project-section">
<ul><li><pre><code>Best performance;</code></pre></li><li><pre><code>A less wrong prediction of peak;</code></pre></li><li><pre><code>Normal prediction is closer to the labels.
</code></pre></li></ul><h2><strong>XGBoost</strong></h2><p>We’re interested in the XGBoost tree model as well because it can give metrics of feature importance. In addition, it helps us to interpret the data and model better since we’re able to plot the structure of the model. </p>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-09.png" alt="Predicting Bitcoin Price Volatility project visual 9">
</figure>

<section class="project-section">
<p>Surprisingly, XGBoost can’t achieve an ideal performance for prediction even though its ensemble methods are famous for solving underfitting. The worse performance implies that XGBoost is overfitting here, and our best model is actually able to exploit all linear information within the features we have. </p>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-10.png" alt="Predicting Bitcoin Price Volatility project visual 10">
</figure>

<section class="project-section">
<h2><strong>LSTM</strong></h2>
</section>

<figure class="project-figure">
  <img src="/images/projects/bitcoin-prediction-11.png" alt="Predicting Bitcoin Price Volatility project visual 11">
</figure>

<section class="project-section">
<h3><strong>Discussion</strong></h3><ul><li><h2><strong>Almost all our models can beat the baseline, which shows that with the information included in the orderbook, we can easily beat the prediction of the baseline model only based on return rate information.&nbsp;</strong></h2></li><li><h2><strong>Only the Garch model can successfully predict the volatility peak, in the future, we may use the output of the Garch’s prediction as another feature.</strong></h2></li><li><h2><strong>Ridge regression model with more features gives the best performance.</strong></h2></li><li><h2><strong>Spread and weighted mid price plays a significant role in volatility,&nbsp;implying the liquidity and momentum effect in the microstructure of the market.</strong></h2></li></ul><h3><strong>References</strong></h3><p>[1] Guo, T., &amp; Antulov-Fantulin, N. (2018). Predicting short-term Bitcoin price fluctuations from buy and sell orders. arXiv preprint arXiv:1802.04065. </p><p>[2] Guo, T., Bifet, A., &amp; Antulov-Fantulin, N. (2018, November). Bitcoin volatility forecasting with a glimpse into buy and sell orders. In 2018 IEEE international conference on data mining (ICDM) (pp. 989-994). IEEE. </p><p>[3] Rathan, K., Sai, S. V., &amp; Manikanta, T. S. (2019, April). Crypto-currency price prediction using decision tree and regression techniques. In 2019 3rd International Conference on Trends in Electronics and Informatics (ICOEI) (pp. 190-194). IEEE. </p><p>[4] Tsai, Wei-Tek, R. Blower, Y. Zhu and L. Yu, “A system view of financial blockchains,” in 2016 IEEE Symposium on, 2016. </p><p>[5] J. Chu, C. Stephen, N. Saralees and O. Joerg, “GARCH Modelling of Cryptocurrencies,” Journal of Risk and Financial Management, vol. 10, no. 4, p. 17, 2017. </p><p>[6] Peter R. Hansen and Asger Lunde. 2005. A forecast comparison of volatility models: does anything beat a GARCH(1, 1)? Journal of Applied Econometrics 20, 7 (2005), 873–889</p>
</section>
  </div>
</main>
