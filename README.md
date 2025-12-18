# 🚀 Startup Finance Dataset (50 Startups)

This repository contains a **startup finance dataset** and a Jupyter Notebook (`startupDB.ipynb`) used to analyze startup spending patterns and **predict profit using machine learning**.

The project is suitable for **data analysis, linear regression practice, and beginner-to-intermediate ML portfolios**.

---

## 📌 Project Overview

The goal of this project is to understand how different types of spending affect a startup’s profitability. Using historical financial data from startups, we analyze relationships between expenditures and profit and build regression models to make predictions.

---

## 📊 Dataset Description

This dataset is commonly known as the **50 Startups Dataset**.

* Each row represents **one startup company**
* The dataset focuses on **spending data and resulting profit**
* The primary machine learning task is **profit prediction**

---

## 🔑 Dataset Columns

| Column Name         | Description                                        |
| ------------------- | -------------------------------------------------- |
| **R&D Spend**       | Amount spent on research and development           |
| **Administration**  | Administrative and operational expenses            |
| **Marketing Spend** | Marketing and advertising costs                    |
| **State**           | Location of the startup (categorical variable)     |
| **Profit**          | Profit earned by the startup (**target variable**) |

---

## 🛠️ Technologies Used

* Python 3
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📥 Required Imports

```python
pip install numpy
pip install scikit-learn
pip install scipy

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error
from scipy.stats import skew , kurtosis
```

---

## ▶️ How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/Blckworld/startup-finance-dataset.git
cd startup-finance-dataset
```

### 2. Open the Notebook

```bash
jupyter notebook startupDB.ipynb
```

### 3. Load the Dataset

```python
df = pd.read_csv('data/50_Startups.csv')
df.head()
```

---

## 📈 Analysis Performed

* Exploratory Data Analysis (EDA)
* Correlation analysis
* Encoding categorical variables (`State`)
* Feature selection
* Linear Regression modeling
* Model evaluation using R² and RMSE

---

## 🤖 Machine Learning Objective

**Target Variable:** `Profit`

**Features Used:**

* R&D Spend
* Marketing Spend
* Administration (evaluated and optionally removed)
* State (encoded)

The notebook demonstrates how removing less impactful features can improve model performance.

---

## 📜 License

This project is licensed for **educational and learning purposes**.

You are free to:

* Use the dataset
* Modify the code
* Share the project

---

## ⭐ Acknowledgments

* 50 Startups Dataset
* Scikit-learn documentation
* Open-source data science community

