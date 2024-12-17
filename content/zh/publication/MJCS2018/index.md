---
title: 'Compressive Sensing Based Convolutional Neural Network for Object Detection'

# Authors
authors:
  - Yirui Wu
  - Zhouyu Meng
  - Palaiahnakote Shivakumara
  - Tong Lu

date: '2018-11-01'
doi: '10.22452/mjcs.vol33no1.5'

# Schedule page publish date (NOT publication's date).
publishDate: '2018-11-01'

# Publication type.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: Malaysian Journal of Computer Science
publication_short: MJCS'18(SCI)

# Volume and issue
volume: 33
issue: 1
pages: '78-89'

# Abstract
abstract: 'Deep neural networks (DNN) have shown significant performance in several domains including computer vision and machine learning. Convolutional Neural Networks (CNN), known as a particular type of DNN, have shown their promising potentials in discovering vision-based patterns from quantity of labeled images. Many CNN-based algorithms are thus proposed to solve the problem of object detection and object recognition. However, CNN-based systems are hard to deploy on embedded systems due to their computationally and storage intensive. In this paper, we propose a method to compress convolutional neural network to decrease its computation and storage cost by exploiting inherent redundancy property of parameters in different kinds of layers of CNN architecture. During the compression, we firstly construct parameter matrices from different kinds of layers and convert parameter matrices to frequency domain through discrete cosine transform (DCT). Due to the smooth property of parameters when processing images, the resulting frequency matrices are dominated by low-frequency components. We thus prune high-frequency part to emphasize the dominating part of frequency matrix and make the frequency matrix sparse. Then, the sparse frequency matrices are sampled with distributed random Gaussian matrix under the guiding of compress sensing. Finally, we retrain the network with the sampling matrices to fine-tune the remaining parameters. We evaluate the proposed method on several typical convolutional neural network and show it outperforms one latest compression approach.'


tags: []

# Display this page in the Featured widget?
featured: true


url_pdf: ''

---