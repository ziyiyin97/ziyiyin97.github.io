---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## 2020
* **Extended source imaging -- a unifying framework for seismic & medical imaging**        
Ziyi Yin, Rafael Orozco, Philipp Witte, Mathias Louboutin, Gabrio Rizzuti, Felix J. Herrmann       
Submitted as Society of Exploration Geophysicists Expanded Abstracts, 2020     
[code](https://github.com/slimgroup/Software.SEG2020)