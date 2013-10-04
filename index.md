---
layout: default
title: svperstarz.github.io
---

<div id="home">
  <h1>포스트 목록</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date: "%Y-%m-%d (%a)" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
