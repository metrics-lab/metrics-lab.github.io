---
title: "LUCAS - Projects"
layout: gridlay
excerpt: "LUCAS -- Projects"
sitemap: false
permalink: /blogs/
---
# Projects

This is a collection of projects of the LUCAS group.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
