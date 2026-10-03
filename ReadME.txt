# Employee Workforce Risk & Layoff Analysis

## Project Overview

This project analyzes workforce characteristics associated with recorded employee layoffs and develops machine learning models to predict the recorded layoff outcome.

The project combines:

- Python
- Statistical Analysis
- SQL
- Machine Learning
- Power BI

The objective is to identify workforce patterns, compare predictive models, and present the findings through an interactive business dashboard.

---

## Business Problem

Organizations need to understand which workforce characteristics are associated with higher recorded layoff rates.

This project examines factors such as:

- Department
- Cost Center Type
- Team Wind-Down
- Role Redundancy
- PIP Status
- Tenure
- Performance Rating
- Salary
- Management Layer
- Employee Level
- Remote Status
- Recent Hire Status

The analysis focuses on recorded outcomes and statistical/predictive relationships. It does not establish causal relationships.

---

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Statistical Analysis
4. SQL Analysis
5. Machine Learning
6. Feature Importance Analysis
7. Power BI Dashboard
8. Business Findings

---

## Tools & Technologies

| Area | Tools |
|---|---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Statistics | SciPy |
| Database | SQLite |
| Querying | SQL |
| Machine Learning | Scikit-learn |
| BI | Microsoft Power BI |
| Development | VS Code, Jupyter |

---

## Machine Learning

The project compares four model configurations:

| Model | Accuracy | Precision | Recall | F1 | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic - Full | 86.35% | 73.54% | 51.43% | 60.53% | 83.30% |
| Random Forest - Full | 83.08% | 58.19% | 59.95% | 59.06% | 80.96% |
| Logistic - Restricted | 79.82% | 53.47% | 6.31% | 11.28% | 69.82% |
| Random Forest - Restricted | 72.63% | 32.76% | 32.76% | 32.76% | 63.91% |

Model performance is reported across multiple metrics because accuracy alone does not adequately describe classification performance.

---

## Feature Importance

The model feature-importance analysis identified the following among the more prominent features:

- Salary
- Tenure
- Performance Rating
- Cost Center Type
- Remote Status
- PIP Status
- Department and organizational attributes

Feature importance indicates model contribution and should not be interpreted as proof of causation.

---

## Power BI Dashboard

### Workforce Overview

The dashboard presents:

- Total employees
- Recorded layoff rate
- Employees laid off
- Salary exposure
- Department-level layoff rates
- Performance patterns
- Team wind-down
- Role redundancy
- Tenure bands
- Cost-center analysis

### Predictive Risk Analysis

The predictive page presents:

- Model comparison
- Accuracy
- Precision
- Recall
- F1 score
- ROC-AUC
- Feature importance
- Machine learning insights

---

## Key Findings

- Recorded layoff rates vary substantially across departments and cost-center types.
- Team wind-down is associated with substantially higher recorded layoff rates.
- Role redundancy is associated with higher recorded layoff rates.
- Remote status showed negligible association in the statistical analysis.
- Salary, tenure and performance rating were among the more prominent model features.
- Restricted-feature models showed weaker predictive performance across the reported metrics.

---

## Important Interpretation Note

This analysis identifies statistical associations and predictive patterns.

It does **not** prove that a particular employee characteristic causes layoffs.

Similarly, salary exposure shown in the dashboard represents the salary associated with recorded layoffs and should not automatically be interpreted as realized company savings.

---

## Project Structure

```text
Employee_Workforce_Risk_Analysis/
│
├── Data/
├── Notebook/
├── SQL/
├── PowerBI/
├── Screenshots/
├── README.md
└── requirements.txt