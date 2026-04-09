
# 🧠 Clinical MRI Classification using CNN

<p align="center">
  <img src="https://img.shields.io/badge/Task-Medical%20Image%20Classification-blue" />
  <img src="https://img.shields.io/badge/Model-CNN-green" />
  <img src="https://img.shields.io/badge/Framework-TensorFlow%2FKeras-orange" />
  <img src="https://img.shields.io/badge/Accuracy-80.44%25-brightgreen" />
  <img src="https://img.shields.io/badge/Classes-4-blueviolet" />
</p>

---

## 📌 Overview

This project presents a **deep learning pipeline for brain MRI classification** using a custom Convolutional Neural Network (CNN). The model classifies MRI scans into:

- Glioma  
- Meningioma  
- Pituitary Tumor  
- No Tumor  

The system is designed with a focus on **clinical reliability**, especially minimizing false negatives in healthy patients.

---

## ⚙️ Pipeline

```text
MRI Images → Preprocessing → CNN Feature Extraction → Classification Head → Predictions