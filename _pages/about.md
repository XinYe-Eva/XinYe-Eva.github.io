---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hello and welcome! I’m **Xin**, a fourth-year Ph.D. student at the
<a href="https://www.si.umich.edu" target="_blank" style="color:#2f80ed; font-weight:600;">University of Michigan School of Information</a> 
advised by 
<a href="https://www.si.umich.edu/people/lionel-robert" target="_blank" style="color:#2f80ed; font-weight:600;">Prof. Lionel Robert</a>.

My research focuses on 
<span style="color:#ff8c00; font-weight:700;">robots deployed in public security and law enforcement</span>, 
exploring how people perceive, respond to, and interact with 
<span style="color:#00a6d6; font-weight:700;">security robots</span>, 
and how these systems can be designed and deployed in service of the 
<span style="color:#00a878; font-weight:700;">public good</span>.

My work has been published or accepted in premier conferences and journals, such as Science Robotics, International Journal of Human-Computer Interaction, ACM Transactions on Human-Robot Interaction, the ACM/IEEE International Conference on Human-Robot Interaction (HRI), the IEEE International Conference on Robot and Human Interactive Communication (RO-MAN), and the Human Factors and Ergonomics Society Annual Meeting (HFES). Prior to my Ph.D., I earned an M.S. in Information Science from the University of Michigan and a B.S. in Psychology from Zhejiang University.

# 🔥 News

- *Aug 20, 2026*: My paper “Mitigating Human–Security Robot Conflict through Fairness” has been accepted by the International Journal of Human-Computer Interaction!
- *Aug 1, 2026*: My paper “Trusting Security Robotic Authority: The Impact of Interactional and Distributive Fairness” was accepted and published online in the Proceedings of the Human Factors and Ergonomics Society Annual Meeting. I will attend ASPIRE 2026, the HFES 70th International Annual Meeting, in Reno, Nevada this October.
- *Dec 22, 2025*: My paper “The Roles of Fairness and Effectiveness in Promoting Legitimacy and Cooperation with Security Robotic Authority” has been accepted as a full paper at HRI 2026 (23% acceptance rate)!&nbsp;🎉🎉 

# 📝 Selected Publications
<div class="pub-filter">
  <button class="filter-btn active" onclick="filterPubs('all', event)">All</button>
  <button class="filter-btn" onclick="filterPubs('security', event)">Security Robots</button>
  <button class="filter-btn" onclick="filterPubs('power-authority', event)">Social Power & Authority</button>
  <button class="filter-btn" onclick="filterPubs('trust-acceptance', event)">Trust & Acceptance</button>
  <button class="filter-btn" onclick="filterPubs('ethics', event)">Ethics & Society</button>
  <button class="filter-btn" onclick="filterPubs('review', event)">Literature Review</button>
  <button class="filter-btn" onclick="filterPubs('Embodiment', event)">Embodiment</button>
</div>

