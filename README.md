Graduate Admissions Prediction using Logistic Regression (R)
This project analyzes applicant data to predict the likelihood of graduate school admission using logistic regression. It explores how academic performance, GRE scores, work experience, research exposure, and programming skills influence admissions outcomes.

📊 Project Overview
The goal is to help university admissions teams make data-informed decisions by modeling patterns in past admissions data. Using R, we perform exploratory data analysis (EDA), preprocess the data, and build a logistic regression model to predict admission outcomes (admitted vs. not admitted).

🧠 Key Features
Exploratory Data Analysis: Visualizations for GPA distribution, GRE scores, and programming experience vs. admission.

Data Preprocessing: Factor conversion, dummy variable creation for categorical data, and data partitioning for training/testing.

Logistic Regression Model: Predicts the binary outcome of admission using all relevant features.

Model Evaluation: Includes confusion matrix to assess model accuracy.

📁 Dataset
The dataset contains 10 observations with the following fields:

GPA: Undergraduate GPA

GRE_Score: GRE exam score

Work_Experience_Years: Years of professional experience

Research_Experience: Binary indicator for research involvement

Programming_Experience: Categorical — None, Basic, Intermediate, Advanced

Admission_Outcome: Binary target variable (1 = Admitted, 0 = Not Admitted)

(A larger dataset would yield more robust results — this example is illustrative.)

🧪 Technologies Used
R: Data manipulation, modeling, and visualization

Libraries: tidyverse, caret, ggplot2

📈 Results Summary
The model correctly classifies most applicants in the test set with reasonable accuracy.

Variables like GPA, GRE Score, and Programming Experience showed influence on admission outcomes.

Visual analysis suggests higher GPA and programming proficiency correlate with admission.

✅ Next Steps / Improvements
Collect or use a larger dataset for better model generalization.

Try other models (e.g., decision trees, random forest) for performance comparison.

Perform cross-validation and hyperparameter tuning.

Add probability thresholds for more nuanced decision-making.

▶️ How to Run
Open eda.R to explore the data visually.

Run model_regression.R to build and evaluate the logistic regression model.

Ensure required libraries are installed:

r
Copy
Edit
install.packages(c("tidyverse", "caret", "ggplot2", "readr"))
💡 Motivation
This project demonstrates how data science can support real-world decision-making, such as optimizing graduate admissions. It also showcases the use of R for classification tasks, a useful skill in academic and research environments.


