# skin-lesion-edge-ai
Skin cancer is one of the most common forms of cancer globally, and early detection can significantly improve treatment outcomes. In this project, we develop a lightweight convolutional neural network for classifying skin lesions into multiple diagnostic categories using the HAM10000 dataset.

# Real-Time Skin Lesion Classification on Edge Devices

This project aims to develop a lightweight and accurate skin lesion classification model using deep learning. The system is optimized for deployment on edge devices such as low-power GPUs or mobile platforms.

## 🔍 Problem Statement
Early detection of skin cancer is crucial for effective treatment. This project classifies dermatoscopic images into multiple lesion types using the HAM10000 dataset.

## 📦 Dataset
- **HAM10000** (Human Against Machine)
- Contains 10,000+ labeled dermatoscopic images across 7 classes
- Preprocessing includes resizing, augmentation, and normalization

## 🧠 Model Architecture
- MobileNetV2 / Custom CNN
- Dropout, BatchNorm
- Grad-CAM for interpretability

## 📊 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- Grad-CAM Visualizations

## 📁 Project Structure

skin-lesion-edge-ai/
├── data/
├── models/
├── notebooks/
├── outputs/
├── research/
├── utils/
├── README.md
├── requirements.txt
└── .gitignore


## 🚀 Goals
- Achieve high classification accuracy
- Compress model for edge deployment
- Ensure transparency through explainability techniques

## ✍️ Author
Mohammed Harfan Abdul Azeez
