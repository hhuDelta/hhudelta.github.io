---
title: Learning Long-range Information with Dual-Scale Transformers for Indoor Scene
  Completion
authors:
- Ziqi Wang
- Fei Luo
- Xiaoxiao Long
- Wenxiao Zhang
- Chunxia Xiao
date: '2023-10-01'
publishDate: '2025-03-05T16:14:07.367226Z'
publication_types:
- paper-conference
publication: '*2023 IEEE/CVF International Conference on Computer Vision (CCF-A)*'
doi: 10.1109/ICCV51070.2023.01702
abstract: Due to the limited resolution of 3D sensors and the inevitable mutual occlusion
  between objects, 3D scans of real scenes are commonly incomplete. Previous scene
  completion methods struggle to capture long-range spatial context, resulting in
  unsatisfactory completion results. To alleviate the problem, we propose a novel
  Dual-Scale Transformer Network (DST-Net) that efficiently utilizes both long-range
  and short-range spatial context information to improve the quality of 3D scene completion.
  To reduce the heavy computation cost of extracting long-range features via transformers,
  DST-Net adopts a self-supervised two-stage completion strategy. In the first stage,
  we split the input scene into blocks and perform completion on individual blocks.
  In the second stage, the blocks are merged together as a whole and then further
  refined to improve completeness. More importantly, we propose a contrastive attention
  training strategy to encourage the transformers to learn distinguishable features
  for better scene completion. Experiments on datasets of Matterport3D, ScanNet, and
  ICL-NUIM demonstrate that our method can generate better completion results, and
  our method outperforms the state-of-the-art methods quantitatively and qualitatively.
tags:
- Training
- Three-dimensional displays
- Transformers
- Color
- Computer vision
- Costs
- Semantics
---
