---
layout: default
title: mpazaryna.github.io
---

<div id="home">
  <h2>Posts</h2>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h2>Work</h2>
  <ul class="posts">
    <li><a href="http://wisesmile.github.io/hills/">Hills</a></li>   
    <li><a href="http://wisesmile.github.io/pages/cv.html">CV</a></li>
    <li><a href="http://bl.ocks.org/wisesmile">Blocks</a></li>
  </ul>
</div>
