---
title: Informative Point cloud Dataset Extraction for Classification via Gradient-based
  Points Moving
authors:
- Wenxiao Zhang
- Ziqi Wang
- Li Xu
- Xun Yang
- Jun Liu
date: '2024-01-01'
publishDate: '2025-03-05T16:14:07.404605Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 32nd ACM International Conference on Multimedia(CCF-A)*'
doi: 10.1145/3664647.3680767
abstract: 'Point cloud plays a significant role in recent learning-based vision tasks,
  which contain additional information about the physical space compared to 2D images.
  However, such a 3D data format also results in more expensive training costs to
  train a sophisticated network with large 3D datasets. Previous methods for point
  cloud compression focus on compacting the representation of each point cloud for
  better storage and transmission but ignore the improvements in training efficiency.
  In this paper, we introduce a new open problem in the point cloud field, named point
  cloud condensation : Can we condense a large point cloud dataset into a much smaller
  synthetic dataset while preserving the important information of the original large
  dataset? In other words, we explore the possibility of training a network on a smaller
  dataset of informative point clouds extracted from the original large dataset but
  maintaining similar network classification performance. Training on this small synthetic
  dataset could largely improve the training efficiency. To achieve this goal, we
  propose a two-stage approach to generate the synthetic dataset. We first introduce
  a nearest-feature-mean based strategy to initialize the synthetic dataset, and then
  formulate our goal as a parameter-matching problem, which we solve by introducing
  a gradient-matching strategy to iteratively refine the synthetic dataset. We conduct
  extensive experiments on various synthetic and real-scanned 3D object classification
  benchmarks, showing that our synthetic dataset could achieve almost the same performance
  with only 5% point clouds of ScanObjectNN dataset compared to training with the
  full dataset. Codes are available at https://github.com/XLechter/PointCondensation.'
tags:
- point cloud
- point cloud condensation
- shape representation
links:
- name: URL
  url: 10.1145/3664647.3680767
---
