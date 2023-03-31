---
layout: page
title: Projects
permalink: /projects/
---

{% for item in site.posts %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href = "{{ item.url }}" >{{ item.title }}</a></p>
{% endfor %}
