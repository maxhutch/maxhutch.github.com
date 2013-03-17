---
layout: page
title: partial, insignificant, and negative results
---
{% include JB/setup %}

## What is this blog for?
Partial, insignificant, and negative results. For now, at least. 

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


