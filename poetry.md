---
layout: default
title: Poetry
permalink: /poetry/
---

# Poetry

Below is a collection of my poems.

{% assign poems = site.poems | sort: "title" %}

{% for poem in poems %}
- [{{ poem.title }}]({{ poem.url | relative_url }})
{% endfor %}
