# Diabetes Prediction Model  

## 📌 Overview  
This project is a **Diabetes Prediction Model** built using **Support Vector Machine (SVM)** in Python. It utilizes the **PIMA Indian Diabetes Dataset**, performing **exploratory data analysis (EDA), feature scaling, and model training** to predict whether a person has diabetes based on medical attributes.  

## 📂 Dataset  
The dataset consists of **8 independent variables** (e.g., glucose level, BMI, insulin, etc.) and **1 dependent variable (`Outcome`)**, where:  
- `0` indicates a person is **not diabetic**  
- `1` indicates a person **has diabetes**  

## 🛠 Tech Stack  
- **Python**  
- **Pandas & NumPy** (for data manipulation)  
- **Scikit-learn** (for model training & evaluation)  

## 🔍 Exploratory Data Analysis (EDA)  
- Checked dataset shape, statistics, and class distribution  
- Identified missing/zero values in medically relevant columns  
- Standardized feature scaling for better accuracy  

## 🚀 Model Development  
- **Feature Scaling** using `StandardScaler()`  
- **Train-Test Split** (80% training, 20% testing)  
- **Classification Model:** Support Vector Machine (SVM)  
- **Evaluation:** Model accuracy calculated on training data  

## 🎯 Prediction System  
The trained model can **predict diabetes status** based on user-provided input values such as glucose level, insulin, BMI, and age. Example usage:  
```python
input_data = (5,166,72,19,175,25.8,0.587,51)  
prediction = Classifier.predict(std_data)  
print("Diabetic" if prediction[0] == 1 else "Not Diabetic")  
