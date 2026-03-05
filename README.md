# Heart-Disease-Prediction-using-Logistic-Regression-and-Hyperparameter-Optimization
Heart Disease Risk Prediction using Logistic Regression

This project implements a machine learning classification model to predict the likelihood of heart disease based on clinical health indicators such as age, cholesterol levels, blood pressure, BMI, heart rate, and glucose levels.

The objective of this project is to demonstrate an end-to-end machine learning workflow, including data preprocessing, model training, hyperparameter optimization, and performance evaluation using Python and Scikit-Learn.

The model uses Logistic Regression, a widely used statistical classification algorithm, to estimate the probability of heart disease occurrence. Hyperparameters were optimized using GridSearchCV combined with cross-validation to improve model performance and ensure robust evaluation.

# Key Features

Data preprocessing and feature selection from clinical dataset

Feature scaling using StandardScaler

Train-test dataset splitting for model validation

Implementation of Logistic Regression classifier

Hyperparameter tuning using GridSearchCV

Model evaluation using cross-validation techniques

Performance analysis using confusion matrix and classification report

Handling class imbalance using balanced class weights

Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn

Jupyter Notebook

Model Evaluation

The model performance was evaluated using:

Accuracy Score

Confusion Matrix

Precision, Recall, and F1-Score

Cross-Validation

These evaluation metrics help assess the model’s ability to correctly classify heart disease cases while identifying potential class imbalance issues.

Dataset Features

The model was trained using the following health indicators:

Age

Total Cholesterol

Systolic Blood Pressure

Diastolic Blood Pressure

Body Mass Index (BMI)

Heart Rate

Glucose Level



## Model Performance

### Confusion Matrix
<img width="809" height="545" alt="image" src="https://github.com/user-attachments/assets/046f8079-ac84-4849-a6c4-1b03022ff14f" />



### ROC Curve
<img width="929" height="604" alt="image" src="https://github.com/user-attachments/assets/75936830-00a2-446c-ac94-97a1612c4aa8" />

# Example Use Case

Machine learning models such as this can assist healthcare professionals in identifying patients at risk of heart disease and support early preventive decision-making.
