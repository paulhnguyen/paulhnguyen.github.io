---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Ph.D. student in the Department of Statistics at the University of Wisconsin--Madison. I recently graduated from Reed College with a BA in mathematics in May 2022. Currently, I am working on Bayesian Additive Regression Trees with Professor Sameer Deshpande.

The PDF version of my CV is available [here](https://paulhnguyen.github.io/files/Nguyen_2023_cv.pdf).


Recent Papers
======

<ol>{% for post in site.publications reversed %}
  {% if forloop.index < 6  %}
   <li> {%include archive-single-publication-about.html %}</li>
  {% endif %}
{% endfor %}</ol>

