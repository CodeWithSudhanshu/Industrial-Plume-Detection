# 🔥 Industrial Plume Segmentation for PCI Furnace

An industrial computer vision project focused on automatically segmenting plume regions from PCI (Pulverized Coal Injection) furnace tuyere images using deep learning techniques.

---

## 📌 Project Overview

Monitoring plume behavior inside PCI furnaces is essential for understanding combustion characteristics and supporting operational decision-making.

This project explores semantic and instance segmentation approaches to identify plume regions from furnace images. The objective is to generate binary segmentation masks that accurately isolate the target plume region from the background.

The work was carried out as part of an industrial internship, emphasizing experimentation, iterative improvement, and real-world validation.

---

## ✨ Features

✅ Polygon-based image annotation workflow

✅ Segmentation mask generation

✅ Custom PyTorch dataset pipeline

✅ Train / Validation / Test split

✅ U-Net experimentation for semantic segmentation

✅ Mask R-CNN experimentation for instance segmentation

✅ Binary mask generation

✅ Inference on unseen furnace images

✅ Generalization testing across different tuyere conditions

---

## 🏗️ Project Workflow

```text
PCI Furnace Images
        ↓
Image Annotation (LabelMe)
        ↓
JSON Annotation Files
        ↓
Segmentation Mask Generation
        ↓
Dataset Preparation
(70% Train • 20% Validation • 10% Test)
        ↓
U-Net Experimentation
        ↓
Mask R-CNN Experimentation
        ↓
Binary Mask Generation
        ↓
Inference on Unseen Images
        ↓
Performance Evaluation
```

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Deep Learning Framework
- PyTorch

### Models
- U-Net
- Mask R-CNN

### Computer Vision
- OpenCV
- NumPy

### Annotation Tools
- LabelMe

### Visualization
- Matplotlib

### Development Environment
- Google Colab (CUDA)

### Version Control
- Git & GitHub

---

## 🚀 Key Contributions

- Annotated **100+ industrial furnace images** using polygon-based annotations.
- Generated segmentation masks for supervised learning workflows.
- Built custom PyTorch datasets and data loaders.
- Trained and evaluated multiple segmentation architectures.
- Developed inference pipelines capable of producing binary plume masks.
- Tested model behavior on previously unseen furnace images.

---

## 📈 Experimental Journey

Rather than relying on a single approach, multiple strategies were explored throughout the project.

### Phase 1: U-Net

- Implemented a semantic segmentation pipeline.
- Trained the model on annotated furnace images.
- Evaluated predictions on unseen samples.
- Identified limitations through iterative feedback.

### Phase 2: Mask R-CNN

- Explored instance segmentation techniques.
- Generated cleaner binary masks.
- Improved interpretability of segmentation outputs.
- Extended testing to unseen tuyere conditions.

---

## 🔒 Confidentiality Notice

> **Important:** The industrial image dataset used during this work is confidential and proprietary. In accordance with organizational guidelines, the original images, annotations, masks, and dataset files are not included in this repository.

This repository contains only the implementation, methodology, and supporting code necessary to understand the approach.

---


## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Industrial Computer Vision
- Semantic Segmentation
- Instance Segmentation
- Dataset Engineering
- Annotation Pipelines
- Deep Learning with PyTorch
- Model Experimentation
- Binary Mask Generation
- Iterative Problem Solving
- Working with Confidential Industrial Data

---

## 🔮 Future Scope

- Generalization across multiple furnace conditions.
- Real-time plume monitoring.
- Interactive web-based inference interface.
- Confidence estimation for predictions.
- Model optimization for deployment.
- Automated reporting and visualization dashboards.

---

## 🤝 Acknowledgement

This work was carried out as part of an industrial internship under the guidance of mentors from Tata Steel. Their continuous feedback and encouragement played an important role in shaping the experimental journey and improving the overall approach.

---

## ⭐ If you found this project interesting, consider giving it a star!
