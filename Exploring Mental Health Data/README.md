# Mental Health Analysis

## Overview

This project focuses on analyzing mental health data using machine learning techniques. The dataset includes various factors such as academic pressure, work pressure, CGPA, study satisfaction, and financial stress, which contribute to mental health conditions. The objective is to build a predictive model that can classify mental health conditions based on the given data.

## Tools and Technologies Used

- **Python**: Programming language used for data analysis and modeling.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: Numerical operations and array handling.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**:
  - Data splitting (`train_test_split`)
  - Classification metrics (`accuracy_score`, `classification_report`, `confusion_matrix`)
- **XGBoost**: Extreme Gradient Boosting classifier used for prediction.
- **Optuna**: Hyperparameter optimization.
- **Warnings**: Suppressing unnecessary warnings in Python.

## Project Structure

- `train.csv`: Training dataset.
- `test.csv`: Testing dataset.
- `sample_submission.csv`: Sample submission file.
- `Mental Health.ipynb`: Jupyter Notebook containing data preprocessing, visualization, modeling, and evaluation steps.

## Key Features
- Data preprocessing: Handling missing values and categorical encoding.
- Data visualization: Understanding feature distributions and correlations.
- Model training: Using XGBoost classifier for prediction.
- Hyperparameter tuning: Using Optuna for improved performance.
- Evaluation: Accuracy, confusion matrix, and classification report.

  
