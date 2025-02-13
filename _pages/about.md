---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Ph.D. student in the Department of Statistics at the University of Wisconsin--Madison.  I graduated from Reed College in 2022 with a BA in mathematics. My current hobbies include rock climbing, playing video games, and following Northern California sports. My research interests include Bayesian modeling, statistical learning, and applications in environment, with a current focus on Bayesian Additive Regression Trees under the mentorship of Professor Sameer K. Deshpande. 

The PDF version of my CV is available [here](https://paulhnguyen.github.io/files/Nguyen_2023_cv.pdf).


Recent Papers
======

<ol>{% for post in site.publications reversed %}
  {% if forloop.index < 6  %}
   <li> {%include archive-single-publication-about.html %}</li>
  {% endif %}
{% endfor %}</ol>

