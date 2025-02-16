# YOUTUBE VIDEO POPULARITY PREDICTION SYSTEM

## Overview
This project aims to predict the popularity of YouTube videos using machine learning models. By leveraging early popularity trends, we analyze various video features to estimate future engagement. Our model helps content creators, advertisers, and network operators make informed decisions based on predicted video performance.

## Features
- Uses **XGBoost Regressor** for predictive modeling
- Feature engineering based on metadata such as views, likes, comments, duration, and upload time
- Optimization experiments on hyperparameters such as learning rate, max depth, number of estimators, etc.
- Comparative study of **Linear Regression** and **XGBoost** for prediction accuracy

## Dataset
The dataset used for this project can be accessed [here](https://drive.google.com/drive/folders/1jT3CGME4u2EFKSniXYCN9YlB5RTaSZ34?usp=sharing).

## Model Used
### **XGBoost Regressor**
- An ensemble learning method based on gradient boosting
- Handles large datasets efficiently
- Provides accurate predictions by optimizing hyperparameters

## Flow Diagram
The workflow of the project follows these steps:
1. Data Collection
2. Preprocessing & Feature Engineering
3. Model Training
4. Hyperparameter Tuning
5. Evaluation & Results

## Challenges & Solutions
- **Data Quality Issues:** Addressed by thorough preprocessing
- **Feature Engineering:** Identified and selected key video attributes
- **Handling Imbalanced Data:** Used oversampling techniques
- **Optimizing Model Performance:** Tuned hyperparameters like learning rate, max depth, estimators, etc.
- **Capturing Temporal Dynamics:** Incorporated time-series data analysis

## Hardware & Software Requirements
### **Hardware**
- **RAM:** 16GB or more
- **Storage:** 500GB+
- **CPU:** Multi-core processor (Intel i7 / AMD Ryzen)
- **GPU:** Recommended for deep learning tasks

### **Software**
- **Python 3**
- **Jupyter Notebook**
- **Required Libraries:** Pandas, Seaborn, NumPy, XGBoost

## Experimentation
### 1. Changing Layers & Weights
- Increasing layers reduced accuracy
- Reducing weights improved accuracy

### 2. Changing Learning Rate
- Increasing learning rate from **0.1 to 0.3** improved accuracy

### 3. Optimizing Parameters
- Increased max depth, learning rate, and estimators to enhance performance

## Results & Observations
- **Linear Regression** provides basic interpretability but lacks deep insights
- **XGBoost** outperforms traditional regression with better predictive power
- Best results achieved by fine-tuning hyperparameters

## References
- [IEEE Research Paper](https://ieeexplore.ieee.org/document/7450136/authors#authors)
- [Colab Notebook](https://colab.research.google.com/drive/1J2_vKWgv2PHvPVRak2RCOthdeNZ5A66M)
- [YouTube 8M Dataset](https://research.google.com/youtube8m/)


## Conclusion
Our experiments demonstrate the effectiveness of **XGBoost Regressor** in predicting YouTube video popularity. Through careful hyperparameter tuning and feature selection, we improved accuracy and provided valuable insights for content optimization.

