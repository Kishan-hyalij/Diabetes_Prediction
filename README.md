# 🩺 Diabetes Prediction using Machine Learning

A Machine Learning project to predict whether a patient is diabetic or not based on medical diagnostic measurements.  
This project uses a dataset containing health-related attributes and applies classification algorithms to make predictions.

---

## 📌 Project Overview

The **Diabetes Prediction** project aims to build a model that can predict whether a person has diabetes or not based on input features such as glucose level, blood pressure, insulin level, BMI, etc.  
This can help in early diagnosis and preventive healthcare.

---

## 🚀 Features

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Machine Learning Model Training (Logistic Regression, Random Forest, etc.)  
- Model Performance Evaluation  
- User-friendly Interface 

---

## 🗂 Dataset

The dataset used in this project is the **PIMA Indians Diabetes Database**, which contains the following features:

- **Pregnancies** – Number of times pregnant  
- **Glucose** – Plasma glucose concentration  
- **BloodPressure** – Diastolic blood pressure (mm Hg)  
- **SkinThickness** – Triceps skin fold thickness (mm)  
- **Insulin** – 2-Hour serum insulin (mu U/ml)  
- **BMI** – Body mass index  
- **DiabetesPedigreeFunction** – Diabetes pedigree function  
- **Age** – Age (years)  
- **Outcome** – Class variable (0 = Non-diabetic, 1 = Diabetic)

---

## 🛠 Tech Stack

- **Programming Language:** Python 🐍  
- **Libraries Used:**
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
- **Model:** Logistic Regression / Random Forest / Support Vector Machine  
- **Deployment:** Flask  

---

## 📊 Exploratory Data Analysis (EDA)

- Distribution plots for each feature  
- Correlation heatmap  
- Outlier detection & handling  
- Feature scaling  

---

## 🤖 Model Training

1. **Data Splitting:** Train-Test Split (80-20)  
2. **Model Used:** Logistic Regression (baseline), Random Forest (final model)  
3. **Hyperparameter Tuning:** GridSearchCV / RandomizedSearchCV  
4. **Performance Metrics:** Accuracy, F1-Score  

---

## 📈 Model Performance

| Model               | Accuracy | F1-Score |
|--------------------|---------|-----------|
| Logistic Regression | 0.80    | 0.70    |
| SVC                 | 0.79    | 0.72    |
| K-NN                | 0.74    | 0.51    |
| Random Forest       | 0.81    | 0.70    |

✅ **Random Forest performed best** and was chosen as the final model.

---

## 🌐 Deployment

The model is deployed and accessible via [GitHub Pages / Streamlit App](YOUR_DEPLOYMENT_LINK_HERE).

---
