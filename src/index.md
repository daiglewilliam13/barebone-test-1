---
title: Hello World
layout: "base.njk"
---
{% include 'components/navbar.md' %}
<p>Hello Jamstack Family!</p>

{% for post in collections.posts %}

- [{{post.data.title}}]({{post.url}})

{% endfor %}
