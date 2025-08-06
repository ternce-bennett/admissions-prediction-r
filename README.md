# Graduate Admissions Prediction using Logistic Regression (R)

This project analyzes applicant data to predict the likelihood of graduate school admission using logistic regression. It explores how academic performance, GRE scores, work experience, research exposure, and programming skills influence admissions outcomes.

---

## 🚀 Project Overview

The goal is to help university admissions teams make data-informed decisions by modeling patterns in past admissions data. Using **R**, the project performs exploratory data analysis (EDA), data preprocessing, and builds a logistic regression model to predict admission outcomes (admitted vs. not admitted).

---

## 🧠 Key Features

- **Exploratory Data Analysis (EDA):** Visualizations of GPA distribution, GRE scores, and programming experience vs. admission outcome  
- **Data Preprocessing:** Factor conversions, dummy variable creation for categorical features, and train-test data partitioning  
- **Logistic Regression Model:** Predicts binary admission outcomes using relevant applicant features  
- **Model Evaluation:** Confusion matrix to assess accuracy and model performance  

---

## 📁 Dataset Description

The dataset includes 10 observations with the following fields:

| Variable               | Description                            |
|------------------------|------------------------------------|
| GPA                    | Undergraduate Grade Point Average   |
| GRE_Score              | GRE exam score                      |
| Work_Experience_Years  | Years of professional experience    |
| Research_Experience    | Binary indicator for research (0/1) |
| Programming_Experience | Categorical: None, Basic, Intermediate, Advanced |
| Admission_Outcome      | Target variable (1 = Admitted, 0 = Not Admitted) |

*Note: This small dataset is illustrative; larger datasets improve model robustness.*

---

## 🧪 Technologies Used

- **R** for data manipulation, modeling, and visualization  
- Key libraries: `tidyverse`, `caret`, `ggplot2`, `readr`  

---

## 📈 Results Summary

- The model correctly classifies most applicants in the test set with reasonable accuracy  
- Variables such as GPA, GRE Score, and Programming Experience strongly influence admission chances  
- Visualizations indicate higher GPA and programming skills correlate with higher admission likelihood  

---

## ✅ Next Steps & Improvements

- Use larger datasets for better model generalization  
- Experiment with other classification models (decision trees, random forests)  
- Apply cross-validation and hyperparameter tuning  
- Incorporate probability thresholds for more nuanced admission decisions  

---

## ▶️ How to Run

1. Open and run `eda.R` to perform exploratory data analysis and visualize the dataset  
2. Run `model_regression.R` to build and evaluate the logistic regression model  

Ensure required libraries are installed:

```r
install.packages(c("tidyverse", "caret", "ggplot2", "readr"))
