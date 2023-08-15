---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<style>



.left {
  float: left;
  width: 150px;
  height: 150px;
  /* background: #bfbfbf; */
}

.right {
  overflow: visible;
  height: 150px;
  /* background: #efefef; */
}

.right p{
  /* margin: 0 20px 0; */
  text-align: left;
  margin-left: 20px;
}
</style>

2023
===


<div class="content">
  <div class="left">
    <img src="https://ihades.cn/images/cloven-arch.png">
  </div>
  <div class="right">
    <p>A Clustering-guided Contrastive Fusion for Multi-view Representation Learning <a href="https://arxiv.org/pdf/2212.13726.pdf" style="color: blue;">[PDF]</a> <a href="https://github.com/Guanzhou-Ke/cloven" style="color: blue;">[CODE]</a> <br> **Guanzhou Ke**, Guoqing Chao, Xiaoli Wang, Chenyang Xu, Yongqi Zhu, and Yang Yu <br> IEEE Transactions on Circuits and Systems for Video Technology </p>
  </div>
</div>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
