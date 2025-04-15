# Heart Disease Risk Prediction
_Associated with Harvard's COMPSCI 109A_

# Overview
This project explores predictive modeling of heart disease risk using patient clinical data. The notebook walks through data cleaning, balancing techniques (SMOTE), feature analysis, model tuning, and final evaluation across several machine learning models.

___
## Notebook Structure

1. **Summary of the Data**
   - Overview of dataset characteristics
   - Analysis of missing values

2. **Data Manipulation**
   - Imputation of missing values
   - Feature normalization
   - SMOTE balancing for class imbalance

3. **Visualization**
   - Feature importance
   - Key feature plots
   - Correlation analysis

4. **Model Tuning**
   - Baseline model performance for:
     - Random Forest
     - Gradient Boosting
     - XGBoost
   - Dimensionality reduction via PCA
   - Multicollinearity check via VIF

5. **Final Model Pipeline**
   - Pipeline construction for each top-performing model
   - Final training and evaluation

6. **Final Model Exploration**
   - Accuracy and classification performance
   - Summary of findings and evaluation

___


## Key Techniques
- Handling missingness and imbalance
- SMOTE oversampling
- PCA and VIF feature selection
- Pipeline integration and grid search
- Evaluation using Accuracy, F1 score and more

___

## 📂 Dataset
- **Source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Description**: Contains patient attributes including age, blood pressure, cholesterol, and chest pain type.

