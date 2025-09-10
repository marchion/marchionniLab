---
title: Projects
nav:
  order: 2
  tooltip: Collaborations, projects, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Here are the projects we are working on...

{% include tags.html tags="biology, bioinformatics, cancer" %}


{% include section.html background="images/longDNA.jpg" dark=true %}
***
## Collaborative projects focusing on biology
{% include section.html %}

{% include list.html component="card" data="projects" filter="group == 'biology'" %}


{% include section.html background="images/longDNA.jpg" dark=true %}
***
## Collaborative projects focusing on computational tools and statistical methods
{% include section.html %}

{% include list.html component="card" data="projects" filter="group == 'bioinformatics'" %}
