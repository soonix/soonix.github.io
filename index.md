---
layout: page
title: Willkommen - Bonvenon - Bienvenu - Welcome!
tagline: hmmm...
---
{% include JB/setup %}

## Posts
List of posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
