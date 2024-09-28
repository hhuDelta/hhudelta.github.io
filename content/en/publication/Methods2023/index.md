---
title: 'Interpretable Thoracic Pathologic Prediction via Learning Group-Disentangled Representation'

# Authors
authors:
  - Hao Li
  - Yirui Wu
  - Hexuan Hu
  - Hu Lu
  - Qian Huang
  - Shaohua Wan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-10-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01'

# Publication type.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: Methods
publication_short: Methods'23(SCI)

abstract: Deep learning has brought a significant progress in medical image analysis. However, their lack of interpretability might bring high risk for wrong diagnosis with limited clinical knowledge embedding. In other words, we believe it's crucial for humans to interpret how deep learning work for medical analysis, thus appropriately adding knowledge constraints to correct the bias of wrong results. With such purpose, we propose Representation Group-Disentangling Network (RGD-Net) to explain the process of feature extraction and decision making inside deep learning framework, where we completely disentangle feature space of input X-ray images into independent feature groups, and each group would contribute to diagnose of a specific disease. Specifically, we first state problem definition for interpretable prediction with auto-encoder structure. Then, group-disentangled representations are extracted from input X-ray images with the proposed Group-Disentangle Module, which constructs semantic latent space by enforcing semantic consistency of attributes. Afterwards, adversarial constricts on mapping from features to diseases are proposed to prevent model collapse during training. Finally, a novel design of local tuning medical application is proposed based on RGB-Net, which is capable to aid clinicians for reasonable diagnosis. By conducting quantity of experiments on public datasets, RGD-Net have been superior to comparative studies by leveraging potential factors contributing to different diseases. We believe our work could bring interpretability in digging inherent patterns of deep learning on medical image analysis.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

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
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
