---
title: news
layout: main
permalink: /news/
---

{% for post in site.posts %}
	<h1><a href="{{ post.url }}">{{ post.title }}</a><h1><br />
	<br /><br />
{% endfor %}
