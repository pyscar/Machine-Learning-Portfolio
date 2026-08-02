# Dataset

## Overview

This project uses two image datasets designed for camouflage object detection under varying illumination conditions.

The datasets contain 15 animal categories represented under normal daylight conditions and natural camouflage environments. Images are further processed to simulate extreme low-light UAV surveillance scenarios.

---

## Dataset Structure

```
dataset/

├── Clear_Animals/
│   ├── Bear/
│   ├── Bird/
│   ├── ...
│
└── Camouflaged_Animals/
    ├── Bear/
    ├── Bird/
    ├── ...
```

---

## Classes

The dataset contains the following classes:

- Bear
- Bird
- Bulky Insect
- Canine
- Feline
- Flat Fish
- Flat Insect
- Frog
- Horse Type
- Octopus
- Owl
- Reptile
- Small Fish
- Small Mammal
- Stick Insect

---

## Image Preprocessing

Each image undergoes the following preprocessing pipeline:

1. Resize to **224 × 224**
2. RGB normalization using ImageNet statistics
3. Low-light UAV simulation through luminance standardization
4. Adaptive enhancement using denoising and CLAHE
5. Conversion into PyTorch tensors

---

## Data Augmentation

The experimental pipeline applies:

- Image resizing
- Normalization
- Environmental luminance simulation
- Adaptive enhancement

---

## Research Purpose

The dataset is used to evaluate:

- Camouflage object classification
- Low-light robustness
- Feature drift analysis
- Attention localization
- Saliency Energy Ratio (SER)
- Transfer learning performance using ResNet-50

---

## Note

Due to dataset size and licensing considerations, the complete image dataset is not included in this repository.

The notebook contains all preprocessing and experimental procedures required to reproduce the study using the original datasets.