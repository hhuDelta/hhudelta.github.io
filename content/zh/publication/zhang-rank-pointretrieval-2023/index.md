---
title: 'Rank-PointRetrieval: Reranking Point Cloud Retrieval via a Visually Consistent
  Registration Evaluation'
authors:
- Wenxiao Zhang
- Huajian Zhou
- Zhen Dong
- Qingan Yan
- Chunxia Xiao
date: '2023-09-01'
publishDate: '2025-03-05T16:14:07.322956Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Visualization and Computer Graphics(CCF-A)*'
doi: 10.1109/TVCG.2022.3170695
abstract: Point cloud-based place recognition is a fundamental part of the localization
  task, and it can be achieved through a retrieval process. Reranking is a critical
  step in improving the retrieval accuracy, yet little effort has been devoted to
  reranking in point cloud retrieval. In this paper, we investigate the versatility
  of rigid registration in reranking the point cloud retrieval results. Specifically,
  after obtaining the initial retrieval list based on the global point cloud feature
  distance, we perform registration between the query and point clouds in the retrieval
  list. We propose an efficient strategy based on visual consistency to evaluate each
  registration with a registration score in an unsupervised manner. The final reranked
  list is computed by considering both the original global feature distance and the
  registration score. In addition, we find that the registration score between two
  point clouds can also be used as a pseudo label to judge whether they represent
  the same place. Thus, we can create a self-supervised training dataset when there
  is no ground truth of positional information. Moreover, we develop a new probability-based
  loss to obtain more discriminative descriptors. The proposed reranking approach
  and the probability-based loss can be easily applied to current point cloud retrieval
  baselines to improve the retrieval accuracy. Experiments on various benchmark datasets
  show that both the reranking registration method and probability-based loss can
  significantly improve the current state-of-the-art baselines.
tags:
- Feature extraction
- Task analysis
- Training
- Point cloud
- Point cloud compression
- Three-dimensional displays
- Cloud computing
- Global Positioning System
- place recognition
- point cloud retrieval
- reranking methods
---
