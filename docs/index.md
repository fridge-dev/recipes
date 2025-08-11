---
layout: default
title: "Home"
---

{% for recipe in site.recipes %}
- [{{ recipe.title }}]({{ recipe.url }})
{% endfor %}
