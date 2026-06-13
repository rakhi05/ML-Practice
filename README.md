# Data Quality Analysis using Python

## 📌 Project Overview

This project focuses on **data quality assessment and missing value
analysis** for a loan payment dataset using Python. The notebook
performs exploratory checks to identify missing data, calculate
null-value statistics, and visualize data quality issues through
graphical representations.

The analysis helps in understanding the completeness of the dataset
before applying machine learning, statistical analysis, or business
intelligence workflows.

------------------------------------------------------------------------

## 🚀 Features

-   Load and inspect dataset structure
-   Preview records using `head()` and `tail()`
-   Detect missing values
-   Calculate column-wise null counts
-   Compute missing-value percentages
-   Visualize missing data using heatmaps
-   Perform basic data quality assessment

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python 3
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn

------------------------------------------------------------------------

## 📂 Project Structure

``` text
├── data_check_graph.ipynb
├── Loan payments data.csv
└── README.md
```

------------------------------------------------------------------------

## 📊 Workflow

### 1. Import Required Libraries

``` python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

### 2. Load Dataset

``` python
dataset = pd.read_csv("Loan payments data.csv")
```

### 3. Explore Dataset

-   View first records
-   View last records
-   Check dataset dimensions
-   Understand overall structure

### 4. Missing Value Analysis

``` python
dataset.isnull().sum()
```

The notebook identifies missing values present in each column.

### 5. Missing Value Percentage Calculation

The percentage of missing values is calculated to determine the impact
of incomplete data on analysis.

### 6. Data Visualization

``` python
sns.heatmap(dataset.isnull())
```

Heatmaps provide a clear visual representation of missing values across
the dataset.

------------------------------------------------------------------------

## 📈 Expected Outcomes

-   Better understanding of dataset quality
-   Identification of incomplete records
-   Visualization of missing-value distribution
-   Preparation of data for further preprocessing and machine learning
    tasks

------------------------------------------------------------------------

## ▶️ How to Run

1.  Clone the repository:

``` bash
git clone <repository-url>
```

2.  Install dependencies:

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

3.  Launch Jupyter Notebook:

``` bash
jupyter notebook
```

4.  Open and run:

``` text
data_check_graph.ipynb
```

------------------------------------------------------------------------

## 🎯 Learning Objectives

This project demonstrates:

-   Data inspection techniques
-   Data cleaning fundamentals
-   Missing value analysis
-   Data visualization using Seaborn
-   Exploratory Data Analysis (EDA) basics

------------------------------------------------------------------------

## 📜 License

This project is intended for educational and learning purposes.

------------------------------------------------------------------------

## 👩‍💻 Author

**Rakhi Jha**\
B.Tech Computer Science Student\
Learning Data Analysis, AI/ML, and Data Engineering
