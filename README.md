# 🧠 Diabetes Prediction using Machine Learning

This project uses supervised Machine Learning algorithms to predict the likelihood of diabetes in a patient using the **Pima Indians Diabetes Dataset**. It includes full data preprocessing, model training, evaluation, visualization, and real-time prediction based on user input.

---

## 📌 Project Goals

- Clean and preprocess medical data
- Handle missing values and outliers
- Perform Exploratory Data Analysis (EDA)
- Train multiple ML models and compare their performance
- Visualize model metrics and feature importance
- Make predictions based on real-time user input

---

## 🧪 Machine Learning Models Used

- ✅ Random Forest
- ✅ Logistic Regression
- ✅ Support Vector Machine (SVM)
---

## 📊 Dataset Overview

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes)
- **Features:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- **Target:**
  - Outcome (0 = No Diabetes, 1 = Diabetes)

---

## 📈 Visualizations Included

- 📌 Correlation Heatmap
- 📌 Histograms (Univariate Analysis)
- 📌 Violin Plots (Bivariate Analysis)
- 📌 Pairplots (Multivariate Analysis)
- 📌 Model Accuracy Comparison
- 📌 Confusion Matrix
- 📌 Feature Importance (Random Forest)

---

## 🏆 Best Performing Model

The **Random Forest Classifier** was selected as the best model based on highest accuracy and overall metrics.

---

## 🧰 Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
---

## ✅ Sample Input & Output

### 🔢 **User Input Example**
Pregnancies: 5
Glucose: 166
Blood Pressure: 62
Skin Thickness: 19
Insulin: 175
BMI: 33.6
Diabetes Pedigree Function: 0.51
Age: 42

---
### 🧾 **Prediction Output**
Prediction: 🟥 Positive for Diabetes
