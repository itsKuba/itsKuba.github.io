---
layout: page
title: animation
permalink: /animation/
order: 03
---

<!-- INSERTED PROJECTS -->
Range of animations.
<br /><br />
Selected projects are listed below.
<br />
<ul class="post-list">
  {% for post in site.animation %}

      >&nbsp;<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      <br />

    {% endfor %}
  </ul>
Feel free to browse through all of them.
<br /><br />
<ul class="post-list">
  {% for post in site.animation %}
  <a href="{{ post.url | prepend: site.baseurl }}">
    <div class="thumbnail-wrapper">
      <div class="FloatLeft">></div>
      <div class="FloatRight">{{ post.title }}</div>
      <br /><br />
      <div class="thumbnail-container-graphic" style="background-image: url('/assets{{ post.url }}/{{ post.thumbnail }}')"></div>

    </div>
  </a>
  <br /><br />
  {% endfor %}
</ul>

<!-- <ul class="post-list">
  {% for post in site.3d %}

      >&nbsp;<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      <br /><br />

    {% endfor %}
  </ul> -->
<!-- INSERTED PROJECTS - CLOSED -->
