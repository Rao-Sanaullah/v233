---
title: Large Neural Networks at a Fraction
openreview: xVbMj75YDD
software: https://github.com/smlab-niser/quatLT23
abstract: Large-scale deep learning models are known for their large amount of parameters,
  weighing down on the computational resources. The core of the Lottery Ticket Hypothesis
  showed us the potential of pruning to reduce such parameters without a significant
  drop in accuracy. Quaternion neural networks achieve comparable accuracy to equivalent
  real-valued networks on multi-dimensional prediction tasks. In our work, we implement
  pruning on real and quaternion-valued implementations of large-scale networks in
  the task of image recognition. For instance, our implementation of the ResNet-101
  architecture on the CIFAR-100 and ImageNet64x64 datasets resulted in pruned quaternion
  models outperforming their real-valued counterparts by 4% and 7% in accuracy at
  sparsities of about 6% and 0.4%, respectively. We also got quaternion implementations
  of ResNet-101 and ResNet-152 on CIFAR-100 with steady Lottery tickets, whereas the
  Real counterpart failed to train at the same sparsity. Our experiments show that
  the pruned quaternion implementations perform better at higher sparsity than the
  corresponding real-valued counterpart, even in some larger neural networks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mukhopadhyay24a
month: 0
tex_title: Large Neural Networks at a Fraction
firstpage: 165
lastpage: 173
page: 165-173
order: 165
cycles: false
bibtex_author: Mukhopadhyay, Aritra and A, Adhilsha and Mishra, Subhankar
author:
- given: Aritra
  family: Mukhopadhyay
- given: Adhilsha
  family: A
- given: Subhankar
  family: Mishra
date: 2024-01-23
address:
container-title: Proceedings of the 5th Northern Lights Deep Learning Conference ({NLDL})
volume: '233'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 1
  - 23
pdf: https://proceedings.mlr.press/v233/mukhopadhyay24a/mukhopadhyay24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
