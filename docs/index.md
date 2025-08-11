---
layout: default
title: Recipes
---

{% for recipe in site.pages %}
  {% if recipe.path contains 'recipes/' %}
- [{{ recipe.title }}]({{ recipe.url | relative_url }})
  {% endif %}
{% endfor %}

---

Source code at <https://github.com/fridge-dev/recipes>