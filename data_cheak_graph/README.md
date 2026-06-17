
---

# README 2 — data_check_graph.ipynb

```markdown
# Missing Value Analysis and Data Quality Assessment

## Project Overview

This project focuses on data quality assessment by identifying and visualizing missing values within a dataset. The notebook demonstrates fundamental data preprocessing techniques that are essential before performing machine learning or advanced analytics.

The analysis is performed on a Loan Payments dataset and includes null value detection, missing percentage calculation, and visual inspection using heatmaps.

---

## Objectives

- Load and inspect dataset
- Identify missing values
- Calculate missing data percentage
- Measure dataset completeness
- Visualize missing data patterns
- Prepare data for preprocessing

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset

### Loan Payments Dataset

The dataset contains loan-related information and is used to analyze:

- Missing values
- Data completeness
- Data quality issues

---

## Analysis Workflow

### 1. Data Loading

```python
dataset = pd.read_csv("Loan payments data.csv")