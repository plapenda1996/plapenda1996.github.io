---
layout: page
title: Deep-tissue NIR-II imaging
description: NIR-II squeezed light-field microscopy for high-speed volumetric imaging deep inside living tissue.
img: assets/img/projects/deep_tissue_nir2.png
importance: 2
category: research
github: https://github.com/plapenda1996/NIR_II_SLIM_Reconstruction
related_publications: false
---

{% include figure.liquid loading="eager" path="assets/img/projects/deep_tissue_nir2.png" class="img-fluid rounded z-depth-1" alt="Schematic: visible light scatters near the tissue surface while NIR-II light reaches deep" %}

**UCLA Intelligent Optics Laboratory** · with Prof. Liang Gao · 2024 – present

Light in the second near-infrared window (NIR-II) scatters less in tissue than visible light, so it reaches deeper. NIR-II squeezed light-field microscopy (NIR-II SLIM) combines this with snapshot volumetric imaging. The light field is rotated by a Dove prism array and compressed anamorphically with cylindrical optics, so many angular views share a single 640 × 512 InGaAs sensor without tiling it. Every camera frame is then deconvolved into a volume, which gives continuous volumetric imaging at up to 600 volumes per second.

**My role**

- Designed the optical architecture, including the Dove prism arrays and cylindrical lenses, in Zemax OpticStudio, and built the microscope.
- Optimized the point-spread-function calibration.
- Implemented Richardson–Lucy deconvolution for volume reconstruction in MATLAB and Python.

**Outputs**

- **D. Y. Kim\***, Z. Zang\*, E. Y. Lin\*, et al., manuscript under review (2026).
- Oral presentation at SPIE Photonics West BiOS 2027; provisional patent application (2026).
- Reconstruction and analysis code: [NIR_II_SLIM_Reconstruction](https://github.com/plapenda1996/NIR_II_SLIM_Reconstruction)
