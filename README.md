# Rice Variety Identification using DENS-INCEP Transfer Learning

[![DOI](https://zenodo.org/badge/DOI/10.1109/ACCESS.2025.3562585.svg)](https://doi.org/10.1109/ACCESS.2025.3562585)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🌾 Overview

This repository contains the full implementation of the proposed **DENS-INCEP** architecture for image-based **rice variety identification**. The project leverages a specialized **Transfer Learning** approach, adapting the powerful feature extraction capabilities of established deep learning models to the domain of agricultural classification.

The primary goal is to develop a highly accurate and efficient model capable of distinguishing between several common rice varieties based solely on visual characteristics derived from image samples. This work aims to provide a robust, automated solution that bypasses the limitations of traditional, manual classification methods.

## 📖 Background & Motivation

Accurate rice variety classification is vital for quality assurance, germplasm preservation, and effective management across the agricultural supply chain. Conventional identification methods, often relying on morphological characteristics or genetic testing, are resource-intensive, time-consuming, and require specialized expertise.

This repository is the dedicated code base for the research paper:

> **"Rice Variety Identification Based on Transfer Learning Architecture Using DENS-INCEP"**
> **Published in IEEE Access (DOI: 10.1109/ACCESS.2025.3562585)**

The DENS-INCEP architecture specifically addresses the challenge of limited domain-specific image data by employing **Transfer Learning**. It utilizes pre-trained weights from complex models (like those based on DenseNet and Inception structures) and strategically fine-tunes them. This hybrid method is designed to maximize the learning efficiency and generalization ability, resulting in superior classification accuracy compared to models trained from scratch, offering a practical deep learning solution for automated agricultural monitoring.

## 💾 Dataset

The model training and evaluation are performed using the following publicly available dataset:

**Rice Image Dataset**
* **Source:** Kaggle
* **Link:** [https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)
* **Description:** This dataset contains categorized images across five rice varieties, providing the necessary data for the image classification task in agricultural research.

## 💡 Model Architecture

The DENS-INCEP architecture, central to this research, is illustrated below, showcasing the integration of DenseNet and Inception concepts for feature extraction. The model is specifically engineered to handle the subtle morphological differences present in rice grain images.

![DENS-INCEP Architecture Diagram](assets/DENS_INCEP_Architecture.png)

The name **DENS-INCEP** is a portmanteau that directly indicates the architecture's hybrid nature, combining two highly effective deep learning components: DenseNet-201 and the Inception Module.

## ✨ Key Features

* **DENS-INCEP Architecture:** Implementation of the proposed hybrid architecture combining **DenseNet** and **Inception** blocks for optimized feature extraction.
* **Transfer Learning Implementation:** Scripts for loading pre-trained weights and strategically fine-tuning the model on the specified rice image dataset.
* **High Accuracy Metrics:** Focus on achieving superior classification performance suitable for real-world agricultural application.
* **Data Preprocessing Pipeline:** Robust scripts for image normalization, augmentation, and efficient data loading.

## 💻 Technology Stack

* **Language:** Python
* **Frameworks:** TensorFlow / Keras 
* **Libraries:** NumPy, Pandas, Matplotlib, scikit-learn
* **Environment:** Jupyter Notebooks / Python Scripts
