# 🚀 PCI Plume Segmentation using U-Net

## 📌 Project Overview

This project focuses on automatic segmentation of PCI (Pulverized Coal Injection) plume regions from industrial images using Deep Learning and Computer Vision techniques.

The complete pipeline includes image annotation, mask generation, dataset preparation, model training, and plume segmentation using a U-Net architecture implemented in PyTorch.

---

## 🎯 Objective

To develop a semantic segmentation model capable of identifying and extracting plume regions from PCI images for industrial monitoring and analysis.

---

## 🛠️ Tech Stack

* Python
* PyTorch
* OpenCV
* NumPy
* Matplotlib
* LabelMe
* Google Colab

---

## 📂 Project Workflow

Raw PCI Images


<img width="500" height="350" alt="img10" src="https://github.com/user-attachments/assets/7c5427cf-63cc-496a-be6c-f38e2686485e" />
<img width="500" height="350" alt="img9" src="https://github.com/user-attachments/assets/b56302a2-e7f0-4f23-9fb6-9bf00a04259d" />
<img width="500" height="350" alt="img75" src="https://github.com/user-attachments/assets/3aa10009-2746-4c6b-8577-754ee1a3b04a" />

and 97 more...

Image Annotation using LabelMe

<img width="1912" height="1023" alt="Screenshot 2026-06-02 124932" src="https://github.com/user-attachments/assets/8fb83072-ac10-4a5d-84ef-1a51bde37771" />


JSON Annotation Files

<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/70fc6380-d7da-4957-8117-b6fd981e8344" />


Mask Generation

<img width="256" height="256" alt="img1" src="https://github.com/user-attachments/assets/e6fb842f-de70-4053-a790-1a68f6ee2ef7" />
<img width="500" height="350" alt="img10_mask" src="https://github.com/user-attachments/assets/21eb4b3a-b5b1-4963-8f44-4b87b0fb1f19" />
<img width="500" height="350" alt="img65_mask" src="https://github.com/user-attachments/assets/3e34bead-182f-4ed5-ae1d-0929d5482e59" />
<img width="256" height="256" alt="img4" src="https://github.com/user-attachments/assets/266bd1f6-d278-481e-aacf-3090bcfeb504" />
<img width="500" height="350" alt="img47_mask" src="https://github.com/user-attachments/assets/d92a90b2-cb57-413e-8fa8-526928444d1e" />


Dataset Splitting (70% Train • 20% Validation • 10% Test)

<img width="1005" height="286" alt="image" src="https://github.com/user-attachments/assets/b30da6e4-07e8-4f3b-a2f4-07dcd567d6c6" />


U-Net Model Training

<img width="616" height="722" alt="Screenshot 2026-06-02 125828" src="https://github.com/user-attachments/assets/1c5e30ab-5d8b-4465-bdf4-a5fca82396c3" />


Inference on Unseen Images

<img width="863" height="392" alt="image" src="https://github.com/user-attachments/assets/8cb4331e-5651-4615-9443-f1e384000b49" />


Plume Segmentation Mask Generation

<img width="388" height="392" alt="Screenshot 2026-06-02 130101" src="https://github.com/user-attachments/assets/678f613a-cbb1-403e-869c-b1115b2ad635" />

---

## 📊 Dataset Details

| Dataset Split          | Images |
| ---------------------- | ------ |
| Training               | 70     |
| Validation             | 20     |
| Testing                | 10     |
| Total Annotated Images | 100    |

---

## 🧠 Model Architecture

The project utilizes a U-Net based semantic segmentation architecture consisting of:

* Encoder (Downsampling Path)
* Bottleneck Layer
* Decoder (Upsampling Path)
* Skip Connections

The model learns pixel-level plume segmentation from manually annotated masks.

---

## ✨ Features

✅ Manual annotation using LabelMe

✅ Automatic mask generation from JSON annotations

✅ Custom PyTorch Dataset & DataLoader

✅ U-Net based semantic segmentation

✅ Model training and validation

✅ Inference on unseen test images

✅ Industrial plume region extraction

---

## 📈 Training Results

Model successfully learned plume patterns from annotated PCI images and generated segmentation masks for unseen test images.

Training and validation losses consistently decreased during training, indicating successful learning and generalization.

---

## 🔮 Future Improvements

* Train using larger datasets (500+ images)
* Implement Mask R-CNN for instance segmentation
* Calculate IoU and Dice Score metrics
* Deploy as a web-based monitoring application
* Real-time industrial plume detection

---


Built as part of an industrial plume segmentation workflow using U-Net and PyTorch.
