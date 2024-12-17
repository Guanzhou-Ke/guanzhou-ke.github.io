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

<!-- header control -->
<!-- 控制每个年份的tag，它后台会自己排序，所以只需要控制第一个就行。只显示近3年的工作了 -->
{% assign v2025 = true %}
{% assign v2024 = true %}
{% assign v2023 = true %}
{% assign early = true %}
{% assign early_year = 2022 %}

{% for post in site.publications reversed %}

  {% if post.year == 2025 and v2025 %}
  {% assign v2025 = false %}
  <!-- 确保只生成一次。 -->
### 2025
  {% endif %}


  {% if post.year == 2024 and v2024 %}
  {% assign v2024 = false %}
### 2024
  {% endif %}


  {% if post.year == 2023 and v2023 %}
  {% assign v2023 = false %}
### 2023
  {% endif %}

  {% if post.year <= early_year and early %}
  {% assign early = false %}
### Early Publication
  {% endif %}

  {% include publications-simple.html %}
{% endfor %}


