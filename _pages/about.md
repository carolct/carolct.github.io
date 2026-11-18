---
permalink: /
title: "Chiao-Tung (Carol) Chan"
excerpt: "Robotics and autonomous systems engineer specializing in perception, localization, tracking, and sensor fusion."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

## Robotics & Autonomous Systems Engineer

**Perception · Localization · Tracking · Sensor Fusion**<br>
San Francisco Bay Area, CA · U.S. work authorization: EAD

I'm a robotics and autonomous systems engineer with 7+ years of hands-on experience building perception, map-based localization, multi-object tracking, and sensor fusion software.

My work connects algorithms with the systems that run them: C++ and ROS software, camera and sensor processing pipelines, TensorRT inference, and vehicle field testing. I’m interested in making autonomous systems work reliably under practical constraints, including delayed observations, occlusion, and limited compute.

Previously at the [Industrial Technology Research Institute (ITRI)](https://www.itri.org.tw/english/), I worked as a Technical Research Engineer and later an R&D Manager. I managed nine engineers while remaining hands-on in development, integration, and validation.

I'm based in the San Francisco Bay Area and seeking robotics and autonomous systems engineering opportunities where I can contribute both implementation and technical leadership.

<span class='anchor' id='engineering-work'></span>

# Selected Engineering Work

## Map-Based Localization & Field Validation

Delivered a driving-test scoring prototype in Japan and Taiwan within 12 months, combining map-based visual localization with IMU and wheel speed.

The system used road-marking detections from four camera views, dynamic-pitch ground projection, ego-motion compensation, and semantic-map registration with BEV GICP. It passed a full-day customer field evaluation and achieved approximately **0.2 m horizontal RMSE against RTK-GPS in Taiwan field tests**.

In phase two, I moved localization and scoring to cloud computation while retaining onboard data collection.

## Multi-Object Tracking & Sensor Fusion

Built a modular C++/ROS tracker that fused PTP-timestamped camera, LiDAR, and radar detections. The tracker used IMM-UKF motion estimation with constant-velocity, turning, and stationary models, together with Mahalanobis gating and Munkres assignment.

A roughly **200 ms replay window** allowed the tracker to incorporate delayed observations, including camera detections with about 150 ms latency. I also combined geometric LiDAR clusters with AI 3D detections to retain coverage outside trained object classes and correct occlusion-induced centroid shifts.

To evaluate tracking without manually annotated ground truth, I used future track displacements to check current velocity and heading estimates.

## Onboard AI & ROS Systems

Co-designed a shared C++ camera pipeline with sensor firmware engineers, defining ring-buffer reuse and callback interfaces for perception stages, and integrated multi-GPU TensorRT inference.

I led a six-month ROS 1 to ROS 2 migration covering message interfaces, coordinate transforms, and bag conversion. I also built semi-automated rosbag replay to verify inputs and profile per-node FPS and latency before vehicle testing.

<span class='anchor' id='-work-experience'></span>

# Experience

**Industrial Technology Research Institute (ITRI)**<br>
**R&D Manager, previously Technical Research Engineer**<br>
Self-Driving Vehicle Department · Hsinchu, Taiwan<br>
April 2019 – June 2026

Developed perception, localization, tracking, and sensor fusion software for autonomous vehicle projects while taking on engineering management responsibilities.

Managed nine direct reports, including hiring, technical reviews, performance reviews, and engineer development. Set a multi-year technical roadmap and translated customer requirements into milestones, staffing and cost estimates, and delivery plans.

<span class='anchor' id='publications'></span>
<span class='anchor' id='-publications'></span>

# Selected Publications

- **[Perseus: Interactive Time Series Segmentation with Sparse Supervision via Stateful Memory](https://arxiv.org/abs/2510.09930)** — IEEE ICDM 2026, accepted.
- **[RMSeg-UDA: Unsupervised Domain Adaptation for Road Marking Segmentation under Adverse Conditions](https://ieeexplore.ieee.org/document/11128761)** — ICRA 2025.
- **[FuseRoad: Enhancing Lane Shape Prediction Through Semantic Knowledge Integration and Cross-Dataset Training](https://doi.org/10.1109/IV64158.2025.11097535)** — IV 2025.
- **[TimeDRL: Disentangled Representation Learning for Multivariate Time-Series](https://doi.org/10.1109/ICDE60146.2024.00054)** — ICDE 2024.
- **[RLMD: A Dataset for Road Marking Segmentation](https://doi.org/10.1109/ICCE-Taiwan58799.2023.10226935)** — ICCE-Taiwan 2023.

[View Google Scholar profile](https://scholar.google.com/citations?user=3yH9i58AAAAJ)

<span class='anchor' id='patents-certification'></span>
<span class='anchor' id='-certifications--patents'></span>

# Patents & Certification

- **Camera Calibration Method Based on Vehicle Localization**<br>
  U.S. Patent 12,400,367 · Lead inventor.
- **Safe Following Distance Estimation System and Method**<br>
  U.S. Patent 11,891,063 · Co-inventor.
- **3D Object Detection Method and System**<br>
  Taiwan/Japan patent applications · Sole inventor. Japanese publication: JP 2026-114887 A.<br>
  Pyramid-mesh refinement for camera-to-map localization and 3D object positioning.
- **Automotive Functional Safety Professional (AFSP), ISO 26262**<br>
  SGS TÜV Saar.

<span class='anchor' id='-education'></span>

# Education

**National Yang Ming Chiao Tung University (NYCU / NCTU)**<br>
Hsinchu, Taiwan

- M.S. in Electrical Engineering, 2019
- B.S. in Electrical Engineering, 2016

<span class='anchor' id='-core-competencies'></span>

# Technical Skills

- **Perception & Robotics:** 2D/3D detection, camera calibration, map-based localization, multi-object tracking, sensor fusion.
- **Software & Systems:** C++, Python, ROS 1 / ROS 2, ONNX, TensorRT, CUDA, PTP, rosbag.
- **Validation:** Vehicle field testing, RTK-GPS reference evaluation, track-consistency checks, replay-based FPS and latency profiling.


# Contact

San Francisco Bay Area, CA<br>
U.S. work authorization: EAD

[Email](mailto:carol.chou.tun@gmail.com) · [LinkedIn](https://www.linkedin.com/in/carolchoutun/) · [GitHub](https://github.com/carolct) · [Google Scholar](https://scholar.google.com/citations?user=3yH9i58AAAAJ) · [Download General CV](/resume/Chiao-Tung%20Chan_Resume.pdf)

<span class='anchor' id='-visitors'></span>

# Visitors
