---
title: Blog
layout: "base.njk"
---

All Ramblings
=============

<ul class='blog-list'>

{% for post in collections.posts %}
<div class='blog-card'>
<a class='post-link' href="{{post.url}}">
<li class='post-title'>{{post.data.title}}</li>
<img class='post-image' width="300px" src="{{post.data.baseURL}}{{post.data.thumbnail}}" alt="">
</a>
<br>
</div>
{% endfor%}