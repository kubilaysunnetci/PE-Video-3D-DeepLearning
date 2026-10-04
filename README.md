# PE-Video-3D-DeepLearning
Video-Based Deep Learning for Pulmonary Embolism Classification on Paired Contrast-Enhanced and Non-Contrast Chest CT. Official repo featuring PureStream-3D, BiLSTM-ResNet-3D, and AttnFocus-3D.

This repository contains the official codebase and network architecture definitions for the study:
**"Video-Based Deep Learning for Pulmonary Embolism Classification on Paired Contrast-Enhanced and Non-Contrast Chest CT: A Single-Centre Retrospective Feasibility Study"**

---

## 📌 Abstract

In this work, we evaluate a video-based 3D deep learning framework trained on a paired clinical cohort of **716 patients (1,432 scans in total)** who underwent both CTPA and NCCT on the same day. Each examination is represented as a 12-second mediastinal-window video (60 x 60 x 3 x 30 volumetric tensor). We benchmark three custom 3D deep learning architectures:
1. **PureStream-3D**
2. **BiLSTM-ResNet-3D**
3. **AttnFocus-3D**

---

## 📁 Repository Structure

```text
.
├── Code.m                  # Complete pipeline (Data preparation, Model setup, Training & Evaluation)
├── README.md               # Project documentation
└── LICENSE                 # MIT License
