# EEG Motor Imagery Classification

EEG motor imagery classification project using Common Spatial Pattern (CSP) feature extraction with Linear Discriminant Analysis (LDA) and Support Vector Machine (SVM) classifiers, implemented using MNE and MOABB.

---

## Overview

This project demonstrates a basic brain–computer interface (BCI) workflow for EEG motor imagery classification.

The project uses the publicly available BNCI2014_001 EEG dataset and evaluates two classification pipelines:

- CSP + LDA
- CSP + SVM

The notebook includes:
- EEG dataset loading
- signal preprocessing
- feature extraction
- classification
- evaluation
- result visualisation
- model export

---

## Dataset

Dataset used:
- BNCI2014_001

Task:
- Left-hand vs right-hand motor imagery classification

Frameworks:
- MOABB
- MNE-Python

---

## Repository Structure

```text
EEG-Motor-Imagery-Classification/
│
├── README.md
├── EEG_Motor_Imagery_Classification.ipynb
├── requirements.txt
├── .gitignore
│
└── results/
    ├── eeg_motor_imagery_results.csv
    ├── eeg_pipeline_summary.csv
    ├── eeg_pipeline_comparison.png
    ├── csp_lda_pipeline.pkl
    └── csp_svm_pipeline.pkl
```

---

## Methods

### Feature Extraction
- Common Spatial Pattern (CSP)

### Classification Models
- Linear Discriminant Analysis (LDA)
- Support Vector Machine (SVM)

### Evaluation
- Within-session evaluation using MOABB

---

## Installation

Install required packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open the notebook:

```bash
jupyter notebook EEG_Motor_Imagery_Classification.ipynb
```

Run all notebook cells sequentially.

---

## Results

The project compares EEG motor imagery classification performance between:

- CSP + LDA
- CSP + SVM

Performance summaries, exported pipelines, and visualisations are automatically saved in the `results/` folder.

---

## Technologies Used

- Python
- MNE
- MOABB
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## Author

Hossein Moeinzadeh
