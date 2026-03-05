# 🥔 High-Accuracy Potato Leaf Disease Classification Using Transfer Learning with ResNet50  

A deep learning-based automated system for detecting and classifying potato leaf diseases using **transfer learning with ResNet50**.  
This project accurately identifies **Early Blight**, **Late Blight**, and **Healthy** potato leaves using real-world agricultural data and pretrained deep networks for precision farming.

---

# 📄 Research Paper

## Title: High-Accuracy Potato Leaf Disease Classification Using Transfer Learning with ResNet50  

📊 Achieved **98.88% average accuracy** using 5-Fold Cross Validation  

🏛 Published at: **IEEE AMICT 2025 Conference**

🔗 **DOI (Official Publication):** https://doi.org/10.1109/AMICT65811.2025.11402659

<p align="center">
  <img src="1766487829015.jpg" width="750">
</p>
📁 Paper available in repository  

---

## 🚀 Features

- Transfer learning with pretrained ResNet50  
- Hybrid real-world + benchmark dataset  
- Custom classifier head with Batch Normalization  
- Multi-class disease classification  
- Data augmentation & preprocessing  
- K-Fold cross validation  
- Confusion matrices, accuracy & loss curves  

---

## 🧠 Classes Detected

| Class | Description |
|------|------------|
| Healthy | Normal potato leaf |
| Early Blight | Fungal leaf infection |
| Late Blight | Severe crop disease |

---

## 📷 Sample Images

<p align="center">
  <img src="4 image.png" width="440"/>
  <img src="4 image h.png" width="440"/>
</p>

---

## 📂 Dataset

**PlantVillage + Real Field Images (Kannauj, India)**  

### Preprocessing:
- Resize to 224×224  
- Normalization  
- Data augmentation:
  - Rotation  
  - Flipping  
  - Zoom  
  - Cropping  

Total images: **900**

---

## 🏗 Model Architecture

- ResNet50 backbone (ImageNet pretrained)  
- Global Average Pooling  
- Dense (512 units + ReLU)  
- Batch Normalization  
- Dropout (0.5)  
- Softmax output layer (3 classes)  

<p align="center">
  <img src="Model Arch.webp" width="750">
</p>

---

## 📈 Performance

| Metric | Value |
|-------|------|
| Average Accuracy | **98.88%** |
| Best Fold Accuracy | **99–100%** |
| Precision | 0.97 |
| Recall | 0.97 |
| F1-Score | 0.97 |

<p align="center">
  <img src="Fold 1/Acc 1.png" width="320"/>
  <img src="Fold 1/Loss 1.png" width="320"/><br>
  <img src="Fold 1/Cnf 1.png" width="320"/>
  <img src="Fold 1/Roc 1.png" width="320"/>
</p>

---

## 📊 Model Comparison

| Model | Accuracy |
|------|---------|
| MobileNetV2 | 86.11% |
| CNN-Transformer | 95% |
| SVM | 95% |
| Previous AI Frameworks | 98% |
| **Proposed ResNet50** | **98.88%** |

---
## Prediction Images
<img src="Prdiction images.png" width="720"/>

## 🛠 Technologies Used

### 🧠 Deep Learning & Machine Learning
- TensorFlow – model building and training  
- Keras – high-level neural network API  
- ResNet50 (Transfer Learning) – pretrained CNN backbone  
- Scikit-learn – evaluation metrics, cross-validation  

### 📷 Image Processing
- OpenCV – image loading and preprocessing  
- PIL (Pillow) – resizing and augmentation  
- NumPy – numerical computation  

### 📊 Data Visualization & Analysis
- Matplotlib – training curves and plots  
- Seaborn – confusion matrices & heatmaps  


## ☁️ Experimentation Platform

All model training and evaluation were performed on **Kaggle Notebooks** using GPU acceleration to ensure faster convergence and reproducibility.

### Environment Details:
- NVIDIA GPU (Kaggle P100/T4)  
- Python 3.8+  
- TensorFlow with CUDA support  
- Pre-installed ML & data science libraries  

### Advantages:
- High-performance training  
- Reproducible experiments  
- Cloud-based dataset management  
- Free GPU compute  



---

## 🌾 Applications

- Smart agriculture systems  
- Mobile disease detection apps  
- IoT crop monitoring  
- Precision farming tools  

---

## ⭐ If you find this project useful, please star the repository!
