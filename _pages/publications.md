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
{% assign v2023 = true %}
{% assign v2022 = true %}

{% for post in site.publications reversed %}

  {% if post.year == 2023 and v2023 %}
  {% assign v2023 = false %}
### 2023
  {% endif %}

  {% if post.year <= 2022 and v2022 %}
  {% assign v2022 = false %}
### 2022 or Early
  {% endif %}

  {% include publications-simple.html %}
{% endfor %}


