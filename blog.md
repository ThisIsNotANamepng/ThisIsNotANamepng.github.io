---
title: "Lab Blog"
layout: base
permalink: /blog/
---

Here we share news, highlights, and publications.

<ul class="posts-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%b %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
