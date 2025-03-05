---
title: 'DGECN: A Depth-Guided Edge Convolutional Network for End-to-End 6D Pose Estimation'
authors:
- Tuo Cao
- Fei Luo
- Yanping Fu
- Wenxiao Zhang
- Shengjie Zheng
- Chunxia Xiao
date: '2022-06-01'
publishDate: '2025-03-05T16:14:07.308789Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern
  Recognition (CVPR)*'
doi: 10.1109/CVPR52688.2022.00376
abstract: 'Monocular 6D pose estimation is a fundamental task in computer vision.
  Existing works often adopt a twostage pipeline by establishing correspondences and
  utilizing a RANSAC algorithm to calculate 6 degrees-of-freedom (6DoF) pose. Recent
  works try to integrate differentiable RANSAC algorithms to achieve an end-to-end
  6D pose estimation. However, most of them hardly consider the geometric features
  in 3D space, and ignore the topology cues when performing differentiable RANSAC
  algorithms. To this end, we proposed a Depth-Guided Edge Convolutional Network (DGECN)
  for 6D pose estimation task. We have made efforts from the following three aspects:
  1) We take advantages of estimated depth information to guide both the correspondences-extraction
  process and the cascaded differentiable RANSAC algorithm with geometric information.
  2)We leverage the uncertainty of the estimated depth map to improve accuracy and
  robustness of the output 6D pose. 3) We propose a differentiable Perspective-n-Point(PnP)
  algorithm via edge convolution to explore the topology relations between 2D-3D correspondences.
  Experiments demonstrate that our proposed network outperforms current works on both
  effectiveness and efficiency.'
---
