---
layout: home
title: Welcome to My Blog
---

# Welcome to My Blog

This is my personal blog where I share my thoughts and experiences about AI and technology.

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul> 