# Diabetes Prediction 🩺

## Overview
This project focuses on predicting whether an individual has diabetes using machine learning techniques applied to medical and physiological data. Early prediction of diabetes can help in timely diagnosis and preventive healthcare decision-making.

The project demonstrates a complete machine learning workflow, from data preprocessing to model training and evaluation, using Python and popular data science libraries.

---

## Problem Statement
Diabetes is a chronic disease that requires early detection to reduce health risks and complications. The objective of this project is to build a supervised machine learning model that can classify individuals as diabetic or non-diabetic based on key medical attributes.

---

## Dataset Description
The dataset contains medical diagnostic measurements collected from patients. Each record includes the following features:

- **Pregnancies** – Number of times the patient has been pregnant  
- **Glucose** – Plasma glucose concentration  
- **BloodPressure** – Diastolic blood pressure (mm Hg)  
- **SkinThickness** – Triceps skin fold thickness (mm)  
- **Insulin** – Serum insulin level  
- **BMI** – Body Mass Index (weight in kg / height in m²)  
- **DiabetesPedigreeFunction** – A measure of genetic predisposition to diabetes  
- **Age** – Age of the patient in years  

The target variable is:
- **Outcome** – Indicates whether the patient has diabetes (1 = diabetic, 0 = non-diabetic)

---

## Project Structure
```text
Diabetes-Prediction/
│── data/                  # Dataset files
│── notebooks/             # Jupyter notebooks
│   └── diabetes_prediction.ipynb
│── README.md
│── requirements.txt
