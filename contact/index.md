---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Here is how you get in contact with us:

{%
  include button.html
  type="email"
  text="marchion@med.cornell.edu"
  link="marchion at med.cornell.edu"
%}
{%
  include button.html
  type="phone"
  text="(001) 646-962-8767"
  link="+1-646-962-8767"
%}
{%
  include button.html
  type="address"
  tooltip="Click for our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/3c6bVr4SeW4LrkfW9"
%}

{% include section.html background="images/longDNA.jpg" dark=false %}

# Locations

{% capture col1 %}

## Office: 

<h2> Belfer Research Building </h2>

<h2> Suite #1524 </h2>


{% endcapture %}

{% capture col2 %}

## Laboratory:

<h2> 413 East 69th Street </h2>

<h2> New York, NY 10021 </h2>


{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}


