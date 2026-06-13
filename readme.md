````markdown
# 📊 Customer Churn Prediction & Revenue Risk Analysis

> An end-to-end Data Analytics, Machine Learning, SQL, and Power BI project that predicts customer churn, identifies high-risk customers, explains the reasons behind churn using Explainable AI (SHAP), and provides actionable business insights to reduce revenue loss.

---

## 📑 Table of Contents

- Project Overview
- Business Problem
- Business Objectives
- Solution Architecture
- Technologies Used
- Dataset
- Project Workflow
- Machine Learning Pipeline
- SQL Analysis
- Explainable AI (SHAP)
- Power BI Dashboard
- Key Business Insights
- Business Recommendations
- Business Impact (ROI)
- Project Structure
- Dashboard Preview
- How to Run
- Future Improvements
- Skills Demonstrated
- Contact

---

# 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Losing existing customers directly impacts recurring revenue and increases customer acquisition costs.

This project develops an end-to-end Customer Churn Prediction System that combines:

- SQL for business analysis
- Python for data cleaning and machine learning
- XGBoost for churn prediction
- SHAP for model explainability
- Power BI for executive dashboards

The solution helps businesses identify customers likely to churn before they leave, understand the reasons behind churn, estimate revenue at risk, and support proactive customer retention strategies.

---

# 🎯 Business Problem

The company was experiencing approximately **5% monthly customer churn**, leading to significant recurring revenue loss.

Without a predictive system, customer retention teams could only react after customers had already left.

### Business Challenges

- High monthly churn rate
- Increasing customer acquisition cost
- No early warning system
- Revenue leakage
- Limited understanding of churn drivers

---

# 🎯 Business Objectives

- Predict customer churn before it happens
- Identify high-risk customers
- Estimate Monthly Recurring Revenue (MRR) at risk
- Understand why customers churn
- Prioritize customers for retention campaigns
- Build executive dashboards for business stakeholders

---

# 🏗 Solution Architecture

