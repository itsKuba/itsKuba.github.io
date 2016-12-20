---
layout: post
title:  "ProxyDude - Unity3d & C# GameDev"
date:   2016-04-09 16:57:06 +0200
categories: graphics
permalink: /graphics/itsrpg-gamedev
images:
  - itsrpg-scene.png
  - itsrpg-scene-closeup.png
  - itsrpg-hero.png
  - itsrpg-skeleton1.png
  - itsrpg-skeleton2.png
  - itsrpg-zombie.png
  - itsrpg-shaman.png
  - itsrpg-skeleton-walkcycle.gif
  - itsrpg-face-arrow.gif
  - itsrpg-face-arrow-closeup.gif
  - itsrpg-face-arrow-closeup.jpg

thumbnail: itsrpg-scene.jpg
---
Experimental 3d isometric game development with Unity3d and C#. Turnbased gameplay with implemented controls, primitive enemy AI pathtracing, and collectibles for health/damage and score keeping. Obstacles and enemies are destructible, toughness is distinguished by color coding. Work in progress.<br />
<br />
<br />
{% for image in page.images %}
  <img rel="nofollow" class="image-full" src="/assets/graphics/proxydude-unity3d-gamedev/{{ image }}"/>
  <br />
{% endfor %}
