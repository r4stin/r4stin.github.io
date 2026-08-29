---
title: "Ensemble-Enhanced Semantic Segmentation for Efficient Waste Recycling"
authors: ["Mohammadhossein Akbari Moafi", "Horst Possegger"]
date: 2025-09-17
publication_types: ['paper-conference']
publication: "Proceedings of the International Conference on Image Analysis and Processing (ICIAP)"
publication_short: 'ICIAP 2025'
doi: 10.1007/978-3-032-10185-3_29
url_pdf: 
abstract: >-
  Efficient and accurate annotation workflows are crucial for advancing semantic
  segmentation, especially in waste recycling applications, where the detailed
  labeling process is highly time-intensive and prone to errors. This work
  proposes a new pipeline to accelerate the annotation process by combining the
  ensemble of three semantic segmentation models (UperNet, OCRNet, and
  DeepLabv3+), each with a ResNet-101 backbone with the Segment Anything Model
  (SAM), for instance segmentation. Within this pipeline, we investigate two
  categories of approaches: (1) purely semantic segmentation-based
  methods—Majority Voting (MV), Max Logits (ML), and SDF Mask Retrieval
  (SDF-MR)—and (2) hybrid methods that integrate both semantic and instance
  segmentation, namely Max Logits with SAM Refinement (ML-SAM) and SDF Mask
  Retrieval with SAM Refinement (SDF-SAM). The work is carried out on household
  waste data that have been annotated with 11-class masks. The experiments
  demonstrated significant improvements in both annotation accuracy and
  efficiency compared to individual models. Integrating SAM into the system
  also resulted in substantially better boundary predictions and an increase in
  mIoU of 4.97% compared to the best-performing individual model. This approach
  demonstrates the potential to enhance waste recycling solutions by
  efficiently generating the necessary labels through the combination of
  semantic and instance segmentation models.
featured: true
---
