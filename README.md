# 🏠 Housing Market Data Analysis

## 📊 Project Overview

This project is a comprehensive **Exploratory Data Analysis (EDA)** of a housing market dataset, completed as part of the **Python and Data Analysis Bootcamp** on the **Baobab Platform** — a program organized by **Arizona State University** in partnership with the **Mastercard Foundation**.

The analysis explores relationships between housing features such as square footage, number of bedrooms, location, and price. It also demonstrates key data analysis techniques including data cleaning, feature engineering, and data visualization using Python.

---

## 🎯 Learning Objectives

- Load and explore datasets using **Pandas**
- Handle missing values using **mean** and **median** imputation
- Perform **feature engineering** (e.g., Price per Square Foot)
- Create meaningful **visualizations** with **Matplotlib** and **Seaborn**
- Identify patterns and insights from housing data

---

## 📁 Dataset

**Source:** Bootcamp provided dataset  
**Records:** 500 rows  
**Features:** 11 columns

| Column | Description |
|--------|-------------|
| `House_ID` | Unique identifier for each house |
| `Neighborhood` | Location category (Rural, Urban, Waterfront) |
| `House_Type` | Type of property (Single Family, Condo, Apartment) |
| `SqFt_Living` | Living area in square feet |
| `Bedrooms` | Number of bedrooms |
| `Bathrooms` | Number of bathrooms |
| `Year_Built` | Year the house was built |
| `Distance_to_City_Center` | Distance to city center in miles |
| `Has_Pool` | Binary indicator (1 = yes, 0 = no) |
| `Condition_Score` | Rating from 1-5 |
| `Price` | Sale price in USD |

---

## 🔧 Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computing |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |
| **Google Colab** | Development environment |

---

## 📈 Analysis Steps

### 1. Data Loading & Exploration

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

df = pd.read_csv('housing_market_dataset.csv')


· Examined first 5 and 10 rows
· Checked data types and missing values with df.info()
· Generated descriptive statistics with df.describe()

2. Data Cleaning

Issue Solution
Missing SqFt_Living values Filled with MEAN
Missing Bedrooms values Filled with MEDIAN

3. Feature Engineering

· Price per Square Foot: Price / SqFt_Living
· Status or Premium: Classified houses above the 75th percentile as "premium"

4. Data Visualization

📊 Price Distribution

[Coming soon]

📊 Living Area Distribution

[Coming soon]

📊 Price vs Living Space

[Coming soon]

---

🔍 Key Insights

· Price Distribution: Right-skewed — most houses fall within a moderate price range with a few high-value outliers
· Living Area: Most houses have between 1,500–2,500 sq ft
· Price vs SqFt: Strong positive correlation — larger homes generally command higher prices
· Missing Data: Handled through mean and median imputation

👤 Author

George Abasiumoh

· Data Analyst | Python Developer | AI/ML Researcher 


📄 License

This project is licensed under the MIT License — see the LICENSE file for details.

---

 Acknowledgments

· Arizona State University — Program partner
· Mastercard Foundation — Program sponsor
· Baobab Platform — Learning platform

---

📬 Contact

📧 georgeabasiumoh@gmail.com
🔗 LinkedIn
💻 GitHub
