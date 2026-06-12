---
permalink: /
title: "Chiao-Tung (Carol) Chan"
excerpt: "Personal website of Chiao-Tung (Carol) Chan."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hello 👋, I'm **Chiao-Tung (Carol) Chan**, a Staff Software Engineer / R&D Manager and **Autonomous Systems Architect**. I'm **ISO 26262 certified (AFSP)** with 7+ years of full-stack experience spanning algorithm design (**Localization & Tracking**) down to low-level hardware optimization (**Edge AI & Compute**).

Most recently I led the Self-Driving Vehicle Department's R&D at the [Industrial Technology Research Institute (ITRI)](https://www.itri.org.tw/english/) in Hsinchu, Taiwan — building 0-to-1 autonomous driving systems, deploying robust **Visual-Inertial Localization** and **Sensor Fusion** pipelines in international testing fields, and scaling the team from 4 to 10+ engineers. My deeper strengths are C++ system architecture, mitigating complex HW/SW bottlenecks (zero-copy memory management, TensorRT acceleration), and building scalable, safety-critical CI/CD infrastructure. I'm currently **open to relocation** (incl. Mountain View / San Francisco).

# 📖 Education

- *2016.09 – 2019.01*, **M.S. in Electrical Engineering**, National Yang Ming Chiao Tung University (NYCU / NCTU), Hsinchu, Taiwan
- *2012.09 – 2016.06*, **B.S. in Electrical Engineering**, National Yang Ming Chiao Tung University (NYCU / NCTU), Hsinchu, Taiwan

# 💻 Work Experience

- *2019.04 – 2026.06*, **R&D Manager, Self-Driving Vehicle Department**, Industrial Technology Research Institute (ITRI), Hsinchu, Taiwan

  **Algorithm development: localization & tracking**
  - Spearheaded the 0-to-1 architecture and cross-border deployment of a safety-critical Visual-Inertial Localization pipeline (camera / IMU / odometry) with RTK-backed ground-truth validation, driving international commercialization at the Toyota Driving School (Japan) and Taiwan testing fields within a 12-month window.
  - Defined the technical vision for a modular C++ object-tracking framework — extensible abstract interfaces for heterogeneous sensor modalities (radar x/y/z/rv, camera IDs) using IMM-UKF, creating a 2× development-velocity multiplier across the Localization and Fusion teams.
  - Pioneered a novel L-Shape tracking method using Iterative Closest Point (ICP) to directly infer precise vehicle yaw, bypassing legacy non-linear state-estimator limits in degenerate scenarios — translated into a sole-inventor 3D Object Detection patent.

  **AI acceleration & edge-compute optimization**
  - Overhauled the deep-learning inference architecture into a Reactive (Rx) streaming paradigm and engineered a custom zero-copy memory-management framework on TensorRT, sustaining 95% GPU utilization while guaranteeing deterministic, safety-critical real-time latency.
  - Led a HW/SW co-design initiative to resolve system-level thermal throttling and OOM failures — defined end-to-end latency budgets (e.g., 28 Hz for visual localization) and adaptive filters to prune stale sensor data, steering the physical thermal redesign of the vehicle compute trunk.
  - Architected a decentralized edge-compute paradigm with hardware partner Chimei, migrating image compression and NN inference onto edge ASICs to eliminate bulky frame grabbers and central compute bottlenecks.

  **Technical leadership & infrastructure (DevOps)**
  - Scaled a cross-functional engineering team from 4 to 10+ members and set a 4-year technical roadmap focused on resilient scalability and continuous automated functional-safety validation.
  - Orchestrated a 6-month ROS1 → ROS2 migration for a junior team with strict SOPs and automated CI/CD pipelines (AWS & internal servers) for bag-file playback, eradicating deployment regressions.
  - Engineered an automated Active-Learning data pipeline that replays offline bag files against ML detectors, using mismatch-trigger logic (track vs. future-track discrepancies) to mine hard-negative edge cases — a closed-loop engine for continuous model refinement.

# 📝 Publications

<a href='https://scholar.google.com/citations?user=3yH9i58AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

- ``ICRA 2025`` RMSeg-UDA: Unsupervised Domain Adaptation for Road Marking Segmentation under Adverse Conditions, Yu-Chen Cai, Hsuan-Chih Hsiao, Wei-Chen Chiu, Hsiu-Yu Lin, **Chiao-Tung Chan**.

- ``IV 2025`` FuseRoad: Enhancing Lane Shape Prediction Through Semantic Knowledge Integration and Cross-Dataset Training, Hsuan-Chih Hsiao, Yu-Chen Cai, Hsiu-Yu Lin, Wei-Chen Chiu, **Chiao-Tung Chan**, Chieh-Chih Wang.

- ``arXiv 2025`` [MemPromptTSS: Persistent Prompt Memory for Iterative Multi-Granularity Time Series State Segmentation](https://arxiv.org/abs/2510.09930), Ching Chang, Ming-Chih Lo, **Chiao-Tung Chan**, Wen-Chih Peng, Tien-Fu Chen.

- ``ICDE 2024`` [TimeDRL: Disentangled Representation Learning for Multivariate Time-Series](https://arxiv.org/abs/2312.04142), Ching Chang, **Chiao-Tung Chan**, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen.

- ``NeurIPS 2024 (Workshop: Self-Supervised Learning — Theory and Practice)`` [Self-Supervised Learning of Disentangled Representations for Multivariate Time-Series](https://openreview.net/forum?id=GnME2Gx5H3), Ching Chang, **Chiao-Tung Chan**, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen.

- ``ICCE-Taiwan 2023`` RLMD: A Dataset for Road Marking Segmentation, Hsuan-Chih Hsiao, Yu-Chen Cai, Hsiu-Yu Lin, Wei-Chen Chiu, **Chiao-Tung Chan**.

# 📜 Certifications & Patents

- **Automotive Functional Safety Professional (AFSP) — ISO 26262**, SGS TÜV Saar
- *2024.12* **3D Object Detection Method and System** (Sole Inventor) — Taiwan Patent App. 113150958 (Pending), Japan Patent App. 2025-069543 (Pending)
- *2023.12* **Camera Calibration Method Based on Vehicle Localization** (Lead Inventor) — US Patent 12,400,367; Taiwan Patent I882582; Japan Patent App. 2024-071947 (Allowed)
- *2021.12* **Safe Following Distance Estimation System and Estimation Method Thereof** (Co-Inventor) — US Patent 11,891,063

# 🛠️ Core Competencies

- **Algorithm & Autonomy**: Visual-Inertial Localization, Sensor Fusion, Object Tracking (IMM-UKF, ICP)
- **AI Acceleration & Compute**: CUDA, TensorRT, Memory Management (zero-copy), HW/SW Co-design
- **Infrastructure & MLOps**: C++, Python, ROS1 / ROS2, AWS CI/CD, Nix, Active-Learning Data Pipelines
- **Leadership & Compliance**: ISO 26262 Functional Safety, Team Scaling, Roadmap Planning, Agile / SOP

# 👤 Visitors