<div class="publication-list">

  <div class="publication-card" data-keywords="review Embodiment">
    <div class="publication-image">
      <img src="/images/publications/science-robotics-embodiment.png" alt="Science Robotics embodiment debate paper thumbnail">
    </div>
    <div class="publication-content">
      <p class="pub-title">
        Embodied or Virtually Represented: Navigating the Embodiment Debate in Human-Robot Interaction
      </p>
      <p class="pub-authors">
        Connor Esterwood, <strong>Xin Ye</strong>, Ruijia Guan, Lionel Robert
      </p>
      <p class="pub-venue">
        Science Robotics
      </p>
      <p class="pub-links">
        <a href="https://www.science.org/doi/10.1126/scirobotics.aed4569" target="_blank">paper</a>
      </p>
      <p class="pub-tags">
        <span>Literature Review</span>
        <span>Embodiment</span>
        <span>Journal (JCR-Q1)</span>
        <span>Impact Factor: 27.5</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="security power-authority">
    <div class="publication-image publication-image--contain">
      <img src="/images/publications/hri-2026-legitimacy.png" alt="HRI 2026 legitimacy and cooperation paper thumbnail">
    </div>
    <div class="publication-content">
      <p class="pub-title">
        The Roles of Fairness and Effectiveness in Promoting Legitimacy and Cooperation with Security Robotic Authority
      </p>
      <p class="pub-authors">
        <strong>Xin Ye</strong>, Lionel P. Robert
      </p>
      <p class="pub-venue">
        ACM/IEEE International Conference on Human-Robot Interaction, 2026
      </p>
      <p class="pub-links">
        <a href="/paper/YeandRobert_HRI2026.pdf" target="_blank">pdf</a>
        <a href="https://dl.acm.org/doi/abs/10.1145/3757279.3788657" target="_blank">paper</a>
      </p>
      <p class="pub-tags">
        <span>Security Robots</span>
        <span>Social Power & Authority</span>
        <span>Cooperation</span>
        <span>HRI 2026 Full Paper</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="security power-authority trust-acceptance">
    <div class="publication-image">
      <img src="/images/publications/hfes-2025-rewarding-trust.jpg" alt="HFES 2025 rewarding trust paper thumbnail">
    </div>
    <div class="publication-content">
      <p class="pub-title">
        Rewarding Trust: How Reward Power Shapes Security Robot Acceptance
      </p>
      <p class="pub-authors">
        <strong>Xin Ye</strong>, Lionel P. Robert
      </p>
      <p class="pub-venue">
        Human Factors and Ergonomics Society Annual Meeting, 2025
      </p>
      <p class="pub-links">
        <a href="/paper/YeandRobert_HFES2025.pdf" target="_blank">pdf</a>
        <a href="https://journals.sagepub.com/eprint/X3ZN9SE7DEFE2GWHHQYT/full" target="_blank">paper</a>
      </p>
      <p class="pub-tags">
        <span>Security Robots</span>
        <span>Social Power & Authority</span>
        <span>Trust & Acceptance</span>
        <span>HFES 2025 Full Paper</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="security review ethics Embodiment">
    <div class="publication-image video-thumb">
      <a href="https://www.youtube.com/watch?v=3HSez3aA41E" target="_blank" aria-label="Play RO-MAN 2025 presentation video">
        <img src="/images/publications/roman-2025-security-review.webp" alt="RO-MAN 2025 paper video thumbnail">
        <span class="play-button">▶</span>
      </a>
    </div>
    <div class="publication-content">
      <p class="pub-title">
        Can Robots Take Over Security? A Brief Review and Critique of Security Robot vs. Human Security Agent
      </p>
      <p class="pub-authors">
        <strong>Xin Ye</strong>, Lionel P. Robert
      </p>
      <p class="pub-venue">
        IEEE International Conference on Robot and Human Interactive Communication, 2025
      </p>
      <p class="pub-links">
        <a href="/paper/YeandRobert_ROMAN25.pdf" target="_blank">pdf</a>
        <a href="https://ieeexplore.ieee.org/document/11217535" target="_blank">paper</a>
        <a href="https://www.youtube.com/watch?v=3HSez3aA41E" target="_blank">video</a>
      </p>
      <p class="pub-tags">
        <span>Security Robots</span>
        <span>Literature Review</span>
        <span>Ethics & Society</span>
        <span>Embodiment</span>
        <span>RO-MAN 2025 Full Paper</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="security power-authority trust-acceptance">
    <div class="publication-image video-thumb">
      <a href="https://www.youtube.com/watch?v=WzFGUtOma78" target="_blank" aria-label="Play HRI 2025 presentation video">
        <img src="/images/publications/hri-2025-power.jpg" alt="HRI 2025 paper video thumbnail">
        <span class="play-button">▶</span>
      </a>
    </div>
    <div class="publication-content">
      <p class="pub-title">
        Security Robot Power and Acceptance: Exploring French and Raven’s Five Forms of Power
      </p>
      <p class="pub-authors">
        <strong>Xin Ye</strong>, Lionel P. Robert
      </p>
      <p class="pub-venue">
        ACM/IEEE International Conference on Human-Robot Interaction, 2025
        <span class="award">🎖️ Honorable Mention Award</span>
      </p>
      <p class="pub-links">
        <a href="/paper/YeandRobert_HRI2025.pdf" target="_blank">pdf</a>
        <a href="https://dl.acm.org/doi/10.5555/3721488.3721754" target="_blank">paper</a>
        <a href="/paper/HRILBR2025poster.pdf" target="_blank">poster</a>
        <a href="https://www.youtube.com/watch?v=WzFGUtOma78" target="_blank">video</a>
      </p>
      <p class="pub-tags">
        <span>Security Robots</span>
        <span>Social Power & Authority</span>
        <span>Trust & Acceptance</span>
        <span>HRI 2025 Late Breaking Report</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="security review">
    <div class="publication-image publication-image--contain">
      <img src="/images/publications/thri-literature-review.webp" alt="THRI literature review thumbnail">
    </div>
    <div class="publication-content">
      <p class="pub-title">
        A Human–Security Robot Interaction Literature Review
      </p>
      <p class="pub-authors">
        <strong>Xin Ye</strong>, Lionel P. Robert
      </p>
      <p class="pub-venue">
        ACM Transactions on Human-Robot Interaction
      </p>
      <p class="pub-links">
        <a href="/paper/YeandRobert_THRI2024.pdf" target="_blank">pdf</a>
        <a href="https://dl.acm.org/doi/full/10.1145/3700888" target="_blank">paper</a>
      </p>
      <p class="pub-tags">
        <span>Security Robots</span>
        <span>Literature Review</span>
        <span>Journal (JCR-Q1)</span>
        <span>Impact Factor: 5.5</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="security review ethics">
    <div class="publication-image video-thumb">
      <a href="https://www.youtube.com/watch?v=UimgZzX-tCA" target="_blank" aria-label="Play AMCIS 2024 presentation video">
        <img src="/images/publications/amcis-2024-gender.jpg" alt="AMCIS 2024 gender and security robot video thumbnail">
        <span class="play-button">▶</span>
      </a>
    </div>
    <div class="publication-content">
      <p class="pub-title">
        Gender and Security Robot Interactions: A Brief Review and Critique
      </p>
      <p class="pub-authors">
        <strong>Xin Ye</strong>, Samia Cornelius Bhatti, Lionel P. Robert
      </p>
      <p class="pub-venue">
        Americas Conference on Information Systems, 2024
        <span class="award">🎖️ Best Paper Nominee</span>
      </p>
      <p class="pub-links">
        <a href="/paper/YeandRobert_AMCIS2024.pdf" target="_blank">pdf</a>
        <a href="https://aisel.aisnet.org/amcis2024/soc_inclusion/social_inclusion/7/" target="_blank">paper</a>
        <a href="https://www.youtube.com/watch?v=UimgZzX-tCA" target="_blank">video</a>
      </p>
      <p class="pub-tags">
        <span>Security Robots</span>
        <span>Literature Review</span>
        <span>Ethics & Society</span>
        <span>AMCIS 2024 Full Paper</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="security trust-acceptance">
    <div class="publication-image publication-image--contain">
      <img src="/images/publications/hri-2024-aam.webp" alt="HRI 2024 AAM thumbnail">
    </div>
    <div class="publication-content">
      <p class="pub-title">
        Autonomy Acceptance Model (AAM): The Role of Autonomy and Risk in Security Robot Acceptance
      </p>
      <p class="pub-authors">
        <strong>Xin Ye</strong>, Wonse Jo, Arsha Ali, Samia C. Bhatti, Connor Esterwood, Hana A. Kassie, Lionel P. Robert
      </p>
      <p class="pub-venue">
        ACM/IEEE International Conference on Human-Robot Interaction, 2024
      </p>
      <p class="pub-links">
        <a href="/paper/YeandRobert_HRI2024.pdf" target="_blank">pdf</a>
        <a href="https://dl.acm.org/doi/abs/10.1145/3610977.3635005" target="_blank">paper</a>
      </p>
      <p class="pub-tags">
        <span>Security Robots</span>
        <span>Trust & Acceptance</span>
        <span>HRI 2024 Full Paper</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="security Embodiment trust-acceptance">
    <div class="publication-image video-thumb">
      <a href="https://www.youtube.com/watch?v=o-bF-nZcpK0" target="_blank" aria-label="Play RO-MAN 2023 presentation video">
        <img src="/images/publications/roman-2023-anthropomorphism.jpg" alt="RO-MAN 2023 anthropomorphism video thumbnail">
        <span class="play-button">▶</span>
      </a>
    </div>
    <div class="publication-content">
      <p class="pub-title">
        Human Security Robot Interaction and Anthropomorphism: An Examination of Pepper, RAMSEE, and Knightscope Robots
      </p>
      <p class="pub-authors">
        <strong>Xin Ye</strong>, Lionel P. Robert Jr.
      </p>
      <p class="pub-venue">
        IEEE International Conference on Robot and Human Interactive Communication, 2023
      </p>
      <p class="pub-links">
        <a href="/paper/YeandRobert_ROMAN2023.pdf" target="_blank">pdf</a>
        <a href="https://ieeexplore.ieee.org/document/10309400" target="_blank">paper</a>
        <a href="https://www.youtube.com/watch?v=o-bF-nZcpK0" target="_blank">video</a>
      </p>
      <p class="pub-tags">
        <span>Security Robots</span>
        <span>Embodiment</span>
        <span>Anthropomorphism</span>
        <span>RO-MAN 2023 Full Paper</span>
      </p>
    </div>
  </div>

  <div class="publication-card" data-keywords="ethics">
    <div class="publication-image">
      <img src="/images/publications/hri-2026-intimacy.png" alt="HRI 2026 AI companion intimacy paper thumbnail">
    </div>
    <div class="publication-content">
      <p class="pub-title">
        The Imitation of Intimacy: Comparing Satisfaction in Intimate Human and AI Companion Relationships
      </p>
      <p class="pub-authors">
        A. Masterson, <strong>Xin Ye</strong>, Y. Li, Lionel Robert
      </p>
      <p class="pub-venue">
        ACM/IEEE International Conference on Human-Robot Interaction, 2026
      </p>
      <p class="pub-links">
        <a href="/paper/Annette_HRI2026.pdf" target="_blank">pdf</a>
        <a href="https://dl.acm.org/doi/10.1145/3776734.3794515" target="_blank">paper</a>
        <a href="/paper/HRILBR2026poster.pdf" target="_blank">poster</a>
      </p>
      <p class="pub-tags">
        <span>AI Companions</span>
        <span>Ethics & Society</span>
        <span>HRI 2026 Late Breaking Report</span>
      </p>
    </div>
  </div>

