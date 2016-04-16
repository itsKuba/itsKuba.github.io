---
layout: post
title:  "City Experiments"
date:   2016-04-09 16:57:06 +0200
categories: 3d
permalink: /3d/city-experiments
images:
  - city-experiments-00.jpg
  - city-experiments-01.jpg
  - city-experiments-02.jpg
  - city-experiments-03.jpg
thumbnail: city-experiments-thumbnail.jpg
---
A mixture of data driven and hand modeled large scale city environments.<br />
<br />
<br />
{% for image in page.images %}
  <img rel="nofollow" class="image-full" src="/assets/3d/city-experiments/{{ image }}"/>
  <br />
{% endfor %}
