# 🏥 Healthcare Data Analysis (EDA) using Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a healthcare dataset to identify patterns, trends, and treatment cost related to different diagnosis.
Multiple datasets were combined and analyzed to gain insights into patient health metrics and outcomes.

The goal of this project is to demonstrate **data cleaning, data merging, visualization, and analytical skills** using Python.

---

## 📊 Dataset Description

The project uses multiple healthcare datasets:

* **patients.csv** – Patient demographic information
* **diagnoses.csv** – Medical diagnosis data
* **labs.csv** – Laboratory test results
* **outcomes.csv** – Patient treatment outcomes

---

## 🛠 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```
healthcare-eda-project
│
├── data
│   ├── patients.csv
│   ├── diagnoses.csv
│   ├── labs.csv
│   └── outcomes.csv
│
├── notebooks
│   └── eda_analysis.ipynb
│
├── images
│   └── plots.png
│
├── README.md
└── requirements.txt
```

---

## 🔧 Project Workflow

### 1. Data Loading

Multiple CSV files were imported using **Pandas**.

### 2. Data Merging

Datasets were joined using **pandas merge()**, similar to SQL joins.

### 3. Data Cleaning

* Handled missing values

### 4. Exploratory Data Analysis

Performed **univariate and bivariate analysis** to understand data distribution and relationships between variables.

### 5. Data Visualization

Visualizations were created using **Matplotlib **.

Example plots:

* Age distribution
* Gender distribution
* Age vs diagnosis
* Cost vs disease

---

## 📈 Key Insights

* Older patients show a higher probability of heart disease.
* Gender differences exist in disease prevalence.
* Certain lab measurements may act as indicators of health risk.

---

## 🚀 Future Improvements

* Build predictive models for heart disease detection
* Deploy dashboard using Streamlit or Power BI
* Add advanced statistical analysis

---


