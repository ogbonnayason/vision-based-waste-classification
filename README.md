# Waste Classification with Deep Learning

## 📌 Project Overview

This repository contains an AI‑based computer vision system for automatically classifying waste into different categories using deep learning techniques.  
The solution combines convolutional neural networks (CNNs) with a user‑friendly web interface built with **Streamlit**.

This project demonstrates practical application of deep learning to support **sustainability and recycling** initiatives.

---

## 🧠 Problem Statement

Improper waste segregation contributes to environmental pollution and inefficient recycling. Manual sorting is slow, inconsistent, and error‑prone.  
This system leverages computer vision to automatically classify waste images into meaningful categories, enabling faster and more accurate waste management.

---

## 🎯 Objectives

- Build and train CNN models on a labeled waste dataset
- Compare model performance (accuracy, confusion matrices)
- Deploy the best model in a Streamlit web app for interactive use
- Highlight limitations and ethical considerations

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV for image preprocessing
- CNN architectures: **MobileNetV2**, **ResNet50**
- Streamlit for web deployment

---

## 📊 Data & Models

This project was trained on the **TrashNet dataset**, a public waste image dataset with six common waste categories (cardboard, glass, paper, plastic, metal, trash). :contentReference[oaicite:0]{index=0}

### Key Datasets
- **TrashNet:** ⟶ Contains ~2,500 images across 6 classes. :contentReference[oaicite:1]{index=1}

---

## 🧪 Results Summary

| Model | Approx. Accuracy |
|-------|------------------|
| MobileNetV2 | ~85% |
| ResNet50 | ~89% |

ResNet50 tends to achieve higher accuracy but at the cost of greater computational complexity.

Confusion matrices typically reveal class overlap (e.g., plastic ↔ glass). Visualization can be found in the `results/` folder.

---

This project is provided for academic and portfolio use.
