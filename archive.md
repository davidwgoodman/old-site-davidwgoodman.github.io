---
layout: page
title: Archive
---

This is my archive. Please to enjoy.

## Blog Posts

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}