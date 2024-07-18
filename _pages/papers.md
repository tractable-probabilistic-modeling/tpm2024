---
layout: default
permalink: /papers/
title: Accepted Papers
---

# Accepted Papers 

<ul>
{% assign sortedPapers = site.data.papers | sort: 'title' %}
{% for item in sortedPapers %}
  <li><strong>{{ item.title }}</strong>
  <br/>
  <small><i>{{ item.authors }}</i></small></li>
{% endfor %}
</ul>
