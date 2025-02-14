---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Current team members 

Please meet our current team members.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include figure.html image="images/digitalPath.jpg" %}
Meet Dr. Mohamed Omar


## Past team members 

Our team of exceptional former lab members

{% include section.html %}

{% capture content %}

{% include figure.html image="images/digitalPath.jpg" %}
Meet Dr. Mohamed Omar

{% include figure.html image="images/dna.png" %}
Meet Dr. Paul Ayietan

{% include figure.html image="images/tumorEvol.jpg" %}
Meet Dr. Diego Sanchez

{% include figure.html image="images/3Dstruct.jpg" %}
Meet Dr. Claudio Zanettini

{% endcapture %}

{% include grid.html style="square" content=content %}
