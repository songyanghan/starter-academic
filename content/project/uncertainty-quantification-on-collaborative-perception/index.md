---
title: Uncertainty Quantification on Collaborative Perception
date: 2022-09-23T01:20:26.156Z
tags:
- Deep Learning
draft: false
external_link: ""
links: []
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
Multi-agent collaborative perception has been proposed to leverage the viewpoints of other agents to improve the detection accuracy compared with the individual viewpoint. Recent research has shown the effectiveness of early, late, and intermediate fusion of collaborative perception, which respectively transmits raw data, output bounding boxes, and intermediate features, and the improved collaborative perception results will benefit the self-driving decisions of connected and autonomous vehicles (CAVs). However, CAVs may still have uncertainties on perception due to out-of-distribution objects, sensor measurement noise, or poor weather. Even a slightly false detection can lead the autonomous vehicle's driving policy to a completely different action. Therefore, it is crucial to quantify the uncertainty of collaborative perception for safety-critical systems such as CAVs.

We designed the uncertainty qualification algorithm for the preception of connected autonomous vehicles (CAVs) in order to improve the performance of the later module of autonomous driving such as prediction and planning. 

Our first work is uncertainty quantification of collaborative object detction for CAVs. We propose a novel uncertainty quantification method, called Double-M Quantification, which tailors a moving block bootstrap (MBB) algorithm with direct modeling of the multivariant Gaussian distribution of each corner of the bounding box.
<strong>Outcomes</strong>: We are the first ones to do it.  Experimental results showed our algorithm achieves more than 4× improvement on uncertainty score and more than 3% accuracy improvement, compared with the state-of-the-art. 

My work: Designed Algorithm, wrote code, conducted experiments, and analyzed the results with Pytorch on Python.