---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html background="images/background.jpg" dark=true %}

## Current team members 

Please meet our team of exceptional scientists

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Past team members 

Former lab members

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filter="group == 'former'" %}
{% include figure.html image="images/dna.jpg" %}
{% include figure.html image="images/rna.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
