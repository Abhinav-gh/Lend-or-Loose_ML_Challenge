# Loan Default Prediction

This project focuses on predicting loan defaults using various machine learning models. The dataset used for this project is available on Kaggle: [Loan Default Dataset](https://www.kaggle.com/datasets/nikhil1e9/loan-default).  The goal is to accurately classify loans as either "Default" or "Not Default" based on a variety of features.

## Project Overview

This repository contains the code and analysis for predicting loan defaults.  A comprehensive suite of machine learning models were developed and evaluated, including tree-based ensembles, classical models, and deep learning architectures.  Extensive Exploratory Data Analysis (EDA) and preprocessing were conducted to prepare the data for modeling.

## Results

The CatBoost model achieved the highest accuracy on the Kaggle submission, reaching 0.88811. Further optimization of a Fully Connected Neural Network (FCNN) improved the performance to 0.88678.  While other models provided competitive results, the tree-based ensemble methods and the fine-tuned FCNN demonstrated the strongest predictive capabilities.

Please refer to the detailed report available in this repository for comprehensive analysis of all the models implemented.

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



## Setup and Running the Code

This project requires Python 3.x and the packages listed in `requirements.txt`. It is highly recommended to create a dedicated conda environment to manage dependencies.

### 1. Download the Data

You'll need to download the following CSV files from the [Kaggle Loan Default dataset](https://www.kaggle.com/datasets/nikhil1e9/loan-default):

*   `train.csv`
*   `test.csv`
*   `sample_submission.csv`

Place these files in a directory named `data/` within the project folder. Create the `data/` directory if it doesn't already exist.

### 2. Create a Conda Environment (Recommended)

It's best practice to use a virtual environment to isolate project dependencies. Conda is recommended for this project.

```bash
conda create -n loan_default_env python=3.9  # Or your preferred Python version
conda activate loan_default_env
```

### 3. Install Dependencies

Navigate to the project directory in your terminal and install the required packages:


```bash
pip install -r requirements.txt
```

### 4. Run the Notebook
The primary analysis and model training are performed in the single Jupyter Notebook given. Run it to generate all the plots and results.



