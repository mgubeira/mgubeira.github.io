---
layout: page
title: Transformer-based architectures for WSI segmentation and tumor grading
description: MSc thesis in Computer Science and Engineering / Biomedical Engineering. Transformer-based pipelines for tissue segmentation, cell detection and tumor grading in whole slide images.
img: assets/img/theses/3_wsi.png
importance: 3
---

**Full title:** Exploring Transformer-Based Architectures for Whole Slide Image Tissue Segmentation and Tumor Grade Prediction in Digital Pathology

**Level:** MSc thesis in Computer Science and Engineering / Biomedical Engineering

**Collaboration:** with ... PhD in Unimi

**Part of:** [IPMN (INCITE)]({% link _projects/ipmn.md %})

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/theses/3_wsi.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

### Description

Development of a multi-stage pipeline for a deep learning-based segmentation of tumor tissue using automated prompts, to enhance segmentation accuracy. Integration of explainable AI techniques to provide clinically interpretable insights, allowing pathologists to understand model decisions and improve diagnoses.

### Possible aims

1. **Improve techniques for cell segmentation.** Cell detection (and segmentation) is a required task to provide accurate cell counts. Comparison of existing models (InstaSeg, StarDist, CellPose) across different tissue types and staining protocols, to improve cell detection and counting.
2. **Improve techniques for quality control.** Current models are accurate but slow for real-time use. The goal is to develop lightweight models capable of deciding in real-time whether a slide requires a full rescan with updated scan parameters.
3. **Improve techniques for tissue classification and derived features' extraction.** The goal will be to compare different advanced models for tissue classification and subsequent segmentation, with extraction of clinically significant features.
