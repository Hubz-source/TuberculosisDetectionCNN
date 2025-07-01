# Tuberculosis Bacteria Detection with CNNs

This repository contains a simple experiment using Convolutional Neural Networks (CNNs) to detect tuberculosis (TB) bacteria in microscopy images stained with the Ziehl-Neelsen method. This project was run as a personal side project to explore transfer learning in Keras and image classification using medical datasets.

The goal was to train a CNN (via transfer learning) to classify image patches for the presence or absence of TB bacilli. All training was done using publicly available datasets and a single Jupyter notebook executed in Google Colab.

<p align="center">
  <img src="media/training.gif" alt="CNN Training Animation" width="600"/>
</p>

> **Note:** This is not a production-grade implementation and does not aim for optimal code structure or computational efficiency. It was purely exploratory.

---

##  Repository Structure


---

## 🧪 Project Overview

- **Framework**: Keras with TensorFlow backend
- **Dataset**: Ziehl-Neelsen stained slide images (patch-level)
- **Approach**: Transfer learning using a pre-trained CNN (e.g., MobileNetV2 or VGG16)
- **Goal**: Binary classification – detect TB-positive patches

---

## 🔧 Getting Started

You can run the notebook directly in Google Colab. Just make sure to:

1. Mount your Google Drive to access datasets and save outputs.
2. Set up the correct file paths depending on your directory structure.
3. (Optional) Modify the network architecture or hyperparameters for experimentation.

---

## 🗃️ Dataset

The dataset used is publicly available and consists of slide images prepared with the Ziehl-Neelsen staining method, often used in TB diagnostics. The notebook preprocesses the data into small patches before feeding them to the network.

---

## 📈 Results & Observations

- The model achieves promising classification accuracy with minimal tuning.
- Transfer learning significantly improves convergence and generalization.
- Some degree of false positives/negatives remains, especially on borderline cases.

See the training progress animation above for a sense of model learning dynamics.

---

## 🚧 Limitations

- This project does not claim to achieve state-of-the-art results.
- No systematic hyperparameter tuning or cross-validation was performed.
- Code is written for exploration, not for deployment.

---