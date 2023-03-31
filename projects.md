---
layout: page
title: Projects
permalink: /projects/
---

# add all posts which have the tag "project" to the page, they are md files in _posts
{% assign posts = site.posts | where: "tags", "project" %}
{% for post in posts %}
  {% include post.html %}
{% endfor %}

