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

.pblock {
  width: 800px;
}

.pblock img {
      float: left;
      margin-right: 10px;
      width: 150px;
      height: 100px;
  }
.pblock p {
    width: 600px;
    line-height: 20px;
    overflow: hidden;
}


</style>

2023
===

<div class="pblock">
    <img src="https://ihades.cn/images/cloven-arch.png">
<p>A Clustering-guided Contrastive Fusion for Multi-view Representation Learning</p>

<p>Guanzhou Ke</p>
</div>


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
