---
title: "UniCal: Unified Neural Sensor Calibration"
names: "Ze Yang, George G. Chen, Haowei Zhang, **Kevin Ta**, Ioan Andrei Bârsan, Daniel Murphy, Sivabalan Manivasagam, and Raquel Urtasun"
date: 2024-10-01
abstract: "Self-driving vehicles (SDVs) require accurate calibration of LiDARs and cameras to fuse sensor data accurately for autonomy. Traditional calibration methods typically leverage fiducials captured in a controlled and structured scene and compute correspondences to optimize over. These approaches are costly and require substantial infrastructure and operations, making it challenging to scale for vehicle fleets. In this work, we propose UniCal, a unified framework for effortlessly calibrating SDVs equipped with multiple LiDARs and cameras. Our approach is built upon a differentiable scene representation capable of rendering multi-view geometrically and photometrically consistent sensor observations. We jointly learn the sensor calibration and the underlying scene representation through differentiable volume rendering, utilizing outdoor sensor data without the need for specific calibration fiducials. This \"drive-and-calibrate\" approach significantly reduces costs and operational overhead compared to existing calibration systems, enabling efficient calibration for large SDV fleets at scale. To ensure geometric consistency across observations from different sensors, we introduce a novel surface alignment loss that combines feature-based registration with neural rendering, as well as a coarse-to-fine sampling approach to optimize regions of interest for sensor alignment. Comprehensive evaluations on multiple datasets demonstrate that UniCal outperforms or matches the accuracy of existing calibration approaches while being more efficient, demonstrating the value of UniCal for scalable calibration."
conf: European Conference on Computer Vision (ECCV), 2024
links:
    - link_name: paper
      link: https://eccv.ecva.net/virtual/2024/poster/629
    - link_name: "blog post"
      link: https://waabi.ai/unical/
    - link_name: bibtex
      link: /papers/2024eccv-waabi.bib
    - link_name: arxiv
      link: http://export.arxiv.org/abs/2409.18953
---