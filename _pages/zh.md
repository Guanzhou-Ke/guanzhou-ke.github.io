---
permalink: /zh/
title: "柯冠舟"
excerpt: "研究不完整观测下的主动具身智能，重点关注主动感知、世界模型与自进化智能体；当前工作以无人机自主与巡检为主要落地场景。"
author_profile: true
locale: zh-CN
---

<div class="home-profile" markdown="1">

[English Homepage]({{ '/' | relative_url }})

## 👋 个人简介

我是**柯冠舟（Guanzhou Ke）**，现任深圳 **Avant Robotics 具身智能研究员（Embodied AI Researcher）**。我研究**不完整观测下的主动具身智能**，重点关注**主动感知、世界模型与自进化智能体**，当前工作以**无人机自主与巡检**为主要落地场景。

我的研究关注具身智能体如何主动获取与任务相关的证据，如何从高难度仿真与真实环境案例中学习，以及如何通过“评测—数据—训练”闭环持续提升。我于**北京交通大学获得博士学位**，曾获国家留学基金委资助赴**新加坡管理大学联合培养**。此前关于多视图表征学习与缺失模态补全的工作，为研究不完整观测条件下的推理与行动提供了方法基础。

**链接：** [Google Scholar]({{ site.data.profile.author.googlescholar }}) · [ORCID]({{ site.data.profile.author.orcid }}) · [GitHub](https://github.com/{{ site.data.profile.author.github }}) · [ResearchGate]({{ site.data.profile.author.researchgate }}) · [邮箱](mailto:{{ site.data.profile.author.email }})

## 🎯 研究方向

1. **面向无人机巡检的主动感知——进行中。** 在视角、带宽、延迟与安全约束下，无人机应如何协调广角相机、高分辨率云台和机体运动，并决定观察什么、去哪里观察以及何时停止观察？
2. **自进化仿真与数据引擎。** 构建评测驱动的闭环，识别系统失效模式，生成针对性交互数据，并持续提升导航与动作模型。
3. **不完整观测下的可靠多模态智能。** 面向观测不完整、模态缺失、信息不确定或视角受限等问题，将以往多模态学习研究拓展到具身推理与行动。

## 🚁 当前系统与研究工作

### 仿真驱动的具身学习闭环

作为具身智能研究员，我负责和参与仿真、评测与数据引擎链路建设，将困难案例发现、针对性交互数据采集和模型优化连接成闭环，覆盖 VLN/VLA、目标搜索、探索、导航与避障等无人机任务。

当前**团队系统**每月可产生 **3900 万条有效仿真交互步数**，在单张 RTX 5090 上将采样吞吐提升 **3 倍**，并支持一个 **0.8B 世界动作模型达到 74% 的导航与避障成功率**。这些数字属于完整团队系统结果，并非个人独立成果。

### 真实世界坐标对齐的场景构建

研究基于真实世界坐标与航拍观测构建地理空间对齐的可执行场景，重点保证任务可执行性、可复现评测，以及将失败案例重新送回数据闭环。具体场景来源与地点名称不对外公开。

### 面向无人机巡检的主动证据获取

这是一个**正在推进的研究方向**，并非已经完成的公开基准或系统。目标是联合考虑视角、感知分辨率、云台控制、机体运动、延迟、带宽和安全约束，使无人机能够判断缺少什么证据，以及何时已经获得足够证据。

## 📣 最新动态

<div class="home-scroll home-scroll--news" markdown="0">
<ul>
<li><span class="news-date">[05/2026]</span> 一篇论文被 IEEE T-PAMI 接收。</li>
<li><span class="news-date">[05/2026]</span> 获评 <strong>ICML 2026 Gold Reviewer</strong>。</li>
<li><span class="news-date">[05/2026]</span> 一篇论文被 ICML 2026 接收。</li>
<li><span class="news-date">[03/2026]</span> 一篇论文被 CVPR 2026 Findings 接收。</li>
<li><span class="news-date">[06/2025]</span> 一篇论文被 ICCV 2025 接收。</li>
<li><span class="news-date">[02/2025]</span> Knowledge Bridger 被 CVPR 2025 接收。</li>
<li><span class="news-date">[12/2024]</span> 两篇论文被 AAAI 2025 接收。</li>
<li><span class="news-date">[10/2024]</span> 开始在新加坡管理大学进行为期一年的 CSC 联合培养。</li>
<li><span class="news-date">[02/2024]</span> 加入微软亚洲研究院担任研究实习生。</li>
<li><span class="news-date">[02/2024]</span> MRDD 被 CVPR 2024 接收。</li>
<li><span class="news-date">[10/2023]</span> 一篇论文被 Information Fusion 接收。</li>
<li><span class="news-date">[07/2023]</span> DMRIB 被 ACM MM 2023 接收。</li>
<li><span class="news-date">[10/2022]</span> 一篇论文被 ICDM 2022 Workshop 接收。</li>
<li><span class="news-date">[09/2022]</span> 开始在北京交通大学攻读博士学位。</li>
<li><span class="news-date">[12/2021]</span> 一篇论文被 IEEE BigData 2021 接收。</li>
</ul>
</div>

## 💼 工作与研究经历

<div class="home-scroll home-scroll--intern" markdown="0">
<ul>
<li><strong>2025年12月 – 至今：具身智能研究员</strong>
  <ul>
  <li>Avant Robotics，深圳。</li>
  <li>主动具身智能、仿真评测、数据引擎、世界动作模型与无人机自主。</li>
  <li>导师：<a href="https://zhenguol.github.io/" target="_blank" rel="noopener noreferrer">李政国</a>。</li>
  </ul>
</li>
<li><strong>2024年2月 – 2024年10月：研究实习生</strong>
  <ul>
  <li>微软亚洲研究院，上海 AI/ML 组。</li>
  <li>多模态医疗报告生成与幻觉缓解。</li>
  <li>导师：<a href="https://www.microsoft.com/en-us/research/people/xinyangjiang/" target="_blank" rel="noopener noreferrer">蒋欣阳</a>。</li>
  </ul>
</li>
<li><strong>2023年6月 – 2023年12月：研究实习生</strong>
  <ul>
  <li>中国科学院自动化研究所。</li>
  <li>面向图像、文本与音频的多模态深度伪造检测。</li>
  <li>导师：<a href="http://vslab.ia.ac.cn/people/" target="_blank" rel="noopener noreferrer">王博</a>。</li>
  </ul>
</li>
</ul>
</div>

## 🎓 教育经历

- **管理科学与工程博士**，北京交通大学，2022–2026。
- **CSC 联合培养博士（计算机科学）**，新加坡管理大学，2024–2025，合作导师：何盛烽教授。
- **系统工程硕士**，五邑大学，2019–2022，优秀硕士学位论文。
- **通信工程学士**，五邑大学，2017–2019，优秀毕业生。

## 📄 代表论文

{% assign featured_pubs = site.publications | where_exp: "post", "post.featured_order" | sort: "featured_order" %}
{% for post in featured_pubs %}
  {% include publications-simple.html %}
{% endfor %}

## 📚 完整论文列表

<div class="home-profile__scholar" markdown="1">
最新引用信息请参见 [Google Scholar]({{ site.data.profile.author.googlescholar }})。
</div>

<div class="home-scroll home-scroll--pubs" markdown="0">
{% include publications-list-by-year.html %}
</div>

## 🏆 获奖情况

- “华为杯”全国研究生数学建模竞赛全国二等奖，2020、2021、2022。
- 蓝桥杯全国软件和信息技术专业人才大赛 B 组全国二等奖，2018。
- 国家奖学金，2015。

## 🤝 学术服务

- **期刊审稿：** IEEE TMM、IEEE T-CSVT、IEEE T-NNLS、Neurocomputing 等。
- **会议审稿：** NeurIPS、CVPR、ICML（Gold Reviewer）、AAAI、ACM MM 等。

## 📬 简历与联系方式

中英文 PDF 简历正在更新，以同步 2026 年 8 月的毕业状态、当前职称和研究定位。在新版 PDF 上线前，本主页是最新的公开信息版本。

邮箱：[{{ site.data.profile.author.email }}](mailto:{{ site.data.profile.author.email }}) · [Google Scholar]({{ site.data.profile.author.googlescholar }}) · [ORCID]({{ site.data.profile.author.orcid }}) · [GitHub](https://github.com/{{ site.data.profile.author.github }})

</div>
