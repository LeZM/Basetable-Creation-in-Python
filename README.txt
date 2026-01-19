# 🧱 Basetable Creation in Python

**Python Programming for Data Science — Individual Project**

This project demonstrates the construction of a **data science basetable** from raw financial data using Python, following best practices in data processing, feature engineering, and documentation.

---

## 📌 Project Objectives

The objectives of this project are to:

- 🧹 Process raw financial data into an analytics-ready basetable  
- 🧠 Design meaningful independent and dependent variables using time windows  
- 📊 Analyze and visualize key variables  
- 🗂 Organize a complete and reproducible data science project  

---

## 🧠 Data & Business Context

The basetable is built at the **client level**, where each row represents an account owner.

To avoid data leakage, a **time-based split** is applied:

- **Independent Variables (IV):** computed using data from **1996**
- **Dependent Variables (Targets):** computed using data from **1997**


---

## 🧱 Basetable Design

### 🔹 Granularity
- One row per client (account owner)

### 🔹 Independent Variables (1996)
Calculated only for clients with sufficient data during the IV window:

- Demographic variables (gender, age, age group)
- Behavioral and transactional indicators
- RFM-style metrics (Recency, Frequency, Monetary)
- Length of Relationship (LOR)
- Additional engineered features

### 🔹 Dependent Variables (1997)

Two binary target variables are created:

- **Loan Granted**
  - `1`: Client had a loan granted in 1997  
  - `0`: No loan granted  

- **Credit Card Issued**
  - `1`: Credit card issued (account owner or disponent) in 1997  
  - `0`: No credit card issued  

---

## 🔄 Data Processing & Feature Engineering

The project includes:

- Data cleaning and validation
- Filtering clients based on data availability
- Time-window-based aggregations
- Feature engineering aligned with business logic
- Documentation of data corrections and transformations

---

## 📊 Analysis & Visualization

After building the basetable, the project includes:

- Distribution analysis of independent variables
- Exploration of dependent variables
- Visualizations to support interpretation and insights

---

## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📂 Project Structure


---

## 🚀 Key Takeaways

- Demonstrates a real-world basetable construction workflow  
- Applies time-aware feature engineering  
- Emphasizes data integrity and documentation  
- Bridges business understanding and data science execution  

---

## 👤 Author

**Mehdi Zorkani**  
Master’s student — Operations & Supply Chain Management  
Specialized Master — AI & Data Analytics for Business  

🔗 LinkedIn: https://www.linkedin.com/in/mehdizorkani
