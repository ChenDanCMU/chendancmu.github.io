---
-layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Working Papers

### Optimal Analysis of Subset-Selection Based L_p Low Rank Approximation

*Submitted*

**Chen Dan**, Hong Wang, Hongyang Zhang, Yuchen Zhou

### Bilu-Linial Stability, Certified Algorithms and the Independent Set Problem

*Submitted*

Haris Angelidakis, Pranjal Awasthi, Avrim Blum, Vaggos Chatziafratis, **Chen Dan**

\* alphabetical order

---
## Preprints

### Identifiability of Nonparametric Mixture Models and Bayes Optimal Clustering

*Submitted*, [ArXiv](https://arxiv.org/abs/1802.04397)

Bryon Aragam, **Chen Dan**, Pradeep Ravikumar, Eric Xing

---

## Conference Papers

### Sample Complexity of Nonparametric Semi-Supervised Learning

*NIPS 2018*

**Chen Dan**, Leqi Liu, Bryon Aragam, Pradeep Ravikumar, Eric Xing

### Low Rank Approximation of Binary Matrices: Column Subset Selection and Generalizations

*MFCS 2018*, [ArXiv](https://arxiv.org/abs/1511.01699)

**Chen Dan**, Kristoffer Arnsfelt Hansen, Liwei Wang, He Jiang, Yuchen Zhou

---

## Undergraduate Thesis

### On Low Rank Approximation of Binary Matrices 

### 布尔矩阵的低秩近似

[PDF (In Chinese)](https://chendancmu.github.io/files/thesis.pdf)

Thesis Advisor: Prof. Liwei Wang

*Top-10 Undergraduate Thesis Award in School of EECS, 2016*
(The only recipient in department)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

