# Binary Prediction with a Rainfall Dataset

[Competition Link](https://www.kaggle.com/competitions/playground-series-s5e3)

This project aims to predict the 'rainfall' target feature values (binary: 0 = no rain, 1 = rain) for each day of the year and maximize AUC-ROC by selecting meaningful features, experimenting with different models, and optimizing hyperparameters.

## Introduction
The goal of this project is to predict whether it will rain on a given day using historical weather data. The prediction is binary, indicating either rain (1) or no rain (0).

## Dataset Description
The dataset used in this project has been synthetically generated from a deep learning model trained on the Rainfall Prediction using Machine Learning dataset.

## Goals and Objectives
- Perform Exploratory Data Analysis (EDA) to analyze trends, visualize distributions, and handle missing values.
- Build and compare machine learning models for rainfall prediction.
- Optimize hyperparameters for improved accuracy.
- Generate and submit predictions to Kaggle.

## Libraries Used
The following libraries are used in this project:

- **Pandas** and **NumPy**: For data manipulation and numerical operations.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**:
  - `SimpleImputer`: Handling missing values.
  - `train_test_split`: Splitting the data into training and testing sets.
  - `MinMaxScaler` and `StandardScaler`: Feature scaling.
  - `KFold`: K-Fold cross-validation.
  - `roc_auc_score`: Calculating AUC score.
- **TensorFlow** and **Keras**:
  - `Sequential`, `Dense`, `Dropout`, `GRU`, `Input`: Building and training neural network models.
  - `EarlyStopping`: Stopping training early to prevent overfitting.
- **Optuna**:
  - `TFKerasPruningCallback`: Pruning unpromising trials for hyperparameter optimization.

## Data Handling
1. **Reading and Cleaning Data**:  
   - Reading CSV files.
   - Dropping unnecessary columns.
   - Handling missing values using imputation techniques.

2. **Exploratory Data Analysis (EDA)**:  
   - Analyzing trends in the dataset.
   - Visualizing distributions of features.
   - Identifying and handling missing values.

3. **Feature Engineering**:  
   - Creating new features based on meteorological insights.
   - Encoding categorical variables.

## Model Building and Evaluation
1. **Machine Learning Models**:  
   - Training various classification models for rainfall prediction.

2. **Hyperparameter Optimization**:  
   - Using **Optuna** for optimizing hyperparameters to improve model performance.

3. **K-Fold Cross-Validation**:  
   - Implementing 5-fold cross-validation for robust model evaluation.

4. **Metrics Used**:  
   - **AUC-ROC (Area Under the Curve - Receiver Operating Characteristic)** for performance evaluation.

## Final Model Training and Submission
1. **Training the Final Model**:  
   - Using the best hyperparameters obtained from Optuna.

2. **Generating Predictions**:  
   - Making predictions on the test set.
   - Preparing submission file for Kaggle competition.
