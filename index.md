---
layout: default
title: Fantayeneh Asres Gizaw
---

<div id="home">
  <h1>Blog Posts</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <h1>Highlighted Talks</h1>
  <ul class="posts">
  </ul>

</div>