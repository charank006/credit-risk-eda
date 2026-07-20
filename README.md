# Credit Risk Exploratory Data Analysis

## Overview

This project presents an end-to-end Exploratory Data Analysis (EDA) of a credit risk dataset to understand borrower characteristics, identify factors influencing loan default, and generate actionable business insights. The project follows a structured data analytics workflow including data cleaning, preprocessing, visualization, and statistical analysis.

---

## Objectives

- Understand the structure of the dataset.
- Assess data quality and clean missing values.
- Explore borrower demographics and financial attributes.
- Analyze relationships between features and loan default.
- Generate business insights for credit risk assessment.

---

## Dataset

- Source: Kaggle Credit Risk Dataset
- Records: 32,581
- Features: 12

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Missingno
- Jupyter Notebook

---

## Project Structure

```text
credit-risk-eda/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── reports/
│   ├── figures/
│   └── insights.md
├── screenshots/
├── src/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Exploratory Analysis

### Data Quality
- Missing value analysis
- Duplicate detection
- Data validation

### Univariate Analysis
- Age distribution
- Income distribution
- Loan amount distribution
- Loan intent
- Loan grade
- Home ownership

### Bivariate Analysis
- Income vs Loan Status
- Loan Grade vs Loan Status
- Interest Rate vs Loan Status
- Loan Intent vs Loan Status

### Multivariate Analysis
- Correlation heatmap
- Default rate analysis
- Credit history analysis

---

## Key Findings

- Lower-income borrowers exhibit higher default rates.
- Higher loan amounts are associated with increased default risk.
- Loan grade strongly influences repayment behavior.
- Previous default history is a strong indicator of future defaults.
- Personal and medical loans contribute significantly to defaults.

---

## Future Work

- Build a credit default prediction model.
- Compare multiple machine learning algorithms.
- Perform feature engineering.
- Deploy a predictive model using Streamlit or FastAPI.

---

## Author

**Charan Kothuru**