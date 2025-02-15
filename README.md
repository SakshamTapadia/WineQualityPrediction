# Wine Quality Prediction using Random Forest

## Overview
This project implements a **Random Forest** model to predict the **quality of wine** based on its chemical composition and physicochemical properties.

## Dataset
The dataset consists of numerical features that influence wine quality, including:
- **Fixed Acidity & Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free & Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol Content**
- **Quality Score (Target Variable)**

## Model & Approach
- **Exploratory Data Analysis (EDA)**:
  - Used **Seaborn & Matplotlib** to visualize feature distributions and correlations.
  - Identified missing values and handled them appropriately.
- **Feature Engineering**:
  - Scaled numerical features for better model performance.
- **Algorithm**:  
  - Used **Random Forest Classifier** for multi-class classification.
- **Evaluation**:  
  - Accuracy, Precision, Recall, F1-score, Confusion Matrix, and Feature Importance Analysis.

## Installation & Requirements
To run this project, install the necessary dependencies:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib
****
