# 📊 Task 12 – Missing Value Identification

## Veda Technology – Data Analytics Internship

This project was completed as part of the **Veda Technology Data Analytics Internship – Task 12**.

The main objective of this task is to identify, analyze, and summarize missing values in a dataset using Python and Pandas.

An interactive dashboard was also developed using Plotly and ipywidgets to visually analyze missing data and explore the dataset using filters.

---

## 🎯 Objective

The objectives of this project are:

- Identify missing values in the dataset
- Count missing values column-wise
- Calculate missing-value percentages
- Identify rows containing missing values
- Create a missing-value summary
- Visualize missing values using charts
- Understand the risks of blindly deleting rows
- Build an interactive dashboard for data exploration

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Plotly
- ipywidgets
- OpenPyXL
- Microsoft Excel
- GitHub

---

## 📂 Dataset

A custom dataset was created for this project.

The dataset contains information such as:

- Order ID
- Order Date
- Customer Name
- Age
- Gender
- Region
- Category
- Sales
- Rating
- Month

Missing values were intentionally included in selected columns to demonstrate missing-data identification and analysis.

---

## 🔍 Missing Value Analysis

The project performs:

```python
df.isnull().sum()
