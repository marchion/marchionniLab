---
---

# marchion's Website

I am an Associate Professor of Pathology and Laboratory Medicine at Weill Cornell Medicine, New York, NY, USA.

I am doctor and a computational biologist, and I specifically work on cancer. I apply quantitative approaches 
to interpret high-dimensional genomic data, understand cancer cell biology, and develop useful clinical tools 
to improve cancer patients' outcomes.

I am also co-Director of the Center for Computational Genomics at Johns Hopkins, a multi-disciplinary initiative 
that has been awarded competitive funding from the University leadership to support research and education 
in the field of Computational Genomics.

**Considerate la vostra semenza: fatti non foste a viver come bruti ma per seguir virtute e canoscenza. **

Ulisse (Divina Commedia, Canto XXVI, Dante Alighieri)

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
