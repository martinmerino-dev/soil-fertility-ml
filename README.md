# Soil Fertility Prediction (Machine Learning Project)

## Overview

This project builds a machine learning model to predict soil fertility based on chemical soil properties. It uses a Random Forest classifier to identify whether soil is fertile or infertile.

---

## Problem

Understanding soil fertility is essential for agriculture and crop optimization. The goal of this project is to predict soil quality using measurable soil attributes such as nutrient levels and pH.

---

## Approach

The project follows a complete machine learning pipeline:

* Data preprocessing using Pandas
* Feature-target separation
* Train-test split (80/20)
* Model training using **Random Forest Classifier**
* Hyperparameter tuning with **GridSearchCV**
* Model evaluation using accuracy, confusion matrix, and classification report
* Cross-validation to ensure model consistency
* Feature importance analysis

---

## Results

* Model accuracy: ~91%
* Stable performance across cross-validation folds
* Key features influencing soil fertility:

  * Nitrogen (N)
  * Phosphorus (P)
  * pH level
  * Copper (Cu)

---

## Technologies

* Python
* Pandas
* Scikit-learn
* Random Forest
* GridSearchCV
* Matplotlib

---

## Key Concepts

* Machine Learning
* Classification Models
* Ensemble Learning (Random Forest)
* Hyperparameter Tuning
* Cross-Validation
* Feature Importance Analysis

