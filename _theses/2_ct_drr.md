---
layout: page
title: Invertible deep learning for CT–DRR bidirectional synthesis
description: MSc thesis in Computer Science and Engineering / Biomedical Engineering. Invertible, physics-informed deep learning for bidirectional CT–DRR synthesis in brain radiotherapy.
img: assets/img/theses/2_ct_drr.png
importance: 2
---

**Full title:** Invertible deep learning for CT–DRR bidirectional synthesis in brain radiotherapy

**Level:** MSc thesis in Computer Science and Engineering / Biomedical Engineering

**Collaboration:** UMC Utrecht, Netherlands

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/theses/2_ct_drr.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

### Background and aims

DRRs are essential for image guidance but lose 3D information. The aim is to develop invertible and physics-informed models for CT→DRR preserving clinically relevant features. As a future aim, we plan to invert the problem (DRR→CT).

### Dataset

CyberKnife cohort (2024–2025): 94 patients with CT + two DRR projections.

### Methods

1. **Models:** GANs, U-Net diffusion, transformers, invertible neural networks (INN)
2. **Physics constraints:** differentiable projection, projection-consistency losses, PINN-inspired approaches
3. **Tasks:**
   1. CT → DRR (realistic projection)
   2. DRR → CT (inverse reconstruction)
4. **Metrics:** SSIM, PSNR, MAE, projection error, latent consistency

### Endpoints and relevance

Development of consistent bidirectional models with quantification of information loss inherent to projection-based imaging. Potential applications include enhanced image guidance during radiotherapy, volumetric reconstruction from projection data, synthetic data augmentation, and alignment with modern AI-driven clinical engineering workflows.
