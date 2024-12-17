---
title: 'Em-SLAM: a Fast and Robust Monocular SLAM Method for Embedded Systems'

# Authors
authors:
  - Yirui Wu
  - Zhikai Li
  - Shivakumara Palaiahnakote
  - Tong Lu

date: '2018-08-01'
doi: '10.1109/ICPR.2018.8545173'

# Conference details
publishDate: '2018-08-01'

# Publication type
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 24th International Conference on Pattern Recognition (ICPR 2018)
publication_short: ICPR'18(CCF-C)

# Conference proceedings and pages
pages: '2456-2460'

# Abstract
abstract: 'Simultaneous Localization and Mapping (SLAM) is difficult to deploy in the embedded systems due to its high computation cost and stable input requirements. Building on excellent algorithms of recent years, we present Em-SLAM, a monocular SLAM method which is fast and robust in the embedded system. We present Em-SLAM in three stages comprising initial pose estimation, iterative pose optimization and correspondences, and mapping with nearest frame queue. During the first stage, we perform stable initial pose estimation based on the matched ORB features extracted around the selected key points. Regarding initial pose and corresponding key points as input, the second stage of Em-SLAM iteratively optimizes these inputs values by tracking key points in the new frames. At the last stage, we firstly determine keyframes with the help of the proposed nearest frame queue and then design a greedy search algorithm to find matched ORB features between keyframes, which are adopted for compact and robust map reconstruction. Due to the special designs for the embedded systems, Em-SLAM demonstrates a high accurate and fast performance on the embedded system for all SLAM tasks: tracking, mapping and loop closing. We evaluate Em-SLAM on he most popular datasets by comparing with one latest SLAM method.'


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
