---
layout: page
title: HexVox
tagline: Hex-Grids and Voxels
---
{% include JB/setup %}

Thoughts on Voxel Rendering, Raytracing and Hexagonal Grids... A combination that might result in a game.

## Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

