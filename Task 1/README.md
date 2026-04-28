# ❤️ Heart Disease Prediction System

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Model-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. This project aims to:

- Analyze patient health data
- Identify key risk factors
- Predict whether a person has heart disease or not

---

## 📊 Dataset

- **Dataset Used:** Heart Disease UCI Dataset
- Includes attributes like age, sex, cholesterol, chest pain, etc.

---

## ⚙️ Features

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis  
- Visualization (heatmaps, plots)  
- Model Training & Evaluation  

---

## 🧠 Models Used

- Logistic Regression  
- Decision Tree Classifier  

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt
jupyter notebook

📌 Target Variable
heart_data['target'] = (heart_data['num'] > 0).astype(int)

📈 Results
Logistic Regression → High Accuracy
Decision Tree → Good Performance

📌 Future Improvements
Add Random Forest / XGBoost
Deploy using Flask or Gradio
Improve accuracy with tuning
