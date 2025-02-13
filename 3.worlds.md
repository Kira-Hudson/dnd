---
layout: page
title: Worlds
permalink: /worlds/
---

This sections concerns less secret information about the worlds my campaigns are set in.

## Worlds

{% for world in site.worlds | sort: 'title' %}

1. [{{ world.title }}]({{ site.baseurl | append: world.url }})

{% endfor %}
