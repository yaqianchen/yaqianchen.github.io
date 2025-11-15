---
layout: page
title: GuidedMorph
description: Two-Stage Deformable Registration for Breast MRI
img: assets/img/publication_preview/guidedmorph.png
importance: 1
category: work
related_publications: true
github: https://arxiv.org/abs/2505.13414
---

GuidedMorph is a two-stage deformable registration method specifically designed for breast MRI, addressing the challenge of aligning fibroglandular tissue (FGT) across different time points and imaging sessions.

## Key Contributions

- **Two-stage architecture**: Combines global alignment with local deformable registration for robust and accurate breast MRI registration
- **Superior performance**: Outperforms existing deep learning-based registration models by over 13.01% in dense tissue Dice score on both internal and external datasets
- **Clinical relevance**: Enables accurate breast density estimation and longitudinal analysis of breast tissue changes
- **Foundation model integration**: Establishes benchmarks for foundation model-based registration in breast MRI

## Applications

- Breast density quantification and tracking over time
- Longitudinal studies of breast tissue changes
- Multi-temporal image analysis for cancer risk assessment
- Clinical decision support for breast imaging

<div class="row">
    <div class="col-sm mt-3">
        {% include figure.liquid path="assets/img/publication_preview/guidedmorph.png" title="GuidedMorph: Two-Stage Deformable Registration" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    GuidedMorph architecture for breast MRI registration, achieving state-of-the-art performance in FGT alignment.
</div>


