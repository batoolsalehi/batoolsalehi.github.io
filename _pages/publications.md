---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
* **Nasim Soltani**\*, V. Chaudhary\*, D. Roy, K. Chowdhury, “Finding Waldo in the CBRS Band: Signal Detection and Localization in the 3.5 GHz Spectrum,” IEEE GLOBECOM 2022. [pdf](https://nasimsoltani.github.io/files/waldo.pdf)
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
