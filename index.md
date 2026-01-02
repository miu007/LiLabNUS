---
title: Home
nav:
  order: 1
  tooltip: Home
---
{% include section.html %}

## Research Focus

{% capture content %}
  {% include figure.html 
  image="images/bg5.png"
  width="100%"
  caption="**Cell and tissue engineering**" 
  %}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

Cells are the fundamental units of life that form tissues and organs. Replacing malfunctioning or degenerative tissues or organs offers a promising path to restoring normal function and curing diseases once thought incurable. However, current cell and tissue therapies still face significant challenges.

At the Li Lab, we strive to overcome these barriers by enhancing cells and multicellular structures through synthetic biology. We engineer cellular systems to decode the principles of developmental biology and pioneer next-generation regenerative therapies. By integrating synthetic biology, stem cell culture, and 3D models, we develop innovative platforms for studying cell fate, disease mechanisms, and drug discovery.

{% include float.html clear=true %}

{% include section.html %}

## More About Us

{% capture text %}

We are engineering synthetic structures, we aim to model implantation, lineage specification, and morphogenesis, offering powerful platforms for studying developmental disorders and advancing regenerative medicine.

{%
  include button.html
  link="research"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="Research"
  title="Our Projects"
  style="bare"
  text=text
%}

{% capture text %}

We are a vibriant and multidisciplinary team working together to solve challenging problems and develop therapeutics for human diseases!

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
  flip=true
  text=text
%}

{% capture text %}

We engineer cell fate.
We reprogram somatic cells to a pluripotent, embryonic-like state.
We transform stem cells into embryo models to uncover the fundamental principles of early development.
We also generate functional cell types for applications in regenerative medicine.

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="https://www.cell.com/cms/10.1016/j.cell.2019.09.029/asset/061f677f-a24e-449f-b150-57aa67afcecb/main.assets/fx1.jpg"
  link="Publications"
  title="Our Publications"
  text=text
  width="100%"
  height="60%"
%}

