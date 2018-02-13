---
layout: default
title: Dictionaryphile's Blog
---

<ul class="posts">
{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
{% endfor %}
</ul>