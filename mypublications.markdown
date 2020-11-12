---
layout: default
title: Publications
permalink: /publications/
order: 2
---

{% for paper in site.mypublications %}
  <h2>{{ paper.name }}</h2>
  <p>{{ paper.content | markdownify }}</p>
{% endfor %}