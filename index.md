---
title: Li Lab @ NUS
header-big: True
layout: default
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
  link="#research"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="#research"
  title="Our Projects"
  style="bare"
  text=text
%}

{% capture text %}

We are a vibriant and multidisciplinary team working together to solve challenging problems and develop therapeutics for human diseases!

{%
  include button.html
  link="#team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="#team"
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
  link="#publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="https://www.cell.com/cms/10.1016/j.cell.2019.09.029/asset/061f677f-a24e-449f-b150-57aa67afcecb/main.assets/fx1.jpg"
  link="#publications"
  title="Our Publications"
  text=text
  width="100%"
  height="60%"
%}

---

<!-- RESEARCH SECTION -->
# {% include icon.html icon="fa-solid fa-microscope" %}Research
{: #research}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Brief introduction

{% capture text %}

The vision of regenerative medicine starts with reprogramming patient's own cells to induced pluripotent stem cells (iPSCs) that can then be differentiated into any cell type of interest. These cells can be undergoing differentiation in vitro to model human development in 3D organoids format and used for disease modeling and drug screening. Alternatively, these cells can be directly differentiated into specific cell types for cell therapy applications. Our lab is interested in understanding the molecular mechanisms that govern cell fate decisions during human development and leveraging this knowledge to improve the efficiency and safety of cell reprogramming and differentiation processes for regenerative medicine applications.

{% endcapture %}

{%
  include feature.html
  image="images/research/stem-cell-organoid_redesign.png"
  title="**stem cell and orgnanoids**"
  style="bare"
  text=text
%}

{% include figure.html
   image="images/research/stem-cell-organoid.png"
   link="https://www-nature-com.libproxy1.nus.edu.sg/articles/s41392-022-01024-9/figures/1"
   caption="**stem cell and orgnanoids**"
   width="50%"
%}

{% include figure.html
   image="images/research/stem-cell-organoid_redesign.png"
   caption="**stem cell and orgnanoids**"
   width="50%"
%}

{% include section.html %}

## Projects

{% capture text %}

Stem cell derived beta cell holds great promise for treating type 1 diabetes. However, current differentiation protocols produce a heterogeneous population of cells, including off-target cell types that may compromise the safety and efficacy of cell therapy. Our lab is working on understanding the molecular mechanisms that govern beta cell differentiation and using this knowledge to improve the efficiency and purity of stem cell-derived beta cells for cell therapy applications.

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  title="Tackle the heterogeneity of stem cell derived beta cells for cell therapy"
  style="bare"
  text=text
%}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}

---

<!-- PUBLICATIONS SECTION -->
# {% include icon.html icon="fa-solid fa-file-signature" %}Publications
{: #publications}

{% include section.html %}

## Highlighted

{% include citation.html lookup="A Mesenchymal-to-Epithelial Transition" style="rich" %}
{% include citation.html lookup="Generation of Blastocyst-like Structures" style="rich" %}
{% include citation.html lookup="Chemical combinations potentiate" style="rich" %}
{% include citation.html lookup="Prevalent mesenchymal drift" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}

---

<!-- TEAM SECTION -->
# {% include icon.html icon="fa-solid fa-users" %}Team
{: #team}

{% include section.html %}

## Current Members

{% include list.html  data="members"  component="portrait"  filter="role == 'pi'" %}
{% include list.html  data="members"  component="portrait"  filter="role == 'current-manager'" %}
{% include list.html  data="members"  component="portrait"  filter="role == 'current-technician'" %}
{% include list.html  data="members"  component="portrait"  filter="role == 'current-postdoc'" %}
{% include list.html  data="members"  component="portrait"  filter="role == 'current-phd'" %}
{% include list.html  data="members"  component="portrait"  filter="role == 'current-rotation'" %}
{% include list.html  data="members"  component="portrait"  filter="role == 'current-undergrad'" %}
{% include list.html  data="members"  component="portrait"  filter="role == 'current-hs'" %}

{% include section.html %}

## Alumni

{% include list.html  data="members"  component="portrait"  filter="role =~ /alum/i" %}

---

<!-- GALLERY SECTION -->
# {% include icon.html icon="fa-solid fa-hands-helping" %}Gallery
{: #gallery}

Li lab over the years

{% include section.html %}

## {% include icon.html icon="fa-solid fa-people-group" %}Facilities

---

<!-- JOIN US SECTION -->
# {% include icon.html icon="fa-solid fa-hands-helping" %}Join Us
{: #joinus}

We welcome postdocs, PhD candidates, students, and collaborators to reach out to explore opportunities and work together to solve biomedical problems.

{% include section.html %}

## {% include icon.html icon="fa-solid fa-people-group" %}Opportunities

**For postdoctoral applicants**

If you hold a PhD degree and are eager to further your research career with us, we invite you to submit your cover letter, CV, and a complete list of publications to our team. Experiences in cell culture, gene editing, organoid culture, and stem cell bioengineering are preferred but not required. 

**For PhD candidates**

We accept graduate students who have already been admitted to the [NUS School of Medicine Graduate Programme](https://medicine.nus.edu.sg/graduatestudies/application-procedures/). If your research interests align with ours, we encourage you to reach out with your CV, academic transcripts, and a brief statement of research interests. 

**For undergrad and master students**

We welcome undergraduate and master's students from NUS and beyond who are interested in research opportunities. Our lab accepts students from a variety of programs, including the [UROPS](https://www.science.nus.edu.sg/undergraduates/undergraduate-research/urops/), [Summer UROPS and Summer URAPS for Exchange Students](https://www.science.nus.edu.sg/undergraduates/study-abroad-programmes/incoming/summer-urops/), [FYP](https://www.dbs.nus.edu.sg/lifesciences/lsm4288/), and [Master Research Project](https://nusgs.nus.edu.sg/). We encourage you to reach out and explore opportunities to join our team.

**For collaborators**

We welcome collaboration with researchers, clinicians, and industry partners who share our interest in synthetic biology, developmental biology, and bioengineering. If you're interested in working together, please feel free to reach out. We're excited to build meaningful partnerships across institutions and disciplines.

{% include section.html %}

## {% include icon.html icon="fa-regular fa-envelope" %}Contact

We welcome anyone interested in our research to reach out and explore opportunities to join us or collaborate. You can find contact details on this page.

{%
  include button.html
  type="email"
  text="email"
  link="ronghui.li@nus.edu.sg"
%}
{%
  include button.html
  type="phone"
  text="phone"
  link="+65 6516 2846"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/QnYWaUy9QdrF8Ubv6"
%}

{% include section.html %}

## {% include icon.html icon="fa-regular fa-compass" %}Directions

The lab is located on the NUS Kent Ridge campus on the 10th floor of the S9 Wet Science Building. 

{% capture col1 %}

<div class="image-container">

  <img src="{{ 'images/1920_wsb1-1267351765.jpg' | relative_url }}" alt="NUS S9 Wet Science Building">

</div>

{% endcapture %}

{% capture col2 %}

<div class="map-container">

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.7978734415537!2d103.78020803488968!3d1.2958822242022032!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31da1bc911595d3d%3A0xd684eb7b6242d35c!2sNUS%20S9%20Wet%20Science%20Building!5e0!3m2!1sen!2ssg!4v1760685171475!5m2!1sen!2ssg" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" ></iframe>

</div>

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}