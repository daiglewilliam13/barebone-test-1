---
title: Blog
layout: "base.njk"
---

{% for post in collections.posts %}

<a href={{post.url}}>{{post.data.title}}</a>
![v]({{post.data.affImage}} "testing")

{% endfor %}