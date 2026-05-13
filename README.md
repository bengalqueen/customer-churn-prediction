# Customer Churn Prediction

A machine learning project to predict whether a telecom customer will churn or not.

## About the Project
Used a real telecom dataset of 7,043 customers and built classification models to predict churn. 
The goal was to find patterns in customer behavior that lead to churn.

## Dataset
- 7,043 customers, 21 features
- Features include tenure, contract type, monthly charges, internet service, etc.
- Target: Churn (Yes / No)

## What I Did
- Cleaned and preprocessed the data (label encoding, handling missing values)
- Split data into 80% train and 20% test
- Trained two models — Logistic Regression and Random Forest
- Compared both models using accuracy, confusion matrix and classification report
- Plotted feature importance to see which factors affect churn the most

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 81.9% |
| Random Forest | 78.99% |

## Key Takeaways
- Logistic Regression worked better on this dataset
- Tenure, Monthly Charges and Total Charges are the biggest factors in churn
- Short tenure + high monthly charges = higher chance of churn

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Notebook
Kaggle: https://www.kaggle.com/code/shreyadutta01/customer-churn-prediction-ml-classification
