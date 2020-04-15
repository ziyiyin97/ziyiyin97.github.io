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

Ziyi Yin, Rafael Orozco, Philipp Witte, Mathias Louboutin, Gabrio Rizzuti, Felix J. Herrmann. **Extended source imaging -- a unifying framework for seismic & medical imaging**. Submitted to the Society of Exploration Geophysicists Annual Meeting 2020.