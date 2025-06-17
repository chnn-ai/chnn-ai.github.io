---
layout: page
title: Blogs
permalink: /blogs/
---

# Blogs

Here you will find all my blog posts.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="post-meta">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul> 