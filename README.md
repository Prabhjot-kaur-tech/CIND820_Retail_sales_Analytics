# Retail Sales Analytics and Customer Purchasing Behaviour Analysis

## CIND 820 – Big Data Analytics Final Project

**Author:** Prabhjot Kaur

**Student ID:** 501409563

**Supervisor:** Dr. Tamer Abdou

Toronto Metropolitan University

---

# Project Overview

This project analyzes customer purchasing behaviour using the Online Retail dataset from the UCI Machine Learning Repository.

The objective is to compare three customer segmentation approaches:

• Descriptive Revenue Baseline

• Rule-Based RFM Segmentation

• K-Means Clustering

The project evaluates both business value and technical performance to identify the most appropriate customer segmentation approach for marketing, customer retention, and business decision-making.

---

# Research Questions

This project addresses the following research questions:

1. Which merchandise products generate the highest revenue?

2. Which countries contribute the highest share of revenue?

3. What monthly sales patterns support inventory planning?

4. How can customers be grouped using Recency, Frequency and Monetary (RFM) values?

5. Which data-quality limitations affect the reliability of the findings?

---

# Dataset

Source:

UCI Machine Learning Repository

Online Retail Dataset

https://archive.ics.uci.edu/ml/datasets/Online+Retail

Dataset Summary

• 541,909 transactions

• December 2010 – December 2011

• 8 variables

• Final cleaned dataset: 524,878 records

• 4,338 unique customers

---

# Project Workflow

Raw Dataset

↓

Data Cleaning & Preparation

↓

Exploratory Data Analysis

↓

Revenue Baseline Analysis

↓

Rule-Based RFM Segmentation

↓

K-Means Clustering

↓

Model Evaluation

↓

Business Recommendations

---
## Notebooks

The project notebooks should be executed in the following order:

1. **_Data_Cleaning_&_Preperation** - Clean raw dataset and prepare new cleaned data file for analysis.
2. **01_Initial_EDA.ipynb** – Initial exploratory data analysis.
3. **02_Business_EDA_&_Analysis.ipynb** – Business-focused exploratory analysis and descriptive analytics.
4.**03_Initial_Result_RFM** -Analysis using RFM .
5. **04_Milestone4_Final_Results_RFM_Baseline_Analysis.ipynb** – Revenue baseline analysis and rule-based RFM segmentation.
6. **04_Milestone4_K_Means_Comparison.ipynb** – K-Means clustering, model evaluation, and comparison.
   
# Repository Structure
CIND820_Retail_sales_Analytics
│
├── data/
├── images/
├── notebooks/
├── reports/
├── README.md
└── requirements.txt

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

  ## Key Findings

- The top 10% of customers generated approximately **61.5%** of total revenue.
- Rule-based RFM segmentation identified five interpretable customer groups based on purchasing behaviour.
- K-Means clustering validated the presence of distinct customer behavioural patterns.
- Rule-based RFM segmentation was selected as the preferred business solution because it provides the best balance between business interpretability and actionable customer insights.

  ## How to Run the Project

### Install Required Packages

```bash
pip install -r requirements.txt
```

### Execute the notebooks in the following order:

1. 01_Initial_EDA.ipynb
2. 02_Business_EDA_&_Analysis.ipynb
3. 02_Data_Cleaning_&_Preperation
4. 03_Initial_Result_RFM
4. 04_Milestone4_Final_Results_RFM_Baseline_Analysis.ipynb
5. 04_Milestone4_K_Means_Comparison.ipynb

   ## References

- Dua, D. & Graff, C. (2019). **Online Retail Dataset**. UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/Online+Retail

  ## Author

**Prabhjot Kaur**

**Student Id**-501409563

CIND 820 – Big Data Analytics

Toronto Metropolitan University

Supervisor: Dr. Tamer Abdou
