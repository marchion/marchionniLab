---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Please meet pur team members.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Past team members 

{% include section.html %}

{% capture content %}

{% include figure.html image="images/FANTOM3.jpg" %}
Meet Dr. Mohamed Omar

{% include figure.html image="images/dna.png" %}
Meet Dr. Paul Ayietan

{% include figure.html image="images/tumorEvol.jpg" %}
Meet Dr. Diego Sanchez

{% include figure.html image="images/3Dstruct.jpg" %}
Meet Dr. Claudio Zanettini

{% endcapture %}

{% include grid.html style="square" content=content %}
