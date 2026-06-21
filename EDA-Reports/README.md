# Automated EDA Reports using Sweetviz

## Project Overview

This project demonstrates automated Exploratory Data Analysis (EDA) using the Sweetviz library in Python. The objective is to generate detailed data profiling reports, understand dataset characteristics, identify missing values, analyze feature distributions, and explore relationships between variables through interactive HTML reports.

The project includes EDA reports generated for two widely used datasets:

* Titanic Dataset
* Iris Dataset

---

## Objectives

* Perform automated Exploratory Data Analysis (EDA)
* Generate interactive HTML reports
* Analyze feature distributions
* Detect missing values
* Explore feature relationships
* Understand dataset structure and quality
* Practice data profiling techniques used in Data Science workflows

---

## Technologies Used

* Python
* Pandas
* Seaborn
* Sweetviz
* Jupyter Notebook

---

## Datasets Included

### 1. Titanic Dataset

The Titanic dataset contains passenger information such as:

* Passenger ID
* Survival Status
* Passenger Class
* Age
* Gender
* Fare
* Cabin Information
* Embarkation Port

#### Analysis Performed

* Survival Distribution Analysis
* Passenger Demographics Analysis
* Missing Value Detection
* Numerical Feature Statistics
* Feature Associations
* Data Quality Assessment

---

### 2. Iris Dataset

The Iris dataset contains measurements of iris flowers belonging to three species.

#### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* Species

#### Analysis Performed

* Species Distribution Analysis
* Feature Distribution Analysis
* Missing Value Assessment
* Statistical Summary
* Feature Relationship Analysis
* Dataset Quality Evaluation

---

## Project Workflow

### Import Required Libraries

```python
import pandas as pd
import seaborn as sns
import sweetviz as sv
```

### Generate EDA Report

```python
report = sv.analyze(df)
report.show_html("EDA_Report.html")
```

---

## Reports Generated

### Titanic Dataset Report

File:

```text
titanicreport.ipynb
```

Output:

```text
Titanic_EDA_Report.html
```

---

### Iris Dataset Report

File:

```text
irisReport.ipynb
```

Output:

```text
Iris_EDA_Report.html
```

---

## Key Learning Outcomes

Through this project, the following concepts were explored:

* Exploratory Data Analysis (EDA)
* Automated Data Profiling
* Missing Value Analysis
* Feature Distribution Analysis
* Data Quality Assessment
* Dataset Understanding
* Data Visualization Fundamentals

---

## Project Structure

```text
EDA-Reports/
│
├── titanicreport.ipynb
├── irisReport.ipynb
├── README.md
│
├── Titanic_EDA_Report.html
└── Iris_EDA_Report.html
```

---

## Why Sweetviz?

Sweetviz provides:

* Automated dataset profiling
* Interactive visual reports
* Feature comparison and analysis
* Missing value detection
* Correlation and association insights
* Fast exploratory analysis for machine learning projects

---

## Future Enhancements

* Comparative EDA between datasets
* Additional datasets and reports
* Correlation Heatmaps
* Statistical Hypothesis Testing
* Machine Learning Model Development

---

## Author

**Rakhi Kumari**

B.Tech Computer Science & Engineering Student

Passionate about Data Analytics, Machine Learning, and Artificial Intelligence.
