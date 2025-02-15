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
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/V4UXJtpFx6Sh6n8Q6"
%}

{% include section.html background="images/longDNA.jpg" dark=true %}


{% capture col1 %}

{%
  include figure.html
  image="images/science/science/DNA.jpg"
  caption="DNA and cells"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
{% endcapture %}

{% capture col2 %}
{% endcapture %}

{% capture col3 %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
