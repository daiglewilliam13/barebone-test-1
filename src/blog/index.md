---
title: Blog
layout: "base.njk"
---

Blog Posts: 

{% for post in collections.posts %}

- [{{post.data.title}}]({{post.url}}) ![v]({{post.data.baseUrl}}{{post.data.thumbnail}} test)

{% endfor %}