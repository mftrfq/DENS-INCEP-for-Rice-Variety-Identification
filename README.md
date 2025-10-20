# Rice Variety Identification using DENS-INCEP Transfer Learning

[![DOI](https://zenodo.org/badge/DOI/10.1109/ACCESS.2025.3562585.svg)](https://doi.org/10.1109/ACCESS.2025.3562585)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🌾 Overview

This repository hosts the source code and resources for a deep learning project focused on the **accurate identification and classification of different rice varieties** from image data.

This project specifically implements and evaluates a custom **Transfer Learning architecture named DENS-INCEP**, which combines features from established Convolutional Neural Networks (CNNs) to achieve high performance in agricultural classification tasks.

## 📖 Background & Motivation

The accurate and rapid identification of rice varieties is crucial for quality control, breeding programs, and agricultural management. Manual identification is time-consuming and often subjective.

This work serves as the practical implementation for the research paper:

> **"Rice Variety Identification Based on Transfer Learning Architecture Using DENS-INCEP"**
> **Published in IEEE Access (DOI: 10.1109/ACCESS.2025.3562585)**

We utilize the power of **Transfer Learning** to leverage models pre-trained on vast image datasets, fine-tuning them to the specific domain of rice variety recognition, thereby maximizing efficiency and classification accuracy.

## ✨ Key Features

* **DENS-INCEP Architecture:** Implementation of the proposed hybrid architecture combining **DenseNet** and **Inception** blocks.
* **Transfer Learning Implementation:** Scripts for loading pre-trained weights and fine-tuning the model on a custom rice image dataset.
* **High Accuracy:** Focus on achieving superior classification metrics for practical field application.
* **Data Preprocessing Pipeline:** Robust scripts for image normalization, augmentation, and data loading.

## 💻 Technology Stack

* **Language:** Python
* **Frameworks:** TensorFlow / Keras (or PyTorch, *sesuaikan dengan yang Anda gunakan*)
* **Libraries:** NumPy, Pandas, Matplotlib, scikit-learn
* **Environment:** Jupyter Notebooks / Python Scripts

## 🚀 Getting Started

### Prerequisites

You will need Python 3.x installed and the following dependencies:

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn
