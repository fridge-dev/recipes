---
layout: home
title: Recipes Index
---

# Recipes Header

{% for recipe in site.pages %}
  {% if recipe.path contains 'recipes/' %}
- [{{ recipe.title }}]({{ recipe.url }})
  {% endif %}
{% endfor %}

---

Source code: https://github.com/fridge-dev/recipes
