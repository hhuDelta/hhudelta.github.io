---
title: Few-shot Semantic Segmentation via Perceptual Attention and Spatial Control
authors:
- Guangchen Shi
- Wei Zhu
- Yirui Wu
- Danhuai Zhao
- Kang Zheng
- Tong Lu
date: '2024-01-01'
publishDate: '2024-12-24T07:13:10.078879Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 32nd ACM International Conference on Multimedia(CCF-A)*'
doi: 10.1145/3664647.3681338
abstract: 'Few-shot semantic segmentation (FSS) aims to locate pixels of unseen classes with clues from a few labeled samples. Recently, thanks to profound prior knowledge, diffusion models have been expanded to achieve FSS tasks.
However, due to probabilistic noising and denoising processes, it is difficult for them to maintain spatial relationships between inputs and outputs, leading to inaccurate segmentation masks. To address this issue, we propose a Diffusion-based Segmentation network (DiffSeg), which decouples probabilistic denoising and segmentation processes.
Specifically, DiffSeg leverages attention maps extracted from a pretrained diffusion model as support-query interaction information to guide segmentation, which mitigates the impact of probabilistic processes while benefiting from rich prior knowledge of diffusion models.
In the segmentation stage, we present a Perceptual Attention Module (PAM), where two cross-attention mechanisms capture semantic information of support-query interaction and spatial information produced by the pretrained diffusion model. Furthermore, a self-attention mechanism within PAM ensures a balanced dependence for segmentation, thus preventing inconsistencies between the aforementioned semantic and spatial information.
Additionally, considering the uncertainty inherent in the generation process of diffusion models, we equip DiffSeg with a Spatial Control Module (SCM), which models spatial structural information of query images to control boundaries of attention maps, thus aligning the spatial location between knowledge representation and query images.
Experiments on PASCAL-5i and COCO datasets show that DiffSeg achieves new state-of-the-art performance with remarkable advantages.'
tags:
- diffusion model
- few-shot segmentation
- perceptual attention
- spatial control
---
