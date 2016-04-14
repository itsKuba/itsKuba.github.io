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

    >&nbsp;<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    <br /><br />

  {% endfor %}
</ul>

<!-- INSERTED PROJECTS - CLOSED -->
