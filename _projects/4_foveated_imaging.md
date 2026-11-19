---
layout: page
title: Foveated imaging
description: A content-aware camera that tracks multiple targets by steering high-resolution foveae with a spatial light modulator.
img: assets/img/projects/foveated_camera_fig2.jpg
importance: 1
category: side projects
related_publications: false
---

{% include figure.liquid loading="eager" path="assets/img/projects/foveated_camera_fig2.jpg" class="img-fluid rounded z-depth-1" alt="System overview: a spatial light modulator steers foveae onto targets in a dynamic scene, and a content-aware algorithm updates the SLM phase from the sensor images" %}

<div class="caption">
  System overview of the content-aware foveated camera. Image: Z. Zang, D. Y. Kim et al., <a href="https://arxiv.org/abs/2509.01165">arXiv:2509.01165</a>, Fig. 2; published in <a href="https://doi.org/10.1364/OE.577673"><em>Optics Express</em> 33, 43359 (2025)</a>.
</div>

**UCLA Intelligent Optics Laboratory** · with Zihan Zang and Prof. Liang Gao · 2024 – 2025

An image sensor can record far more pixels per second than downstream processing can use. This camera spends its sensing budget where it matters instead. A phase-only spatial light modulator steers and magnifies several foveae onto regions of interest, and because the modulator has no moving parts, the configuration can change from one frame to the next. Alternating frames among the foveae keeps a wide-field view for context while each target is refreshed quickly, which cuts the data needed for multi-target tracking.

**My role**

- Developed the foveated camera and designed its dynamic optical architecture.
- Optimized the target-tracking algorithms.
- Integrated the hardware and software interfaces.

**Output**

- Z. Zang\*, **D. Y. Kim\***, Y. Zeng, L. Gao, _Optics Express_ 33(20), 43359 (2025). [Paper](https://doi.org/10.1364/OE.577673) · [arXiv](https://arxiv.org/abs/2509.01165)
