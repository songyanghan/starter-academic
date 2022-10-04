---
abstract: Sharing information between connected and autonomous vehicles (CAVs)
  fundamentally improves the performance of collaborative object detection for
  self-driving. However, CAVs still have uncertainties on object detection due
  to practical challenges, which will affect the later modules in self-driving
  such as planning and control. Hence, uncertainty quantification is crucial for
  safety-critical systems such as CAVs. Our work is the first to estimate the
  uncertainty of collaborative object detection. We propose a novel uncertainty
  quantification method, called Double-M Quantification, which tailors a moving
  block bootstrap (MBB) algorithm with direct modeling of the multivariant
  Gaussian distribution of each corner of the bounding box. Our method captures
  both the epistemic uncertainty and aleatoric uncertainty with one inference
  pass based on the offline Double-M training process. And it can be used with
  different collaborative object detectors. Through experiments on the
  comprehensive collaborative perception dataset, we show that our Double-M
  method achieves more than 4$\times$ improvement on uncertainty score and more
  than 3\% accuracy improvement, compared with the state-of-the-art uncertainty
  quantification methods. Our code is public on 
  https://coperception.github.io/double-m-quantification/.
slides: ""
url_pdf: "https://arxiv.org/pdf/2209.08162.pdf"
publication_types:
  - "1"
authors:
  - Sanbao Su
  - Yiming Li
  - Sihong He
  - admin
  - Chen Feng
  - Caiwen Ding
  - Fei Miao
author_notes: []
publication: ""
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: "https://coperception.github.io/double-m-quantification/"
title: Uncertainty Quantification of Collaborative Detection for Self-Driving
doi: ""
featured: false
tags: []
projects:
  - uncertainty-quantification-on-collaborative-perception
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: ./uq.png
date: 2022-09-22T23:29:00.499Z
url_slides: ""
publishDate: 2022-09-22T23:29:00.499Z
url_poster: ""
url_code: ""
---


