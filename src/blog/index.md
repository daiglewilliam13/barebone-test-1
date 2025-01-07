---
title: Blog
layout: "base.njk"
---

{% for post in collections.posts %}

[{{post.data.title}}]({{post.url}})  
![v]({{post.data.affImage}} "testing")

{% endfor %}