---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.bgithub.xyz/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

{% include_relative includes/intro.md %}

{% include_relative includes/publications.md %}


# 🎖 Honors and Awards
- *2022.12* excellent master dissertation from the China Ordnance Industry Society.  

# 📖 Educations
- *2022.03 - now,  Doctor, Computer Science,   Xi’an Research Institute of High-tech, Xi'an, Shaanxi, China. 
- *2019.09 - 2021.12,  Master, Computer Science,   Xi’an Research Institute of High-tech, Xi'an, Shaanxi, China.
- *2015.09 - 2019.06,  Bachelor, Computer Science,  Xi’an Research Institute of High-tech, Xi'an, Shaanxi, China.

