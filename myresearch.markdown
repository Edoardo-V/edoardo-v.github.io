---
layout: page
title: Research
permalink: /research/
---

{% for paper in site.myresearch %}
  <h2>{{ paper.name }}</h2>
  <p>{{ paper.content | markdownify }}</p>
{% endfor %}