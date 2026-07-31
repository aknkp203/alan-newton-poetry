---
layout: default
title: Poetry
permalink: /poetry/
---

# Poetry

*A selection of poems.*

---

{% assign poems = site.poems | sort: "title" %}

{% for poem in poems %}

### [{{ poem.title }}]({{ poem.url | relative_url }})

{% endfor %}
