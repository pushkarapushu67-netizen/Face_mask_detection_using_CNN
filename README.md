# 😷 Face Mask Detection using CNN

With increasing emphasis on public health and safety, automated systems for monitoring mask compliance have become highly relevant.  

This project focuses on building a **Convolutional Neural Network (CNN)** model to detect whether a person is wearing a face mask or not using image data.

The model classifies images into:
- With Mask  
- Without Mask  

---

## 🚀 Project Overview

This project implements an end-to-end deep learning pipeline:

- Data collection from Kaggle dataset  
- Image preprocessing (resizing and normalization)  
- Data augmentation to improve generalization  
- Building a CNN architecture  
- Model training and validation  
- Performance evaluation using classification metrics  

---

## 🎯 Objective

- Develop a binary image classification model  
- Detect mask compliance in images or video frames  
- Enable real-world safety and surveillance applications  

---

## 📂 Dataset

- Source: Kaggle Face Mask Dataset  
- Image-based dataset containing masked and unmasked faces  

---

## 🛠️ Project Workflow

### 1. Problem Understanding
- Binary classification problem  
- Input: Face images  
- Output: Mask / No Mask  

### 2. Data Preprocessing
- Resized images (e.g., 128x128 / 224x224)  
- Normalized pixel values (0–1)  
- Converted labels into numerical format  

### 3. Data Augmentation
- Rotation  
- Flipping  
- Zooming  
- Shearing  

### 4. Model Building
- CNN architecture:
  - Convolution + ReLU  
  - MaxPooling  
  - Dropout  
  - Fully Connected Layers  
  - Sigmoid output layer  

### 5. Model Training
- Loss Function: Binary Crossentropy  
- Optimizer: Adam  
- Metric: Accuracy  

### 6. Model Evaluation
- Accuracy  
- Confusion Matrix  
- Precision & Recall  

---

## 📊 Results

The model effectively distinguishes between masked and unmasked faces, demonstrating the capability of CNNs in real-time safety compliance systems.

---

## 💡 Applications

- Public surveillance systems  
- Entry control in offices, malls, and airports  
- Smart health monitoring solutions  

---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## 📌 Conclusion

This project demonstrates how deep learning can be applied to real-world public safety challenges, enabling automated and scalable monitoring systems.
