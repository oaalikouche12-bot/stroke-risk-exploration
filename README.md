# 🧠 Stroke Prediction — Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) of the **Stroke Prediction Dataset** from Kaggle.  
The goal is to understand the main **risk factors associated with stroke** by analyzing demographic, lifestyle and medical attributes.

Dataset link: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

---

## 📊 Project Overview

Stroke is one of the leading causes of death and long-term disability worldwide.  
Identifying early risk patterns is essential for prevention.

This project performs a deep analysis of the dataset to answer questions such as:

- Which variables are most correlated with stroke?
- How do age, glucose levels, BMI, smoking or hypertension affect stroke probability?
- Are there clear patterns between gender, marital status, work type or residence type?

---

## 🎯 Objectives

- Perform **data cleaning** and identify missing values.
- Analyze **categorical** and **numerical features**.
- Create **visualizations** to explore risk factor distributions.
- Investigate **relationships** between variables and stroke occurrence.
- Provide meaningful **insights** for future ML modeling.

---

## 📁 Dataset Information

The dataset contains **5,110 rows** and **12 columns**.

### **Main Features**
- `gender`
- `age`
- `hypertension`
- `heart_disease`
- `ever_married`
- `work_type`
- `Residence_type`
- `avg_glucose_level`
- `bmi`
- `smoking_status`
- `stroke` (target)

---

## 🔧 Methods Used

### ✔ Data Cleaning
- Detection and handling of missing values (`bmi` column).
- Type conversion and categorical encoding.

### ✔ Univariate Analysis
- Distributions of age, glucose levels, BMI.
- Countplots for gender, marital status, smoking, work type, residence type.

### ✔ Bivariate Analysis
- Age vs stroke.
- Glucose vs stroke.
- BMI vs stroke.
- Crosstabs for categorical variables.

### ✔ Outlier Detection
- Boxplots for numerical features.

### ✔ Correlation Study
- Heatmap to identify relationships between variables.

---

## 📈 Visualizations

The notebook includes visualizations such as:

- Histograms  
- Boxplots  
- Countplots  
- Pairplots  
- Correlation heatmaps  

Each figure helps interpret how different factors contribute to stroke risk.

---

## 🧠 Key Insights (Summary)

- **Age** is the strongest predictor of stroke: older individuals show substantially higher stroke rates.
- Higher **average glucose levels** are associated with increased stroke probability.
- People with **hypertension or heart disease** have significantly higher risk.
- **BMI** shows moderate influence, with very high or low BMI slightly increasing risk.
- **Smoking status** presents interesting patterns, especially among former smokers.

---

## 📝 Files in This Repository

- `stroke_eda.ipynb` → Main analysis notebook  
- `healthcare-dataset-stroke-data.csv` → Dataset  
- `README.md` → Project documentation  

---

## ▶ How to Run the Notebook

### **Google Colab**
1. Open Colab  
2. Upload the `.ipynb` file  
3. Upload the dataset `.csv`  
4. Run all cells

### **Local**
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook
