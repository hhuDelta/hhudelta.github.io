---
title: 'End-PolarT: Polar Representation for End-to-End Scene Text Detection'

# Authors
authors:
  - Yirui Wu
  - Qiran Kong
  - Cheng Qian
  - Michele Nappi
  - Shaohua Wan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
#   - 'Equal contribution'
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-11-28'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-28'

# Publication type.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: Big Data Research
publication_short: BigDR

abstract: Deep learning has achieved great success in text detection, where recent methods adopt inspirations from segmentation to detect scene texts. However, most segmentation based methods have high computation cost in pixel-level classification and post refinements. Moreover, they still faces challenges like arbitrary directions, curved texts, illumination and so on. Aim to improve detection accuracy and computation cost, we propose an end-to-end and single-stage method named as End-PolarT network by generating contour points in polar coordinates for text detection. End-PolarT not only regress locations of contour points instead of pixels to relieve high computation cost, but also fits with intrinsic characteristics of text instances by centers and contours to suppress mislabeling boundary pixels. To cope with polar representation, we further propose polar IoU and centerness as key parts of loss functions to generate effective paradigms for text detection. Compared with the existing methods, End-PolarT achieves superior results by testing on several public datasets, thus keeping balance between efficiency and effectiveness in complicated scenes.

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
