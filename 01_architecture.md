---
layout: page
title: architecture
permalink: /architecture/
order: 01
---

<!-- INSERTED PROJECTS -->
Working stages range from concept development, function planning, cad drawing, traditional & parametric 3d modeling, and archviz.
<br /><br />
Selected architectural projects are listed below.
<br />
Feel free to browse through all of them.
<br /><br />

<ul class="post-list">
  {% for post in site.architecture %}
  <a href="{{ post.url | prepend: site.baseurl }}">
    <div class="thumbnail-wrapper">
      <div class="FloatLeft">></div>
      <div class="FloatRight">{{ post.title }}</div>
      <br /><br />
      <div class="thumbnail-container" style="background-image: url('/assets{{ post.url }}/{{ post.thumbnail }}')"></div>

    </div>
  </a>
  <br /><br />
  {% endfor %}
</ul>

<!-- <ul class="post-list">
  {% for post in site.architecture %}

      >&nbsp;<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      <br /><br />

    {% endfor %}
  </ul> -->

<!-- INSERTED PROJECTS - CLOSED -->
