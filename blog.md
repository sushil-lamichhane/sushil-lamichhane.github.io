---
layout: page
title: Blog
permalink: /blog/
---

# Blog

Posts will appear here as I publish them.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%d %b %Y" }}</small>
    </li>
  {% endfor %}
</ul>
