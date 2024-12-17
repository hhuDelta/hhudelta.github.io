---
title: 'TK-Text: Multi-shaped Scene Text Detection via Instance Segmentation'

# Authors
authors:
  - Xiaoge Song
  - Yirui Wu
  - Wenhai Wang
  - Tong Lu

date: '2020'
doi: '10.1007/978-3-030-37734-2_17'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01'

# Publication type
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'MultiMedia Modeling: 26th International Conference, MMM 2020'
publication_short: MMM'20(CCF-C)

# Conference proceedings and pages
pages: '201-213'

# Abstract
abstract: 
  Benefit from the development of deep neural networks, scene text detectors have progressed rapidly over the past few years and achieved outstanding performance on several standard benchmarks. However, most existing methods adopt quadrilateral bounding boxes to represent texts, which are usually inadequate to deal with multi-shaped texts such as the curved ones. To keep consist detection performance on both quadrilateral and curved texts, we present a novel representation, i.e., text kernel, for multi-shaped texts. On the basis of text kernel, we propose a simple yet effective scene text detection method, named as TK-Text. The proposed method consists of three steps, namely text-context-aware network, segmentation map generation and text kernel based post-clustering. During text-context-aware network, we construct a segmentation-based network to extract feature map from natural scene images, which are further enhanced with text context information extracted from an attention scheme TKAB. In segmentation map generation, text kernels and rough boundaries of text instances are segmented based on the enhanced feature map. Finally, rough text instances are gradually refined to generate accurate text instances by performing clustering based on text kernel. Experiments on public benchmarks including SCUT-CTW1500, ICDAR 2015 and ICDAR 2017 MLT demonstrate that the proposed method achieves competitive detection performance comparing with the existing methods.


tags: []

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
