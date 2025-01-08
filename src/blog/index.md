---
title: Blog
layout: "base.njk"
---

{% for post in collections.posts %}

<a class="blog-card" href={{post.url}}>{{post.data.title}}</a>
![v]({{post.data.affImage}} "testing")

{% endfor %}