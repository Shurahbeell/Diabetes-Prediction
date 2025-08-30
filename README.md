# Diabetes-Prediction
Diabetes is one of the most common chronic diseases worldwide. Early detection can help patients manage symptoms and prevent complications.
In this project, we apply machine learning classification algorithms to predict whether a patient is diabetic based on diagnostic features.

Dataset:

Source: PIMA Indians Diabetes Dataset
Rows: 768
Columns: 8 features + 1 target variable
Key Features:
Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
Target variable:
0 → Non-diabetic
1 → Diabetic

Project Workflow:
Data Preprocessing
Handled missing/zero values.
Standardized features.
Model Training
Trained multiple classification models:
Logistic Regression
Decision Tree
Random Forest
XGBoost
KNN
Naive Bayes
SVM
Evaluation Metrics:
Accuracy
Precision
Recall
F1-score
ROC-AUC

Results
Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Logistic Regression	0.75	0.67	0.59	0.63	0.82
Decision Tree     	0.68	0.55	0.48	0.51	-
Random Forest	      0.78	0.73	0.59	0.65	-
XGBoost	            0.75	0.65	0.63	0.64	0.82
KNN	                0.69	0.54	0.50	0.52	-
Naive Bayes	        0.70	0.57	0.63	0.60	-
SVM	                0.74	0.65	0.56	0.60	-
