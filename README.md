# 🍄 Mushroom Disease Detection Using Deep Learning

This repository contains deep learning models for automated fungal disease detection in mushroom cultivation bags.  
The models are trained and evaluated on a high-resolution dataset (761 images) collected from the **Mushroom Development Institute, Savar, Dhaka, Bangladesh**, featuring three classes: **healthy**, **single-infected**, and **mixed-infected**.

## 🧠 Overview
- Focuses on detecting **green mold (Trichoderma)** and **black mold (Aspergillus)** contamination.
- Implements and benchmarks **seven CNN architectures**, including:
  - InceptionV3  
  - ResNet50  
  - EfficientNetV2  
  - (and others)
- **InceptionV3** achieved the highest accuracy of **89.2%**.
- Extensive **data augmentation** (rotation, flipping, zooming, brightness, etc.) was applied to improve model generalization and reduce overfitting.


## 🚀 Features
- Ready-to-train model scripts  
- Configurable preprocessing and augmentation  
- Easy benchmarking and evaluation  
- Reproducible experiment setup  


## 📊 Dataset Information
The dataset is **not included** in this repository.  
It consists of **761 high-resolution images** of mushroom cultivation bags, categorized as:
- 🟢 Healthy  
- 🧫 Single-Infected (green or black mold)  
- ⚫ Mixed-Infected (co-occurring pathogens)

## 🧑‍💻 Author
Developed by **Tazbir Hossain Akash**

---

⭐ If you find this useful, consider giving the repository a star!
