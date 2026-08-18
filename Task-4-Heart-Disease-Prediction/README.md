# Task 4: Heart Disease Prediction from Medical Data

## Project Overview

This project focuses on predicting the presence of heart disease using machine learning algorithms based on medical data. The model is trained using patient health information and predicts whether a person is likely to have heart disease.

## Dataset

The project uses the **Heart Disease Dataset** containing medical attributes such as:

* Age
* Sex
* Chest pain type
* Resting blood pressure
* Cholesterol level
* Fasting blood sugar
* Resting ECG results
* Maximum heart rate achieved
* Exercise-induced angina
* ST depression
* Slope
* Number of major vessels
* Thalassemia

The target variable:

* `1` → Heart disease detected
* `0` → No heart disease

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* GitHub

## Machine Learning Models Used

The following classification models were trained and compared:

1. Logistic Regression
2. Random Forest Classifier
3. Support Vector Machine (SVM)

The best-performing model was selected based on accuracy.

## Project Workflow

1. Import required libraries
2. Load and explore the dataset
3. Perform data preprocessing
4. Split data into training and testing sets
5. Scale features where required
6. Train machine learning models
7. Compare model performance
8. Evaluate the best model
9. Predict heart disease for new patient data
10. Save the trained model

## Project Files

```
Task-4-Heart-Disease-Prediction/
│
├── heart.csv
├── heart_disease_prediction.ipynb
├── heart_model.pkl
├── scaler.pkl
└── README.md
```

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

## Sample Prediction

The trained model can predict whether a patient has a risk of heart disease based on their medical details.

Example output:

```
Prediction: 1
Heart Disease Detected
```

or

```
Prediction: 0
No Heart Disease
```

## How to Run the Project

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Install required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all notebook cells to train and test the model.

## Conclusion

This project demonstrates how machine learning classification techniques can be used for healthcare prediction. The trained model helps identify possible heart disease risk based on patient medical data.
