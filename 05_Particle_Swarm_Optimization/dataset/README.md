# Dataset Information

## Breast Cancer Wisconsin Diagnostic Dataset

This project uses the Breast Cancer Wisconsin Diagnostic Dataset available through scikit-learn.

---

## Dataset Summary

Number of Samples

569

Number of Features

30 numerical features

Number of Classes

2

Target Classes

- Malignant
- Benign

---

## Feature Categories

The dataset contains measurements extracted from digitized images of fine needle aspirates (FNA) of breast masses.

Examples include

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Mean Symmetry
- Radius Error
- Texture Error
- Worst Radius
- Worst Texture
- Worst Perimeter
- Worst Area
- Worst Smoothness

Each feature describes geometric or textural characteristics of cell nuclei.

---

## Target Variable

0 — Malignant

1 — Benign

---

## Data Source

The dataset is distributed with scikit-learn.

It can be loaded using

```python
from sklearn.datasets import load_breast_cancer

data = load_breast_cancer()
```

Official documentation

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

---

## Data Preprocessing

The following preprocessing steps were performed.

- Feature extraction
- Target separation
- Train/Test split
- Standardization using StandardScaler

No missing values were present.

---

## Research Purpose

The dataset was selected because it is a well-established benchmark for binary medical classification and feature selection research.

It provides an excellent platform for evaluating optimization algorithms such as Particle Swarm Optimization.

---

## Citation

Wolberg, W. H., Street, W. N., Mangasarian, O. L.

Breast Cancer Wisconsin (Diagnostic) Database.

University of Wisconsin Hospitals.