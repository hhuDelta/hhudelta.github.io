---
title: 'KT-Net: Knowledge Transfer for Unpaired 3D Shape Completion'
authors:
- Zhen Cao
- Wenxiao Zhang
- Xin Wen
- Zhen Dong
- Yu-Shen Liu
- Xiongwu Xiao
- Bisheng Yang
date: '2023-06-01'
publishDate: '2025-03-05T16:14:07.330676Z'
publication_types:
- paper-conference
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence*'
doi: 10.1609/aaai.v37i1.25101
abstract: Unpaired 3D object completion aims to predict a complete 3D shape from an
  incomplete input without knowing the correspondence between the complete and incomplete
  shapes. In this paper, we propose the novel KTNet to solve this task from the new
  perspective of knowledge transfer. KTNet elaborates a teacher-assistant-student
  network to establish multiple knowledge transfer processes. Specifically, the teacher
  network takes complete shape as input and learns the knowledge of complete shape.
  The student network takes the incomplete one as input and restores the corresponding
  complete shape. And the assistant modules not only help to transfer the knowledge
  of complete shape from the teacher to the student, but also judge the learning effect
  of the student network. As a result, KTNet makes use of a more comprehensive understanding
  to establish the geometric correspondence between complete and incomplete shapes
  in a perspective of knowledge transfer, which enables more detailed geometric inference
  for generating high-quality complete shapes. We conduct comprehensive experiments
  on several datasets, and the results show that our method outperforms previous methods
  of unpaired point cloud completion by a large margin. Code is available at https://github.com/a4152684/KT-Net.
links:
- name: URL
  url: https://ojs.aaai.org/index.php/AAAI/article/view/25101
---
