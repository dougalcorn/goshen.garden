---
layout: page
title: Journal
permalink: /journal/
---

Notes from the field. Observations, questions, failures, small wins.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

{% if site.posts.size == 0 %}
*Nothing yet. Season is just getting started.*
{% endif %}
