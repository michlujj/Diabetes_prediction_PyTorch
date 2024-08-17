# Diabetes_prediction_PyTorch

Background:

Dataset is a collection of medical and demographic data from 100,000 patients, with diagnosis of diabetes (0 or 1).

Dataset contains features such as gender, age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level.

This is a classification problem.

Objective:

1) To identify the factors that causes diabetes based on patients' medical history

2) To build a PyTorch ANN prediction model that can predict if the patient will develop diabetes based on a given set of characteristics.

Dataset is highly imbalanced, only 8.5% of patients have Diabetes

Thus, AUC and F1 scores are used to compute the accuracy rate of the prediction model

AdaBoost classifier prediction model has the highest AUC score = 89.25%.

Factors assciated with being Diabetic: 1) HbA1c level, 2) blood glucose level, 3) Hypertension, 4) Heart Disease, 5) Age
