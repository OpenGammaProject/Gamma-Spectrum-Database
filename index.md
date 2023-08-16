---
title: "Welcome!"
layout: splash #posts #home
classes: wide

excerpt: "GammaDB is the open and comprehensive database of (common) gamma-ray emitting radioisotopes for gamma-spectroscopy."
    
header:
  overlay_image: /assets/images/Ra-226-header.png
  caption: "Spectrum of Ra-226"
  #overlay_filter: 0.5
  #show_overlay_excerpt: false
  overlay_filter: linear-gradient(rgba(255, 255, 255, 0.5), rgba(0, 0, 0, 0.5))
  actions:
    - label: "<i class='fas fa-database'></i> View All Spectra"
      url: /overview/

#sidebar:
#  - title: "GammaDB"
#    text: "Database of common gamma-ray emitting radioisotopes. [Text](/overview/){: .btn .btn--primary }"
---

## Last Updated Isotopes <a href="https://hits.seeyoufarm.com"><img style="float: right" src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgammadb.nuclearphoenix.xyz&count_bg=%23FF9328&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=true"/></a>

{% assign sorted = site.spectrum | sort: 'last_modified_at' | reverse %}
{% for post in sorted limit:3 %}
  {% include archive-single.html type="grid" %}
{% endfor %}

