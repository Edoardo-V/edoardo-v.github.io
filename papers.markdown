---
layout: page
title: Papers
permalink: /papers/
order: 0
---

{% for paper in site.papers %}
  <h2>{{ paper.name }}</h2>
  <p>{{ paper.content | markdownify }}</p>
{% endfor %}