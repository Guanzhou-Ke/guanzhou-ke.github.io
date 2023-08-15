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
  height: 100px;
  /* background: #bfbfbf; */
}

.right {
  overflow: visible;
  padding: 10px;
  padding-left: 160px
}

.small-text {
  font-size: 14px;
  padding-top: 5px;
}

</style>


### 2023

<div class="list__item">
  <img src="https://ihades.cn/images/cloven-arch.png" class="left">

  <div class="right">
    <b>A Clustering-guided Contrastive Fusion for Multi-view Representation Learning</b> <a href="https://arxiv.org/pdf/2212.13726.pdf" style="color: blue;">[PDF]</a> <a href="https://github.com/Guanzhou-Ke/cloven" style="color: blue;">[CODE]</a> 
    <br> <text class="small-text"> <b>Guanzhou Ke</b>, Guoqing Chao, Xiaoli Wang, Chenyang Xu, Yongqi Zhu, and Yang Yu </text>
    <br> <text class="small-text"> IEEE Transactions on Circuits and Systems for Video Technology (TCSVT) <text style="color: red;"> CCF B </text> </text>
  </div>
</div>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
