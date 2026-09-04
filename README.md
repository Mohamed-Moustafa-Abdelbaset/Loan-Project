# 🏦 Loan Approval Prediction Pipeline

An end-to-end Machine Learning pipeline to predict loan approvals based on customer financial and demographic data. 

## 📊 Project Overview
This project analyzes a dataset of 45,000 records to predict whether a loan will be approved or rejected. It includes comprehensive Exploratory Data Analysis (EDA), data preprocessing, and a direct performance comparison of 6 different machine learning algorithms before and after applying Principal Component Analysis (PCA).

## 🛠️ Models Used
The following 6 models were trained and evaluated:
1. Logistic Regression
2. Random Forest Classifier
3. XGBoost
4. Gradient Boosting
5. K-Nearest Neighbors (KNN)
6. Support Vector Machine (SVM)

## ✨ Key Features
* **Data Preprocessing:** Handled missing values, scaled features using `StandardScaler`, and applied One-Hot Encoding for categorical variables.
* **Dimensionality Reduction:** Used PCA to retain 95% of the data's variance, significantly reducing feature space and training time for distance-based algorithms.
* **Visualizations:** Included interactive charts for EDA and comprehensive Confusion Matrices for model evaluation.
* **Decision Logic:** Generated a visualized Decision Tree (depth=3) to explain the internal logic of the predictions.

## 🚀 How to Use
1. Open the `loan project.ipynb` file in this repository.
2. You can view the code and the outputs directly on GitHub.
3. To run it yourself, download the `.ipynb` file and the `loan_data.csv` dataset, and open them in Google Colab or Jupyter Notebook.
