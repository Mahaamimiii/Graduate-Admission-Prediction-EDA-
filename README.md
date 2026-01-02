# Graduate-Admission-Prediction-EDA-
Data analysis and prediction of graduate admission probability using Python in Jupyter Notebook.
Introduction

With the increasing competition for graduate admissions, students often find it difficult to understand how different academic and profile-related factors influence their chances of getting admitted to a university. Decisions are typically based on multiple parameters such as academic scores, test results, research experience, and qualitative assessments like SOP and LOR. Analyzing these factors using data-driven techniques can provide clearer insights into admission trends and help applicants better evaluate their profiles.

This project aims to analyze a graduate admission dataset and identify the key factors that affect a student’s probability of admission. By performing exploratory data analysis and building a simple predictive model, the project demonstrates how data analysis and machine learning techniques can be used to understand admission patterns and predict the likelihood of admission based on student profiles.

Dataset Information

The dataset consists of student academic and profile attributes collected for graduate admission prediction. All features are numerical and represent standardized or rating-based inputs commonly used in admission evaluation.

Key Features in the Dataset

GRE Score – Graduate Record Examination score

TOEFL Score – English proficiency test score

University Rating – Ranking of the target university

SOP – Strength of Statement of Purpose (rating-based)

LOR – Strength of Letter of Recommendation (rating-based)

CGPA – Undergraduate academic performance

Research – Indicates whether the student has research experience

Chance of Admit – Probability of admission (target variable)

Metrics Information

Since the target variable Chance of Admit is a continuous value between 0 and 1, this problem is treated as a regression task. Therefore, regression evaluation metrics are used to assess model performance.

Evaluation Metrics Used

Mean Squared Error (MSE)
Measures the average squared difference between the actual and predicted admission probabilities. Lower MSE indicates better prediction accuracy.

R² Score (Coefficient of Determination)
Indicates how well the model explains the variation in admission probability. A higher R² value means the model captures the relationship between features and the target effectively.

Why These Metrics Were Chosen

Accuracy is not suitable for this problem because the output is a probability, not a class label.

MSE provides insight into prediction error magnitude.

R² helps understand how much of the admission outcome is explained by the selected features.

Project Objective (One-Line Summary)

To analyze graduate admission data, identify key influencing factors, and predict the probability of admission using regression-based modeling techniques.
