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

# About Me

I am a PhD Candidate in Boston University working with [Prof. Yigong Hu](https://yigonghu.github.io/).  

My research interests are primarily on improving the **performance and reliability** of distributed system. One focus is to enhance system performance, spanning from **machine learning systems** to **cloud computing** platforms.

[//]: # (Previsouly I worked with [Prof. Chang Lou]&#40;https://changlousys.github.io/&#41; of LiftLab at **University of Virginia**. Fortunately, I am also advised by [Dr. Zhen Zhang]&#40;https://zarzen.me/&#41;, **Johns Hopkins University**, [Dr. Yuan Zhou]&#40;https://zhouyuan1119.github.io/&#41;, **Cornell University**, and [Dr. Shaowei Zhu]&#40;https://www.cs.princeton.edu/~shaoweiz/&#41;, **Princeton University**.)

[//]: # (For the past year, I've working in providing reliability support for machine learning developers, inspired by observations made from our collaborating team in **AWS**.  )
Previously I worked at **Alibaba Group** as a Software Engineer for two years, undertaking objectives of enhancing quality and efficiency while empowering internal teams.

## [CV](https://drive.google.com/file/d/1AJFomQbjvxwnVk1dDaFwoJKEJV4GjDQc/view?usp=sharing)

<span class='anchor' id='-news'></span>

# News
- *2026.07*: &nbsp;🎉🎉 Our paper [Eprof](https://arxiv.org/pdf/2512.08365) has been accepted by [NSDI '27](https://www.usenix.org/conference/nsdi27)!
- *2026.07*: &nbsp; Glad to serve on the Artifact Evaluation Committee for [NSDI '27](https://www.usenix.org/conference/nsdi27).
- *2026.03*: &nbsp; Glad to serve on the Artifact Evaluation Committee for [MLSys '26](https://mlsys.org/).
- *2026.01*: &nbsp; Had a talk at [New England Systems Day 2026](https://newenglandsystemsday.github.io/2026/schedule.html), hosted at Harvard.
- *2025.09*: &nbsp; Start a new chapter as a PhD student at Boston University.
- *2025.02*: &nbsp;🎉 Our workshop paper on [Verifying Large ML Models](https://dl.acm.org/doi/10.1145/3721146.3721943) has been accepted by [EuroMLSys '25](https://euromlsys.eu/#) (co-located with EuroSys 2025)! 
- *2024.05*: &nbsp; Proposal of [enhancing the cloud automation](https://summerofcode.withgoogle.com/programs/2024/projects/M6IH4Vev) for Google Summer of code(GSoC) 2024 is accepted.

[//]: # (- *2023.12*: &nbsp; Start the position as a research assistant in LiftLab at University of Virginia from December 2023.)

[//]: # (# 🎖 Honors and Awards)
[//]: # (- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.)
[//]: # (- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.)

<span class='anchor' id='publications'></span>

<style>
.pub-card {
  display: flex;
  align-items: flex-start;
  gap: 16px;
  margin-bottom: 24px;
  padding-bottom: 20px;
  border-bottom: 1px solid #eee;
}
.pub-badge {
  flex-shrink: 0;
  background-color: #4a3f9e;
  color: #fff;
  font-weight: 600;
  font-size: 13px;
  padding: 6px 14px;
  border-radius: 6px;
  white-space: nowrap;
  margin-top: 4px;
}
.pub-content h3 {
  margin: 0 0 6px 0;
  font-size: 17px;
  font-weight: 600;
}
.pub-content h3 a {
  color: #1a0dab;
  text-decoration: none;
}
.pub-content h3 a:hover {
  text-decoration: underline;
}
.pub-content .pub-authors {
  margin: 0 0 4px 0;
  color: #333;
  font-size: 14px;
}
.pub-content .pub-venue {
  margin: 0 0 8px 0;
  font-style: italic;
  color: #666;
  font-size: 14px;
}
.pub-content .pub-venue a {
  color: #666;
}
.pub-buttons a {
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 4px 12px;
  margin-right: 8px;
  font-size: 13px;
  text-decoration: none;
  color: #333;
}
.pub-buttons a:hover {
  background-color: #f0f0f0;
}
</style>

# Publications

<div class="pub-card">
  <div class="pub-badge">NSDI '27</div>
  <div class="pub-content">
    <h3><a href="https://arxiv.org/pdf/2512.08365" target="_blank">Eprof: Optimizing Energy Efficiency of ML Systems via Differential Energy Debugging</a></h3>
    <p class="pub-authors">Yi Pan*, <strong>Wenbo Qian</strong>* (co-first author), Dedong Xie, Ruiyan Hu, Yigong Hu, Baris Kasikci</p>
    <p class="pub-venue"><a href="https://www.usenix.org/conference/nsdi27" target="_blank">24th USENIX Symposium on Networked Systems Design and Implementation (NSDI 2027)</a></p>
    <div class="pub-buttons">
      <a href="https://arxiv.org/pdf/2512.08365" target="_blank">Paper</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-badge">EuroMLSys '25</div>
  <div class="pub-content">
    <h3><a href="https://dl.acm.org/doi/10.1145/3721146.3721943" target="_blank">Verifying Semantic Equivalence of Large Models with Equality Saturation</a></h3>
    <p class="pub-authors">Kahfi S. Zulkifli*, <strong>Wenbo Qian</strong>* (co-first author), Shaowei Zhu, Yuan Zhou, Zhen Zhang, Chang Lou</p>
    <p class="pub-venue"><a href="https://2025.euromlsys.eu/" target="_blank">EuroMLSys 2025 (co-located with EuroSys)</a></p>
    <div class="pub-buttons">
      <a href="https://dl.acm.org/doi/10.1145/3721146.3721943" target="_blank">Paper</a>
    </div>
  </div>
</div>

<span class='anchor' id='-educations'></span>

# Educations

- *2025.09 - Present*, PhD Candidate in Computer Engineering, [Boston University](https://www.bu.edu/)
- *2023.09 - 2025.08*, Master of Computer Science, Northeastern University
- *2017.09 - 2021.06*, Bachelor of Computer Science, Sichuan University, Chengdu, China
- *2019.01 - 2019.02*, Academic Exchange Program, University of California, Berkeley, California

[//]: # (# Invited Talks)
[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.)
[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

<span class='anchor' id='work-exp'></span>

# Work Experience
- *July 2021 - June 2023*, Software Engineer, [Alibaba Group](https://www.alibabagroup.com/en-US/)
- *May 2024 - Sep 2024*, Open Source Contributor, [Google Summer of Code](https://summerofcode.withgoogle.com/)
- *July 2020 - Sept 2020*, Software Engineer Intern, [NetEase Game](https://www.neteasegames.com/)
