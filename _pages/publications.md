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

### 2023
{% for post in site.publications.2023 reversed %}
  {% include publications-simple.html %}
{% endfor %}

### 2022 or early
{% for post in site.publications.2022-early reversed %}
  {% include publications-simple.html %}
{% endfor %}
