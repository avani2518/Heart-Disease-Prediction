# Heart-Disease-Prediction


📌 Heart Disease Prediction System is a Machine Learning-based application that predicts the likelihood of a person having heart disease based on medical parameters. It helps in early diagnosis and risk assessment using supervised learning algorithms and user-friendly input forms.

❤️ Project Features:

1️⃣ User Input Interface:
Accepts input for key medical attributes:
  Age, Gender, Chest Pain Type
  Resting Blood Pressure, Cholesterol Level
  Fasting Blood Sugar, Resting ECG
  Max Heart Rate, Exercise-Induced Angina
  Oldpeak, ST Slope, and more
Inputs can be via CLI or Web UI (if implemented using Streamlit/Flask)

2️⃣ Model Training & Evaluation:
Uses labeled dataset (like UCI Heart Disease dataset)
Data preprocessing: Handling nulls, encoding, normalization
Splits data into training and test sets
Applies multiple ML algorithms:
  Logistic Regression
  XGBoost
  AdaBoost
Evaluates models based on accuracy, precision, recall, F1-score

3️⃣ Prediction Output:
Displays:
  Whether heart disease is likely or not
  Model confidence score (probability)
  Option to compare predictions from different models
