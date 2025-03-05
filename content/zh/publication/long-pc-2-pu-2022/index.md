---
title: 'PC2-PU: Patch Correlation and Point Correlation for Effective Point Cloud
  Upsampling'
authors:
- Chen Long
- WenXiao Zhang
- Ruihui Li
- Hao Wang
- Zhen Dong
- Bisheng Yang
date: '2022-01-01'
publishDate: '2025-03-05T16:14:07.345373Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 30th ACM International Conference on Multimedia*'
doi: 10.1145/3503161.3547777
abstract: "Point cloud upsampling is to densify a sparse point set acquired from 3D
  sensors, providing a denser representation for the underlying surface. Existing
  methods divide the input points into small patches and upsample each patch separately,
  however, ignoring the global spatial consistency between patches. In this paper,
  we present a novel method PCtextasciicircum2-PU, which explores patch-to-patch and
  point-to-point correlations for more effective and robust point cloud upsampling.
  Specifically, our network has two appealing designs: (i) We take adjacent patches
  as supplementary inputs to compensate the loss structure information within a single
  patch and introduce a Patch Correlation Module to capture the difference and similarity
  between patches. (ii) After augmenting each patch's geometry, we further introduce
  a Point Correlation Module to reveal the relationship of points inside each patch
  to maintain the local spatial consistency. Extensive experiments on both synthetic
  and real scanned datasets demonstrate that our method surpasses previous upsampling
  methods, particularly with the noisy inputs. The code and data are at: https://github.com/chenlongwhu/PC2-PU.git."
tags:
- deep neural networks
- point cloud upsampling
links:
- name: URL
  url: https://doi.org/10.1145/3503161.3547777
---
