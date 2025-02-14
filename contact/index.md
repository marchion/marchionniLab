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

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/RNA.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/DNA.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
https://www.ncbi.nlm.nih.gov
{% endcapture %}

{% capture col2 %}
https://genome.ucsc.edu/index.html
{% endcapture %}

{% capture col3 %}
https://www.cbioportal.org
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
