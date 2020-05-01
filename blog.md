---
layout: post
title: "Blog"
permalink: /blog/
---

This is where my blog can go?

A list of posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
