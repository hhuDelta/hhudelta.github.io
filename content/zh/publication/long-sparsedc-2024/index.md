---
title: 'SparseDC: Depth completion from sparse and non-uniform inputs'
authors:
- Chen Long
- Wenxiao Zhang
- Zhe Chen
- Haiping Wang
- Yuan Liu
- Peiling Tong
- Zhen Cao
- Zhen Dong
- Bisheng Yang
date: '2024-01-01'
publishDate: '2025-03-05T16:14:07.337886Z'
publication_types:
- article-journal
publication: '*Information Fusion*'
doi: 10.1016/j.inffus.2024.102470
abstract: We propose SparseDC, a model for Depth Completion from Sparse and non-uniform
  inputs. Unlike previous methods focusing on completing fixed distributions on benchmark
  datasets (e.g., NYU with 500 points, KITTI with 64 lines), SparseDC is specifically
  designed to handle depth maps with poor quality in real usage. Our SparseDC makes
  two major contributions. First, we design a simple strategy, called SFFM, to improve
  the robustness under sparse inputs by explicitly filling the unstable depth features
  with stable image features. Second, we suggest utilizing a two-branch feature embedder
  in order to forecast the exact local geometry of regions with available depth values
  and accurate structures in regions with no depth. The key of the embedder is an
  uncertainty-based feature fusion module called UFFM to balance the local and long-term
  information extracted by CNNs and ViTs. Numerous experiments conducted both indoors
  and outdoors show how robust and effective our framework is when facing sparse and
  non-uniform input depths. And SparseDC outperforms the current state-of-the-art
  (SOTA) method, CFormer, with varying inputs. We use less parameters (38.2M textless
  45M) and achieve a +18.6% increase in the REL metric and a +9.9% increase in the
  RMSE metric on NYU Depth dataset. The pre-trained model and the complete code repository
  can be accessed at https://github.com/WHU-USI3DV/SparseDC.
tags:
- Depth completion
- Information fusion
- Uncertainty
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1566253524002483
---
