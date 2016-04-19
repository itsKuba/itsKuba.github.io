---
layout: post
title:  "Various Renders"
date:   2016-04-09 16:57:06 +0200
categories: graphics
permalink: /graphics/various-renders
images:
  - 3d_abstract_01.jpg
  - 3d_herbs.jpg
  - 3d_interior.jpg
  - 3d_abstract_00.jpg
  - 3d_car.jpg
  - 3d_fruits.jpg
  - 3d_paidinfull.jpg
  - 3d_geometry.jpg
  - 3d_memories.jpg
  - 3d_violence.jpg
thumbnail: various-renders-thumbnail.jpg
---
Various 3d model, texture, shader, and lighting render tests.<br />
<br />
{% for image in page.images %}
  <img rel="nofollow" class="image-full" src="/assets/graphics/various-renders/{{ image }}"/>
  <br />
{% endfor %}
