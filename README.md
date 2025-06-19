# Credit Risk Classification with Machine Learning

This project aims to predict credit risk using a dataset from an Excel file (`CreditRisk_Data.xls`). The analysis walks through the steps of preprocessing, feature selection, model training, and performance evaluation using several machine learning algorithms.

## 📁 Project Structure

- **Final_Assignment.ipynb**: Main notebook containing all the analysis and modeling steps.
- **CreditRisk_Data.xls**: Excel file containing credit-related data (expected to be in the same folder as the notebook).

## 🧪 Main Features

- **Exploratory Data Analysis (EDA)**: Understands the structure and distribution of the dataset.
- **Feature Selection**:
  - Recursive Feature Elimination (RFE)
  - SelectKBest using ANOVA F-statistic
- **Data Preprocessing**:
  - Standardization with `StandardScaler`
  - Class imbalance handling using `SMOTE`
- **Model Training**:
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - AdaBoost
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
- **Model Evaluation**:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC AUC Score
  - Confusion Matrix & Classification Report

## ⚙️ Dependencies

Make sure the following Python libraries are installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn openpyxl

