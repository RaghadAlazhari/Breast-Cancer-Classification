# Breast Cancer Classification 

## Overview
This repository contains a Breast Cancer Classification dataset, which is used for training machine learning models to predict whether a tumor is malignant or benign. The dataset consists of various statistical features extracted from digitized images of breast masses, and it is commonly used in machine learning and data science tasks.

## Dataset Description
The dataset includes information about breast cancer patients, with multiple features extracted from tumor cell images. The goal is to predict whether a tumor is **benign** (B) or **malignant** (M) based on these features.

### Data Fields
The dataset contains the following columns:

- `id`: Unique identifier for each patient.
- `diagnosis`: Tumor label (either **M** for malignant or **B** for benign).
- `radius_mean`: Mean radius of the tumor.
- `texture_mean`: Mean texture of the tumor.
- `perimeter_mean`: Mean perimeter of the tumor.
- `area_mean`: Mean area of the tumor.
- `smoothness_mean`: Mean smoothness of the tumor.
- `compactness_mean`: Mean compactness of the tumor.
- `concavity_mean`: Mean concavity of the tumor.
- `concave points_mean`: Mean concave points of the tumor.
- `symmetry_mean`: Mean symmetry of the tumor.
- `fractal_dimension_mean`: Mean fractal dimension of the tumor.
- `radius_se`: Standard error of radius.
- `texture_se`: Standard error of texture.
- `perimeter_se`: Standard error of perimeter.
- `area_se`: Standard error of area.
- `smoothness_se`: Standard error of smoothness.
- `compactness_se`: Standard error of compactness.
- `concavity_se`: Standard error of concavity.
- `concave points_se`: Standard error of concave points.
- `symmetry_se`: Standard error of symmetry.
- `fractal_dimension_se`: Standard error of fractal dimension.
- `radius_worst`: Worst radius value.
- `texture_worst`: Worst texture value.
- `perimeter_worst`: Worst perimeter value.
- `area_worst`: Worst area value.
- `smoothness_worst`: Worst smoothness value.
- `compactness_worst`: Worst compactness value.
- `concavity_worst`: Worst concavity value.
- `concave points_worst`: Worst concave points value.
- `symmetry_worst`: Worst symmetry value.
- `fractal_dimension_worst`: Worst fractal dimension value.


## Objectives
The primary goals of this project are:
- Data preprocessing and cleaning.
- Exploratory Data Analysis (EDA).
- Building machine learning models using algorithms like Logistic Regression, Decision Trees, and Random Forest.
- Evaluating the models using accuracy, precision, recall, and F1-score.
- Hyperparameter tuning for model optimization.

## Installation & Requirements
To use this dataset, ensure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter (for running Jupyter notebooks)

## Model Evaluation
The models will be evaluated using:
- **Accuracy**: The proportion of correct predictions.
- **Precision**: The proportion of true positives out of all positive predictions.
- **Recall**: The proportion of true positives out of all actual positives.
- **F1-Score**: The harmonic mean of precision and recall.
