# Predicting Cancer Stages

## Introduction
MicroRNA profiling technology has been found to give clues to the progression of multiple types of cancer, which granted researchers an opportunity to create non-invasive screenings for early stage diagnosis. The goal of this project is predict the phase of cancer based on microRNA profile by developing machine learning models.

### Dataset
- Source: Kaggle Competition (https://www.kaggle.com/c/ml2-usf-2021/overview)
- Shape: 8302 rows, 980 columns
- Target: Cancer stages (0, 1, 2, 3, 4)
- Features:
  - problem id (indicating cancer in different studies)
  - MicroRNA profiles

### Methods Used
* Machine Learning (Imbalanced Multiclass Classification)
  - Logistic Regression
  - KNN
  - Support Vector Machine
  - XGBoost
  - LightGBM
  - Ensemble
* Exploratory Data Analysis
* Mean Target Encoding
* Hyperparameter Tuning

### Technologies
* Python
  - Pandas
  - Numpy
  - Matplotlib
  - Sklearn
    - Pipeline
    - StandardScaler
    - cross_val_score
    - RandomizedSearchCV
