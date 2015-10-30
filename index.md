---
layout: page
title: Willkommen - Bonvenon - Welcome - &#1079;&#1076;&#1088;&#1072;&#1074;&#1089;&#1090;&#1074;&#1091;&#1081;&#1090;&#1077;!
tagline: Supporting tagline
---
{% include JB/setup %}

## Posts

List of all posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

