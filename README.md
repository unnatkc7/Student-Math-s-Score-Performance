# Math Score Prediction Using EDA and Hypothesis Testing

This project explores and predicts student math scores based on demographic and educational factors using Exploratory Data Analysis (EDA), hypothesis testing, and regression modeling.

---

# 📚 Project Overview

**Objective:**  
- Understand factors influencing student math performance
- Identify significant differences between groups (e.g. gender, parental education)
- Predict math scores using regression analysis

This analysis helps educators and policymakers gain insights into student performance and identify areas for intervention.

---

## 🗂️ Dataset

- **Source:** [Student Performance Data Set - UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- Features include:
  - Gender
  - Parental level of education
  - Lunch type
  - Test preparation course
  - Math score (target)

Example dataset snippet:

| gender | parental_education | lunch    | test_prep | math_score |
|--------|--------------------|----------|-----------|------------|
| female | bachelor's degree  | standard | none      | 72         |
| male   | high school        | free/reduced | completed | 69     |

---

## 🔎 Exploratory Data Analysis (EDA)

Key EDA tasks:
- Checked for missing data
- Visualized score distributions
- Examined correlations between features and math scores
- Explored differences in scores by gender, parental education, and test preparation

Sample plots:
- Boxplots of math scores across parental education levels
- Histograms of math scores
- Correlation heatmaps

---

## 🧪 Hypothesis Testing

Performed statistical tests to validate insights:
- **Two-sample t-test:** Compared mean math scores between students who completed test preparation and those who did not.
- **ANOVA:** Tested whether math scores differ significantly across different levels of parental education.

---

## 🤖 Regression Modeling

- Built a regression model to predict math scores using significant features
- Evaluated model performance using:
  - Root Mean Squared Error (RMSE)
  - R² score

---

## 🚀 Results & Insights

- Test preparation completion significantly improves math scores
- Higher parental education correlates with better math performance
- Gender differences in math scores are present but smaller in magnitude


## 📊 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn



## 🙋‍♂️ Author

- [Unnat Kc](https://github.com/unnatkc7)


