# CIFAR-10 Image Classifier (PyTorch)  
### *Build vs Buy Evaluation for Self-Driving Car Vision System*

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-EE4C2C.svg)
![Status](https://img.shields.io/badge/Status-Completed-blue.svg)

---

## 🚀 Project Overview

This repository contains a PyTorch implementation of a **CIFAR-10 image classifier**, built to help a self-driving car startup decide whether to **build** an in-house computer vision solution or **buy** a commercial algorithm from Detectocorp.

Detectocorp claims **70% accuracy** on CIFAR-10.  
Your task was to build a model from scratch and compare results.

This project:

- Loads and preprocesses the CIFAR-10 dataset  
- Builds a custom Convolutional Neural Network  
- Trains the model and records loss  
- Evaluates accuracy on unseen data  
- Provides a **Build vs Buy recommendation**  

Final model accuracy: **76.97%**

---

### 📊 Accuracy Comparison

| Model | CIFAR-10 Accuracy |
|-------|--------------------|
| **Your PyTorch CNN** | **73.22%** |
| Detectocorp Algorithm | 70% |
| State-of-the-Art | 90% – 97% |

Your model **outperformed** the Detectocorp commercial baseline.

---

## 📝 Recommendation: Build, Don’t Buy

Because the custom-built PyTorch model achieved **76.97%**, it clearly exceeds Detectocorp's claimed **70%** accuracy.  

This demonstrates that an in-house solution:

- Can outperform the external commercial option  
- Offers flexibility for fine-tuning on real roadside data  
- Avoids vendor lock-in  
- Has substantial room for improvement using deeper CNNs or transfer learning  

**Recommendation:**  
The company should **build** the vision system in-house rather than purchasing Detectocorp’s 70% model.

---

## 🔮 Future Improvements

Potential next steps to enhance performance:

- Add data augmentation (random crop, flip, color jitter)  
- Add Batch Normalization  
- Use deeper architectures (ResNet-18, VGG-16)  
- Apply learning rate schedulers  
- Fine-tune pretrained ImageNet models  
- Explore object detection architectures (YOLO, SSD, Faster-RCNN)  

---





