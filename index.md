---
title: Exploring genes, genomes, cells, and more
---

# Marchionni Lab

<!--- This is the content of the main page of the site --->

The Marchionni Lab uses quantitative methods to anlyze and interpret high-dimensional data,
understand cancer cell biology, and develop useful clinical tools to improve cancer patients' outcomes.
Our final goal is to improve human health and disease treatment through the development
of robust quantitative tools for the analysis of the molecular and cellular interactions
driving cancer.

We also believe that an inclusive environment for research,
centered on the values of diversity and inclusion,
is crucial to push the boundaries the boundaries of our curiosity
and ingenuity, ultimately serving the process of discovery, 
for the benefit of cancer research patients of all backgrounds.

***"Considerate la vostra semenza: fatti non foste a viver come bruti ma per seguir virtute e canoscenza."***
***(Ulisse nella Divina Commedia, Canto XXVI, Dante Alighieri)***


{% include section.html background="images/longDNA.jpg" dark=true %}

## Our research interests

{% include section.html %}

{% capture text %}

Millions of cells are dividing every day in our human body. 
This process is well coordinated and cell divisions are followed by cell specialization,
allowing the maintenance of tissues and organs (homeostasis).
Cancer is a deviation from such state of balance: a cell that has undergone mutations in its DNA, 
instead of maturing and dying normally, reproduces without restraint, giving rise to a progeny that also fails to mature.
As a result, cancer is a very complex disease, that involves not only cancerous cells, 
but also surrounding and distant normal cells, which engage in a network of complex interactions. 

{%
  include button.html
  link="research"
  text="Check our research in computational biology"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/science/cancerCells.jpg"
  link="research"
  title="Computation Cancer Biology"
  text=text
%}

{% capture text %}

It is now possible to digitize and store large archives of histopaholoy slides.
At the same time, thanks to advances in algorithmics, statistics, mathematics, and computer science 
it is also possible to extract and analyze quantifiable information from such images. 
We, like others, are trying to exploit this unprecedented opportunity for 
the the systematic and quantitative analysis of images routinely generated in pathology departments around the world. 
The adoption of Artificial Intelligence (AI), Machine Learning (ML) 
– including more data and computation intensive approaches like Deep Learning (DL) – 
holds the promise to project pathology in the next millennium.

{%
  include button.html
  link="research"
  text="Check our research in digital pathology"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/science/digitalPath.png"
  link="projects"
  title="Digital Pathology"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Medicine is transitioning from treating the “average patient” to seeking to treat each individual in a tailored way. At present, this approach to medicine, however, can only be delivered at lead academic institutions, hence the opportunity to deliver state of the art clinical care on a large scale and in the community is still missed. By integrating big molecular data, standard clinical laboratory measurements, and digital pathology images, my laboratory strive to bridge this gap. The goal here is to develop robust, parsimonious models that can forecast patients molecular make-up (e.g., their mutational profiles) and outcome (e.g., their response to targeted treatments). While the development of these approaches can only be achieved in leading academic institutions, deploying and disseminating such methods in community and rural hospitals nationwide is of paramount importance. Ultimately, through research in this domain, my lab fosters the democratization of precision and personalized medicine. 

{%
  include button.html
  link="research"
  text="Check our research in cancer and precision oncology"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/science/gelBands.jpg"
  link="team"
  title="Precision Medicine"
  text=text
%}

