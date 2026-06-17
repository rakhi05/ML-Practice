# Exploratory Data Analysis (EDA) and Data Visualization using Python

## Project Overview

This project demonstrates Exploratory Data Analysis (EDA) techniques using Python visualization libraries such as Matplotlib and Seaborn. The notebook covers various methods to analyze categorical and numerical data and explores relationships between variables using different statistical plots.

The project uses the famous Titanic dataset along with built-in Seaborn datasets (Tips and Iris) to showcase practical data visualization techniques.

---

## Objectives

- Understand data distributions
- Analyze categorical variables
- Analyze numerical variables
- Identify patterns and trends
- Explore relationships between features
- Learn common visualization techniques used in Data Science

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

### Titanic Dataset
Used for:
- Survival analysis
- Passenger demographics
- Fare distribution
- Class-wise survival patterns

### Tips Dataset
Used for:
- Bill amount vs tip analysis

### Iris Dataset
Used for:
- Feature relationship analysis
- Pairwise visualization

---

## Visualizations Implemented

### 1. Categorical Data Analysis

#### Count Plot
Visualizes frequency distribution of categorical variables.

Examples:
- Survived
- Embarked

```python
sns.countplot(df['Survived'])