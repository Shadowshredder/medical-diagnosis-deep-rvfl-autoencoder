# Cloud-Based Hybrid ML Framework for Medical Dataset Analysis

## Overview

This project presents a cloud-based hybrid machine learning framework for medical diagnosis using Deep RVFL (Random Vector Functional Link) and AutoEncoder models. The framework aims to improve disease prediction accuracy while providing explainable and scalable solutions through cloud computing technologies.

## Problem Statement

Traditional deep learning models require high computational resources, longer training times, and often operate as black-box systems. This project addresses these challenges by integrating Deep RVFL and AutoEncoder models with cloud-based infrastructure to achieve efficient, scalable, and explainable medical diagnosis.

## Datasets

### Bladder Cancer Dataset

* 1337 patient records
* 39 medical features
* Multi-class classification problem
* Objective: Predict different cancer types

### Heart Disease Dataset

* 303 patient records
* 13 clinical features
* Binary classification problem
* Objective: Predict presence of heart disease

## Methodology

1. Data Collection and Preprocessing
2. Missing Value Handling
3. Feature Scaling and Normalization
4. Dataset Balancing using SMOTE
5. Deep RVFL Feature Extraction
6. AutoEncoder-based Classification
7. Model Training and Evaluation
8. Explainability using SHAP and LIME
9. Cloud-based Execution using AWS Services

## Technologies Used

* Python
* Google Colab
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-Learn
* TensorFlow / Keras
* SHAP
* LIME
* Matplotlib
* AWS SageMaker
* AWS S3
* SMOTE

## Project Structure

```text
medical-diagnosis-deep-rvfl-autoencoder
│
├── datasets/
├── notebooks/
├── results/
│   ├── bladder_cancer/
│   └── heart_disease/
├── screenshots/
├── report/
├── README.md
└── requirements.txt
```

## Cloud Deployment

* Amazon SageMaker was used for model training and experimentation.
* Amazon S3 was used for dataset storage and management.
* Cloud infrastructure improved scalability and resource utilization.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score

## Explainable AI

To improve transparency and interpretability:

* SHAP (SHapley Additive exPlanations) was used for feature importance analysis.
* LIME (Local Interpretable Model-Agnostic Explanations) was used for local prediction explanations.

## Results

The framework was evaluated on both Heart Disease and Bladder Cancer datasets. Performance was analyzed using classification metrics, ROC curves, SHAP visualizations, and LIME explanations. The proposed approach demonstrated effective medical diagnosis capabilities while maintaining interpretability and scalability.

## Authors

* Gayathri U
* Kaviya Sri N
* Lakshmi Prabha T

