---
title: 'CRA-PCN: Point Cloud Completion with Intra-and Inter-level Cross-Resolution
  Transformers'
authors:
- Yi Rong
- Haoran Zhou
- Lixin Yuan
- Cheng Mei
- Jiahao Wang
- Tong Lu
date: '2024-01-01'
publishDate: '2024-12-18T16:43:54.971648Z'
publication_types:
- paper-conference
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence*'
doi: /10.1609/aaai.v38i5.28268
abstract: "Point cloud completion is an indispensable task for recovering complete point clouds due to incompleteness caused by occlusion, limited sensor resolution, etc. The family of coarse-to-fine generation architectures has recently exhibited great success in point cloud completion and gradually became mainstream. In this work, we unveil one of the key ingredients behind these methods: meticulously devised feature extraction operations with explicit cross-resolution aggregation. We present Cross-Resolution Transformer that efficiently performs cross-resolution aggregation with local attention mechanisms. With the help of our recursive designs, the proposed operation can capture more scales of features than common aggregation operations, which is beneficial for capturing fine geometric characteristics. While prior methodologies have ventured into various manifestations of inter-level cross-resolution aggregation, the effectiveness of intra-level one and their combination has not been analyzed. With unified designs, Cross-Resolution Transformer can perform intra- or inter-level cross-resolution aggregation by switching inputs. We integrate two forms of Cross-Resolution Transformers into one up-sampling block for point generation, and following the coarse-to-fine manner, we construct CRA-PCN to incrementally predict complete shapes with stacked up-sampling blocks. Extensive experiments demonstrate that our method outperforms state-of-the-art methods by a large margin on several widely used benchmarks. Codes are available at https://github.com/EasyRy/CRA-PCN."
url_code: 'https://github.com/EasyRy/CRA-PCN'
---
