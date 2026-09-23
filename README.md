# Neural Networks and Deep Learning
### MDS505-2 — MSc Data Science | CHRIST (Deemed to be University)

---

## Overview

This repository contains all lab exercises completed as part of the **Neural Networks and Deep Learning** course. Each exercise focuses on a core concept in deep learning — from building basic networks from scratch to fine-tuning state-of-the-art pretrained models.

All implementations are in **Python** using **TensorFlow / Keras**, and were developed and tested on **Google Colab**.

---

## Topics Covered

| # | Topic |
|---|-------|
| 1 | Artificial Neural Networks — Classification |
| 2 | Artificial Neural Networks — Regression |
| 3 | Backpropagation and Optimization |
| 4 | MLP with Dropout and Batch Normalization |
| 5 | Convolutional Operations and Feature Map Visualization |
| 6 | Transfer Learning and Fine-Tuning with Pre-trained CNNs |

---

## Datasets Used

- Pima Indians Diabetes Dataset
- California Housing Dataset
- MNIST Handwritten Digits
- CIFAR-10
- Flowers Dataset (TensorFlow)

---

## Key Concepts Implemented

- Data preprocessing — normalization, handling missing values, train/val/test splits
- ANN architecture design — Dense layers, activation functions, output layers
- Regression vs Classification networks
- Loss functions — MSE, Binary Crossentropy, Categorical Crossentropy
- Optimizers — Adam, SGD, RMSProp
- Regularization — Dropout, Batch Normalization
- Callbacks — EarlyStopping, ModelCheckpoint, ReduceLROnPlateau
- Convolution operations — manual implementation and Keras Conv2D
- Filter visualization — Edge Detection, Sharpening, Blur, Emboss
- Feature map extraction and visualization across CNN layers
- Transfer Learning with MobileNetV2 (ImageNet weights)
- Fine-tuning pretrained layers

---

## Tools and Libraries

```
Python          3.x
TensorFlow      2.x
Keras           (via TensorFlow)
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
SciPy
Google Colab
```

---

## Results Summary

| Exercise | Model | Dataset | Metric | Score |
|---|---|---|---|---|
| Classification | ANN | Pima Diabetes | Accuracy | ~77% |
| Regression | ANN | California Housing | R² Score | ~0.80 |
| Regularization | MLP + Dropout + BN | MNIST | Accuracy | ~98% |
| CNN Features | Custom CNN | CIFAR-10 | Visual Analysis | — |
| Transfer Learning | MobileNetV2 | Flowers | Accuracy | ~90% |

---

## How to Run

1. Clone the repository
```bash
git clone https://github.com/Faustena25/neural-networks-deep-learning.git
```

2. Open any `.ipynb` file in Google Colab or Jupyter Notebook

3. Run cells sequentially from top to bottom

4. All datasets load automatically — no manual downloads required

---

## Repository Structure

```
📦 neural-networks-deep-learning
 ┣ 📂 classification
 ┣ 📂 regression
 ┣ 📂 backpropagation
 ┣ 📂 mlp-regularization
 ┣ 📂 cnn-feature-maps
 ┣ 📂 transfer-learning
 ┗ 📜 README.md
```

---

## Author

**Faustena S (Tina)**
MSc Data Science — Batch 2025–27
CHRIST (Deemed to be University), Bengaluru

[![GitHub](https://img.shields.io/badge/GitHub-Faustena25-black?logo=github)](https://github.com/Faustena25)

---

> *All exercises were implemented for academic purposes as part of the MDS505-2 coursework.*
