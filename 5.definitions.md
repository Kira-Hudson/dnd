---
layout: page
title: Definitions
permalink: /definitions/
---

I will be putting any definitions of D&D, homebrewing, homebrew-specific, world building and world-specific terms here.

{% for term in site.definitions %}

- [{{ term.title }}]({{ site.baseurl | append: term.url }})

{% endfor %}
