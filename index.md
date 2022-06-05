---
title: "Welcome to the database!"
author_profile: false

layout: splash #posts #home
classes: wide

excerpt: "... of (common) gamma-ray emitting radioisotopes."
    
header:
  overlay_image: /assets/images/Ra-226-header.png
  caption: "Spectrum of Ra-226"
  #overlay_filter: 0.5
  overlay_filter: linear-gradient(rgba(255, 255, 255, 0.5), rgba(0, 0, 0, 0.5))
  actions:
    - label: "<i class='fas fa-database'></i> View All Spectra"
      url: /overview/

#sidebar:
#  - title: "GammaDB"
#    text: "Database of common gamma-ray emitting radioisotopes. [Text](/overview/){: .btn .btn--primary }"
---

# Latest Posts

{% for post in site.posts limit:3 %}
  {% include archive-single.html type="grid" %}
{% endfor %}

