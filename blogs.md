---
layout: default
title: Posts
---

# Posts

{% for post in site.categories['techpost'] %}
<li><a href="{{post.url}}">{{post.title}}</a></li>
{% endfor %}
