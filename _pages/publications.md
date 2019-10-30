---
-layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
“+”: Alphabetical order or Equal contribution.

## Preprints
### Learning Sparse Nonparametric DAGs

[arXiv 1909.13189](http://arxiv.org/abs/1909.13189)

[Xun Zheng](http://www.cs.cmu.edu/~xunzheng/), **Chen Dan**, [Bryon Aragam](https://www.bryonaragam.com/), [Pradeep Ravikumar](https://www.cs.cmu.edu/~pradeepr/), [Eric P. Xing](http://www.cs.cmu.edu/~epxing/)

### Adversarially Robust Generalization Just Requires More Unlabeled Data

[arXiv 1906.00555](https://arxiv.org/abs/1906.00555)

[Runtian Zhai](http://www.runtianzhai.com/), [Tianle Cai](http://tianle.website/), [Di He](https://www.microsoft.com/en-us/research/people/dihe/), **Chen Dan**, [Kun He](http://faculty.hust.edu.cn/hekun/en/index.htm), [John Hopcroft](https://www.cs.cornell.edu/jeh/), [Liwei Wang](http://www.cis.pku.edu.cn/faculty/vision/wangliwei/)

---
## Journal Papers

### Identifiability of Nonparametric Mixture Models and Bayes Optimal Clustering

*Annals of Statistics 2019*, [arXiv 1802.04397](https://arxiv.org/abs/1802.04397)

[Bryon Aragam](https://www.bryonaragam.com/), **Chen Dan**, [Pradeep Ravikumar](https://www.cs.cmu.edu/~pradeepr/), [Eric P. Xing](http://www.cs.cmu.edu/~epxing/)

---

## Conference Papers

### Optimal Analysis of Subset-Selection Based L_p Low Rank Approximation

*NeurIPS 2019*, [Preprint](https://chendancmu.github.io/files/NeurIPS_Lp_preprint.pdf)

**Chen Dan**, [Hong Wang](https://sites.google.com/view/hongwang/home)+, [Hongyang Zhang](https://www.cs.cmu.edu/~hongyanz/)+, [Yuchen Zhou](https://stat.wisc.edu/staff/zhou-yuchen/)+, [Pradeep Ravikumar](https://www.cs.cmu.edu/~pradeepr/)

### Bilu-Linial Stability, Certified Algorithms and the Independent Set Problem

*ESA 2019*,  [arXiv 1810.08414](https://arxiv.org/abs/1810.08414)

[Haris Angelidakis+](http://n.ethz.ch/~angelidc/), [Pranjal Awasthi+](https://www.cs.rutgers.edu/~pa336/), [Avrim Blum+](https://ttic.uchicago.edu/~avrim/), [Vaggos Chatziafratis+](https://cs.stanford.edu/~vaggos/), **Chen Dan**+

### The Sample Complexity of Semi-Supervised Learning with Nonparametric Mixture Models

*NeurIPS 2018*, [arXiv 1809.03073](https://arxiv.org/abs/1809.03073)

**Chen Dan**, [Liu Leqi](https://www.cs.cmu.edu/~leqil/), [Bryon Aragam](https://www.bryonaragam.com/), [Pradeep Ravikumar](https://www.cs.cmu.edu/~pradeepr/), [Eric P. Xing](http://www.cs.cmu.edu/~epxing/)

### Low Rank Approximation of Binary Matrices: Column Subset Selection and Generalizations

*MFCS 2018*, [arXiv 1511.01699](https://arxiv.org/abs/1511.01699)

**Chen Dan**, [Kristoffer Arnsfelt Hansen](http://www.cs.au.dk/~arnsfelt/), [Liwei Wang](http://www.cis.pku.edu.cn/faculty/vision/wangliwei/), [He Jiang](https://scholar.google.com/citations?user=CnAuFCYAAAAJ&hl=en), [Yuchen Zhou](https://stat.wisc.edu/staff/zhou-yuchen/)

---

## Undergraduate Thesis

### On Low Rank Approximation of Binary Matrices , 二元矩阵的低秩近似

[PDF (In Chinese)](https://chendancmu.github.io/files/pkuthss.pdf)

Thesis Advisor: Prof. [Liwei Wang](http://www.cis.pku.edu.cn/faculty/vision/wangliwei/).

*Top-10 Undergraduate Thesis Award in School of EECS, 2016*
(The only recipient in department of Machine Intelligence)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

