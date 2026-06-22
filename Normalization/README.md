# 📊 Data Normalization using Min-Max Scaling

## 📌 Project Overview

This project demonstrates **Data Normalization** using the **Min-Max Scaling** technique in Machine Learning. The notebook explores how feature scaling transforms data into a common range while preserving the relationships between data points.

Using the **Wine Dataset**, the project visualizes feature distributions before and after normalization and highlights the impact of scaling on machine learning preprocessing.

---

## 🎯 Objectives

* Understand the concept of Data Normalization
* Learn how Min-Max Scaling works
* Scale features into a fixed range (0 to 1)
* Compare data distributions before and after normalization
* Visualize the effect of scaling using scatter plots and KDE plots
* Prepare data for machine learning algorithms

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Project Structure

```text
├── Normalization.ipynb
├── wine_data.csv
└── README.md
```

---

## 📊 Dataset Information

Dataset: **Wine Dataset**

Features Used:

* Alcohol
* Malic Acid

Target Variable:

* Class Label

The dataset contains chemical properties of wines and is commonly used for classification and preprocessing demonstrations.

---

## 🔍 Workflow

### 1. Data Loading

* Load the Wine Dataset using Pandas
* Select relevant features and target variable

### 2. Data Exploration

* Visualize feature distributions using KDE plots
* Analyze the relationship between features using scatter plots

### 3. Train-Test Split

* Split the dataset into training and testing sets
* Maintain data integrity for model evaluation

### 4. Min-Max Scaling

Apply **MinMaxScaler** to:

* Learn minimum and maximum values from training data
* Transform training data
* Transform testing data

### 5. Visualization

Compare data before and after normalization using:

* Scatter Plots
* KDE (Kernel Density Estimation) Plots
* Feature Distribution Analysis

### 6. Statistical Comparison

Analyze descriptive statistics before and after scaling to understand the effect of normalization.

---

## 📈 Key Concepts Covered

* Data Preprocessing
* Feature Scaling
* Data Normalization
* Min-Max Scaling
* Train-Test Split
* Data Visualization
* KDE Plots
* Scatter Plots

---

## 📚 What is Min-Max Scaling?

Min-Max Scaling transforms features into a fixed range, typically **0 to 1**.

### Formula

```text
X_scaled = (X - Xmin) / (Xmax - Xmin)
```

Where:

* X = Original Value
* Xmin = Minimum Value
* Xmax = Maximum Value

---

## 🚀 Learning Outcomes

By completing this project, you will understand:

* Why normalization is important in Machine Learning
* How Min-Max Scaling transforms feature values
* The difference between scaled and unscaled data
* How scaling improves data consistency for model training
* Best practices for preprocessing numerical features

---

## ▶️ How to Run

### Clone Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open Notebook

```text
Normalization.ipynb
```

Run all cells sequentially.

---

## 📊 Sample Visualizations

The notebook includes:

* Feature Distribution Plots
* KDE Curves Before and After Scaling
* Scatter Plot Comparison
* Statistical Summary Tables

---

## 📖 Machine Learning Concepts Practiced

* Data Cleaning & Preparation
* Feature Engineering
* Normalization
* MinMaxScaler
* Exploratory Data Analysis (EDA)
* Data Visualization

---

## 📜 License

This project is created for educational and learning purposes.

---

## 👩‍💻 Author

**Rakhi kumari**

B.Tech Computer Science Engineering Student

Exploring Data Science, Machine Learning, Artificial Intelligence, and Data Engineering. 🚀

---

⭐ If you found this project helpful, consider giving the repository a star!
