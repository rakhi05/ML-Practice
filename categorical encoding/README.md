# 📊 Categorical Data Encoding in Machine Learning

## 📌 Project Overview

This project demonstrates how to handle **Categorical Data Encoding** using two commonly used encoding techniques in Machine Learning:

* **Ordinal Encoding** (for ordered categorical features)
* **Label Encoding** (for target variables)

The notebook uses a customer dataset containing educational qualifications and review ratings to transform categorical values into numerical format that can be understood by machine learning algorithms.

---

## 🎯 Objectives

* Understand why categorical data must be encoded
* Apply **Ordinal Encoding** to ordered input features
* Apply **Label Encoding** to target variables
* Split data into training and testing sets
* Prepare categorical data for machine learning models
* Learn best practices for encoding categorical variables

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn

---

## 📂 Project Structure

```text
├── Encoding_cat.ipynb
├── customer.csv
└── README.md
```

---

## 📊 Dataset Information

### Features Used

| Feature   | Type                |
| --------- | ------------------- |
| Review    | Ordinal Categorical |
| Education | Ordinal Categorical |

### Target Variable

| Feature          | Type               |
| ---------------- | ------------------ |
| Purchased/Placed | Binary Categorical |

The dataset contains customer-related information where categorical attributes are converted into machine-learning-friendly numerical values.

---

## 🔍 Workflow

### 1. Import Libraries

Load essential Python libraries:

* NumPy
* Pandas
* Scikit-learn

---

### 2. Load Dataset

Read the dataset using Pandas and select the required columns for encoding.

---

### 3. Feature and Target Separation

Split the dataset into:

* **X (Independent Features)**

  * Review
  * Education

* **y (Target Variable)**

---

### 4. Train-Test Split

Divide the dataset into:

* Training Data (80%)
* Testing Data (20%)

This prevents data leakage and ensures fair model evaluation.

---

### 5. Ordinal Encoding

Apply **OrdinalEncoder** on ordered categorical features.

#### Review Encoding

```text
Poor    → 0
Average → 1
Good    → 2
```

#### Education Encoding

```text
School → 0
UG     → 1
PG     → 2
```

The encoder learns the order of categories and transforms them into meaningful numerical values.

---

### 6. Label Encoding

Apply **LabelEncoder** on the target variable.

Example:

```text
No  → 0
Yes → 1
```

This converts class labels into numerical form required by machine learning algorithms.

---

### 7. Transform Training and Testing Data

The fitted encoders are used to transform both:

* Training Data
* Testing Data

ensuring consistency across the dataset.

---

## 📚 Key Concepts Covered

### Ordinal Encoding

Used when categories have a meaningful order.

Example:

```text
Poor < Average < Good
```

---

### Label Encoding

Used primarily for target variables.

Example:

```text
No  → 0
Yes → 1
```

---

### Train-Test Split

Separates data into training and testing subsets for better model evaluation.

---

## 🚀 Learning Outcomes

By completing this project, you will understand:

* Difference between categorical and numerical data
* Why encoding is necessary in Machine Learning
* When to use Ordinal Encoding
* When to use Label Encoding
* How to prepare categorical features for ML models
* Importance of train-test splitting before preprocessing

---

## ▶️ How to Run

### Clone Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open Notebook

```text
Encoding_cat.ipynb
```

Run all cells sequentially.

---

## 📈 Encoding Techniques Demonstrated

### Ordinal Encoder

Suitable for:

* Education Levels
* Ratings
* Experience Levels
* Customer Satisfaction Scores

### Label Encoder

Suitable for:

* Binary Classification Labels
* Target Variables
* Class Names

---

## 💡 Practical Applications

* Customer Analytics
* Student Performance Prediction
* Employee Classification
* Recommendation Systems
* Classification Problems
* Data Preprocessing Pipelines

---

## 📖 Machine Learning Concepts Practiced

* Data Preprocessing
* Categorical Data Handling
* Feature Engineering
* Ordinal Encoding
* Label Encoding
* Train-Test Split
* Machine Learning Data Preparation

---

## 📜 License

This project is created for educational and learning purposes.

---

## 👩‍💻 Author

**Rakhi kumari**

B.Tech Computer Science Engineering Student

Exploring Machine Learning, Data Science, Artificial Intelligence, and Data Engineering.

---

⭐ If you found this project useful, consider giving the repository a star!
