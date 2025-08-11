---
layout: default
title: "Home"
---

{% for recipe in site.recipes %}
- [{{ recipe.title }}]({{ recipe.url }})
{% endfor %}


Source code: https://github.com/fridge-dev/recipes
