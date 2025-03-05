---
title: 'MegaSurf: Scalable Large Scene Neural Surface Reconstruction'
authors:
- Yusen Wang
- Kaixuan Zhou
- Wenxiao Zhang
- Chunxia Xiao
date: '2024-01-01'
publishDate: '2025-03-05T16:14:07.397270Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 32nd ACM International Conference on Multimedia(CCF-A)*'
doi: 10.1145/3664647.3681303
abstract: We present MegaSurf, a Neural Surface Reconstruction (NSR) framework to
  reconstruct 3D models of large scenes from aerial images. Many methods utilize geometry
  cues to overcome the shape-radiance ambiguity, which would produce large geometric
  errors. In addition, directly using inevitable imprecise geometric cues would lead
  to degradation in the reconstruction results, especially on large-scale scenes.
  To address this phenomenon, we propose a Learnable Geometric Guider (LG Guider)
  to learn a sampling field from reliable geometric cues. The LG Guider decides which
  position should fit the input radiance and can be continuously refined by rendering
  loss. Our MegaSurf uses a Divide-and-Conquer training strategy to address the synchronization
  issue between the Guider and the lagging NSR's radiance field. This strategy enables
  the Guider to transmit the information it carried to the radiance field without
  being disrupted by the gradients back-propagated from the lagging rendering loss
  at the early stage of training. Furthermore, we propose a Fast PatchMatch MVS module
  to derive the geometric cues in the planer regions that help overcome ambiguity.
  Experiments on several aerial datasets show that MegaSurf can overcome ambiguity
  while preserving high-fidelity details. Compared to SOTA methods, MegaSurf achieves
  superior reconstruction accuracy of large scenes and boosts the acquisition of geometric
  cues more than four times.
tags:
- derived from neural radiance field
- neural surface reconstruction (nsr)
- recently
links:
- name: URL
  url: https://doi.org/10.1145/3664647.3681303
---
