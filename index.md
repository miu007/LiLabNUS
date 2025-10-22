---
title: Home      # This is the text that will appear in the menu
nav:
  order: 1       # This makes it the first item in the menu
  tooltip: "Back to Home"
---
{% include section.html %}

{% capture col1 %}

## Research Focus

Cells are the fundamental units of life. Replacing malfunctioning or degenerative tissues offers a promising path to restoring normal function and curing diseases once thought incurable. However, current cell and tissue therapies still face significant challenges.

At SynDevBio Lab, we strive to overcome these barriers by enhancing cells and multicellular structures through synthetic biology. We engineer cellular systems to decode the principles of developmental biology and pioneer next-generation regenerative therapies. By integrating synthetic biology, stem cell culture, and 3D models, we develop innovative platforms for studying cell fate, disease mechanisms, and drug discovery.

{% endcapture %}

{% capture col2 %}

{% include profile-card.html
   image="images/headshots/ronghui-li.jpeg"
   bio="Ronghui Li, Ph.D., received his Ph.D. from the University of Wisconsin-Madison, USA, with a major in Cellular…"
   link="/members/ronghui-li"
   show_link=true
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 ratio="5fr 3fr" %}

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

