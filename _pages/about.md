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

Hello and welcome! I’m **Xin**, a third-year Ph.D. student at the 
<a href="https://www.si.umich.edu" target="_blank" style="color:#2f80ed; font-weight:600;">University of Michigan School of Information</a> 
advised by 
<a href="https://www.si.umich.edu/people/lionel-robert" target="_blank" style="color:#2f80ed; font-weight:600;">Prof. Lionel Robert</a>.

My research focuses on 
<span style="color:#ff8c00; font-weight:700;">robots deployed in public security and law enforcement</span>, 
exploring how people perceive, respond to, and interact with 
<span style="color:#00a6d6; font-weight:700;">security robots</span>, 
and how these systems can be designed and deployed in service of the 
<span style="color:#00a878; font-weight:700;">public good</span>.

My work has been published in premier conferences and journals, such as ACM Transactions on Human-Robot Interaction, the ACM/IEEE International Conference on Human-Robot Interaction (HRI), the IEEE International Conference on Robot and Human Interactive Communication (RO-MAN), and the Human Factors and Ergonomics Society Annual Meeting (HFES). Prior to my Ph.D., I earned an M.S. in Information Science from the University of Michigan and a B.S. in Psychology from Zhejiang University.

# 🔥 News

- *Dec 22, 2025*: My paper “The Roles of Fairness and Effectiveness in Promoting Legitimacy and Cooperation with Security Robotic Authority” has been accepted as a full paper at HRI 2026 (23% acceptance rate)!&nbsp;🎉🎉 
- *Oct 13, 2025*: Attended the 69th Human Factors and Ergonomics Society Annual Meeting (HFES 2025) in Chicago, IL and presented my paper “Rewarding Trust: How Reward Power Shapes Security Robot Acceptance”.
- *Aug 29, 2025*: Attended the IEEE International Conference on Robot and Human Interactive Communication (RO-MAN 2025) in Eindhoven, Netherlands and presented my paper “Can Robots Take Over Security? A Brief Review and Critique of Security Robot vs. Human Security Agent”. 🤖👮

# 📝 Publications

<div class="pub-filter">
  <button class="filter-btn active" onclick="filterPubs('all', event)">All</button>
  <button class="filter-btn" onclick="filterPubs('security', event)">Security Robots</button>
  <button class="filter-btn" onclick="filterPubs('hri', event)">Human–Robot Interaction</button>
  <button class="filter-btn" onclick="filterPubs('trust', event)">Trust & Acceptance</button>
  <button class="filter-btn" onclick="filterPubs('power', event)">Power</button>
  <button class="filter-btn" onclick="filterPubs('review', event)">Review</button>
  <button class="filter-btn" onclick="filterPubs('gender', event)">Gender</button>
  <button class="filter-btn" onclick="filterPubs('anthropomorphism', event)">Anthropomorphism</button>
</div>

