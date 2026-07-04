# Power Transformer in Machine Learning

This project demonstrates how to use **Power Transformer** techniques to improve the distribution of numerical features before training a Machine Learning model.

## 📌 Overview

In this notebook, I explored two popular power transformation methods:

- Box-Cox Transformation
- Yeo-Johnson Transformation

The transformed data is then used to train a **Linear Regression** model, and the performance is compared with the original data.

## 📂 Dataset

- Concrete Strength Dataset
- Target Column: `Strength`

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📖 What I Learned

- Data preprocessing using PowerTransformer
- Difference between Box-Cox and Yeo-Johnson transformations
- Training a Linear Regression model
- Model evaluation using Cross Validation (R² Score)
- Comparing feature distributions before and after transformation

## 📊 Project Workflow

1. Load the dataset
2. Explore the data
3. Split into training and testing sets
4. Train Linear Regression on original data
5. Apply Box-Cox transformation
6. Train and evaluate the model
7. Apply Yeo-Johnson transformation
8. Compare model performance
9. Visualize feature distributions before and after transformation

## 🚀 Results

The notebook compares model performance before and after applying Power Transformations using Cross Validation (R² Score).

## 📁 Repository Structure

```
├── powTransformer.ipynb
├── concrete_data.csv
└── README.md
```

## 📌 Note

This project is part of my Machine Learning learning journey, where I practice different preprocessing techniques and understand their impact on model performance.

---
⭐ Feel free to explore the notebook and share your suggestions!