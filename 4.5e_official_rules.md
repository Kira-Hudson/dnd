---
layout: page
title: 5e Official Rules
permalink: /official5e/
---

A reference for official D&D 5e rules.

## Challenge Ratings

A simple challenge rating table for D&D 5e, with only the proficiency bonus and the experience for each rating.

| Rating | Proficiency Bonus |  XP |
| ------:|:-----------------:| ---:|{% for cr in site.crs %}
| {{cr.rating}} | +{{cr.pb}} | {{cr.xp}} |{% endfor %}
