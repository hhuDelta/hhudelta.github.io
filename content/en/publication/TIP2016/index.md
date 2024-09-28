---
title: 'Contour Restoration of Text Components for Recognition in Video/Scene Images'

# Authors
authors:
  - Yirui Wu
  - Palaiahnakote Shivakumara
  - Tong Lu
  - Chew Lim Tan
  - Michael Blumenstein
  - G. Hemantha Kumar

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2016-12-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2016-12-01'

# Publication type.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Image Processing
publication_short: IEEE TIP'16(CCF-A)

abstract: Text recognition in video/natural scene images has gained significant attention in the field of image processing in many computer vision applications, which is much more challenging than recognition in plain background images. In this paper, we aim to restore complete character contours in video/scene images from gray values, in contrast to the conventional techniques that consider edge images/binary information as inputs for text detection and recognition. We explore and utilize the strengths of zero crossing points given by the Laplacian to identify stroke candidate pixels (SPC). For each SPC pair, we propose new symmetry features based on gradient magnitude and Fourier phase angles to identify probable stroke candidate pairs (PSCP). The same symmetry properties are proposed at the PSCP level to choose seed stroke candidate pairs (SSCP). Finally, an iterative algorithm is proposed for SSCP to restore complete character contours. Experimental results on benchmark databases, namely, the ICDAR family of video and natural scenes, Street View Data, and MSRA data sets, show that the proposed technique outperforms the existing techniques in terms of both quality measures and recognition rate. We also show that character contour restoration is effective for text detection in video and natural scene images.

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
