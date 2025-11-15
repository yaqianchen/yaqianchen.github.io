---
layout: page
title: Vision Foundation Models for Medical Imaging
description: Evaluating and adapting vision foundation models for medical image registration and segmentation
img: assets/img/publication_preview/vision_foundation_models.png
importance: 4
category: work
related_publications: true
github: https://arxiv.org/abs/2408.00756
---

We evaluate and adapt vision foundation models (VFMs) for medical imaging tasks, establishing benchmarks and demonstrating their potential for out-of-the-box medical image registration and segmentation.

## Key Contributions

- **Foundation model evaluation**: Conducted rapid, large-scale evaluation of SAM2 across 21 diverse medical imaging datasets within 72 hours of its release
- **Registration benchmarks**: Established benchmarks for foundation model-based registration in breast MRI, demonstrating their readiness for out-of-the-box medical image registration (Best Paper Award at MICCAI Workshop 2025)
- **2D and 3D segmentation**: Extended Segment Anything Model (SAM2) to handle both 2D and 3D medical imaging tasks, showing significant improvements in segmentation flexibility
- **Multi-modal adaptation**: Participated in developing multiple medical segmentation models through foundation model fine-tuning strategies

## Impact

- **Best Paper Award**: "Are Vision Foundation Models Ready for Out-of-the-Box Medical Image Registration?" won Best Paper Award at Deep-Breath @ MICCAI 2025
- **Early contribution**: Established an early and impactful contribution to the field by rapidly evaluating SAM2 across diverse medical datasets
- **Clinical translation**: Demonstrated the feasibility of using pre-trained foundation models for medical imaging tasks, reducing the need for extensive domain-specific training

## Applications

- Medical image registration using pre-trained vision foundation models
- Zero-shot and few-shot segmentation in medical imaging
- Rapid deployment of AI models for new medical imaging tasks
- Foundation model fine-tuning strategies for medical applications

<div class="row">
    <div class="col-sm mt-3">
        {% include figure.liquid path="assets/img/publication_preview/vision_foundation_models.png" title="Vision Foundation Models for Medical Image Registration" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3">
        {% include figure.liquid path="assets/img/publication_preview/sam2_pipeline_final.png" title="SAM2 for 2D and 3D Medical Images" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Left: Evaluation of vision foundation models for medical image registration. Right: SAM2 application to 2D and 3D medical imaging tasks.
</div>
