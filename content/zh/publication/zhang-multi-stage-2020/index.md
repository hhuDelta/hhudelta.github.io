---
title: Multi-stage point completion network with critical set supervision
authors:
- Wenxiao Zhang
- Chengjiang Long
- Qingan Yan
- Alix L. H. Chow
- Chunxia Xiao
date: '2020-01-01'
publishDate: '2025-03-05T16:14:07.315736Z'
publication_types:
- article-journal
publication: '*Computer Aided Geometric Design*'
doi: 10.1016/j.cagd.2020.101925
abstract: Point cloud based shape completion has great significant application values
  and refers to reconstructing a complete point cloud from a partial input. In this
  paper, we propose a multi-stage point completion network (MSPCN) with critical set
  supervision. In our network, a cascade of upsampling units is used to progressively
  recover the high-resolution results with several stages. Different from the existing
  works that generate the output point cloud structure supervised by the complete
  ground truth, we leverage the critical set at each stage for supervision and generate
  a more informative and useful intermediate outputs for the next stage. We propose
  a strategy by combining max-pooling selected points and volume-downsampling points
  to determine critical sets (MVCS) for supervision, which concerns both critical
  features and the shape of the model. We conduct extensive experiments on the ShapeNet
  dataset and the experimental results clearly demonstrate that our proposed MSPCN
  with critical set supervision outperforms the state-of-the-art completion methods.
tags:
- Point cloud
- Deep learning
- Shape completion
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0167839620301126
---
