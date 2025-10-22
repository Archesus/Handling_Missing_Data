# 🧹 Handling Missing Data in Python

This repository contains multiple Jupyter notebooks that explore **different methods to handle missing (NaN) values** in datasets using Python.  
Missing data is a common issue in real-world datasets, and learning how to handle it properly is a critical step in data preprocessing before applying any machine learning models.

---

## 📘 Project Overview

In this mini-series, I practiced various techniques to **detect, clean, and impute missing values** using both **manual methods** (Pandas) and **automated tools** (Scikit-learn).

Each notebook demonstrates a different approach with practical examples and explanations.

---

## 🧰 Tools & Libraries Used

- **Python**
- **NumPy** — numerical operations  
- **Pandas** — handling and manipulating tabular data  
- **Scikit-learn (sklearn)** — using `SimpleImputer` for missing value imputation  

---

## 📂 Notebooks Included

| Notebook | Description |
|-----------|--------------|
| **1️⃣ Handling_missing_data_dropna().ipynb** | Demonstrates removing rows or columns containing NaN values using `dropna()` |
| **2️⃣ Handling_missing_data_fillna().ipynb** | Shows how to replace missing values using `fillna()` with **mean**, **median**, and **mode** |
| **3️⃣ Handling_missing_data_sklearn.ipynb** | Uses **`SimpleImputer`** from scikit-learn to automatically fill missing values for numeric and categorical columns using **for loop**|

---

## 🧠 Key Learnings

- How to **identify missing data** using:
  ```python
  df.isnull().sum()
  ```
  Difference between dropping and imputing data

When to use:

dropna() → when the missing data is small or irrelevant

fillna() → when the data can be logically filled (e.g., mean, median, mode)

SimpleImputer → for automated, scalable solutions

Filling categorical columns using loops or most frequent category

How improper handling of NaN values can affect model accuracy

🚀 How to Run

Clone this repository
```bash
git clone https://github.com/yourusername/handling-missing-data.git
```

Navigate to the project directory
```bash
cd handling-missing-data
```

Install the required dependencies
```bash
pip install pandas numpy scikit-learn
```

Open the notebooks
```bash
jupyter notebook
```

and explore each method step by step.

📚 Future Scope

Compare the effect of different imputation methods on ML model accuracy

Explore KNNImputer and IterativeImputer for more advanced handling

Build a small project on data preprocessing pipeline using ColumnTransformer

🧑‍💻 Author

Anurag Kumar
Frontend Developer | UI/UX Designer | Aspiring AI Engineer
📍 GitHub: Archesus

⭐ If you found this helpful, consider giving it a star on GitHub!
