---
layout: default
title: "Kyona's Poetry Archive"
---

Welcome to a collection of poetry by Kyona.

<ul>
  {% for post in site.posts %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> — <em>{{ post.date | date: "%B %d, %Y" }}</em></li>
  {% endfor %}
</ul>