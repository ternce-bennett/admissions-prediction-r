# 🎓 Admissions Prediction Using Logistic Regression

This project explores the use of logistic regression to predict graduate admissions outcomes based on academic and personal factors. It is designed to demonstrate core data analysis and modeling skills relevant to a Master's program in Statistics and Data Science.

---

## 📁 Project Structure

- **data/**
  - `admissions_data.csv` – Dataset with applicant features and outcomes
- **scripts/**
  - `eda.R` – Exploratory Data Analysis (EDA)
  - `model_logistic_regression.R` – Logistic regression modeling

---

## 📊 Dataset Overview

The dataset contains synthetic admissions data with the following features:

- `GPA`: Undergraduate Grade Point Average  
- `GRE_Score`: Graduate Record Examination score  
- `Work_Experience_Years`: Years of work experience  
- `Research_Experience`: Binary indicator for research experience (0 or 1)  
- `Programming_Experience`: Level of programming skill (`None`, `Basic`, `Intermediate`, `Advanced`)  
- `Admission_Outcome`: Binary target (1 = Admitted, 0 = Rejected)

---

## 📈 Analysis Summary

The project consists of two main parts:

### 1. Exploratory Data Analysis (`eda.R`)  
- Summary statistics and visualizations  
- Relationships between features and admission outcomes  
- Insights into how experience and GPA correlate with admission success

### 2. Modeling (`model_logistic_regression.R`)  
- Logistic regression to classify applicants  
- Feature encoding and preprocessing  
- Evaluation using confusion matrix and accuracy metrics

---

## ⚙️ How to Run

You can run this project in [Posit Cloud](https://posit.cloud) or in your local R environment:

1. Upload the files and folders as shown in the project structure  
2. Open and run `scripts/eda.R` for data exploration  
3. Then run `scripts/model_logistic_regression.R` to train and evaluate the model

### 📦 Required R packages

```r
install.packages("ggplot2")
install.packages("dplyr")
install.packages("caret")
