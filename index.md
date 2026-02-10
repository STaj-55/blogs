---
layout: default
title: Home
---

Welcome 👋

## Latest posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

[View all posts]({{ site.baseurl }}/archive/)
