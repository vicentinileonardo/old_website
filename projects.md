---
layout: page
title: Projects
permalink: /projects/
---

{% assign posts = site.posts %}
{% for post in posts %}
  {% include post.html %}
{% endfor %}

