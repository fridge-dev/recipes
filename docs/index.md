---
layout: default
title: "Home"
---

# Recipes

Welcome to my recipe collection.

## Recipes
{% for recipe in site.recipes %}
- [{{ recipe.title }}]({{ recipe.url }})
{% endfor %}
