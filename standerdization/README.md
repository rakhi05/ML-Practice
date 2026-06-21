# 📊 Feature Scaling with StandardScaler

## 📌 Project Overview

This project demonstrates the importance of **Feature Scaling** in Machine Learning using **StandardScaler** from Scikit-learn.

The notebook explores how scaling transforms feature distributions, affects data visualization, influences model performance, and handles datasets with varying feature ranges. It also compares machine learning models trained on scaled and unscaled data.

The project uses the **Social Network Ads Dataset** and includes practical examples of applying Standard Scaling before training classification models.

---

## 🚀 Objectives

* Understand the concept of Feature Scaling
* Learn how StandardScaler works
* Compare data before and after scaling
* Visualize the effect of scaling on feature distributions
* Evaluate model performance with and without scaling
* Analyze the impact of outliers on scaling

---

## 🛠️ Technologies Used

* Python 3
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Project Structure

```text
├── day24.ipynb
├── Social_Network_Ads.csv
└── README.md
```

---

## 📊 Dataset Information

Dataset: **Social Network Ads Dataset**

Features:

* Age
* EstimatedSalary

Target Variable:

* Purchased

The dataset is used to predict whether a customer purchased a product based on age and estimated salary.

---

## 🔍 Workflow

### 1. Data Loading & Preprocessing

* Load dataset using Pandas
* Select relevant features
* Prepare target variable

### 2. Train-Test Split

* Split dataset into training and testing sets
* Preserve unseen data for evaluation

### 3. Standard Scaling

Apply StandardScaler to:

* Learn feature statistics from training data
* Transform training data
* Transform testing data

### 4. Visualization

Compare:

* Feature distributions before scaling
* Feature distributions after scaling
* Scatter plots before and after scaling
* KDE plots for scaled and unscaled data

### 5. Model Comparison

Models used:

#### Logistic Regression

* Without Scaling
* With Standard Scaling

#### Decision Tree Classifier

* Without Scaling
* With Standard Scaling

Performance is evaluated using Accuracy Score.

### 6. Outlier Analysis

* Artificial outliers are added to the dataset
* Effect of outliers on scaling is visualized
* Demonstrates how extreme values influence feature transformation

---

## 📈 Key Concepts Covered

* Feature Scaling
* Standardization
* Mean and Standard Deviation
* Data Distribution
* Logistic Regression
* Decision Tree Classification
* Accuracy Evaluation
* Outlier Impact Analysis

---

## 🎯 Learning Outcomes

This project demonstrates:

* Why feature scaling is important
* When StandardScaler should be used
* Effect of scaling on machine learning algorithms
* Visual comparison of scaled vs unscaled features
* Influence of outliers on standardized data

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
day24.ipynb
```

Run all cells sequentially.

---

## 📚 Machine Learning Concepts Practiced

* Data Preprocessing
* Feature Scaling
* StandardScaler
* Logistic Regression
* Decision Tree Classifier
* Model Evaluation
* Outlier Analysis

---

## 📜 License

This project is intended for educational and learning purposes.

---

## 👩‍💻 Author

**Rakhi kumari**

B.Tech Computer Science Student

Exploring Data Science, Machine Learning, Artificial Intelligence, and Data Engineering.
