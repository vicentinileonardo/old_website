---
layout: page
title: Projects
permalink: /projects/
---

{% assign posts = site.posts | where: "tags", "project" %}
{% for post in posts %}
  {% include post.html %}
{% endfor %}

