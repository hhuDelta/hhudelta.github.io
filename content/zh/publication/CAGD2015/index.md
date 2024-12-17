---
title: 'HIRM: A Handle-Independent Reduced Model for Incremental Mesh Editing'

# Authors
authors:
  - Yirui Wu
  - Oscar Kin-Chung Au
  - Chiew-Lan Tai
  - Tong Lu

date: '2015-03-24'
doi: '10.1016/j.cagd.2015.03.001'

# Schedule page publish date (NOT publication's date).
publishDate: '2015-03-24'

# Publication type.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: Computer Aided Geometric Design
publication_short: CAGD'15(SCI,CCF-B)

# Volume and issue
volume: '35-36'
pages: '56-68'

# Abstract
abstract: 'Most existing handle-based mesh deformation methods require costly re-computation for every handle set updating, namely, adding or removing of handles on the mesh surface. In this paper, we propose a reduced deformation model that is independent of handle configuration, allowing users to dynamically update the handle set without noticeable waiting time. We represent the deformation space of a mesh as propagation fields defined by only the mesh geometry, independent of the handle set. We define the propagation fields as selected eigenvectors of the Laplacian operator and adopt the transformations of isolines sampled from the fields as the deformation descriptors. In this way, the deformation descriptors are pre-computed before handle specification. During interactive manipulation, constraints generated from the handles are incorporated into the deformation system in real time. Our method therefore supports incremental mesh editing where the user can freely define different handle sets to edit different parts of the shape without waiting for long re-computation. Our reduced model is scalable since the updating time per iteration is independent of the mesh size and the number of handles. We demonstrate the effectiveness of the proposed deformation method and compare its performance with related reduced deformation models.'


tags: []

# Display this page in the Featured widget?
featured: true


url_pdf: ''

---