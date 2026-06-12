---
layout: default
title: Ramsys
---
<!-- 1. Add your CSS here -->
<style>
  .btn {
    display: none;
  }
  
  .site-footer-owner {
    display: none;
  }
</style>

Ramsys for Empowered Agentic AI solutions 
---
## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
---
