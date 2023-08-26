---
title: "UncLe-SLAM: Uncertainty Learning for Dense Neural SLAM"
names: "**Kevin Ta***, Erik Sandström*, Luc Van Gool, and Martin R. Oswald"
date: 2023-08-10
abstract: "We present an uncertainty learning framework for dense neural simultaneous localization and mapping (SLAM). Estimating pixel-wise uncertainties for the depth input of dense SLAM methods allows to re-weigh the tracking and mapping losses towards image regions that contain more suitable information that is more reliable for SLAM. To this end, we propose an online framework for sensor uncertainty estimation that can be trained in a self-supervised manner from only 2D input data. We further discuss the advantages of the uncertainty learning for the case of multi-sensor input. Extensive analysis, experimentation, and ablations show that our proposed modeling paradigm improves both mapping and tracking accuracy and often performs better than alternatives that require ground truth depth or 3D. Our experiments show that we achieve a 38% and 27% lower absolute trajectory tracking error (ATE) on the 7-Scenes and TUM-RGBD datasets respectively. On the popular Replica dataset on two types of depth sensors we report an 11% F1-score improvement on RGBD SLAM compared to the recent state-of-the-art neural implicit approaches."
conf: ICCV 2nd Workshop on Uncertainty Quantification for Computer Vision (ICCVW), 2023
links:
    - link_name: code
      link: https://github.com/kev-in-ta/UncLe-SLAM
    - link_name: bibtex
      link: /papers/2023iccvw-cvl.bib
    - link_name: arxiv
      link: https://arxiv.org/abs/2306.11048
---