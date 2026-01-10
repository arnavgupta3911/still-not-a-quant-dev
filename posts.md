---
layout: page
title: Posts
permalink: /posts/
---

{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
