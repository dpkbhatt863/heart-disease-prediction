# Heart Attack Analysis

## 📌 Overview
This project focuses on analyzing data related to heart attacks and developing predictive machine learning models to support early detection. The goal is to identify key factors that influence heart attack risk and use this understanding to build accurate classification models.

---

## 🛠️ Libraries Used
- **pandas** – for data loading and manipulation  
- **numpy** – for numerical computations  
- **matplotlib** & **seaborn** – for static data visualization  
- **plotly.express** – for interactive and dynamic plots  

---

## 📊 Dataset Description
The dataset (heart.csv) includes various medical and demographic features such as:

- Age, Sex, Chest Pain Type  
- Resting Blood Pressure, Cholesterol  
- Fasting Blood Sugar, ECG Results  
- Exercise-Induced Angina, Thalium Stress Test  

The target column, **`output`**, indicates heart attack status:
- `1` = Heart attack
- `0` = No heart attack

---

## 🔍 Exploratory Data Analysis (EDA)
We performed EDA to understand data distributions and relationships. Visualizations include:

- Gender and Age Distribution  
- Chest Pain Types and Fasting Blood Sugar  
- ECG and Exercise-Induced Angina  
- Thalium Test Results  
- Blood Pressure and Cholesterol Histograms  
- Correlation Matrix and Heatmaps  

---

## ⚙️ Data Preprocessing
- No missing values were found in the dataset.  
- No categorical encoding was required.

---

## ✂️ Data Splitting & Scaling
- The dataset was split into training and test sets using `train_test_split`.  
- Feature scaling was applied using `StandardScaler` for better model performance.

---

## 🤖 Machine Learning Models

### 1. Random Forest Classifier
- Implemented using `RandomForestClassifier` from scikit-learn  
- Achieved approximately **85% accuracy**  
- Evaluation: Confusion Matrix and Classification Report

### 2. Support Vector Machine (SVM)
- Implemented using `SVC` from scikit-learn  
- Achieved approximately **82% accuracy**  
- Evaluation: Confusion Matrix and Classification Report

---

## ✅ Conclusion
This project demonstrates how data science and machine learning can be applied to predict heart attack risk. These models could be further optimized and deployed in healthcare systems to aid in early detection and intervention.

---

## 📁 Files in This Project
- `project_work.ipynb`: Main analysis and model-building notebook  
- `heart.csv`: Dataset used for training and testing  
- `README.md`: Project documentation
