---
layout: page
title: Super-resolution techniques
description: Non-bleaching super-resolution imaging with gold nanorods, from the phase intensity nanoscope (PINE) to interferometric PINE (iPINE).
img: assets/img/projects/super_resolution.png
importance: 3
category: research
related_publications: false
---

{% include figure.liquid loading="eager" path="assets/img/projects/super_resolution.png" class="img-fluid rounded z-depth-1" alt="Schematic: one diffraction-limited spot resolved into two nanorods with different orientations" %}

**University of Michigan, Bioplasmonics Laboratory** · with Prof. Somin Eunice Lee · 2022 – 2024

Fluorescence super-resolution methods are limited in observation time by photobleaching. Phase intensity nanoscopy localizes gold nanorods instead, which scatter light without bleaching. A liquid-crystal phase-intensity (PI) device modulates the phase difference between field components and converts it into intensity changes. These changes separate nanorods that sit within the same diffraction-limited spot, and the positions are reconstructed with the FISTA algorithm.

- **PINE** resolved sub-10 nm cellular architectures and followed nanoscale reorganization for more than 250 hours.
- **iPINE** carries the approach over to interferometric scattering (iSCAT), using circularly polarized illumination to suppress background fluctuations and resolve neighboring nanometer objects.

**My role**

- Built the iSCAT-based iPINE system and its phase-intensity module (liquid crystal, quarter-wave plate, and linear polarizer under LabVIEW control).
- Extracted nanorod phase from elliptical Airy patterns and reconstructed images with FISTA.
- Built a compact soft multimaterial photonic device (mINC) from liquid crystal, a film polarizer, and a film quarter-wave plate for plasmonic super-resolution imaging.

**Outputs**

- G. Cui\*, **D. Y. Kim\***, D. Zu, G. Chai, S. E. Lee, _ACS Applied Nano Materials_ 7(16), 18443–18449 (2024). [Paper](https://doi.org/10.1021/acsanm.3c04361)
- G. Cui\*, Y. Liu\*, D. Zu, X. Zhao, Z. Zhang, **D. Y. Kim**, et al., _Nature Communications_ 14, 4318 (2023). [Paper](https://doi.org/10.1038/s41467-023-39624-w)
- Three SPIE BiOS 2024 proceedings and oral presentations.
