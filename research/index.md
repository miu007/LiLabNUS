---
title: Research
nav:
  order: 2
  tooltip: Our ongoing research topics
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Brief introduction

The vision of regenerative medicine starts with reprogramming patient's own cells to induced pluripotent stem cells (iPSCs) that can then be differentiated into any cell type of interest. these cells can be undergoing differntiation in vitro to model human development in 3D organoids format and used for disease modeling and drug screening. Alternatively, these cells can be directly differentiated into specific cell types for cell therapy applications. Our lab is interested in understanding the molecular mechanisms that govern cell fate decisions during human development and leveraging this knowledge to improve the efficiency and safety of cell reprogramming and differentiation processes for regenerative medicine applications.

{% include figure.html
   image="images/research/stem-cell-orgnanoid.png"
   link="https://www-nature-com.libproxy1.nus.edu.sg/articles/s41392-022-01024-9/figures/1"
   caption="**stem cell and orgnanoids**"
%}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
