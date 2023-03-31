---
layout: page
title: Projects
permalink: /projects/
---

{% for post in posts %} 
    {% if post.tags contains 'project' %}
        {% include post.html %}
    {% endif %}
{% endfor %}
