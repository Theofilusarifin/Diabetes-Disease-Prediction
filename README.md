# Diabetes Disease Prediction Project

## Background
Diabetes, characterized by high blood sugar levels due to ineffective insulin production or usage, poses serious health risks if not managed. Deep Learning offers promising avenues for diabetes management.

## Goals
To diagnostically predict whether a patient has diabetes or not.

## Dataset
- 768 data entries of Indian Pima female patients, aged at least 21.
- 9 medical information columns.
- No missing values; anomalies in certain features (e.g., Insulin, SkinThickness) will be imputed.
- High outliers in DiabetesPedigreeFunction and SkinThickness will be handled using IQR.
- Target data imbalance addressed via SMOTE oversampling.

## Model
- Utilizes an Artificial Neural Network (ANN).
- Achieved 70.13% accuracy on test data.
- Architecture: narrow and shallow.

## Conclusion
The Artificial Neural Network (ANN) model, trained on the provided dataset, offers a significant step forward in diabetes prediction. With a commendable accuracy of 70.13% on the test data, the model demonstrates its potential in aiding clinical decision-making. By leveraging deep learning techniques, it provides valuable insights into diagnosing diabetes in patients. This predictive capability can assist healthcare professionals in early intervention and personalized treatment strategies, ultimately improving patient outcomes and quality of life.

