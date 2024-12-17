---
title: "Deconfound Semantic Shift and Incompleteness in Incremental Few-shot Semantic Segmentation"
authors:
  - Yirui Wu
  - Yuhang Xia
  - Hao Li
  - Lixin Yuan
  - Junyang Chen
  - Jun Liu
  - Tong Lu
  - Shaohua Wan

# Author notes (optional)
author_notes:

date: '2024-12-10'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-10'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Association for the Advancement of Artificial Intelligence
publication_short: AAAI'25(CCF-A)

abstract:  Incremental few-shot semantic segmentation (IFSS) expands segmentation capacity of the trained model to segment new class images with few samples. However, semantic meanings may shift from background to object class or vice versa dur ing incremental learning. Moreover, new-class samples of ten lack representative attribute features when the new class greatly differs from the pre-learned old class. In this paper, we propose a causal framework to discuss the cause of semantic shift and incompleteness in IFSS, and we deconfound the revealed causal effects from two aspects. First, we propose a Causal Intervention Module (CIM) to resist semantic shift. CIM progressively and adaptively updates prototypes of old class, and removes the confounder in an intervention manner. Second, a Prototype Refinement Module (PRM) is proposed to complete the missing semantics. In PRM, knowledge gained from the episode learning scheme assists in fusing fea tures of new-class and old-class prototypes. Experiments on both PASCAL-VOC 2012 and ADE20k benchmarks demon strate the outstanding performance of our method.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/LegendSherlock/Deconfound-IFSS'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
<!-- ![screen reader text](featured1.png)
![screen reader text](featured2.png) -->