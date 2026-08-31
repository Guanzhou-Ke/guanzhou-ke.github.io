---
permalink: /
title: "Guanzhou Ke"
excerpt: "Active embodied intelligence under partial observability, focused on active perception, world models, and self-improving agents, with current work grounded in UAV autonomy and inspection."
author_profile: true
locale: en-US
redirect_from:
  - /about/
  - /about.html
---

<div class="home-profile" markdown="1">

[中文主页]({{ '/zh/' | relative_url }})

## 👋 Profile

I am **Guanzhou Ke (柯冠舟)**, an **Embodied AI Researcher at Avant Robotics** in Shenzhen. I study active embodied intelligence under partial observability, with a focus on **active perception, world models, and self-improving agents**. My current work is grounded in **UAV autonomy and inspection**.

My research asks how embodied agents can actively acquire task-relevant evidence, learn from difficult simulated and real-world scenarios, and improve through an evaluation–data–training loop. I received my **Ph.D. from Beijing Jiaotong University** and was a **CSC visiting Ph.D. researcher at Singapore Management University**. My earlier work on multi-view representation learning and missing-modality completion provides the foundation for reasoning and action under incomplete observations.

**Links:** [Google Scholar]({{ site.data.profile.author.googlescholar }}) · [ORCID]({{ site.data.profile.author.orcid }}) · [GitHub](https://github.com/{{ site.data.profile.author.github }}) · [ResearchGate]({{ site.data.profile.author.researchgate }}) · [Email](mailto:{{ site.data.profile.author.email }})

## 🎯 Research Agenda

1. **Active Perception for UAV Inspection — Ongoing research.** How should a drone coordinate wide-field cameras, a high-resolution gimbal, and body motion to decide what, where, and when to observe under viewpoint, bandwidth, latency, and safety constraints?
2. **Self-evolving Simulation and Data Engines.** Build evaluation-driven loops that identify failure modes, generate targeted interaction data, and improve navigation and action models.
3. **Reliable Multimodal Intelligence under Partial Observability.** Learn and reason when observations are incomplete, missing, uncertain, or viewpoint-dependent, connecting prior multimodal work with embodied reasoning and action.

## 🚁 Current Systems and Research

### Simulation-driven embodied learning loop

As an Embodied AI Researcher, I work on the simulation, evaluation, and data-engine pipeline that connects hard-case discovery, targeted interaction collection, and model improvement across VLN/VLA, object search, exploration, navigation, and obstacle avoidance.

The resulting **team system** produces **39 million valid simulated interaction steps per month**, improves sampling throughput by **3× on a single RTX 5090**, and supports a **0.8B world/action model reporting 74% navigation-and-avoidance success**. These figures describe the integrated team system rather than an individual result.

### Real-world-grounded scenario construction

I work on geospatially aligned scenario construction using real-world coordinates and aerial observations, emphasizing task executability, repeatability, evaluation, and the return of failure cases into the data loop. Specific scene sources and named locations remain private.

### Active evidence acquisition for UAV inspection

This is an **ongoing research agenda**, not a completed benchmark or public system. The goal is to jointly reason over viewpoint, sensing resolution, gimbal control, body motion, latency, bandwidth, and safety, so a UAV can determine what evidence is missing and when enough evidence has been gathered.

## 📣 News

<div class="home-scroll home-scroll--news" markdown="0">
<ul>
<li><span class="news-date">[05/2026]</span> One paper accepted at IEEE T-PAMI.</li>
<li><span class="news-date">[05/2026]</span> Recognized as an <strong>ICML 2026 Gold Reviewer</strong>.</li>
<li><span class="news-date">[05/2026]</span> One paper accepted at ICML 2026.</li>
<li><span class="news-date">[03/2026]</span> One paper accepted to the CVPR 2026 Findings track.</li>
<li><span class="news-date">[06/2025]</span> One paper accepted at ICCV 2025.</li>
<li><span class="news-date">[02/2025]</span> Knowledge Bridger accepted at CVPR 2025.</li>
<li><span class="news-date">[12/2024]</span> Two papers accepted at AAAI 2025.</li>
<li><span class="news-date">[10/2024]</span> Started a one-year CSC visiting Ph.D. appointment at Singapore Management University.</li>
<li><span class="news-date">[02/2024]</span> Joined Microsoft Research Asia as a research intern.</li>
<li><span class="news-date">[02/2024]</span> MRDD accepted at CVPR 2024.</li>
<li><span class="news-date">[10/2023]</span> One paper accepted in Information Fusion.</li>
<li><span class="news-date">[07/2023]</span> DMRIB accepted at ACM MM 2023.</li>
<li><span class="news-date">[10/2022]</span> One paper accepted at the ICDM 2022 Workshop.</li>
<li><span class="news-date">[09/2022]</span> Started Ph.D. studies at Beijing Jiaotong University.</li>
<li><span class="news-date">[12/2021]</span> One paper accepted at IEEE BigData 2021.</li>
</ul>
</div>

## 💼 Experience

<div class="home-scroll home-scroll--intern" markdown="0">
<ul>
<li><strong>12/2025 – Present: Embodied AI Researcher</strong>
  <ul>
  <li>Avant Robotics, Shenzhen, China.</li>
  <li>Active embodied intelligence, simulation-based evaluation, data engines, world/action models, and UAV autonomy.</li>
  <li>Mentor: <a href="https://zhenguol.github.io/" target="_blank" rel="noopener noreferrer">Zhenguo Li</a>.</li>
  </ul>
</li>
<li><strong>02/2024 – 10/2024: Research Intern</strong>
  <ul>
  <li>Microsoft Research Asia, Shanghai AI/ML Group.</li>
  <li>Multimodal medical report generation and hallucination mitigation.</li>
  <li>Mentor: <a href="https://www.microsoft.com/en-us/research/people/xinyangjiang/" target="_blank" rel="noopener noreferrer">Xinyang Jiang</a>.</li>
  </ul>
</li>
<li><strong>06/2023 – 12/2023: Research Intern</strong>
  <ul>
  <li>Institute of Automation, Chinese Academy of Sciences.</li>
  <li>Multimodal deepfake detection across visual, textual, and audio signals.</li>
  <li>Mentor: <a href="http://vslab.ia.ac.cn/people/" target="_blank" rel="noopener noreferrer">Bo Wang</a>.</li>
  </ul>
</li>
</ul>
</div>

## 🎓 Education

- **Ph.D., Management Science and Engineering**, Beijing Jiaotong University, 2022–2026.
- **CSC Visiting Ph.D. Researcher, Computer Science**, Singapore Management University, 2024–2025. Advisor: Prof. Shengfeng He.
- **M.S., Systems Engineering**, Wuyi University, 2019–2022. Outstanding Thesis Award.
- **B.Eng., Communication Engineering**, Wuyi University, 2017–2019. Outstanding Graduate.

## 📄 Selected Publications

{% assign featured_pubs = site.publications | where_exp: "post", "post.featured_order" | sort: "featured_order" %}
{% for post in featured_pubs %}
  {% include publications-simple.html %}
{% endfor %}

## 📚 Full Publications

<div class="home-profile__scholar" markdown="1">
For the latest citation record, see [Google Scholar]({{ site.data.profile.author.googlescholar }}).
</div>

<div class="home-scroll home-scroll--pubs" markdown="0">
{% include publications-list-by-year.html %}
</div>

## 🏆 Awards

- Second Prize, “Huawei Cup” National Graduate Mathematical Modeling Competition, 2020, 2021, and 2022.
- Second Prize, National Finals, Blue Bridge Cup Information Competition Group B, 2018.
- National Scholarship of China, 2015.

## 🤝 Academic Service

- **Journals:** IEEE Transactions on Multimedia, IEEE Transactions on Circuits and Systems for Video Technology, IEEE Transactions on Neural Networks and Learning Systems, Neurocomputing, and others.
- **Conferences:** NeurIPS, CVPR, ICML (Gold Reviewer), AAAI, ACM Multimedia, and others.

## 📬 CV and Contact

The downloadable English and Chinese CV files are being refreshed to synchronize the August 2026 graduation status, current title, and research positioning. Until then, this homepage is the current public profile.

Email: [{{ site.data.profile.author.email }}](mailto:{{ site.data.profile.author.email }}) · [Google Scholar]({{ site.data.profile.author.googlescholar }}) · [ORCID]({{ site.data.profile.author.orcid }}) · [GitHub](https://github.com/{{ site.data.profile.author.github }})

</div>
