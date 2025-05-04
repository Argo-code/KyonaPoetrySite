---
layout: blog
title: Blog
description: Poetry
permalink: /blog
---

Welcome to a collection of poetry by Argo.

<ul>
  {% for post in site.posts %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> — <em>{{ post.date | date: "%B %d, %Y" }}</em></li>
  {% endfor %}
</ul>