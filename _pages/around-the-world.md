---
layout: single
title: "Around the World"
permalink: /blog/
---

#### Recent posts from Around the World:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
