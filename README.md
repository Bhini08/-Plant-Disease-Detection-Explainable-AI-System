# 🌿 Plant Disease Detection & Explainable AI System (2025–2026)

> A production-grade deep learning system for **automated plant disease detection**, severity estimation, and **explainable AI visualization using Grad-CAM**. Designed to support precision agriculture and early crop disease intervention.

---

## 🚀 Project Highlights

- 🧠 **Multi-class plant disease classification** using state-of-the-art CNN architectures  
- 🌱 **Transfer Learning** with EfficientNetB0, MobileNetV2, and ResNet50  
- 📍 **Explainable AI (XAI)** using Grad-CAM heatmaps for transparency  
- ⚠️ **Disease severity estimation** (Healthy → Mild → Moderate → Severe)  
- 🌾 Built for **real-world agricultural decision support systems**

---

## 🧠 Problem Statement

Crop diseases significantly reduce agricultural productivity worldwide. Manual inspection is:

- Time-consuming ⏳  
- Error-prone ❌  
- Not scalable 📉  

This project solves the problem using **deep learning-based image classification + explainable AI**, enabling early detection and actionable insights.

---

## 🌿 Supported Plant Diseases

The model is trained on the **PlantVillage dataset** and supports detection of:

### 🍅 Tomato
- Early Blight  
- Late Blight  
- Septoria Leaf Spot  
- Leaf Mold  

### 🥔 Potato
- Early Blight  
- Late Blight  

### 🌶️ Pepper Bell
- Bacterial Spot  

### 🌱 Healthy Class
- Healthy Leaf (No Disease)

---

## ⚠️ Severity Classification System

Each prediction includes a severity level:

| Level | Description | Action |
|------|-------------|--------|
| 🟢 Healthy | No infection detected | No treatment required |
| 🟡 Mild | Early symptoms visible | Preventive monitoring |
| 🟠 Moderate | Disease spreading | Treatment required |
| 🔴 Severe | Extensive infection | Immediate intervention |

---

## 📍 Explainability (Grad-CAM)

To ensure transparency and trust in predictions, the system uses **Grad-CAM (Gradient-weighted Class Activation Mapping)**:

- Highlights infected regions on leaf images  
- Visualizes model attention areas  
- Helps validate AI decision-making  
- Improves interpretability for farmers & researchers  

---

## 🧠 Model Architecture

### Deep Learning Pipeline:
- Convolutional Neural Networks (CNN)
- Transfer Learning:
  - EfficientNetB0
  - MobileNetV2
  - ResNet50
- Fully Connected Classification Head
- Softmax Output Layer

### Explainability:
- Grad-CAM Heatmap Generation

