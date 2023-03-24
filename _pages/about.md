---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an PhD student in the Department of Statistics at the University of Wisconsin--Madison. I recently graduated from Reed College with a BA in mathematics in May 2022. I am currently working on Bayesian Additive Regression Trees with Sameer Deshpande.

If I had one, my CV would be available [here](google.com).


Recent Papers
======

<ol>{% for post in site.publications reversed %}
  {% if forloop.index < 6  %}
   <li> {%include archive-single-publication-about.html %}</li>
  {% endif %}
{% endfor %}</ol>

