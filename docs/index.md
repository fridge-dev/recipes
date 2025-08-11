---
layout: default
title: My Recipe Collection
---

# My Recipe Collection

A simple collection of my favorite cooking recipes.

## Recipes

{% for recipe in site.pages %}
  {% if recipe.path contains 'recipes/' %}
- [{{ recipe.title }}]({{ recipe.url | relative_url }})
  {% endif %}
{% endfor %}