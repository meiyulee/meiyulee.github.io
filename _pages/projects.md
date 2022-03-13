---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true

---

My projects fall into two main areas: (1) series of research and (2) teaching for forward-looking knowledge and technology. The two main areas are bsed on the probability distribution simulator, probabilty theory, statistical analysis method to build models from data.

The closed project includes the research and development of Durbin-Watson test statistic (see the book and published journal papers).

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.projects | sort:"order_number" %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}