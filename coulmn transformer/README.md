# 🚀 Column Transformer in Machine Learning

This project demonstrates how to preprocess different types of features using **Scikit-learn's ColumnTransformer**. It covers handling missing values, encoding categorical variables, and combining multiple preprocessing steps into a single pipeline.

## 📌 Project Overview

Data preprocessing is one of the most important steps in a Machine Learning workflow. Instead of manually transforming each column separately, **ColumnTransformer** allows multiple preprocessing techniques to be applied efficiently in a single step.

This notebook compares two approaches:

- Manual preprocessing (traditional method)
- Preprocessing using `ColumnTransformer` (recommended approach)

---

## 📂 Dataset

The notebook uses a sample dataset:

- **covid_toy.csv**

### Features

| Feature | Type | Preprocessing |
|---------|------|---------------|
| Age | Numerical | No transformation |
| Fever | Numerical | Missing Value Imputation |
| Cough | Ordinal Categorical | Ordinal Encoding |
| Gender | Nominal Categorical | One-Hot Encoding |
| City | Nominal Categorical | One-Hot Encoding |
| Has Covid | Target Variable | Prediction Label |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 📚 Concepts Covered

- Train-Test Split
- Handling Missing Values
- Simple Imputer
- Ordinal Encoding
- One-Hot Encoding
- Feature Concatenation
- ColumnTransformer
- Data Preprocessing Pipeline

---

## 📖 Workflow

### 1️⃣ Load Dataset

- Import the required libraries.
- Read the dataset using Pandas.

### 2️⃣ Split the Dataset

- Separate features and target.
- Perform Train-Test Split.

### 3️⃣ Manual Preprocessing

The notebook first preprocesses each feature separately:

- Impute missing values in **Fever**
- Apply **Ordinal Encoding** on **Cough**
- Apply **One-Hot Encoding** on **Gender** and **City**
- Extract numerical feature (**Age**)
- Concatenate all transformed features

---

### 4️⃣ Using ColumnTransformer

Instead of manually preprocessing every column, a single `ColumnTransformer` is created that performs:

- Simple Imputer → Fever
- Ordinal Encoder → Cough
- OneHotEncoder → Gender & City
- Pass Through → Remaining Numerical Columns

This approach makes preprocessing cleaner, scalable, and production-ready.

---

## 📁 Project Structure

```
ColumnTransformer/
│
├── columntrans.ipynb
├── covid_toy.csv
└── README.md
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### Navigate to the project

```bash
cd your-repository
```

### Install dependencies

```bash
pip install numpy pandas scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
columntrans.ipynb
```

---

## 📸 Notebook Demonstrates

- Manual Feature Engineering
- Missing Value Imputation
- Ordinal Encoding
- One-Hot Encoding
- Combining Features
- Efficient preprocessing using ColumnTransformer

---

## 💡 Key Learning

Using **ColumnTransformer** helps:

- Reduce repetitive code
- Improve readability
- Avoid preprocessing mistakes
- Create reusable preprocessing pipelines
- Simplify deployment of Machine Learning models

---

## 📌 Future Improvements

- Integrate preprocessing with a Machine Learning model
- Create a complete Scikit-learn Pipeline
- Perform Model Evaluation
- Add Cross Validation
- Save preprocessing pipeline using Joblib

---

## 👩‍💻 Author

**Rakhi Kumari**

- GitHub: https://github.com/rakhi05
- LinkedIn: https://www.linkedin.com/in/rakhi-kumari2007

---

⭐ If you found this project helpful, consider giving it a star!