```text
Customer Dataset
        │
        ▼
Data Cleaning (Python)
        │
        ▼
Feature Engineering
        │
        ▼
SQL Business Analysis
        │
        ▼
Exploratory Data Analysis
        │
        ▼
XGBoost Model
        │
        ▼
SHAP Explainability
        │
        ▼
Business Insights
        │
        ▼
Power BI Dashboard
        │
        ▼
Retention Strategy
````

---

# 🛠 Technologies Used

| Tool             | Purpose                          |
| ---------------- | -------------------------------- |
| Python           | Data Cleaning & Machine Learning |
| Pandas           | Data Analysis                    |
| NumPy            | Numerical Computing              |
| SQL              | Business Analysis                |
| XGBoost          | Churn Prediction                 |
| SHAP             | Explainable AI                   |
| Scikit-learn     | Model Evaluation                 |
| Matplotlib       | Data Visualization               |
| Power BI         | Dashboard & Reporting            |
| Jupyter Notebook | Development Environment          |

---

# 📂 Dataset

The dataset contains customer information including:

* Customer ID
* Gender
* Age
* Subscription Type
* Monthly Charges
* Total Spend
* Contract Type
* Payment Method
* Tenure
* Login Activity
* Support Tickets
* Feature Usage
* Churn Status

---

# 🔄 Project Workflow

### Step 1

Data Collection

↓

### Step 2

Data Cleaning

↓

### Step 3

Feature Engineering

↓

### Step 4

Exploratory Data Analysis

↓

### Step 5

SQL Business Analysis

↓

### Step 6

Machine Learning

↓

### Step 7

SHAP Explainability

↓

### Step 8

Power BI Dashboard

↓

### Step 9

Business Recommendations

---

# 🤖 Machine Learning Pipeline

### Algorithm

**XGBoost Classifier**

### Why XGBoost?

* High prediction accuracy
* Handles missing values
* Excellent for tabular datasets
* Fast training
* Feature importance support

---

## Model Evaluation

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 91.4%   |
| Precision | 88.6%   |
| Recall    | 86.1%   |
| F1 Score  | 87.3%   |
| ROC-AUC   | 94.2%   |

> Replace the above metrics with your actual model performance.

---

# 🗄 SQL Business Analysis

SQL was used to answer business questions such as:

* Overall churn rate
* Monthly revenue at risk
* Customer segmentation
* High-risk customer identification
* Subscription performance
* Customer lifetime trends
* Login activity analysis
* Support ticket analysis
* Revenue distribution

---

# 🔬 Explainable AI (SHAP)

To make predictions transparent and understandable, SHAP (SHapley Additive Explanations) was used.

SHAP helps explain:

* Why a customer is predicted to churn
* Which features contribute most to churn
* Global feature importance
* Individual customer explanations

This enables business stakeholders to trust and act on the model's predictions.

---

# 📊 Power BI Dashboard

The Power BI dashboard provides interactive insights into:

## Executive KPIs

* Total Customers
* Active Customers
* Churn Rate
* Monthly Revenue
* Revenue at Risk

## Business Reports

* Customer Risk Segmentation
* Top 100 High-Risk Customers
* Business Summary
* Feature Importance
* Subscription & Revenue Analysis
* Login Activity vs Churn
* Support Ticket Impact
* Churn by Tenure

---

# 📈 Key Business Insights

* Customers with low login activity are significantly more likely to churn.
* Support ticket frequency strongly correlates with churn probability.
* Customers with shorter tenure exhibit the highest churn rate.
* Premium subscription customers contribute the largest share of revenue at risk.
* High-risk customers can be prioritized for targeted retention campaigns.
* SHAP analysis identifies the most influential factors driving churn.

---

# 💡 Business Recommendations

* Contact high-risk customers before renewal.
* Improve customer onboarding during the first 90 days.
* Increase feature adoption through tutorials.
* Monitor login activity as an early warning signal.
* Reduce support response times.
* Launch personalized retention campaigns.

---

# 💰 Business Impact (ROI)

If the retention strategy successfully saves **10%** of customers identified as high risk:

Example:

```
High Risk Customers = 500

Average Monthly Revenue = $100

Revenue at Risk

500 × $100

=

$50,000/month

Saving only 10%

=

50 customers retained

Recovered Monthly Revenue

=

$5,000

Recovered Annual Revenue

=

$60,000
```

> Replace the example values above with calculations from your own dataset.

---

# 📁 Project Structure

```
Customer-Churn-Prediction/

│
├── data/
│   ├── customer_churn.csv
│
├── notebooks/
│   ├── analysisbypython.ipynb
│
├── dashboard/
│   ├── churn.pbix
│
├── reports/
│   ├── Business_Summary.csv
│   ├── Customer_Risk_Segmentation.csv
│   ├── Top_100_High_Risk_Customers.csv
│   ├── Model_Feature_Importance.csv
│
├── requirements.txt
│
└── README.md
```

---



# ▶ How to Run

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
analysisbypython.ipynb
```

Run all cells to train the model and generate reports.

---

## 4️⃣ Execute SQL Queries

Import the dataset into your SQL database and execute the SQL scripts to generate business reports.

---

## 5️⃣ Open Power BI Dashboard

Open the following file:

```
churn.pbix
```

Refresh the data source if necessary to explore the dashboard.

---

# 🚀 Future Improvements

* Deploy the model using Flask or FastAPI
* Real-time churn prediction
* Automated model retraining
* Customer retention recommendation engine
* Cloud deployment
* Interactive web dashboard

---

# 💼 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* SQL Analytics
* Predictive Modeling
* Feature Engineering
* Machine Learning
* Explainable AI (SHAP)
* Business Intelligence
* Dashboard Development
* Data Visualization
* Business Storytelling
* Revenue Risk Analysis
* Customer Segmentation

---

# 📬 Contact

**Utsav Gangadiya**

📧 Email:utsavgangadiya886@gmail.com

---

## ⭐ If you found this project useful, consider giving it a Star!

```
```
