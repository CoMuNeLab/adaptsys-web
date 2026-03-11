---
title: Papers
layout: collection
collection: papers
permalink: /papers/
entries_layout: list
header:
  overlay_image: assets/img/lightning-landscape.jpeg
---

# Papers

{% for paper in site.data.contribs.papers %}
## {{ paper.title }}
*{{ paper.authors | join: ", " }}*, {{ paper.journal }} (**{{ paper.year }}**)
{% endfor %}
