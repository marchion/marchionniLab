---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

<!--- section for the current members --->

{% include section.html background="images/longPeople.jpg" dark=false %}

## Current team members 

Please meet our team of exceptional scientists

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="group == 'alum'" %}


<!--- section for the visiting students --->

{% include section.html background="images/longPeople.jpg" dark=false %}

## Visiting scholars and students

Visiting scholars and students

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filter="group == 'visiting'" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

<!--- section for the former members --->

{% include section.html background="images/longPeople.jpg" dark=false %}

## Past team members 

Former lab members

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filter="group == 'former'" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
