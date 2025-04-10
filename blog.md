---
layout: default
title: Blog
permalink: /blog/
---

## NOVEDADES
---

<div class="post-grid">
  {% for post in site.posts %}
    <div class="post-card">
      {% if post.image %}
        <img src="{{ post.image }}" alt="{{ post.title }}">
      {% endif %}
      <div class="post-content">
        <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Leer más »</a>
      </div>
    </div>
  {% endfor %}
</div>