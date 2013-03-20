---
layout: page
title: partial, insignificant, and negative results
tagline: from Max Hutchinson
---
{% include JB/setup %}

This blog is still under construction.  Content, even posts, will be changing.

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


