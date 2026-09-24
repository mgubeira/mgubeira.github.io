---
layout: page
title: Physics-informed MRI-to-CT synthesis for brain SSRT
description: MSc thesis in Physics. Optimizing physics-informed generative models for MRI-to-CT synthesis and validating them from image metrics to dosimetry.
img: assets/img/theses/1_mri2ct.png
importance: 1
---

**Full title:** Physics-informed MRI-to-CT synthesis for brain SSRT: model optimization and clinical validation

**Level:** MSc thesis in Physics

**Collaboration:** Gemelli, Rome

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/theses/1_mri2ct.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

### Background and aims

MRI-only workflows require accurate synthetic CT (sCT), especially for bone reconstruction in stereotactic salvage radiotherapy (SSRT). The aim is to optimize MRI→CT generative models and assess their clinical reliability from image metrics to dosimetry.

### Dataset

CyberKnife cohort (2024–2025): 94 patients (CT + gadolinium MRI).

### Methods

1. **Models:** GANs, diffusion, transformers
2. **Physics-informed approaches:** PINNs / custom loss (HU consistency, bone-enhancing, structural constraints)
3. **Evaluation (technical):** MAE, RMSE, SSIM, PSNR, bone-specific HU error
4. **Evaluation (clinical):** TPS recalculation on sCT vs CT → DVH, ΔDmean, ΔDmax, ΔV95, gamma analysis

### Endpoints and relevance

Identify optimal models/losses and assess dosimetric agreement. Supports MRI-only workflows and bridges AI optimization with clinical radiotherapy.
