# 🏥 Healthcare Cost Drivers: A Data-Driven Statistical Exploration

This project explores and analyzes a health insurance dataset to understand how personal, demographic, and lifestyle factors affect medical charges. Using Exploratory Data Analysis (EDA) and statistical tests, the goal is to uncover patterns, trends, and significant relationships between variables like age, BMI, smoking status, and insurance costs.

---

## 📁 Dataset Overview

- **Source**: Kaggle / Public health insurance dataset
- **Rows**: 1,338
- **Columns**: 7
- **Target**: `charges` (Medical insurance cost)

| Feature     | Description                        |
|-------------|------------------------------------|
| `age`       | Age of the individual              |
| `sex`       | Gender (male/female)               |
| `bmi`       | Body Mass Index                    |
| `children`  | Number of children/dependents      |
| `smoker`    | Smoking status (yes/no)            |
| `region`    | Residential region (US)            |
| `charges`   | Annual medical insurance charges   |

---

## 🧠 Skills Demonstrated

- Python for data analysis
- Exploratory Data Analysis (EDA)
- Data visualization (Seaborn, Matplotlib)
- Outlier detection using boxplots
- Kernel Density Estimation (KDE)
- Hypothesis testing (Z-Test, ANOVA, Tukey HSD)
- Business insights from data
- Git & GitHub version control

---

## 📊 Key Insights

- **Smokers** are charged significantly higher than non-smokers.
- **BMI** is positively correlated with charges; higher BMI → higher risk.
- **Young adults (20–30)** form a large portion of the dataset.
- **Charges are skewed** with several high-cost outliers.
- **No strong charge difference** between genders, but males show more high-cost outliers.
- **Statistically significant** differences in charges based on:
  - Smoking status (Z-test)
  - Region (ANOVA)
  - Number of children (ANOVA)

---

## 📌 Visuals Used

- Count plots (gender, smoker, children, region)
- KDE plots (age, BMI, charges)
- Box plots (charges by gender/smoker/region/children)
- Correlation heatmap
- Pair plots for multivariate patterns

---



