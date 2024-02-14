---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Ph.D. student in the Department of Statistics at the University of Wisconsin--Madison.  I hold a BA in mathematics from Reed College, having graduated in May 2022. My current favorite hobbies are rock climbing, playing video games, and team sports. My research interests span tree ensemble methods and statistical learning, with a current focus on Bayesian Additive Regression Trees under the mentorship of Professor Sameer Deshpande.

The PDF version of my CV is available [here](https://paulhnguyen.github.io/files/Nguyen_2023_cv.pdf).


Recent Papers
======

<ol>{% for post in site.publications reversed %}
  {% if forloop.index < 6  %}
   <li> {%include archive-single-publication-about.html %}</li>
  {% endif %}
{% endfor %}</ol>

