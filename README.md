# 📊 Customer Churn Intelligence Analysis

## 📌 Project Overview

Customer churn is one of the most important business metrics for subscription-based companies. This project analyzes customer behavior to identify the major factors that contribute to customer churn using Python for data cleaning, exploratory data analysis (EDA), and visualization.

The objective is to uncover actionable insights that can help businesses improve customer retention and reduce churn.

--- 

## 🎯 Objectives

* Clean and preprocess the customer churn dataset.
* Perform Exploratory Data Analysis (EDA).
* Identify the key factors influencing customer churn.
* Visualize customer behavior using informative charts.
* Generate business insights and recommendations.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📂 Dataset

The dataset contains customer demographic information, subscription details, services used, payment methods, contract types, tenure, monthly charges, total charges, and churn status.

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Replaced blank values in the **TotalCharges** column with `0` for customers having zero tenure.
* Converted the **SeniorCitizen** column from numeric values (`0`, `1`) to descriptive labels (`No`, `Yes`).
* Checked for missing values and duplicate records.
* Verified and corrected data types where necessary.

---

## 📈 Exploratory Data Analysis

The analysis includes visualizations for:

* Customer Churn Distribution
* Senior Citizen vs Churn
* Customer Tenure vs Churn
* Contract Type vs Churn
* Internet Service vs Churn
* Online Security vs Churn
* Online Backup vs Churn
* Device Protection vs Churn
* Tech Support vs Churn
* Phone Service vs Churn
* Multiple Lines vs Churn
* Payment Method vs Churn

---

## 🔍 Key Insights

### 📉 Overall Churn

* **26.54%** of customers have churned.
* **73.46%** of customers remain with the company.

### 👥 Customer Demographics

* Senior citizens have a higher churn rate than non-senior customers.

### ⏳ Customer Tenure

* Customers with **1–2 months of tenure** are most likely to churn.
* Longer-tenure customers are significantly more likely to stay.

### 📃 Contract Type

* Customers on **Month-to-Month contracts** show the highest churn.
* **One-Year** and **Two-Year** contracts have much lower churn rates.

### 🌐 Internet Services

* Customers using **Fiber Optic Internet** have the highest churn among internet service types.

### 🛡️ Value-Added Services

Customers without the following services are more likely to churn:

* Online Security
* Tech Support
* Online Backup
* Device Protection

### 💳 Payment Method

Customers using **Electronic Check** have the highest churn rate compared to other payment methods.

---

## 💼 Business Recommendations

* Encourage customers to switch from month-to-month plans to longer-term contracts.
* Provide promotional offers during the first few months of a customer's subscription.
* Bundle Online Security, Tech Support, and Device Protection services to improve retention.
* Investigate why Fiber Optic customers churn at a higher rate and improve service quality if needed.
* Encourage customers to adopt more stable payment methods instead of Electronic Check.

---

## 📁 Project Structure

```text
Customer-Churn-Intelligence/
│
├── Customer Churn Intelligence.ipynb
├── Customer Churn.csv
├── README.md
└── images/                # Optional: Store charts and visualizations
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Customer-Churn-Intelligence.git
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run **Customer Churn Intelligence.ipynb**.

---

## 📊 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Insight Generation
* Customer Behavior Analysis
* Python Data Analysis

---

## 📌 Conclusion

This project demonstrates how exploratory data analysis can uncover the primary drivers of customer churn. The findings provide valuable business insights that can help organizations improve customer satisfaction, increase retention, and make data-driven decisions.

---

### ⭐ If you found this project helpful, consider giving the repository a star!
