---
layout: default
title: Home
---

# Welcome to Social Base
An open resource for qualitative research methods, theoretical concepts, and debates in the social sciences.

- [About](About)

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
 