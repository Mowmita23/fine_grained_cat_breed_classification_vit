# Dataset Information

## 📌 Dataset Name

Oxford-IIIT Pet Dataset

---

## 🧠 Overview

The Oxford-IIIT Pet Dataset is a fine-grained image classification dataset consisting of images of 37 different pet breeds, including both cats and dogs. It is widely used in computer vision research for fine-grained visual classification (FGVC) tasks.

---

## 📊 Dataset Statistics

* Total Classes: 37
* Cat Breeds: 12
* Dog Breeds: 25
* Total Images: ~7,400
* Image Variability: High intra-class similarity and inter-class variation

---

## ✂️ Data Split

The dataset is typically divided into:

* Training set
* Validation set
* Test set

(Exact split used in this project follows standard FGVC setup or official split where applicable.)

---

## 🧹 Preprocessing Steps

The following preprocessing techniques were applied:

* Resizing images to 224 × 224 pixels
* Normalization using ImageNet mean and standard deviation
* Data augmentation:

  * Random horizontal flipping
  * Random cropping
  * Color jittering
  * Random erasing (optional)

---

## 🎯 Task Definition

This project focuses on:

> Fine-grained image classification of pet breeds using Vision Transformer-based architectures.

The main challenge lies in distinguishing visually similar breeds with subtle differences in texture, shape, and pattern.

---

## 🧪 Challenges

* High inter-class similarity (visually similar breeds)
* Large intra-class variation (pose, lighting, background)
* Limited dataset size compared to large-scale datasets

---

## 📌 Usage in This Project

This dataset is used to train and evaluate:

* Vision Transformer (ViT)
* Global Context Vision Transformer (GCViT)
* Fine-grained classification models

---

## 🔗 Reference

* https://www.robots.ox.ac.uk/~vgg/data/pets/