</div>


<style>
.pub-filter {
  margin: 1rem 0 1.5rem 0;
}

.filter-btn {
  border: 1px solid #d0d7de;
  background: #ffffff;
  color: #333;
  padding: 6px 12px;
  margin: 4px 5px 4px 0;
  border-radius: 18px;
  font-size: 0.85rem;
  cursor: pointer;
  transition: all 0.2s ease;
}

.filter-btn:hover {
  background: #f2f6ff;
  border-color: #2f80ed;
  color: #2f80ed;
}

.filter-btn.active {
  background: #2f80ed;
  color: #ffffff;
  border-color: #2f80ed;
}

.publication-card {
  display: flex;
  gap: 24px;
  margin-bottom: 2rem;
  padding-bottom: 1.7rem;
  border-bottom: 1px solid #eeeeee;
  align-items: flex-start;
}

.publication-image {
  flex: 0 0 240px;
  max-width: 100%;
}

.publication-image img,
.publication-image--placeholder {
  width: 100%;
  aspect-ratio: 16 / 9;
  border-radius: 8px;
  border: 1px solid #e5e5e5;
  background: #ffffff;
  box-sizing: border-box;
}

.publication-image img {
  display: block;
  height: auto;
  object-fit: cover;
}

.publication-image--contain img {
  object-fit: contain;
  padding: 6px;
}

