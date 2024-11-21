---
title: Hello World
layout: "base.njk"
---

Hello Jamstack Family!

{% for post in collections.posts %}

- [{{post.data.title}}]({{post.url}})

{% endfor %}
