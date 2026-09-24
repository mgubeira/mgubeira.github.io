---
layout: page
title: End-to-end vs segmentation-guided deep learning for IPMN on EUS
description: MSc thesis. Comparing end-to-end and segmentation-guided deep learning on EUS images to predict IPMN histopathological grade and surgical indication.
img: assets/img/theses/4_eus_ipmn.png
importance: 4
---

**Full title:** End-to-End versus Segmentation-Guided Deep Learning for Histopathological Grading and Surgical Decision Support in IPMN from Endoscopic Ultrasound Images

**Level:** MSc thesis

**Part of:** [IPMN (INCITE)]({% link _projects/ipmn.md %})

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/theses/4_eus_ipmn.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

### Description

This thesis compares two deep learning strategies on 2D EUS images of IPMN to predict the histopathological score and the surgical indication (operate vs. surveil): direct end-to-end classification versus a supervised pipeline based on U-Net segmentation/detection, extraction of lesion and anatomical context features, and downstream classification. Acquisition information (contrast, zoom, device) is included as additional input in both approaches. Annotations are managed in CVAT, where the best models may later be integrated for testing.