.publication-image--placeholder {
  display: flex;
  align-items: center;
  justify-content: center;
  color: #7a7a7a;
  font-size: 0.78rem;
  text-align: center;
  padding: 0 14px;
}

.publication-content {
  flex: 1;
}

.pub-title {
  font-weight: 700;
  margin-bottom: 0.25rem;
  color: #222;
}

.pub-authors {
  margin-bottom: 0.25rem;
  color: #444;
}

.pub-venue {
  margin-bottom: 0.35rem;
  color: #666;
  font-style: italic;
}

.pub-links {
  margin-bottom: 0.4rem;
}

.pub-links a,
.pub-link-missing {
  display: inline-block;
  margin-right: 8px;
  color: #2f80ed;
  font-weight: 600;
  text-decoration: none;
}

.pub-link-missing {
  color: #9aa0a6;
  cursor: default;
}

.pub-links a::before,
.pub-link-missing::before {
  content: "[ ";
  color: #777;
  font-weight: 400;
}

.pub-links a::after,
.pub-link-missing::after {
  content: " ]";
  color: #777;
  font-weight: 400;
}

.pub-links a:hover {
  text-decoration: underline;
}

.pub-tags span {
  display: inline-block;
  background: #f2f6ff;
  color: #2f80ed;
  padding: 3px 8px;
  margin: 2px 4px 2px 0;
  border-radius: 12px;
  font-size: 0.75rem;
}

