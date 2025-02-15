---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Ed ecco i progetti a cui stiamo lavorando

{% include tags.html tags="biology, bioinformatics, cancer" %}

{% include search-info.html %}

{% include section.html background="images/science/longDNA.jpg" dark=false %}

## Collaborative projects focusing on cancer biology

{% include list.html component="card" data="projects" filter="group == 'biology'" %}

{% include section.html background="images/science/researchDNA.jpg" dark=false %}

## Collaborative projects focusing on computational tools

{% include list.html component="card" data="projects" filter="group == 'bioinformatics'" %}

{% include section.html background="images/background.jpg" dark=true %}
