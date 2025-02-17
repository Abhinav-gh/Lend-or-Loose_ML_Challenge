# Loan Default Prediction

This project focuses on predicting loan defaults using various machine learning models. The dataset used for this project is available on Kaggle: [Loan Default Dataset](https://www.kaggle.com/datasets/nikhil1e9/loan-default).  The goal is to accurately classify loans as either "Default" or "Not Default" based on a variety of features.

## Project Overview

This repository contains the code and analysis for predicting loan defaults.  A comprehensive suite of machine learning models were developed and evaluated, including tree-based ensembles, classical models, and deep learning architectures.  Extensive Exploratory Data Analysis (EDA) and preprocessing were conducted to prepare the data for modeling.

## Methodology

### Data Preprocessing and EDA

A significant portion of the project was dedicated to understanding and preparing the data.  This included:

* **Exploratory Data Analysis (EDA):**  Visualizations and statistical analysis were performed to understand feature distributions, identify potential relationships between variables, and uncover any data anomalies.
* **Data Cleaning:** Missing values were handled, and categorical features were encoded appropriately.
* **Feature Engineering:**  New features were potentially created to improve model performance.  (Details of specific feature engineering techniques can be added here if applicable)
* **Handling Imbalanced Classes:**  Strategies were employed to address the class imbalance present in the dataset (e.g., oversampling, undersampling, cost-sensitive learning).  (Specify the methods used)

### Model Development and Evaluation

The following machine learning models were implemented and evaluated:

* **Tree-based Ensembles:**
    * XGBoost
    * Random Forest
    * CatBoost
* **Classical Models:**
    * Logistic Regression
    * Support Vector Machine (SVM) with Linear, RBF, and Polynomial kernels
* **Deep Learning Architectures:**
    * Artificial Neural Network (ANN)
    * Fully Connected Neural Network (FCNN)
    * Recurrent Neural Network (RNN)

Each model was trained and evaluated using appropriate metrics, including precision, recall, F1-score, and accuracy.  Confusion matrices were generated to visualize model performance. Hyperparameter tuning was performed to optimize model performance.

## Results

The CatBoost model achieved the highest accuracy on the Kaggle submission, reaching 0.88811. Further optimization of a Fully Connected Neural Network (FCNN) improved the performance to 0.88678.  While other models provided competitive results, the tree-based ensemble methods and the fine-tuned FCNN demonstrated the strongest predictive capabilities.

**(Include a table summarizing the performance of all models.  This could be a Markdown table or a link to a CSV file containing the results.)**

