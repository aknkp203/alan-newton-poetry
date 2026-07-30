---
layout: default
title: Home
---
# Alan Newton

*A selection of poems, essays, and stories.*

---

Welcome. This website is a home for my creative writing. Here you'll find poems, essays, stories, and information about my published books.

## Recent Poetry

{% assign recent_poems = site.poems | reverse %}

{% for poem in recent_poems limit:5 %}

### [{{ poem.title }}]({{ poem.url | relative_url }})

{% endfor %}

---

Explore the complete collection on the **Poetry** page.
