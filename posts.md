---
layout: page
title: Posts
permalink: /posts/
---

Here's a bunch of my blog posts where I may post things occasionally.

<ul>
{% for post in site.posts %}
    <li><time datetime="{{ post.date }}">{{ post.date | date: "%B %-d, %Y" }}</time>: <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>