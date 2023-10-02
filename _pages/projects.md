---
title: Projects
permalink: /projects/
layout: single
---

{% for project in site.projects %}
<div class="project-block">
  <img src="{{ project.image }}" alt="{{ project.title }} Image" class="project-image">
  <div class="project-info">
    <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
    <p>{{ project.description }}</p>
  </div>
</div>
{% endfor %}