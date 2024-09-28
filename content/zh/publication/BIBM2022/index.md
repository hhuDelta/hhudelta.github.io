---
title: 'Learning Group-Disentangled Representation for Interpretable Thoracic Pathologic Prediction'

# Authors
authors:
  - Hao Li
  - Yirui Wu
  - Hexuan Hu
  - Hu Lu
  - Shaohua Wan

# Author notes (optional)
author_notes:
  - 'Student'
  - 'Corresponding author'

date: '2022-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Bioinformatics and Biomedicine
publication_short: IEEE BIBM'22(CCF-B)

abstract: Deep learning methods have shown significant performance in medical image analysis tasks. However, they generally act like ”black box” without explanations in both feature extraction and decision processes, leading to lack of clinical insights and high risk assessments. To aid deep learning in envisioning diseases with visual clues, we propose Representation Group-Disentangling Network (RGD-Net), which can completely disentangle feature space of input X-ray images into several independent feature groups, each corresponding to a specific disease. Taking several semantically related and labeled X-ray images as input, RGD-Net firstly extracts completely group-disentangled representations of diseases through Group-Disentangle Module, which applies group-swap and linking operations to construct latent space by enforcing semantic consistency of attributes. To prevent learning degenerate representations defined as shortcut problem, we further introduce adversarial constricts on mapping from features to diseases, thus avoiding model collapse with former free-form disentanglement. Experiments on chestxray-14 and ChestXpert datasets demonstrate that RGD-Net are effective in predicting diseases with remarkable advantages, which leverage potential factors contributing to different diseases, thus enhancing interpretability in working patterns of deep learning methods.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
