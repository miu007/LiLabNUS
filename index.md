---
---
{% include section.html %}

{% capture col1 %}

# Enhance Cells and Multicellular Structure through Synthetic Biology

At SynDevBio Lab, we engineer multicellular systems to decode developmental biology and pioneer regenerative therapies. By integrating synthetic biology, stem cell culture, and 3D models, we create novel platforms for studying cell fate, disease, and drug discovery.

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/headshot/ronghui-li.jpeg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 ratio="5fr 3fr" %}

{% include section.html %}

## Highlights

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
  flip=true
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
  text=text
%}
