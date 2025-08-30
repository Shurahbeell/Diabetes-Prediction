# 🩺 Diabetes Prediction (Classification Project)

A beginner-friendly ML project to predict diabetes (yes/no) using the **Pima Indians Diabetes** dataset.  
We compare multiple algorithms and visualize their performance.

## 📦 Tech
Python · scikit-learn · XGBoost · NumPy · Pandas · Matplotlib · Seaborn · Jupyter

## 📊 Dataset
- Source: Pima Indians Diabetes Dataset (e.g., Kaggle/UCI)
- Target: `Outcome` (1 = Diabetic, 0 = Non-Diabetic)

## Preprocessing
- Treated zeros as missing for: `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`
- Filled missing with **median**
- Train/Test split (80/20), scaled features

## 🤖 Models Compared
Logistic Regression · Decision Tree · Random Forest · XGBoost · KNN · Naive Bayes · SVM

Results (Test Set)
| Model                | Accuracy | Precision (1) | Recall (1) | F1 (1) | ROC-AUC |
|----------------------|----------|---------------|------------|--------|---------|
| Logistic Regression  | 0.75     | 0.67          | 0.59       | 0.63   | 0.82    |
| Decision Tree        | 0.68     | 0.55          | 0.48       | 0.51   | –       |
| Random Forest        | 0.78     | 0.73          | 0.59       | 0.65   | –       |
| XGBoost              | 0.75     | 0.65          | 0.63       | 0.64   | 0.82    |
| KNN                  | 0.69     | 0.54          | 0.50       | 0.52   | –       |
| Naive Bayes          | 0.70     | 0.57          | 0.63       | 0.60   | –       |
| SVM                  | 0.74     | 0.65          | 0.56       | 0.60   | –       |




jupyter notebook notebooks/diabetes_classification.ipynb
