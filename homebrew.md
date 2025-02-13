---
layout: page
title: Homebrew
permalink: /homebrew/
---

This is lists of my own custom homebrew and other peoples' homebrew I accept in my D&D campaigns.

### Sources

The homebrew on this site will have a list of sources at the bottom, like so:

<div style="border:2px solid #e8e8e8;padding:7px">Sources: <em>source one, source two, source three, and so on</em></div>

If the source is "_Custom_" then the item was made by me (and is up for criticism).

If it is "_customised_" then the item has been modified by me. The modifications I make will be marked with an asterisk (\*).

## Homebrew Items

{% for item in site.homebrew | sort: 'type', 'title' %}

- **{{ item.name | split: "." | first | upcase }}** [{{ item.title }}]({{ site.baseurl | append: item.url }}) _({{ item.sources | join: ", " }})_

{% endfor %}
