# 🧱 Basetable Creation in Python

**Building an analytics-ready basetable from raw financial data using a time-aware data science approach.**

---

## 🏷 Badges

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Project](https://img.shields.io/badge/Project-Data%20Science-lightgrey)

---

## 🛠 Built with the tools and technologies

![Python](https://img.shields.io/badge/-Python-black?logo=python)
![Pandas](https://img.shields.io/badge/-Pandas-black?logo=pandas)
![NumPy](https://img.shields.io/badge/-NumPy-black?logo=numpy)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-black)
![Seaborn](https://img.shields.io/badge/-Seaborn-black)
![Jupyter](https://img.shields.io/badge/-Jupyter-black?logo=jupyter)
![Git](https://img.shields.io/badge/-Git-black?logo=git)

---

## 📌 Overview

This project consists of constructing a **data science basetable** from a raw financial dataset using Python.

The basetable is designed to support **analytics, reporting, and predictive modeling**, following best practices in:
- data preprocessing
- feature engineering
- time-based variable construction
- documentation and analysis

---

## 🧠 Data & Business Context

- **Granularity:** one row per client (account owner)
- All account activities are assumed to be performed by the owner

To avoid data leakage, a **time-based split** is applied:

1996 → Independent Variables (features)
1997 → Dependent Variables (targets)


This mirrors real-world analytics and modeling workflows.

---

## 🧱 Basetable Design

### Independent Variables (1996)
Calculated only for clients with sufficient data during the IV window:

- Demographic variables (gender, age, age group)
- Behavioral and transactional indicators
- RFM-style metrics (Recency, Frequency, Monetary)
- Length of Relationship (LOR)
- Additional engineered features

### Dependent Variables (1997)

Two binary target variables are created:

- **Loan Granted**
- `1`: loan granted in 1997
- `0`: no loan granted

- **Credit Card Issued**
- `1`: credit card issued (account owner or disponent)
- `0`: no credit card issued

---

## 🔄 Methodology

The project follows a structured data science workflow:

1. Data loading and inspection
2. Data cleaning and validation
3. Time-window-based filtering
4. Feature engineering
5. Basetable construction
6. Descriptive analysis and visualization

All transformations and assumptions are documented.

---

## 📊 Outputs

- Final analytics-ready basetable
- Descriptive statistics of independent variables
- Analysis of target variables
- Visualizations supporting interpretation and insights

The basetable can be directly reused for BI dashboards or predictive modeling tasks.

---

## 📂 Project Structure

```text
basetable-creation-in-python/
├── data/
├── docs/
├── src/
└── README.md
```

---

## 👤 Author

**Mehdi Zorkani**
- Master’s student – Operations & Supply Chain Management  
- Specialized Master – AI & Data Analytics for Business  

🔗 LinkedIn: https://www.linkedin.com/in/mehdizorkani

