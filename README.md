# Graduate Admission Prediction – EDA & Regression Analysis

## Introduction
With increasing competition in graduate admissions, students often find it difficult to understand how different academic and profile-related factors influence their chances of getting admitted to a university. Admission decisions are typically based on multiple parameters such as academic scores, standardized test results, research experience, and qualitative assessments like SOP and LOR.

This project aims to analyze a graduate admission dataset and identify the key factors that affect a student’s probability of admission. By performing exploratory data analysis (EDA) and building a simple predictive model, the project demonstrates how data analysis and machine learning techniques can be used to understand admission patterns and estimate admission likelihood based on student profiles.

---

## Dataset Information
The dataset consists of student academic and profile attributes commonly used in graduate admission evaluation. All features are numerical and represent standardized scores or rating-based inputs.

### Key Features
- **GRE Score** – Graduate Record Examination score  
- **TOEFL Score** – English proficiency test score  
- **University Rating** – Ranking of the target university  
- **SOP** – Strength of Statement of Purpose (rating-based)  
- **LOR** – Strength of Letter of Recommendation (rating-based)  
- **CGPA** – Undergraduate academic performance  
- **Research** – Indicates whether the student has research experience  
- **Chance of Admit** – Probability of admission (target variable)

---

## Problem Type
- Regression problem
- Target variable (*Chance of Admit*) is a continuous value between 0 and 1, representing admission probability.

---

## Approach & Methodology
- Data loading and preprocessing
- Column standardization and removal of irrelevant features
- Exploratory Data Analysis (univariate, bivariate, and multivariate)
- Correlation analysis to understand feature relationships
- Linear Regression model for predicting admission probability
- Model evaluation using appropriate regression metrics
- Interpretation of feature importance to derive insights

---

## Evaluation Metrics
Since this is a regression task, the following metrics were used:

- **Mean Squared Error (MSE)**  
  Measures the average squared difference between actual and predicted admission probabilities. Lower values indicate better performance.

- **R² Score (Coefficient of Determination)**  
  Indicates how well the model explains the variation in admission probability. Higher values suggest a better fit.

### Why These Metrics Were Chosen
- Accuracy is not suitable because the output is a probability, not a class label.
- MSE quantifies prediction error.
- R² explains how much of the outcome is captured by the model.

---

## Key Insights
- CGPA is the most influential factor affecting admission probability.
- Research experience significantly improves admission chances.
- GRE and TOEFL scores show correlation with admission probability but have lower independent impact when combined with other features.
- SOP and LOR contribute as supporting factors rather than primary drivers.

---

## Conclusion
This project demonstrates how exploratory data analysis and regression modeling can be used to understand graduate admission trends. The results highlight the importance of academic consistency and research experience in improving admission chances. Overall, the project showcases an end-to-end data analysis workflow, from understanding the data to building and interpreting a predictive model.

---

## Tools Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Project Objective (One-Line Summary)
> To analyze graduate admission data, identify key influencing factors, and predict admission probability using regression-based modeling techniques.
