# Image Classification on MNIST Using Support Vector Machines with PCA & LDA

This repository contains a **Jupyter Notebook** demonstrating a **machine learning** workflow for **image classification**.The project includes:

- **Data loading** and basic exploration (MNIST).
- **Dimensionality reduction** techniques:
  - **Principal Component Analysis (PCA)**
  - **Linear Discriminant Analysis (LDA)**
- **Model training and comparison**:
  - SVM trained on raw data.
  - SVM trained on PCA-reduced data.
  - SVM trained on LDA-reduced data.
- **Hyperparameter tuning** for all SVM models.


## Project Overview

1. **Data Loading**:
   - Fetch and format the MNIST dataset into training and test sets.
2. **Data Exploration**:
   - Preview sample digits.
   - Check shapes and basic statistics.
3. **Baseline SVM Training**:
   - Train an SVM on the original MNIST dataset.
   - Evaluate baseline accuracy.
4. **Dimensionality Reduction**:
   - Apply **PCA**.
   - Apply **LDA**.
   - Visualize explained variance (for PCA) or scatter plot (for LDA).
5. **SVM Training on Reduced Data**:
   - Train SVM on PCA-transformed data.
   - Train SVM on LDA-transformed data.
6. **Hyperparameter Tuning**:
   - Use `GridSearchCV` (or similar) to optimize SVM parameters (`C`, `gamma`, `kernel`, etc.).
7. **Results & Comparison**:
   - Compare performance metrics (accuracy, time complexity, etc.) for:
     - Baseline SVM
     - PCA + SVM
     - LDA + SVM