.award {
  display: inline-block;
  margin-left: 6px;
  color: #b26a00;
  font-style: normal;
  font-weight: 600;
}

.grant-amount {
  white-space: nowrap;
}

.money-sign::before {
  content: "$";
}

.publication-image.video-thumb {
  position: relative;
}

.publication-image.video-thumb a {
  display: block;
  position: relative;
}

.play-button {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: rgba(0, 0, 0, 0.58);
  color: white;
  width: 42px;
  height: 42px;
  border-radius: 50%;
  text-align: center;
  line-height: 42px;
  font-size: 18px;
  padding-left: 2px;
}

@media screen and (max-width: 600px) {
  .publication-card {
    flex-direction: column;
    gap: 12px;
  }

  .publication-image {
    flex: none;
    width: 100%;
  }
}

</style>

<script>
function filterPubs(keyword, event) {
  var pubs = document.getElementsByClassName("publication-card");
  var buttons = document.getElementsByClassName("filter-btn");

  for (var i = 0; i < buttons.length; i++) {
    buttons[i].classList.remove("active");
  }

  event.target.classList.add("active");

  for (var j = 0; j < pubs.length; j++) {
    var keywords = pubs[j].getAttribute("data-keywords");

    if (keyword === "all" || keywords.includes(keyword)) {
      pubs[j].style.display = "flex";
    } else {
      pubs[j].style.display = "none";
    }
  }
}
</script>


# 🎖 Honors and Awards

- *03/2025*: [Best Late Breaking Report Award, Honorable Mention](https://humanrobotinteraction.org/2025/awards/), ACM/IEEE International Conference on Human-Robot Interaction.
- *08/2024*: [Top 25% Paper, Winner](https://aisel.aisnet.org/amcis2024/awards.html), Americas Conference on Information Systems.
- *08/2024*: [Best Paper Award, Nominated](https://aisel.aisnet.org/amcis2024/awards.html), Americas Conference on Information Systems.
- *06/2024*: Ph.D. Pre-candidacy Paper Passed with Distinction, University of Michigan.
- *2023, 2024, 2025*: School of Information Travel Grant, <span class="grant-amount"><span class="money-sign"></span>1,500</span>.
- *2023, 2024, 2025*: Rackham Conference Travel Grant, <span class="grant-amount"><span class="money-sign"></span>900 and <span class="money-sign"></span>1,100</span>.
- *02/2024*: Rackham Pre-candidate Research Grant, <span class="grant-amount"><span class="money-sign"></span>1,500</span>, University of Michigan.
- *09/2022*: School of Information Master Student Research Grant, <span class="grant-amount"><span class="money-sign"></span>1,500</span>.


# 📖 Education

- *2023 - Present*, Ph.D. in Information, University of Michigan.
- *2021 - 2023*, M.S. in Information Science, Data Science and Big Data Analytics, University of Michigan.
- *2017 - 2021*, B.S. in Psychology, Zhejiang University.
