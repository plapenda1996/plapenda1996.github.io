---
layout: page
title: NIR-II squeezed light-field microscopy
description: High-speed volumetric imaging of deep-tissue dynamics in vivo in the second near-infrared window.
importance: 1
github: https://github.com/plapenda1996/NIR_II_SLIM_Reconstruction
related_publications: false
---

**UCLA Intelligent Optics Laboratory** · with Prof. Liang Gao · 2024 – present

Light-field microscopy captures an entire volume in a single camera exposure, and imaging in the second near-infrared window (NIR-II) reduces tissue scattering so that light reaches deeper. NIR-II squeezed light-field microscopy (SLIM) brings the two together. The light field is rotated by a Dove prism array and compressed anamorphically with cylindrical optics, so many angular views share a single 640 × 512 InGaAs sensor without tiling it. Every camera frame is then deconvolved into a volume, which gives continuous volumetric imaging at up to 600 volumes per second.

**My role**

- Designed the optical architecture, including the Dove prism arrays and cylindrical lenses, in Zemax OpticStudio, and built the microscope.
- Optimized the point-spread-function calibration.
- Implemented Richardson–Lucy deconvolution for volume reconstruction in MATLAB and Python.

**Outputs**

- Manuscript under review; oral presentation at SPIE Photonics West BiOS 2027.
- Provisional patent application (2026).
- Reconstruction and analysis code: [NIR_II_SLIM_Reconstruction](https://github.com/plapenda1996/NIR_II_SLIM_Reconstruction)
