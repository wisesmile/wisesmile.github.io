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
  <h2>Production</h2>
  <ul class="posts">
    <li><a href="http://glowsalon.com">Glow Salon</a></li>
    <li><a href="http://www.gandhimemorialcenter.org">Gandhi Memorial Center</a></li>
    <li><a href="http://www.eastportdc.org">Eastport Democratic Club</a></li>
    <li><a href="http://gandhimemorialcenter.herokuapp.com">Gandhi Center Data App</a></li>
  </ul>
  <h2>Staging</h2>
  <ul class="posts">
    <li><a href="http://www.wisesmile.net.s3.amazonaws.com/glow/public/index.html">Glow Salon Update</a></li>
  </ul>
  <h2>Development</h2>
  <ul class="posts">
    <li><a href="http://www.prayers-of-self-revelation.com.s3.amazonaws.com/index.html">Prayers of Self Revelation</a></li>
  </ul>
  <h2>Koans</h2>
  <ul class="posts">
    <li><a href="http://github.com/wisesmile/hills/">Hills</a></li>
    <li><a href="http://bl.ocks.org/wisesmile">Blocks</a></li>
    <li><a href="http://jsfiddle.net/user/mpazaryna/fiddles/">jsFiddle</a></li>
  </ul>
</div>