<div class="publication-list">

  <div class="publication-item" data-keywords="security hri trust power">
    <p class="pub-title">
      Rewarding Trust: How Reward Power Shapes Security Robot Acceptance
    </p>
    <p class="pub-authors">
      <strong>Xin Ye</strong>, Lionel Peter Robert
    </p>
    <p class="pub-venue">
      Human Factors and Ergonomics Society Annual Meeting, 2025
    </p>
    <p class="pub-tags">
      <span>Security Robots</span>
      <span>Trust & Acceptance</span>
      <span>Power</span>
      <span>HFES 2025</span>
    </p>
  </div>

  <div class="publication-item" data-keywords="security hri review">
    <p class="pub-title">
      Can Robots Take Over Security? A Brief Review and Critique of Security Robot vs. Human Security Agent
    </p>
    <p class="pub-authors">
      <strong>Xin Ye</strong>, Lionel Peter Robert
    </p>
    <p class="pub-venue">
      IEEE International Conference on Robot and Human Interactive Communication, 2025
    </p>
    <p class="pub-links">
      <a href="#" target="_blank">pdf</a>
    </p>
    <p class="pub-tags">
      <span>Security Robots</span>
      <span>Human–Robot Interaction</span>
      <span>Review</span>
      <span>RO-MAN 2025</span>
    </p>
  </div>

  <div class="publication-item" data-keywords="security hri trust power">
    <p class="pub-title">
      Security Robot Power and Acceptance: Exploring French and Raven’s Five Forms of Power
    </p>
    <p class="pub-authors">
      <strong>Xin Ye</strong>, Lionel Peter Robert
    </p>
    <p class="pub-venue">
      ACM/IEEE International Conference on Human-Robot Interaction, 2025
      <span class="award">🎖️ Honorable Mention Award</span>
    </p>
    <p class="pub-links">
      <a href="#" target="_blank">pdf</a>
      <a href="#" target="_blank">paper</a>
      <a href="#" target="_blank">poster</a>
    </p>
    <p class="pub-tags">
      <span>Security Robots</span>
      <span>Trust & Acceptance</span>
      <span>Power</span>
      <span>HRI 2025</span>
    </p>
  </div>

  <div class="publication-item" data-keywords="security hri review">
    <p class="pub-title">
      A Human–Security Robot Interaction Literature Review
    </p>
    <p class="pub-authors">
      <strong>Xin Ye</strong>, Lionel Peter Robert
    </p>
    <p class="pub-venue">
      ACM Transactions on Human-Robot Interaction
    </p>
    <p class="pub-links">
      <a href="#" target="_blank">pdf</a>
      <a href="#" target="_blank">paper</a>
    </p>
    <p class="pub-tags">
      <span>Security Robots</span>
      <span>Human–Robot Interaction</span>
      <span>Review</span>
      <span>THRI</span>
    </p>
  </div>

  <div class="publication-item" data-keywords="security hri review gender">
    <p class="pub-title">
      Gender and Security Robot Interactions: A Brief Review and Critique
    </p>
    <p class="pub-authors">
      <strong>Xin Ye</strong>, Samia Cornelius Bhatti, Lionel Peter Robert
    </p>
    <p class="pub-venue">
      Americas Conference on Information Systems, 2024
      <span class="award">🎖️ Best Paper Nominee</span>
    </p>
    <p class="pub-links">
      <a href="#" target="_blank">pdf</a>
      <a href="#" target="_blank">paper</a>
    </p>
    <p class="pub-tags">
      <span>Security Robots</span>
      <span>Gender</span>
      <span>Review</span>
      <span>AMCIS 2024</span>
    </p>
  </div>

  <div class="publication-item" data-keywords="security hri trust">
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
      <a href="#" target="_blank">pdf</a>
      <a href="#" target="_blank">paper</a>
    </p>
    <p class="pub-tags">
      <span>Security Robots</span>
      <span>Human–Robot Interaction</span>
      <span>Trust & Acceptance</span>
      <span>HRI 2024</span>
    </p>
  </div>

  <div class="publication-item" data-keywords="security hri anthropomorphism">
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
      <a href="#" target="_blank">pdf</a>
      <a href="#" target="_blank">paper</a>
    </p>
    <p class="pub-tags">
      <span>Security Robots</span>
      <span>Human–Robot Interaction</span>
      <span>Anthropomorphism</span>
      <span>RO-MAN 2023</span>
    </p>
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

.publication-item {
  margin-bottom: 1.45rem;
  padding-bottom: 1.1rem;
  border-bottom: 1px solid #eeeeee;
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

.pub-links a {
  display: inline-block;
  margin-right: 8px;
  color: #2f80ed;
  font-weight: 600;
  text-decoration: none;
}

.pub-links a::before {
  content: "[ ";
  color: #777;
  font-weight: 400;
}

.pub-links a::after {
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
</style>

<script>
function filterPubs(keyword, event) {
  var pubs = document.getElementsByClassName("publication-item");
  var buttons = document.getElementsByClassName("filter-btn");

  for (var i = 0; i < buttons.length; i++) {
    buttons[i].classList.remove("active");
  }

  event.target.classList.add("active");

  for (var j = 0; j < pubs.length; j++) {
    var keywords = pubs[j].getAttribute("data-keywords");

    if (keyword === "all" || keywords.includes(keyword)) {
      pubs[j].style.display = "block";
    } else {
      pubs[j].style.display = "none";
    }
  }
}
</script>

# 🎖 Honors and Awards

- *2025*: Honorable Mention Award, ACM/IEEE International Conference on Human-Robot Interaction.
- *2024*: Best Paper Nominee, Americas Conference on Information Systems.

# 📖 Education

- *2022 - Present*, Ph.D. in Information, University of Michigan School of Information.
- *M.S.*, Information Science, University of Michigan.
- *B.S.*, Psychology, Zhejiang University.
