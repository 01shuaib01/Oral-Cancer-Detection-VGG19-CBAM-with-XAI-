# Oral-Cancer-Detection-VGG19-CBAM-with-XAI-
Oral Cancer Detection using VGG19 + CBAM with Explainable AI (XAI)
# 🧠 Oral Cancer Detection Using VGG19 + CBAM with Explainable AI (XAI)

## 📌 Overview

This project focuses on detecting oral squamous cell carcinoma (OSCC) from histopathological images using deep learning techniques. We fine-tuned the **VGG19** model and enhanced it with **Convolutional Block Attention Module (CBAM)** to boost classification performance. Additionally, **Explainable AI (XAI)** methods such as **Grad-CAM** were employed to provide transparency into the model's decision-making process—crucial for clinical adoption.

## 🎯 Objective

- Automate the detection of oral cancer from histopathology images.
- Enhance model accuracy using attention mechanisms (CBAM).
- Integrate interpretability using Grad-CAM for explainable decision support.

## 🛠️ Methodology

### 🖼 Dataset
- Publicly available dataset of **Oral Squamous Cell Carcinoma (OSCC)** histology images.
- Binary classification: **Cancerous** vs **Non-Cancerous**.

### 🔍 Model Architecture
- **Base Model**: VGG19 (pre-trained on ImageNet)
- **Enhancement**: Convolutional Block Attention Module (CBAM)
- **Training**: Fine-tuned on OSCC dataset using transfer learning.

### 🎓 Explainable AI
- **Grad-CAM (Gradient-weighted Class Activation Mapping)** was applied to visualize key regions in the histological images that influenced the classification decisions.

## 📊 Results

| Model         | Accuracy | Precision | Recall | F1-Score |
|---------------|----------|-----------|--------|----------|
| VGG19         | 91.87%   | 93.81%    | 89.44% | 91.57%   |
| VGG19 + CBAM  | 94.59%   | 95.98%    | 93.10% | 94.52%   |

- **CBAM** improved the model's ability to focus on critical features within the images.
- **Grad-CAM** visualizations demonstrated the model’s interpretability, highlighting tumor regions.

## 💻 Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib, Seaborn
- Grad-CAM (via Keras/TF hooks)
- Google Colab (optional for training)


