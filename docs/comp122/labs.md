---
title: COMP122 - Labs
layout: article
aside:
 toc: true
sidebar:
 nav: comp122
---
{% for post in site.posts %}
{% if post.tags contains "Labs" and post.tags contains "COMP122" %}
# [{{post.title}}]({{site.baseurl}}{{post.url}})
{{post.content}}
{% endif %}
{% endfor %}
