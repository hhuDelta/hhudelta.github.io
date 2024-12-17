---
title: 'Multiple Attention Encoded Cascade R-CNN for Scene Text Detection'

# Authors
authors:
  - Yirui Wu
  - Wenxiang Liu
  - Shaohua Wan

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2021-08-01'
doi: '10.1016/j.jvcir.2021.103261'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-01'

# Publication type.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: Journal of Visual Communication and Image Representation
publication_short: JVCIR'21(SCI, CCF-C)

# Volume and issue
volume: 80
pages: '103261'

# Abstract
abstract: 'Inspired by instance segmentation algorithms, researchers have proposed a variety of segmentation-based methods for text detection, achieving remarkable results on scene text with arbitrary orientation and large aspect ratios. Following their success, we believe cascade architecture and extracting contextual information in multiple aspects are powerful in boosting performance on the basis of segmentation-based methods, especially in decreasing false positive texts in complex natural scenes. Based on such considerations, we propose a multiple-context-aware and cascade CNN structure, which appropriately encodes multiple categories of context information into a cascade R-CNN framework. Specifically, the proposed method consists of two stages: feature generation and cascade detection. In the first stage, we define the ISTK (Isolated Selective Text Kernel) module to refine the feature map, which sequentially encodes channel-wise and kernel-size attention information by designing multiple branches and different kernel sizes in isolated form. Afterwards, we build long-range spatial dependencies in the feature map via non-local operations. Built on the contextual feature map, the Cascade Mask R-CNN structure progressively refines the accurate boundaries of text instances with a multi-stage framework. We conduct comparative experiments on ICDAR2015 and 2017-MLT datasets, where the proposed method outperforms comparative methods in terms of effectiveness and efficiency.'


tags: []

# Display this page in the Featured widget?
featured: true


url_pdf: ''

---