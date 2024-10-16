---
title: "MUSES: The Multi-Sensor Semantic Perception Dataset for Driving under Uncertainty"
names: "Tim Brödermann, David Bruggemann, Christos Sakaridis, **Kevin Ta**, Odysseas Liagouris, Jason Corkill, and Luc Van Gool"
date: 2024-07-01
abstract: "Achieving level-5 driving automation in autonomous vehicles necessitates a robust semantic visual perception system capable of parsing data from different sensors across diverse conditions. However, existing semantic perception datasets often lack important non-camera modalities typically used in autonomous vehicles, or they do not exploit such modalities to aid and improve semantic annotations in challenging conditions. To address this, we introduce MUSES, the MUlti-SEnsor Semantic perception dataset for driving in adverse conditions under increased uncertainty. MUSES includes synchronized multimodal recordings with 2D panoptic annotations for 2500 images captured under diverse weather and illumination. The dataset integrates a frame camera, a lidar, a radar, an event camera, and an IMU/GNSS sensor. Our new two-stage panoptic annotation protocol captures both class-level and instance-level uncertainty in the ground truth and enables the novel task of uncertainty-aware panoptic segmentation we introduce, along with standard semantic and panoptic segmentation. MUSES proves both effective for training and challenging for evaluating models under diverse visual conditions, and it opens new avenues for research in multimodal and uncertainty-aware dense semantic perception."
conf: European Conference on Computer Vision (ECCV), 2024
links:
    - link_name: paper
      link: https://eccv.ecva.net/virtual/2024/poster/1376    
    - link_name: dataset
      link: https://muses.vision.ee.ethz.ch 
    - link_name: code
      link: https://github.com/timbroed/MUSES
    - link_name: bibtex
      link: /papers/2024eccv-cvl.bib
    - link_name: arxiv
      link: https://arxiv.org/abs/2401.12761
---