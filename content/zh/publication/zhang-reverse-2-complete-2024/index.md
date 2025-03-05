---
title: 'Reverse2Complete: Unpaired Multimodal Point Cloud Completion via Guided Diffusion'
authors:
- Wenxiao Zhang
- Hossein Rahmani
- Xun Yang
- Jun Liu
date: '2024-01-01'
publishDate: '2025-03-05T16:14:07.382374Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 32nd ACM International Conference on Multimedia(CCF-A)*'
doi: 10.1145/3664647.3680590
abstract: Unpaired point cloud completion involves filling in missing parts of a point
  cloud without requiring partial-complete correspondence. Meanwhile, since point
  cloud completion is an ill-posed problem, there are multiple ways to generate the
  missing parts. Existing unpaired completion methods usually leverage generative
  adversarial training by transforming partial shape encoding into a complete one
  in the low-dimensional latent feature space. However, \"mode collapse\" often occurs,
  where only a subset of the shapes is represented in the low-dimensional space, reducing
  the diversity of the generated shapes. In this paper, we propose a novel unpaired
  multimodal shape completion approach that directly operates on point coordinate
  space. We achieve unpaired completion via a single diffusion model trained on complete
  data by \"hijacking\" the generative process. We further augment the diffusion model
  by introducing two guidance mechanisms to facilitate mapping the partial point cloud
  to the complete one while preserving its original structure. We conduct extensive
  evaluations of our approach, which show that our method generates shapes that are
  more diverse and better preserve the original structures compared to alternative
  methods.
tags:
- point cloud
- point cloud diffusion model
- shpae completion
links:
- name: URL
  url: 10.1145/3664647.3680590
---
