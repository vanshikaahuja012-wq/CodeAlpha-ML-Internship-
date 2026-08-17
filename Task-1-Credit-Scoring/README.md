# Credit Scoring Model

## 📌 Project Overview

This project was developed as part of the CodeAlpha Machine Learning Internship.

The goal of this project is to predict the quality of a loan using customer financial and demographic information. Machine learning classification algorithms are used to classify loans as **Good (G)** or **Bad (B)**.

## 🎯 Objective

The main objective is to build a machine learning model that can identify whether a loan is likely to be good or bad based on available customer information.

## 📂 Dataset

The dataset provided for this project contains financial and customer information.

### Features Used

- ACC_NO
- INVESTMENT_TOTAL
- ACCCURRENTBALANCE
- INF_MARITAL_STATUS
- INF_GENDER
- INSTALL_SIZE
- DUE_PAYMENT
- CLIENT_TYPE
- REPAY_MODE

### Target Variable

`QUALITY_OF_LOAN`

- `G` = Good Loan
- `B` = Bad Loan

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔄 Project Workflow

1. Load the dataset
2. Explore the data
3. Handle missing values
4. Clean invalid values
5. Encode categorical variables
6. Split the dataset into training and testing sets
7. Train machine learning models
8. Evaluate model performance
9. Select the best-performing model
10. Save the trained model

## 🤖 Machine Learning Models

Three classification algorithms were trained and compared:

- Logistic Regression
- Decision Tree
- Random Forest

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 88.89% | 88.89% | 100.00% | 94.12% | 58.05% |
| Decision Tree | 91.98% | 95.75% | 95.20% | 95.48% | 81.06% |
| Random Forest | **93.36%** | **94.59%** | **98.14%** | **96.33%** | **90.71%** |

## 🏆 Best Model

The **Random Forest Classifier** performed best overall.

It achieved:

- Accuracy: **93.36%**
- Precision: **94.59%**
- Recall: **98.14%**
- F1-Score: **96.33%**
- ROC-AUC: **90.71%**

Therefore, Random Forest was selected as the final model.

## 📈 Evaluation

The final Random Forest model was evaluated using:

- Confusion Matrix
- ROC Curve
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## 💾 Model

The trained Random Forest model was saved as:

`credit_scoring_model.pkl`

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK

2. Install dependencies
pip install -r requirements.txt
3. Open the notebook
jupyter notebook

Open:

credit_scoring_model.ipynb

and run the cells.

📌 Conclusion

The project demonstrates how machine learning can be used for credit scoring. Among the tested algorithms, Random Forest provided the best overall performance with a ROC-AUC score of 90.71% and an accuracy of 93.36%.

This project was completed as part of the CodeAlpha Machine Learning Internship