---
title: 'New COLD Feature Based Handwriting Analysis for Ethnicity/Nationality Identification'

# Authors
authors:
  - Sauradip Nag
  - Palaiahnakote Shivakumara
  - Yirui Wu
  - Umapada Pal
  - Tong Lu

date: '2018-08-01'
doi: '10.1109/ICFHR-2018.2018.00097'

# Conference details
publishDate: '2018-08-01'

# Publication type
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 16th International Conference on Frontiers in Handwriting Recognition (ICFHR 2018)
publication_short: ICFHR'18(EI)

# Conference proceedings and pages
pages: '523-527'

# Abstract
abstract: 
  Identifying crime for forensic investigating teams when crimes involve people of different nationals is challenging. This paper proposes a new method for ethnicity (nationality) identification based on Cloud of Line Distribution (COLD) features of handwriting components. The proposed method, at first, uses tangent angle of the contour pixels in each row and the mean of intensity values of each row for segmenting text lines. For segmented text lines, we use tangent angle and direction of base lines to remove rule lines in the image. We use polygonal approximation for finding dominant points for contours of edge components. Then the proposed method connects the nearest dominant points of every dominant point, which results in line segments of dominant point pairs. For each line segment, the proposed method estimates angle and length, which gives a point in polar domain. For all the line segments, the proposed method generates dense points in polar domain, which results in COLD distribution. As character component shapes change, according to nationals, the shape of the distribution changes. This observation is extracted based on distance from pixels of distribution to Principal Axis of the distribution. Then the features are subjected to an SVM classifier for identifying nationals. Experiments are conducted on a complex dataset, which show the proposed method is effective and outperforms the existing method.


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
