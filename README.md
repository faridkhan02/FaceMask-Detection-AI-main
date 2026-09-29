from pathlib import Path

readme = r"""# 😷 Face Mask Detection AI

> An AI-powered computer vision system for detecting whether people are wearing face masks using **YOLOv11**.

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org/)
[![YOLOv11](https://img.shields.io/badge/YOLOv11-Ultralytics-orange)](https://docs.ultralytics.com/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)](https://opencv.org/)
[![License](https://img.shields.io/badge/License-See%20NOTICE-lightgrey)](NOTICE.md)

---

## 📌 Project Overview

**Face Mask Detection AI** is a computer vision project designed to detect face-mask usage from images, videos, and other supported inputs.

The project uses a **YOLOv11 object-detection model** trained for face-mask detection and provides a simple Python-based workflow for:

- Face-mask detection
- Image/video inference
- Model downloading
- Evaluation
- Training through Google Colab
- Saving detection results

The repository is organized so that model files, test data, videos, evaluation scripts, and inference code can be maintained separately.

---

## ✨ Features

- 🎯 **YOLOv11-based object detection**
- 😷 Detects face-mask usage
- 🖼️ Supports image-based inference
- 🎥 Supports video-based detection
- 📊 Model evaluation support
- ☁️ Google Colab training notebook
- 📦 Automated model download script
- 💾 Saves inference/output results
- 🧪 Dedicated test resources
- 🧩 Modular Python implementation

---

## 🧠 How It Works

The overall workflow is:

```text
Input Image / Video
        │
        ▼
   YOLOv11 Model
        │
        ▼
Face / Mask Detection
        │
        ▼
Bounding Boxes
        │
        ▼
Confidence Scores
        │
        ▼
Detection Results
        │
        ▼
Saved Output
