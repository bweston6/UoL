---
title: COMP124 - Labs
layout: article
aside:
 toc: true
sidebar:
 nav: comp124
---
{% for post in site.posts %}
{% if post.tags contains "Labs" and post.tags contains "COMP124" %}
# [{{post.title}}]({{site.baseurl}}{{post.url}})
{{post.content}}
{% endif %}
{% endfor %}
