# Customer Shopping Behavior Analysis — Data Analytics Project

## Project Overview

This project focuses on analyzing customer shopping behavior to uncover purchasing patterns, customer segments, and factors influencing subscription decisions.

The objective was to transform raw customer transaction data into meaningful business insights using a complete analytics workflow involving **Python, SQL, Power BI, and Machine Learning**.

The project covers the complete data analytics lifecycle:

* Data cleaning and preprocessing
* Exploratory data analysis
* Business analysis using SQL
* Interactive dashboard development
* Customer subscription prediction using machine learning

---

# Business Objectives

The analysis aims to answer key business questions:

* Which customer groups generate the highest revenue?
* How do purchasing patterns differ across customer segments?
* Do discounts influence customer behavior?
* Which products and categories perform best?
* What factors are associated with customer subscriptions?
* Can we predict whether a customer is likely to subscribe?

---

# Tools & Technologies

| Tool                   | Purpose                                 |
| ---------------------- | --------------------------------------- |
| Python (Pandas, NumPy) | Data cleaning and feature engineering   |
| Matplotlib & Seaborn   | Exploratory data visualization          |
| SQL                    | Business analysis and customer insights |
| Power BI               | Interactive dashboard creation          |
| Scikit-learn           | Machine learning model development      |

---

# Project Workflow

```
Raw Customer Data
        |
        ↓
Data Cleaning & Preparation (Python)
        |
        ↓
Exploratory Data Analysis
        |
        ↓
Business Analysis (SQL)
        |
        ↓
Power BI Dashboard
        |
        ↓
Machine Learning Prediction Model
```

---

# Data Preparation & Analysis (Python)

The dataset was cleaned and prepared using Python.

Key preprocessing steps:

* Loaded and inspected customer transaction data
* Checked and handled missing values
* Imputed missing review ratings using category-level median values
* Standardized column names for easier analysis
* Removed redundant fields
* Created additional analytical features:

  * Customer age groups
  * Purchase frequency in days

---

# SQL Business Analysis

SQL queries were used to answer business-focused questions such as:

* Revenue comparison between customer groups
* Customer spending behavior
* Discount usage analysis
* Top-performing products
* Customer loyalty segmentation
* Subscription behavior analysis

Examples of insights explored:

* Which products receive the highest ratings?
* Which customer segments contribute the most revenue?
* How does purchase frequency relate to customer value?

---

# Power BI Dashboard

An interactive dashboard was created to present key business insights.

Dashboard sections include:

* Customer demographics overview
* Sales and revenue analysis
* Product performance
* Subscription trends
* Purchasing behavior patterns

The dashboard helps convert analytical findings into business-friendly visual insights.

---

# Machine Learning Model

A classification model was developed to predict customer subscription status.

### Model Used:

**Random Forest Classifier**

### Objective:

Predict whether a customer is likely to subscribe based on:

* Purchase amount
* Previous purchases
* Customer demographics
* Shopping preferences
* Purchase frequency
* Discount behavior

### Model Evaluation:

Metrics used:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Results:

* Accuracy: ~81%
* F1-score (Subscriber class): ~0.72

Feature importance analysis showed that variables such as:

* Discount usage
* Purchase history
* Purchase amount

had a stronger relationship with subscription prediction.

---

# Key Insights

Some important findings from the analysis:

* Customer purchase behavior varies significantly across segments.
* Discount usage appears strongly associated with subscription behavior.
* Previous purchase history is an important indicator of customer engagement.
* Customer spending patterns provide useful signals for predicting subscription likelihood.

---

# 👩‍💻 About This Project

This project demonstrates practical skills required for a Data Analyst role:

* Data cleaning
* Exploratory analysis
* SQL querying
* Dashboard development
* Business storytelling
* Basic machine learning

The goal was to build an end-to-end analytics workflow that connects technical analysis with real business decisions.
