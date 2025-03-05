---
title: Point Cloud Completion Via Skeleton-Detail Transformer
authors:
- Wenxiao Zhang
- Huajian Zhou
- Zhen Dong
- Jun Liu
- Qingan Yan
- Chunxia Xiao
date: '2023-10-01'
publishDate: '2025-03-05T16:14:07.301408Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Visualization and Computer Graphics(CCF-A)*'
doi: 10.1109/TVCG.2022.3185247
abstract: Point cloud shape completion plays a central role in diverse 3D vision and
  robotics applications. Early methods used to generate global shapes without local
  detail refinement. Current methods tend to leverage local features to preserve the
  observed geometric details. However, they usually adopt the convolutional architecture
  over the incomplete point cloud to extract local features to restore the diverse
  information of both latent shape skeleton and geometric details, where long-distance
  correlation among the skeleton and details is ignored. In this work, we present
  a coarse-to-fine completion framework, which makes full use of both neighboring
  and long-distance region cues for point cloud completion. Our network leverages
  a Skeleton-Detail Transformer, which contains cross-attention and self-attention
  layers, to fully explore the correlation from local patterns to global shape and
  utilize it to enhance the overall skeleton. Also, we propose a selective attention
  mechanism to save memory usage in the attention process without significantly affecting
  performance. We conduct extensive experiments on the ShapeNet dataset and real-scanned
  datasets. Qualitative and quantitative evaluations demonstrate that our proposed
  network outperforms current state-of-the-art methods.
tags:
- Task analysis
- Correlation
- Point cloud
- point cloud completion
- Point cloud compression
- Shape
- shape completion
- Skeleton
- Three-dimensional displays
- Transformers
---
