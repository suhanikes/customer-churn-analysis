# Customer Churn Analysis

## 📌 Project Overview

This project analyzes customer churn to identify **high-risk customer segments, churn drivers, and revenue exposure**.

The analysis combines **SQL and Python** to clean, transform, analyze, and visualize customer, subscription, and support data. The goal is to convert customer-level data into actionable insights that can support **targeted retention strategies and revenue protection**.

---

## 🎯 Business Objectives

The project aims to answer the following questions:

- What is the overall customer churn rate?
- Which plans and contract types have the highest churn?
- Which customer segments represent the greatest revenue risk?
- Which customer groups have the highest customer lifetime value (CLTV)?
- What are the major reasons customers cancel?
- Does customer satisfaction (CSAT) strongly differentiate churn?
- Which customer segments should be prioritized for retention?

---

## 📊 Dataset

The project contains data from **10,000 customers** across multiple related tables.

### Key Tables

#### Customer
Contains demographic and geographic information:

- Customer ID
- Customer Name
- Country
- State
- Gender
- Date of Birth

#### Subscription
Contains subscription and financial information:

- Customer ID
- Plan Type
- Contract Type
- Subscription Start Date
- Cancellation Date
- Monthly Charges
- CLTV
- Churn Score
- Cancellation Reason

#### Support
Contains customer support information:

- Customer ID
- Complaint Date
- Escalations
- CSAT Score
- Customer Comments

---

## 🛠️ Tools & Technologies

- **Python**
- **SQL**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **MySQL / SQLite**
- **Jupyter Notebook**

---

## 🔄 Analysis Workflow

```text
Raw Customer Data
        ↓
Data Cleaning & Standardization
        ↓
Data Transformation & Feature Engineering
        ↓
SQL-Based KPI Analysis
        ↓
Python Exploratory Data Analysis
        ↓
Customer Segmentation
        ↓
Churn & Revenue Risk Analysis
        ↓
Business Insights
        ↓
Retention Recommendations
