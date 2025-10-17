---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

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
