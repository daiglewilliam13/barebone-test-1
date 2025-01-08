---
title: Blog
layout: "base.njk"
---

All Ramblings
=============

{% for post in collections.posts %}

<a class="blog-card" href={{post.url}}>{{post.data.title}}</a><br>
![v]({{post.data.affImage}} "testing")

{% endfor %}