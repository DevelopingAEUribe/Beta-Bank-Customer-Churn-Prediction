Beta Bank Churn Prediction
This project predicts customer churn for Beta Bank using machine learning models. The goal is to identify customers likely to leave the bank and help reduce customer attrition through proactive engagement strategies.

📊 Project Overview
Problem: Beta Bank is losing customers. The bank wants to identify customers likely to churn.

Goal: Build a machine learning model with a minimum F1 score of 0.59 to predict churn.

Data: Includes customer demographics, credit score, account balance, and more.

🧠 ML Pipeline
Data Preprocessing:

Handled missing values

Encoded categorical variables

Standardized numerical features

Data Splitting:

Train/test split (75/25 stratified)

Avoided data leakage

Class Imbalance Handling:

Applied upsampling to the minority class

Model Training:

Tested models: Logistic Regression, Decision Tree, Random Forest

Tuned hyperparameters

Evaluation Metrics:

F1 Score (target ≥ 0.59)

ROC AUC Score

Confusion Matrix

📈 Results
Final model: Random Forest Classifier

Achieved:

F1 Score: e.g., 0.63

ROC AUC Score: e.g., 0.85

🛠️ Tools & Technologies
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn (for EDA and visualizations)

🚀 How to Run
Clone this repo

Open the notebook or script in your Python environment

Run each cell/section step by step

bash
Copy
Edit
git clone https://github.com/DevelopingAEUribe/beta-bank-churn.git
📬 Contact
Created by Adam Edwards-Uribe
