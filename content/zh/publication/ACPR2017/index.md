---
title: 'Compressing YOLO Network by Compressive Sensing'

# Authors
authors:
  - Yirui Wu
  - Zhouyu Meng
  - Shivakumara Palaiahnakote
  - Tong Lu

date: '2017-10-01'
doi: '10.1109/ACPR.2017.11'

# Conference details
publishDate: '2017-10-01'

# Publication type
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2017 4th IAPR Asian Conference on Pattern Recognition (ACPR)
publication_short: ACPR'17(EI)
# Conference proceedings and pages
pages: '19-24'

# Abstract
abstract: 
  Object detection is one of the fundamental challenges in pattern recognition community. Recently, convolutional neural networks (CNN) are increasingly exploited in object detection, showing their promising potentials of generatively discovering patterns from quantity of labeled images. Among CNN-based systems, we focus on one state-of-the-art architecture designed for fast object detection, named as YOLO. However, YOLO, as well as CNN-based systems are hard to deploy on embedded systems due to their computationally and storage intensive. In this paper, we propose to compress YOLO network by compressive sensing, which exploits in-herent redundancy property of parameters in layers of CNN architecture, leading to decrease the computation and storage cost. We firstly convert parameter matrix to frequency domain through discrete cosine transform (DCT). Due to the smooth property of parameters when processing images, the resulting frequency matrix are dominated by low-frequency components. Next, we prune high-frequency part to make the frequency matrix sparse. After pruning, we sample the frequency matrix with distributed random Gaussian matrix. Finally, we retrain the network to finetune the remaining parameters. We evaluate the proposed compress method on VOC 2012 dataset and show it outperforms one latest compression approach.


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
