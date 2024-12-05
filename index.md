---
layout: default
title: Welcome to My Site
---

# Welcome to My Site

This is the homepage of my site where you can find links to the posts and other pages.

## Pages

- [Home Page](/home.html)
- [Admin Panel](/admin.html)

## Posts

Here are some of my recent blog posts:

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
