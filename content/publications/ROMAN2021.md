---
title: "Offline and Real-Time Implementation of a Personalized Wheelchair User Intention Detection Pipeline: A Case Study"
names: Mahsa Khalili, Kevin Ta, H. F. Machiel Van der Loos, and Jaimie F. Borisoff
date: 2021-08-08
abstract: "Pushrim-activated power-assisted wheels (PAPAWs) are assistive technologies that provide on-demand assistance to wheelchair users. PAPAWs operate based on a collaborative control scheme and require an accurate interpretation of the user’s intent to provide effective propulsion assistance. This paper investigates a user-specific intention estimation framework for wheelchair users. We used Gaussian Mixture models (GMM) to identify implicit intentions from user-pushrim interactions (i.e., input torque to the pushrims). Six clusters emerged that were associated with different phases of a stroke pattern and the intention about the desired direction of motion. GMM predictions were used as 'ground truth' labels for further intention estimation analysis. Next, Random Forest (RF) classifiers were trained to predict user intentions. The best optimal classifier had an overall prediction accuracy of 94.7%. Finally, a Bayesian filtering (BF) algorithm was used to extract sequential dependencies of the user-pushrim measurements. The BF algorithm improved sequences of intention predictions for some wheelchair maneuvers compared to the GMM and RF predictions. The proposed intention estimation pipeline is computationally efficient and was successfully tested and used for real-time prediction of wheelchair user’s intentions. This framework provides the foundation for the development of user-specific and adaptive PAPAW controllers."
conf: International Conference on Robot and Human Interactive Communication (ROMAN), 2021
links:
    - link_name: paper
      link: https://ieeexplore.ieee.org/document/9515488
    - link_name: code
      link: https://github.com/kev-in-ta/CARIS-PAW-RT-intention-detection
    - link_name: bibtex
      link: /papers/2021roman-caris.bib
---