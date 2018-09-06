---
-layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

# Working Papers

##Optimal Analysis if Subset-Selection Based L_p Low Rank Approximation

*Submitted*

**Chen Dan**, Hong Wang, Hongyang Zhang, Yuchen Zhou



## Bilu-Linial Stability, Certified Algorithms and the Independent Set Problem

*Submitted - alphabetical order* 

Haris Angelidakis, Pranjal Awasthi, Avrim Blum, Vaggos Chatziafratis, **Chen Dan**

# Preprints

## Identifiability of Nonparametric Mixture Models and Bayes Optimal Clustering

*Submitted*, [ArXiv](https://arxiv.org/abs/1802.04397)

Bryon Aragam,**Chen Dan**, Pradeep Ravikumar, Eric Xing

#Conference Papers

## Sample Complexity of Nonparametric Semi-Supervised Learning

**NIPS 2018**

**Chen Dan**, Leqi Liu, Bryon Aragam, Pradeep Ravikumar, Eric Xing

##Low Rank Approximation of Binary Matrices: Column Subset Selection and
Generalizations

**MFCS 2018**, [ArXiv](https://arxiv.org/abs/1511.01699)

**Chen Dan**, Kristoffer Arnsfelt Hansen, Liwei Wang, He Jiang, Yuchen Zhou

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
