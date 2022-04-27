---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

#{% if author.googlescholar %}
  #You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
#{% endif %}

#{% include base_path %}

#{% for post in site.publications reversed %}
  #{% include archive-single.html %}
#{% endfor %}
---


{% include base_path %}

Preprints
======
Homogeneity and Sub-homogeneity Pursuit: Iterative Complement Clustering PCA, 2022, arXiv, https://arxiv.org/abs/2203.06573

Spiked eigenvalues of high-dimensional sample autocovariance matrices: CLT and applications, 2022, arXiv, https://arxiv.org/abs/2201.03181

AR-sieve Bootstrap for High-dimensional Time Series, 2021, arXiv, https://arxiv.org/abs/2112.00414

Publications
======
  #<ul>{% for post in site.publications %}
    #{% include archive-single-cv.html %}
  #{% endfor %}</ul>
