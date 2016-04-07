---
layout: page
title: Archive
---

This is my archive. Please to enjoy.

I've written many more words than this on the internet, but they were mostly on now long-defunct self-hosted Wordpress sites. I also blogged for a time over at [Tumblr](https://davidgoodman.tumblr.com), but I've [switched to Jekyll](/trying-out-jekyll) now.

## Blog Posts

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}