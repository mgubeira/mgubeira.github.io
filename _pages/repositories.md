---
layout: page
permalink: /repositories/
title: repositories
description: Software and medical imaging pipelines developed on GitHub.
nav: true
nav_order: 4
---

## mAItre

<a href="https://github.com/pymaitre"><img src="/assets/img/pymaitre_logo.png" alt="mAItre logo" style="width: 90px;"></a>

Development of medical pipelines on GitHub: [pymaitre](https://github.com/pymaitre)

### Private libraries (for images)

- **pydicom-link**: Automatic retrieval of patient imaging studies from the PACS for a specific research project, with subsequent storage in Orthanc.
- **pydicom-toolkit**: Python library for DICOM folder organization in batch (dcm_folder) and to anonimize dicom files in parallel (dcm_anonymize).
- <img src="/assets/img/resmip_logo.png" alt="ResMIP logo" style="width: 40px; vertical-align: middle;"> **resmip**: Python library for Medical Image Processing (MIP) es. dicom-to-nifti conversion.
- <img src="/assets/img/probslab_logo.png" alt="ProbS-LAB logo" style="width: 40px; vertical-align: middle;"> **ProbS-LAB**: Package for probabilistic segmentation using DL models.
- <img src="/assets/img/vetrai_logo.png" alt="Vetr-AI logo" style="width: 40px; vertical-align: middle;"> **VetrAI**: Python library for processing, analyzing, and preparing Whole Slide Images (WSIs) in digital pathology. Training of YOLO/Sam for tissue segmentation.

### Private libraries (for DBs)

- **SQLHub**: Code dealing with the interaction between analysis in Python and databases stored in SQL servers.
- **medicalAI**: database pre-processing: cleaning and features selection (e.g. bootstrap or backward feature selection); simple AI models for training and prediction; automatic saving plots and and model output storage (via excel/SQL; e.g., ROC, PR, calibration map, SHAP).
- **medicalDL**: more advanced model's implementation (es. lightGBM) for training and predictions.

---
