---
layout: page
title: Projects
permalink: /projects/
---

<ul>
  {% for post in site.posts %}
    <li>
        <p>test</p>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
