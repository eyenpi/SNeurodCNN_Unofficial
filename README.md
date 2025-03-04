# Numerical Analysis for Machine Learning - Alzheimer’s Disease Classification

## Project Overview
This project implements and analyzes the **SNeurodCNN** model, a deep learning architecture for **Alzheimer's Disease (AD) classification** using MRI scans. The model is based on the work by Odimayo et al. (2024) and focuses on **structural neurodegeneration** in the brain's cerebral cortex. The **SNeurodCNN** is designed to enhance classification accuracy by capturing focal structural atrophy features.

## Features
- **Deep Learning Model:** SNeurodCNN, a convolutional neural network tailored for AD classification.
- **Data Preprocessing:** Gamma correction is applied to MRI scans for better feature extraction.
- **Regularization Techniques:** L2 regularization, dropout, and early stopping to prevent overfitting.
- **Evaluation Metrics:** Accuracy, precision, recall, F1-score, sensitivity, and specificity.

## Implementation
- **Dataset:** Alzheimer’s Disease Neuroimaging Initiative (ADNI)
- **Framework:** PyTorch
- **Optimization:** Adam optimizer with learning rate = `0.0001`
- **Loss Function:** Sparse Categorical Cross-entropy
- **Batch Size:** 32
- **Number of Epochs:** 100 (with early stopping)

## Results
The model achieves:
- **Accuracy:** 98.26%
- **Precision:** 98.27%
- **Recall:** 98.26%
- **F1 Score:** 98.25%
- **Sensitivity:** 98.18%
- **Specificity:** 99.41%

The high performance suggests that **SNeurodCNN** is a reliable tool for **early diagnosis** of Alzheimer’s Disease.

## Try It Yourself
If you want to try the codes and investigate it by yourself, use the notebook below:

Make sure to first download all the necessary files from [here](https://drive.google.com/drive/folders/1G1CrE6r-DP3bq4CZEKlp1oZ9lTmQSbKQ?usp=sharing).

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15r3_ORQYjA-dBZGwWOAaJCawMXhuejSx?usp=sharing)


## Authors
- **Hosein Mirhoseini**  
- **Ali Nabipour Dargah**


