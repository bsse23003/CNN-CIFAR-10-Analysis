# 🧠 Comparative Analysis of CNN Architectures on CIFAR-10 using PyTorch

## 📌 Project Overview
This project presents a **comparative analysis of three popular Convolutional Neural Network (CNN) architectures**:

- AlexNet  
- VGG  
- ResNet  

The models are trained and evaluated on the **CIFAR-10 dataset** using **PyTorch**.  
The study focuses on comparing performance, training efficiency, and the impact of different optimization strategies.

---

## 🎯 Objectives

- Implement multiple CNN architectures  
- Compare their performance on CIFAR-10  
- Analyze optimization techniques  
- Understand the effect of network depth on accuracy  


---

## 🏗️ CNN Architectures

### 🔹 AlexNet
- Early deep CNN architecture  
- Large convolution filters  
- Uses dropout for regularization  

### 🔹 VGG (VGG16)
- Deep network with small (3×3) filters  
- Uniform architecture  
- High computational cost  

### 🔹 ResNet (ResNet18/34)
- Uses residual (skip) connections  
- Solves vanishing gradient problem  
- Allows deeper networks  

---

## ⚙️ Optimization Strategies

- Optimizers:
  - SGD  
  - Adam  

- Techniques:
  - Learning Rate Scheduling  
  - Batch Normalization  
  - Dropout  
  - Data Augmentation:
    - Random Crop  
    - Horizontal Flip  

---

## 🧪 Experimental Setup

- Framework: PyTorch  
- Loss Function: CrossEntropyLoss  
- Evaluation Metrics:
  - Accuracy  
  - Loss  

.com/your-username/cnn-comparison-cifar10.git
cd cnn-comparison-cifar10
