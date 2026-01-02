---
title: News
nav:
  order: 6
  tooltip: Our latest
---

# {% include icon.html icon="fa-solid fa-bullhorn" %}News

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
