INSURANCE CLAIM PREDICTION

📌 Project Overview

This project builds a machine learning model to predict whether a building will file an insurance claim during an insured period.
The goal is to classify buildings as:

1 → At least one claim

0 → No claim

The model uses building characteristics to estimate claim probability.
This project demonstrates data preprocessing, exploratory analysis, model building, and evaluation.

🎯 Objectives

Clean and preprocess insurance building data

Perform Exploratory Data Analysis (EDA)

Train multiple machine learning models

Evaluate and compare model performance

Produce a deployable and reproducible notebook

📂 Project Structure


insurance-claim-prediction/
│
├── data/
│   ├── Train_data.csv
│   └── Variable Description.csv
│
├── notebooks/
│   └── insurance_claim_prediction.ipynb
│
├── requirements.txt
├── README.md

🛠 Tools & Libraries

Python

Pandas & NumPy — Data manipulation

Matplotlib & Seaborn — Visualization

Scikit-learn — Machine Learning models

🧹 Data Cleaning & Preprocessing

Missing Values:
Missing values were checked and handled to ensure model stability and prevent training errors.

Categorical Encoding:
Categorical variables were converted into numerical format using encoding to make them usable by machine learning models.

Feature Scaling:
StandardScaler was applied to normalize numerical features, improving Logistic Regression convergence and model performance.

📊 Exploratory Data Analysis (EDA)

EDA was performed to:

Understand feature distributions

Identify relationships between variables and claim outcomes

Detect class imbalance

Observe potential predictors of insurance claims

Visualizations include histograms, correlation heatmaps, and target distribution plots.

🤖 Models Implemented

Logistic Regression

Random Forest Classifier

Each model was trained on the same processed dataset for fair comparison.

📈 Model Evaluation

Models were evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

ROC Curve & AUC Score

The best-performing model was selected based on overall predictive performance.
