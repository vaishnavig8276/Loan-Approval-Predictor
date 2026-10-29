# Loan-Approval-Predictor
An interactive Machine Learning web app built with Streamlit to predict bank loan approvals using classification models
# 🏦 Bank Loan Approval Predictor

## 📌 Project Overview
This project predicts whether a bank loan will be approved or rejected based on an applicant's financial profile. I have performed data analysis and built Machine Learning models to automate the loan approval decision process.

## 🛠️ What I Did (My Work)
1. **Data Preprocessing**: Cleaned the `loan_approval_data.csv` dataset by handling missing values (using median for numbers and mode for text).
2. **Feature Engineering**: Transformed existing data (like squaring the DTI ratio and Credit Score) and converted categorical text data (like 'Rural', 'Urban') into numerical format using One-Hot Encoding so the ML models can understand it.
3. **Feature Scaling**: Applied `StandardScaler` to bring all numerical features to the same scale, which is highly required for distance-based algorithms.
4. **Model Training**: Trained two different classification models to compare their performance:
   * **K-Nearest Neighbors (KNN)**
   * **Naive Bayes (Gaussian)**

## 📊 Output & Results
* The models successfully learned to classify and predict the `Loan_Approved` status.
* I evaluated the models using **Accuracy, Precision, Recall, and Confusion Matrix**.
* **Result**: Both models were successfully able to predict the loan status on unseen test data, with Naive Bayes showing strong precision in identifying true loan approvals.

## 📂 Repository Files
* `credit_wise.ipynb`: The main Jupyter Notebook containing the complete step-by-step code for EDA, feature engineering, and model training.
* `loan_approval_data.csv`: The raw dataset used for this project.