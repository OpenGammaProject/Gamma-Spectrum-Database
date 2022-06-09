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

# Last Updated Isotopes

{% assign sorted = site.spectrum | sort: 'date' | reverse %}
{% for post in sorted limit:3 %}
  {% include archive-single.html type="grid" %}
{% endfor %}

