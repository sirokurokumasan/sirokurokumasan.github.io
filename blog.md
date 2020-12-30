---
layout: default
title: Latest Posts
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}" class="btn">{{ post.title }}
      {{ post.excerpt }}</a>
    </li>
  {% endfor %}
</ul>
