---
title: 'Context-Aware Attention LSTM Network for Flood Prediction'

# Authors
authors:
  - Yirui Wu
  - Zhaoyang Liu
  - Weigang Xu
  - Jun Feng
  - Shivakumara Palaiahnakote
  - Tong Lu

date: '2018-08-01'
doi: '10.1109/ICPR.2018.8545385'

# Conference details
publishDate: '2018-08-01'

# Publication type
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 24th International Conference on Pattern Recognition (ICPR 2018)
publication_short: ICPR'18(CCF-C)

# Conference proceedings and pages
pages: '1301-1306'

# Abstract
abstract: To minimize the negative impacts brought by floods, researchers from pattern recognition community utilize artificial intelligence based methods to solve the problem of flood prediction. Inspired by the significant power of Long Short-Term Memory (LSTM) networks in modeling the dynamics and dependencies of sequential data, we intend to utilize LSTM networks to predict sequential flow rate values based on a set of collected flood factors. Since not all factors are informative for flood prediction and the irrelevant factors often bring a lot of noise, we need to pay more attention to the informative ones. However, original LSTM doesn't have strong attention capability. Hence we propose an context-aware attention LSTM (CA-LSTM) network for flood prediction, which is capable to selectively focus on informative factors. During training, the local context-aware attention model is constructed by learning probability distributions between flow rate and hidden output of each LSTM cell. During testing, the learned local attention model assign weights to adjust relations between input factors and predictions at all steps of LSTM network. We conduct experiments on a flood dataset with several comparative methods to demonstrate high accuracy of the proposed method and the effectiveness of the proposed context-aware attention model.


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
