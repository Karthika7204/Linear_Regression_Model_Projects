# Diabetes-Prediction
Project Description: Diabetes Prediction Using SVM Classifier This project employs a Support Vector Machine (SVM) classifier to predict whether a patient has diabetes based on various medical and demographic features. The goal is to develop a reliable model for early diabetes detection.

# Features
Input: Blood sugar level, BMI, age, blood pressure, insulin levels, and skin thickness.
Output: Binary classification indicating diabetic (1) or non-diabetic (0).

# Dataset
The model uses the Pima Indians Diabetes Dataset, which includes:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI (Body Mass Index)
Diabetes Pedigree Function
Age
Outcome (0 or 1)

# Model Overview
Data Preprocessing: Handle missing values, scale features, and split the dataset.
SVM Classifier: Use a linear kernel to find the optimal hyperplane separating the classes.
Model Training: Train the SVM model on the training set.
Evaluation: Assess performance using accuracy, precision, recall, and F1-score

# Results
The SVM classifier achieves an accuracy of approximately 78% on the test set, demonstrating its effectiveness in diabetes prediction. Detailed evaluation metrics are provided in the project notebook/script.

