# Methodology

## Overview

This project follows a complete machine learning workflow for multi-domain network intrusion detection using deep learning techniques.

The methodology consists of the following stages:

1. Data Collection
2. Dataset Integration
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Model Development
7. Model Evaluation
8. Ensemble Learning

---

# 1. Data Collection

Four publicly available cybersecurity datasets were collected representing different network environments:

- NSL-KDD
- Healthcare IoT
- IoT Network Traffic
- CAN Bus Intrusion Dataset

Each dataset contains labeled normal and attack traffic.

---

# 2. Dataset Integration

The datasets were standardized and merged into a unified dataset.

The integration process included:

- Standardizing feature names
- Mapping attack labels
- Removing inconsistencies
- Handling missing values
- Combining datasets

---

# 3. Data Preprocessing

The preprocessing pipeline included:

- Duplicate removal
- Missing value handling
- Label encoding
- Feature scaling
- Dataset balancing
- Train/Test split

---

# 4. Exploratory Data Analysis

EDA was performed to understand:

- Class distribution
- Domain contribution
- Feature correlations
- Feature importance
- Statistical relationships

Several visualizations were generated to validate data quality.

---

# 5. Model Development

Three deep learning models were implemented:

- Artificial Neural Network (ANN)
- One-Dimensional CNN
- Hybrid CNN–LSTM

Each model was trained using TensorFlow/Keras.

---

# 6. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

# 7. Ensemble Learning

An ensemble approach was explored to improve robustness by combining predictions from multiple deep learning models.

---

# Workflow Summary

Data Collection

↓

Dataset Integration

↓

Data Cleaning

↓

EDA

↓

Feature Engineering

↓

ANN

↓

CNN

↓

CNN–LSTM

↓

Evaluation

↓

Ensemble Learning