# 🌍 3D Reconstruction -- From Pixel to the World

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv&logoColor=white)](https://opencv.org/)
[![License](https://img.shields.io/badge/License-MIT-purple)](LICENSE)

## 📖 Overview

**From Pixel to the World** is a computer vision project aimed at reconstructing 3D scenes from 2D images using Python.
This project implements a Structure from Motion (SfM) pipeline from scratch, covering everything from camera calibration to dense point cloud generation.

It is designed to run **locally** to leverage native 3D visualization capabilities (using Open3D/Matplotlib).

> **Note:** This project is based on the course *Reconstruction 3D à partir d'images multivues* (Udemy).

---

## 🚀 Features

The pipeline is divided into modular steps:

* **📸 Camera Calibration:** Estimation of the Intrinsic Matrix ($K$) and distortion coefficients.
* **🧩 Feature Extraction:** Detection and matching of keypoints using SIFT/ORB.
* **📐 Epipolar Geometry:** Computation of the Fundamental Matrix ($F$) and Essential Matrix ($E$).
* **🧊 3D Triangulation:** Converting 2D image points into 3D world coordinates.
* **☁️ Visualization:** Rendering the resulting Point Cloud (`.ply`).

---

## 🛠️ Installation

### 1. Clone the repository
```bash
