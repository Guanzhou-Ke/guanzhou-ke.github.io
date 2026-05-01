---
permalink: /
title: "About Me"
excerpt: "Ph.D. candidate (BJTU) — multi-modal learning, missing modalities, UAV intelligence (VLN/VLA); papers at ICML, ICCV, CVPR, AAAI, and more."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

🕰️ Bio
---
I’m **(Gavin) Guanzhou Ke**, a Ph.D. candidate in **Information Management** at **Beijing Jiaotong University** (B.S. in Communication Engineering and M.S. in Systems Engineering from **Wuyi University**, 2019 and 2022). I work on **multi-view / multi-modal representation learning**, with a focus on **incomplete or missing views and modalities** and on **fusion** that remains expressive when data are partial.

My research has appeared at top venues including **ICML, ICCV, CVPR, AAAI,** and **ACM MM** (see News and publications below). Along the way I have been a **CSC visiting Ph.D. student** at **Singapore Management University** (with Prof. Shengfeng He) and have interned at **Microsoft Research Asia** and the **Institute of Automation, CAS** on multimodal and reliability-oriented problems. Recently I focus on **embodied AI for UAVs**, linking representation learning to **vision-and-language navigation (VLN)** and **vision–language–action (VLA)**-style autonomy.

Download my full CV as **[English PDF]({{ '/files/guanzhou-ke-cv-en.pdf' | relative_url }})** or **[中文 PDF]({{ '/files/guanzhouke-cv-cn-new.pdf' | relative_url }})**.


🎯 Interested
---
Embodied AI (UAV), Unified Visual Understanding and Generation, Large Multimodal models, Missing modality completion.


🔥 Status
---
I expect to graduate from **Beijing Jiaotong University** in **June 2026**. I am currently with **Avant Robotics** in **Shenzhen**, working on **UAV intelligence**—including **high-quality benchmarks** and **stronger autonomous-drone algorithms** that combine **VLN** and **VLA** (and related multimodal planning and control). **Colleagues and peers in similar areas are very welcome to reach out; I enjoy exchanging ideas.**


💼 Internships
---

<div style="width: auto; height: 300px; overflow: auto; padding-right: 0.5rem;">

<ul>
<li><strong>12/2025 – Now: Research Intern</strong>
  <ul>
  <li>Avant Robotics, Shenzhen, China.</li>
  <li>Duties: Design intelligent benchmarks for UAV autonomy, and develop hierarchical “big-brain / small-brain” algorithms for drones—covering high-level vision-and-language navigation (VLN), UAV vision–language–action (UAV-VLA), and related multimodal planning and control stacks.</li>
  <li>Mentor: <a href="https://zhenguol.github.io/">Zhenguo Li</a>.</li>
  </ul>
</li>
<li><strong>02/2024 – 10/2024: Research Intern</strong>
  <ul>
  <li>Microsoft Research Lab - Asia (MSRA), Shanghai AI/ML Group.</li>
  <li>Duties: Study medical report automatic generation technique.</li>
  <li>Mentor: <a href="https://www.microsoft.com/en-us/research/people/xinyangjiang/">Xinyang Jiang</a>.</li>
  </ul>
</li>
<li><strong>06/2023 – 12/2023: Research Intern</strong>
  <ul>
  <li>The Institute of Automation, Chinese Academy of Sciences.</li>
  <li>Duties: Collect Deepfake data, including AIGC, Face swap, etc., and train model to detect fake information. (focus on multi-modalities, such as text and images).</li>
  <li>Mentor: <a href="http://vslab.ia.ac.cn/people/">Bo Wang</a>.</li>
  </ul>
</li>
</ul>

</div>


📣 News
---

<ul style="width: auto; height: 300px; overflow: auto">

<li> <span style="color:red">[05/2026]</span>, one papers is accepted in ICML 2026 (CCF A).</li>
<li> <span style="color:red">[03/2026]</span>, one papers is accepted in CVPR 2026 Findings (CCF A).</li>
<li> <span style="color:red">[06/2025]</span>, one papers is accepted in ICCV 2025 (CCF A).</li>
<li> <span style="color:red">[02/2025]</span>, one papers is accepted in CVPR 2025 (CCF A).</li>
<li> <span style="color:red">[12/2024]</span>, two papers are accepted in AAAI 2025 (CCF A).</li>
<li> <span style="color:red">[10/2024]</span>, as CSC visiting PhD student (1 year) at Singapore Management University.</li>
<li> <span style="color:red">[02/2024]</span>, as an intern in the AI4Science group at Microsoft Research Asia Shanghai.</li>
<li> <span style="color:red">[02/2024]</span>, one paper is accepted in CVPR 24 (CCF A).</li>
<li> <span style="color:red">[10/2023]</span>, one paper is accepted in Information Fusion.</li>
<li> <span style="color:red">[07/2023]</span>, one paper is accepted in ACM MM 2023. (CCF A)</li>
<li> <span style="color:red">[10/2022]</span>, one paper is accepted in ICDM Workshop 2022. (CCF B)</li>
<li> <span style="color:red">[09/2022]</span>, is studied at Beijing Jiaotong University. (Ph.D.)</li>
<li> <span style="color:red">[12/2021]</span>, one paper is accepted in IEEE Bigdata 2021. (CCF C)</li>


</ul>



📄 Selected Publications
---

<ul>{% for post in site.selectedpubs reversed %}
    {% include publications-simple.html %}
    <!-- {% include archive-single-cv.html %} -->
  {% endfor %}</ul>


📄 Full Publications
---
{% if site.author.googlescholar %}
You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<div style="width: auto; max-height: 520px; overflow: auto; padding-right: 0.5rem;">

{% assign v2025 = true %}
{% assign v2024 = true %}
{% assign v2023 = true %}
{% assign early = true %}
{% assign early_year = 2022 %}

{% for post in site.publications reversed %}

  {% if post.year == 2025 and v2025 %}
  {% assign v2025 = false %}
<h3>2025</h3>
  {% endif %}


  {% if post.year == 2024 and v2024 %}
  {% assign v2024 = false %}
<h3>2024</h3>
  {% endif %}


  {% if post.year == 2023 and v2023 %}
  {% assign v2023 = false %}
<h3>2023</h3>
  {% endif %}

  {% if post.year <= early_year and early %}
  {% assign early = false %}
<h3>Early Publication</h3>
  {% endif %}

  {% include publications-simple.html %}
{% endfor %}

</div>


🤝 Services
---

* Journal Reviewer:
  * IEEE TMM / T-CSVT / T-NNLS
  * Information Sciences
* Conference Reviewer:
  * ACM MM 2023 & 24
  * AAAI 2023

<div style="text-align: center;">
  <a href="https://clustrmaps.com/site/1c39f" title="ClustrMaps">
    <img src="//www.clustrmaps.com/map_v2.png?d=6PhQno-uz8qYO3a_jzhJcRHooRKmewUkZxaFZw3oaGI&cl=ffffff" />
  </a>
</div>
