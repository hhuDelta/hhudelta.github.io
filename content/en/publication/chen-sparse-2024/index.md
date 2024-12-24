---
title: 'Sparse Enhanced Network: An Adversarial Generation Method for Robust Augmentation
  in Sequential Recommendation'
authors:
- Junyang Chen
- Guoxuan Zou
- Pan Zhou
- Yirui Wu
- Zhenghan Chen
- Houcheng Su
- Huan Wang
- Zhiguo Gong
date: '2024-01-01'
publishDate: '2024-12-24T07:13:10.099096Z'
publication_types:
- paper-conference
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence(CCF-A)*'
doi: 10.1609/AAAI.V38I8.28669
abstract: Sequential Recommendation plays a significant role in daily recommendation
  systems, such as e-commerce platforms like Amazon and Taobao. However, even with
  the advent of large models, these platforms often face sparse issues in the historical
  browsing records of individual users due to new users joining or the introduction
  of new products. As a result, existing sequence recommendation algorithms may not
  perform well. To address this, sequence-based data augmentation methods have garnered
  attention. Existing sequence enhancement methods typically rely on augmenting existing
  data, employing techniques like cropping, masking prediction, random reordering,
  and random replacement of the original sequence. While these methods have shown
  improvements, they often overlook the exploration of the deep embedding space of
  the sequence. To tackle these challenges, we propose a Sparse Enhanced Network (SparseEnNet),
  which is a robust adversarial generation method. SparseEnNet aims to fully explore
  the hidden space in sequence recommendation, generating more robust enhanced items.
  Additionally, we adopt an adversarial generation method, allowing the model to differentiate
  between data augmentation categories and achieve better prediction performance for
  the next item in the sequence. Experiments have demonstrated that our method achieves
  a remarkable 4-14% improvement over existing methods when evaluated on the real-world
  datasets. https://github.com/junyachen/SparseEnNet
url_code: 'https://github.com/junyachen/SparseEnNet'
---
