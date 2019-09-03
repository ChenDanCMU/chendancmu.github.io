---
-layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
---
## Preprints

### Adversarially Robust Generalization Just Requires More Unlabeled Data

[arXiv:1906.00555](https://arxiv.org/abs/1906.00555)

Runtian Zhai, Tianle Cai, Di He, **Chen Dan**, Kun He, John Hopcroft, Liwei Wang

---
## Journal Papers

### Identifiability of Nonparametric Mixture Models and Bayes Optimal Clustering

*Annals of Statistics 2019*, [arXiv 1802.04397](https://arxiv.org/abs/1802.04397)

Bryon Aragam, **Chen Dan**, Pradeep Ravikumar, Eric Xing

---

## Conference Papers

### Optimal Analysis of Subset-Selection Based L_p Low Rank Approximation

*NeurIPS 2019*, Preprint will be available soon

**Chen Dan**, Hong Wang, Hongyang Zhang, Yuchen Zhou, Pradeep Ravikumar

### Bilu-Linial Stability, Certified Algorithms and the Independent Set Problem

*ESA 2019*,  [arXiv 1810.08414](https://arxiv.org/abs/1810.08414)

Haris Angelidakis, Pranjal Awasthi, Avrim Blum, Vaggos Chatziafratis, **Chen Dan** (alphabetical order)

### The Sample Complexity of Semi-Supervised Learning with Nonparametric Mixture Models

*NeurIPS 2018*, [arXiv 1809.03073](https://arxiv.org/abs/1809.03073)

**Chen Dan**, Liu Leqi, Bryon Aragam, Pradeep Ravikumar, Eric Xing

### Low Rank Approximation of Binary Matrices: Column Subset Selection and Generalizations

*MFCS 2018*, [arXiv 1511.01699](https://arxiv.org/abs/1511.01699)

**Chen Dan**, Kristoffer Arnsfelt Hansen, Liwei Wang, He Jiang, Yuchen Zhou

---

## Undergraduate Thesis

### On Low Rank Approximation of Binary Matrices , 二元矩阵的低秩近似

[PDF (In Chinese)](https://chendancmu.github.io/files/pkuthss.pdf)

Thesis Advisor: Prof. Liwei Wang

*Top-10 Undergraduate Thesis Award in School of EECS, 2016*
(The only recipient in department of Machine Intelligence)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

