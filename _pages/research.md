---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Following research is ongoing.

{% for paper in site.research %}
- **{{ paper.title }}**  
  _{{ paper.authors }}_  
  **Abstract：** {{ paper.abstract }}  
  **Keywords：** {{ paper.keywords }}  
{% endfor %}
