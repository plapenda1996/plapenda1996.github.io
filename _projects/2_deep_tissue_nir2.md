---
layout: page
title: Deep-tissue NIR‑II imaging
description: NIR-II squeezed light-field microscopy for high-speed volumetric imaging deep inside living tissue.
img: assets/img/projects/nir2_slim_fig1a.jpg
importance: 2
category: research
github: https://github.com/plapenda1996/NIR_II_SLIM_Reconstruction
related_publications: false
---

{% include figure.liquid loading="eager" path="assets/img/projects/nir2_slim_fig1a.jpg" class="img-fluid rounded z-depth-1" alt="Optical configuration of NIR-II SLIM: objective, dichroic, Dove prism array, lenslet array, anamorphic lenses and InGaAs camera, with dark-field and fluorescence imaging modes" %}

<div class="caption">
  Optical configuration of NIR-II SLIM, shown with its dark-field and fluorescence imaging modes. Image: D. Y. Kim et al., <a href="https://doi.org/10.64898/2026.08.13.744709"><em>bioRxiv</em> (2026)</a>, Fig. 1a.
</div>

**UCLA Intelligent Optics Laboratory** · with Prof. Liang Gao · 2024 – present

Light in the second near-infrared window (NIR-II) scatters less in tissue than visible light, so it reaches deeper. NIR-II squeezed light-field microscopy (NIR-II SLIM) combines this with snapshot volumetric imaging. The light field is rotated by a Dove prism array and compressed anamorphically with cylindrical optics, so many angular views share a single 640 × 512 InGaAs sensor without tiling it. Every camera frame is then deconvolved into a volume, which gives continuous volumetric imaging at up to 600 volumes per second.

**My role**

- Designed the optical architecture, including the Dove prism arrays and cylindrical lenses, in Zemax OpticStudio, and built the microscope.
- Optimized the point-spread-function calibration.
- Implemented Richardson–Lucy deconvolution for volume reconstruction in MATLAB and Python.

**Outputs**

- **D. Y. Kim\***, Z. Zang\*, E. Y. Lin\*, et al., _bioRxiv_ (2026); under review at _Nature Communications_. [Preprint](https://doi.org/10.64898/2026.08.13.744709)
- Oral presentation at SPIE Photonics West BiOS 2027; provisional patent application (2026).
- Reconstruction and analysis code: [NIR_II_SLIM_Reconstruction](https://github.com/plapenda1996/NIR_II_SLIM_Reconstruction)
