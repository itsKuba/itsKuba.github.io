---
layout: post
title:  "City Experiments"
date:   2016-04-09 16:57:06 +0200
categories: graphics
permalink: /graphics/city-experiments
images:
  - city-experiments-00.jpg
  - city-experiments-01.jpg
  - city-experiments-02.jpg
  - city-experiments-03.jpg
thumbnail: city-experiments-00.jpg
---
Large scale 3d city environment of Warsaw, Poland, achieved through a mixture of OSM-data driven model generation, DirectX geometry capture, and traditional poly modeling.<br />
<br />
<br />
{% for image in page.images %}
  <img rel="nofollow" class="image-full" src="/assets/graphics/city-experiments/{{ image }}"/>
  <br />
{% endfor %}
