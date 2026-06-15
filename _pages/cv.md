---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D., Agricultural and Biosystems Engineering; Minor in Applied Mathematics, Iowa State University, 2024–2025
* M.Eng., Agricultural and Biosystems Engineering; Minor in Applied Mathematics, Iowa State University, 2021–2023
* M.S., Engineering Science and Ocean Engineering, National Taiwan University, 2015–2017
* B.S., Systems and Naval Mechatronic Engineering, National Cheng Kung University, 2011–2015

Experience
======
* **Postdoctoral Research Associate** (Jan 2025 – Present)
  * Soils Laboratory, University of Illinois Urbana-Champaign, Urbana, IL
  * Conduct recurring synchrotron micro-XCT campaigns at the APS 2-BM beamline for soil aggregates and intact soil cores; developed a novel dual-energy contrast-enhanced approach using iodine staining for chemical-guided organic matter segmentation.
  * Design transformer-based deep learning frameworks for automated 3D supervised segmentation of synchrotron XCT volumes, enabling quantitative pore network analysis and spatial OM distribution mapping.
  * Design and maintain HPC-based reconstruction and inference pipelines on ALCF Polaris and NERSC Perlmutter, integrating tomocupy for GPU-accelerated image reconstruction.
  * Develop post-reconstruction correction pipelines: geometric tilt correction, ring artifact suppression, and Noise2Inverse self-supervised denoising (PSNR +4.38 dB, SSIM +0.015 on APS 2-BM soil XCT data).
  * Mentor undergraduate researchers across soil science, computational imaging, synchrotron physics, and agricultural systems.

* **Digital Agriculture Research Assistant** (Nov 2023 – Jan 2025)
  * Soil Machine Dynamics Laboratory, Iowa State University, Ames, IA
  * Designed AI-enabled, site-specific tillage decision systems combining sensitivity analysis, machine learning, cloud-based data integration, and on-site sensing.
  * Developed ML models to predict tillage performance and crop yield from multi-sensor soil indicator datasets.
  * Conducted field soil sampling across multiple tillage systems.

* **GIS for Agriculture Summer Research Intern** (May 2024 – Jan 2025)
  * Center for GIS and RCHSS, Academia Sinica, Taipei, Taiwan
  * Developed AI workflows for rice growth monitoring and yield prediction using Sentinel-2 satellite data and deep learning via Google Earth Engine.
  * Analyzed UV index data from GEMS and fused multimodal remote sensing signals.

* **Teaching Assistant** (Aug 2021 – May 2024)
  * Department of Mathematics, Iowa State University, Ames, IA
  * Introduction to Data Science (DS 201) — Fall 2022
  * Calculus 1 (MATH 165) — Fall 2023
  * Calculus 2 (MATH 166) — Fall 2021
  * Calculus 3 (MATH 265) — Spring 2022, Spring 2023
  * Military Affiliated Tutoring for Calculus and General Physics

* **Robotic Integration and Computer Vision Assistant** (May 2022 – Aug 2023)
  * Agricultural Automation and Robotics Laboratory, Iowa State University, Ames, IA
  * Applied deep learning for corn feature extraction and optimized gradient-based algorithms for ML convergence.

* **Structural Analysis Research Assistant** (Sep 2015 – Jan 2021)
  * Advanced Structures and Materials Laboratory, National Taiwan University, Taipei, Taiwan
  * Conducted multiphysics finite element simulations and implemented vibrational sensors for structural damage detection.

Technical Skills
======
* **ML & Deep Learning**: PyTorch, transformer architectures, CNNs, 3D segmentation, SVM, random forest, XGBoost, AdaBoost
* **Computational Imaging**: Synchrotron XCT reconstruction, tomographic algorithms, FFT-based frequency-domain transforms, polar-to-Cartesian inversion, pore network analysis
* **HPC & Scientific Programming**: ALCF Polaris, NERSC Perlmutter, GPU-accelerated pipelines
* **Multimodal Imaging**: Dual-energy micro-CT, iodine-contrast staining, infrared thermography, SEM, optical microscopy, remote sensing
* **Software & Tools**: Python, MATLAB, ImageJ, 3D Slicer, COMSOL, SolidWorks, Google Earth Engine, Git, Globus

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Certificates
======
* Data Structures and Algorithms – Python, Udemy (August 2022)
