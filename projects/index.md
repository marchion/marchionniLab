---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Ed ecco i progetti a cui stiamo lavorando

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Collaborative projects

{% include list.html component="card" data="projects" filter="group == 'biology'" %}

{% include section.html %}

## Other  projects

{% include list.html component="card" data="projects" filter="group == 'bioinf'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
