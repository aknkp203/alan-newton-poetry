---
layout: default
title: Home
---

# Welcome

*A selection of poems, essays, and stories.*

---

## Recent Writing

{% for poem in site.poems limit:5 %}
- [{{ poem.title }}]({{ poem.url | relative_url }})
{% endfor %}

---

## Books

My published books are available on Amazon.

(We'll add your Amazon author page link here.)

---

## About

Thank you for visiting. This site is a home for my creative writing—poems, essays, stories, and other work, both published and new.
