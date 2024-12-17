---
title: 'CT-CAD: Context-Aware Transformers for End-to-End Chest Abnormality Detection on X-Rays'

# Authors
authors:
  - Qiran Kong
  - Yirui Wu
  - Chi Yuan
  - Yongli Wang

# Author notes (optional)
author_notes:
  - 'Student'
  - 'Corresponding author'

date: '2021-12-09'
doi: '10.1109/BIBM52615.2021.9669743'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-09'

# Publication type
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Bioinformatics and Biomedicine
publication_short: IEEE BIBM'21(CCF-B)

abstract: Supervised based deep learning methods have achieved great success in medical image analysis domain. Essentially, most of them could be further improved by exploring and embedding context knowledge for accuracy boosting. Moreover, they generally suffer from slow convergency and high computing cost, which prevents their usage in a practical scenario. To tackle these problems, we present CT-CAD, context-aware transformers for end-to-end chest abnormality detection on X-Ray images. The proposed method firstly constructs a context-aware feature extractor, which enlarges receptive fields to encode multi-scale context information via an iterative feature fusion scheme and dilated context encoding blocks. Afterwards, deformable transformer detector are built for category classification and location regression, where their deformable attention block attend to a small set of key sampling points, thus allowing the transformer to focus on feature subspace and accelerate convergence speed. Through comparative experiments on Vinbig Chest and Chest Det10 Datasets, the proposed CT-CAD demonstrates its effectiveness and outperforms the existing methods in mAP and training epoches.


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
