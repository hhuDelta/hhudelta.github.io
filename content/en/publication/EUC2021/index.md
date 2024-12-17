---
title: 'PolarText: Single-stage Scene Text Detection with Polar Representation'

# Authors
authors:
  - Qiran Kong
  - Yirui Wu
  - Shaohua Wan

date: '2021-10-01'
doi: '10.1109/EUC53437.2021.00030'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-01'

# Publication type
publication_types: ['paper-conference']


# Publication name and optional abbreviated publication name.
publication: 2021 IEEE 19th International Conference on Embedded and Ubiquitous Computing (EUC)
publication_short: EUC'21(Best Paper Award,EI)

# Conference proceedings and pages
pages: '1-8'

# Abstract
abstract: 
  Although deep learning has achieved great success in object detection recently, scene text detection remains a challenging task due to inherent difficulties in locating texts in complex scenes. Many approaches are inspired by segmentation methods to detect arbitrarily shaped scene text. However, most segmentation-based methods are computationally expensive and require significant refinements for accurate results. To address this issue, we propose PolarText, a novel single-stage method that detects text regions by generating contour points in polar coordinates. PolarText reduces computation costs by directly regressing contour points instead of pixels and better aligns with the intrinsic characteristics of text instances using centers and contours, mitigating boundary pixel mislabeling caused by pixel-level labeling. The network introduces Polar IoU loss and polar centerness to adapt effective paradigms from box representation for polar representation. Additionally, we incorporate a bounding box branch to handle text detection, as most text instances are approximately rectangular. Experimental results on CTW 1500 and ICDAR 2015 datasets show that PolarText achieves superior accuracy and efficiency compared to existing methods.


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
