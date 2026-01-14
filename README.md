# 🩺 Diabetic Retinopathy Screening using Ensemble Deep Learning

## 📌 Overview
Diabetic Retinopathy (DR) is a serious complication of diabetes that can lead to vision loss if not detected early. This project implements an **automated diabetic retinopathy screening system** using an **ensemble of deep learning models** to classify retinal fundus images into different severity levels.

The ensemble combines **DenseNet**, **EfficientFormer**, and **ConvNeXt** to leverage both CNN-based and transformer-inspired representations for improved accuracy and robustness.

---

## 🚀 Key Highlights
- Automated retinal image classification
- Ensemble learning for better generalization
- Transfer learning with pretrained models
- Improved performance over single-model approaches
- Suitable for healthcare AI research and screening systems

---

## 🧠 Models Used
The ensemble consists of the following architectures:

- **DenseNet** – Efficient feature reuse and strong gradient flow  
- **EfficientFormer** – Lightweight transformer-based vision model  
- **ConvNeXt** – Modern CNN inspired by transformer design principles  

### 🔗 Ensemble Method
- Each model predicts class probabilities independently  
- Final prediction is obtained using **soft voting (average probabilities)**

---

## 🗂️ Dataset
- **Input**: Retinal fundus images
- **Output**: Diabetic retinopathy severity classification

Example classes:
- No DR  
- Mild  
- Moderate  
- Severe  
- Proliferative DR  

⚠️ Dataset is **not included** in this repository due to size and licensing restrictions.

---

## 🛠️ Tech Stack
- Python  
- PyTorch  
- Hugging Face 

---

