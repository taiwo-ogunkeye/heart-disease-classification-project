# End-to-End Heart Disease Classification

This project predicts whether a patient has heart disease based on clinical parameters using machine learning.

📊 Dataset

The dataset comes from the Cleveland Heart Disease dataset
.
It contains 303 patient records with 13 features such as age, cholesterol, blood pressure, chest pain type, and more.

🧠 Approach

1. Problem Definition
Predict heart disease presence (binary classification: 1 = disease, 0 = no disease).

2. Data Exploration

EDA with Pandas, Matplotlib, Seaborn

Class balance check, correlation matrix, feature visualization

3. Modeling

Trained Logistic Regression, KNN, and Random Forest

Compared performance on test data

Hyperparameter Tuning

Used RandomizedSearchCV and GridSearchCV for Logistic Regression & Random Forest

Evaluated models with accuracy, precision, recall, F1-score

4. Evaluation

ROC Curve, Confusion Matrix, Cross-Validation metrics

🛠️ Tech Stack

Python

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn

🚀 Results

Achieved ~88-89% accuracy on test set with tuned Logistic Regression, good precision/recall balance.
