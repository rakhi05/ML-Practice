---

# 📊 Missing Data Handling using Complete Case Analysis (CCA)

## 📖 Overview

This notebook demonstrates how to handle missing values using **Complete Case Analysis (CCA)** in Python with Pandas.

Complete Case Analysis is one of the simplest techniques for dealing with missing data. It removes all rows containing missing values and keeps only the complete observations for further analysis.

The notebook also compares the data distribution before and after applying CCA to understand its impact on the dataset.

---

## 🎯 Objectives

* Load and explore a dataset.
* Identify missing values.
* Calculate the percentage of missing data.
* Select columns with a small percentage of missing values.
* Apply Complete Case Analysis.
* Compare the dataset before and after removing missing values.
* Visualize the effect of CCA using histograms and density plots.
* Compare categorical feature distributions before and after CCA.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 📂 Dataset

The notebook uses:

```
data_science_job.csv
```

The dataset contains information related to data science jobs and includes both numerical and categorical features with missing values.

---

## 📚 Concepts Covered

* Missing Values
* Complete Case Analysis (CCA)
* Missing Value Percentage
* Data Cleaning
* Data Distribution
* Histograms
* Density Plots
* Categorical Distribution Comparison

---

## ⚙️ Workflow

1. Import required libraries.
2. Load the dataset.
3. Detect missing values.
4. Calculate the percentage of missing data.
5. Select columns with less than 5% missing values.
6. Remove rows containing missing values.
7. Compare dataset dimensions before and after CCA.
8. Visualize numerical feature distributions.
9. Compare categorical feature distributions before and after cleaning.

---

## 📈 Visualizations

The notebook includes:

* Histogram Comparison
* Density Plot Comparison
* Category Distribution Comparison

These visualizations help determine whether removing missing values significantly changes the data distribution.

---

## 💡 Key Learning

Complete Case Analysis is easy to implement and works well when the percentage of missing values is very small. However, it can reduce the dataset size and may introduce bias if the missing data is not random.

---

## 📁 Project Structure

```
📦 Missing-Data-CCA
│── datamissing.ipynb
│── data_science_job.csv
└── README.md
```

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/your-repository.git

cd your-repository

pip install pandas numpy matplotlib

jupyter notebook
```

Open **`datamissing.ipynb`** and run the cells sequentially.

---

## ⭐ Learning Outcome

By completing this notebook, you will understand:

* How to identify missing values.
* When to use Complete Case Analysis.
* Advantages and limitations of CCA.
* How missing value removal affects numerical and categorical data distributions.
* Basic visualization techniques for validating data preprocessing steps.

---
