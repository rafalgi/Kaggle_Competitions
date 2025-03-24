# Backpack Price Prediction

This project aims to predict the prices of backpacks based on various factors such as brand, material, waterproof capability, number of compartments, and presence of a laptop compartment.

## Aims & Objectives

The main objective of this project is to determine the various factors that affect the price of backpacks. The dataset used includes features such as:

- Brand
- Material
- Waterproof capability
- Number of compartments
- Presence of a laptop compartment

## Key Takeaways

- The dataset includes both categorical and numerical features, requiring different preprocessing steps.
- Handling missing values in categorical variables is a priority.
- Weight capacity and price have relatively wide distributions, suggesting possible feature scaling or transformation.
- Feature engineering on categorical variables (like brand and material) may improve model performance.

## Dataset

The dataset consists of the following columns:

- `id`: Unique identifier for each backpack
- `Brand`: Brand name of the backpack
- `Material`: Material type of the backpack
- `Size`: Size of the backpack (e.g., small, medium, large)
- `Compartments`: Number of compartments in the backpack
- `Laptop Compartment`: Indicates if the backpack has a laptop compartment (Yes/No)
- `Waterproof`: Indicates if the backpack is waterproof (Yes/No)
- `Style`: Style of the backpack (e.g., tote, messenger, backpack)
- `Color`: Color of the backpack
- `Weight Capacity (kg)`: Weight capacity of the backpack in kilograms
- `Price`: Price of the backpack

## Notebook Structure

1. **Data Loading**: 
    - Load the training, extra training, and test datasets.

2. **Data Exploration**:
    - Display the columns of the training and extra training datasets.
    - Combine the training and extra training datasets.

3. **Data Preprocessing**:
    - Handle missing values and encode categorical variables.

4. **Model Training**:
    - Train a machine learning model to predict the prices of backpacks.

5. **Evaluation**:
    - Evaluate the performance of the model using appropriate metrics.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Catboost

## Usage

To run the notebook, ensure you have the required libraries installed and execute the cells in the given order. The notebook provides a step-by-step guide to preprocess the data, train the model, and evaluate its performance.

## Results

The notebook includes summary statistics and visualizations to understand the distribution of features and the target variable. The final model's performance is evaluated using metrics such as root mean squared error.

