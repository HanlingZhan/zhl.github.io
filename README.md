# DimHand 🖐️✨

> **A Large-Scale Benchmark for Hand Pose Estimation under Dynamic Low-Light Conditions** 🌙💡

**Website:** [https://hanlingzhan.github.io/DimHand/](https://hanlingzhan.github.io/DimHand/) 🌐

---

## 📌 Overview | 概述

**DimHand** is the **first large-scale 3D hand pose dataset** capturing continuous motion under **dynamic low-light conditions**, comprising **745,280 frames** from **15 subjects** performing **15 distinct sequential actions** across **5 viewpoints** with illumination ranging from **0.1 to 10 lux**. 🌟

DimHand 是首个在**动态弱光条件**下捕捉连续运动的**大规模 3D 手部姿态数据集**，包含 **15 位受试者**执行 **15 种不同序列动作**的 **745,280 帧**图像，覆盖 **5 个视角**，光照范围从 **0.1 到 10 lux**。📊

> 🔗 **Visit our project website for full details:** [https://hanlingzhan.github.io/DimHand/](https://hanlingzhan.github.io/DimHand/)

---

## 🏆 Highlights | 亮点

| Feature | Description |
|---------|-------------|
| 🎯 **First of its kind** | First low-light 3D hand pose dataset with continuous motion |
| 🌈 **Dynamic illumination** | 0.1–10 lux range covering extreme low-light to dim conditions |
| 👥 **Diverse subjects** | 15 subjects (9♂ 6♀) with varied hand shapes |
| 🤲 **Rich gestures** | 15 distinct sequential actions including grasping, pinching, waving, etc. |
| 📹 **Multi-view** | 5 synchronized RGB-D camera views |
| 🏷️ **High-quality annotations** | 3D joints + MANO parameters + mesh annotations |

---

## 📦 Dataset Statistics | 数据集统计

| Statistic | Value |
|-----------|-------|
| Total frames | **745,280** 🎞️ |
| Subjects | **15** (9 male, 6 female) 👫 |
| Actions | **15** distinct gestures 🤲 |
| Camera views | **5** 📷 |
| Illumination range | **0.1 – 10 lux** 💡 |
| Modality | RGB + Depth 🎨📏 |
| Annotations | 3D Joints + MANO + Mesh 🏷️ |

---

## 📊 Website Sections | 网页内容导览

Our project website [https://hanlingzhan.github.io/DimHand/](https://hanlingzhan.github.io/DimHand/) includes:

| Section | Content |
|---------|---------|
| 🎬 **Video** | Project demo video showcasing DimHand and DimNet |
| 📄 **Abstract** | Paper abstract and motivation |
| 📊 **Benchmark** | Dataset comparison table with existing works |
| 🔬 **Experiments** | Qualitative results and comparisons |
| 🤲 **Gestures** | 15 gesture classes with descriptions |
| 📁 **Directory** | Dataset folder structure |
| 📝 **Citation** | BibTeX citation for the paper |
| 📋 **Application** | Dataset request form |

---
```
## 🗂️ Directory Structure | 目录结构
${ROOT}
├── multidata/
│ ├── subject01 ~ subject15/
│ │ ├── action01 ~ action15/
│ │ │ ├── camera0 ~ camera4/
│ │ │ │ ├── rgb/ # RGB sequences 
│ │ │ │ ├── depth/ # Depth maps 
│ │ │ │ └── center_uvd.json
│ │ │ └── camera_paras.json
│ │ │...
│ │...
├── annotations/
│ ├── subject01 ~ subject15/
│ │ ├── action01 ~ action15/
│ │ │ ├── joint.json # 3D joints 
│ │ │ ├── mano.json # MANO params 
│ │ │ └── mesh.json # 3D mesh 
│ │ │...
│ │...
```
---

## 📖 Citation | 引用

If you use DimHand in your research, please cite:
bibtex
@inproceedings{zhan2026dimhand,
title={DimHand: A Large-Scale Benchmark for Hand Pose Estimation under Dynamic Low-Light Conditions},
author={Zhan, Hanling and Ren, Pengfei and Zhang, Haoyang and Wang, Xinyi and Xie, Liang and Yin, Erwei},
booktitle={Proceedings of the 34th ACM International Conference on Multimedia (MM '26)},
year={2026}
}

---

## 📬 Contact | 联系方式

For dataset access, please fill out the application form on our website: [https://hanlingzhan.github.io/DimHand/](https://hanlingzhan.github.io/DimHand/) 📋

---

## 🙏 Acknowledgement | 致谢

This work is supported by Shanghai Jiao Tong University, Beijing University of Posts and Telecommunications, and Defense Innovation Institute, Academy of Military Sciences. 🤝

---

> **⭐ If you find this work useful, please consider starring our repo!**
