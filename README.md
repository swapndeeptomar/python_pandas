#  Pandas Data Analysis & Practice Project

##  Overview

This repository contains hands-on practice and mini-projects using **Pandas**, focused on real-world data manipulation, cleaning, and analysis.

The project demonstrates key data handling techniques such as:

* Data cleaning
* Handling missing values
* Feature engineering
* Indexing & slicing
* Data transformation

---

##  Tech Stack

* Python 
* Pandas 
* Jupyter Notebook 

---

##  Project Structure

```
python_pandas/
│── Feature_Engineering.ipynb   # Feature creation & transformation
│── practice_pandas.ipynb      # Core pandas practice
│── basic_pandas.py            # Fundamental pandas operations
│── data.csv                   # Custom dataset (practice)
│── nba.csv                    # NBA dataset for analysis
│── Pandas_Project.ipynb       # PAndas Final Project 
│── anime.csv                  # Anime dataset for exploration
│── README.md                  # Project documentation
```

---

##  Key Concepts Covered

### 🔹 Data Loading & Exploration

* Reading CSV files
* Viewing data (`head()`, `info()`, `describe()`)

### 🔹 Data Cleaning

* Handling missing values (`NaN`)
* Filling null values (`fillna`)
* Dropping null values (`dropna`)

### 🔹 Indexing & Selection

* Label-based indexing (`loc`)
* Position-based indexing (`iloc`)
* Setting custom index (`index_col`)

### 🔹 Data Manipulation

* Adding & removing columns
* Dropping rows and columns
* Filtering data using conditions

### 🔹 Feature Engineering

* Creating new columns
* Transforming existing data
* Preparing data for analysis

---

## 📊 Datasets Used

###  NBA Dataset

* Player information
* Team, age, salary analysis

### 🎌 Anime Dataset

* Anime ratings and popularity insights

###  Custom Dataset

* Practice dataset for:

  * Missing values
  * Data cleaning
  * Transformations

---

##  Sample Operations

```python
import pandas as pd

df = pd.read_csv("data.csv", index_col='name')

# Access row
df.loc['John']

# Filter data
df[df['sales'] > 200]

# Handle missing values
df['category'].fillna('Unknown', inplace=True)

# Drop rows
df.drop("Riya", inplace=True)
```

---

##  Learning Outcomes

* Strong understanding of Pandas DataFrame operations
* Ability to clean and preprocess real-world datasets
* Hands-on experience with indexing, slicing, and filtering
* Practical implementation of feature engineering

---

##  Future Improvements

* Add visualization (Matplotlib / Seaborn)
* Perform exploratory data analysis (EDA)
* Build mini data analysis reports
* Integrate with machine learning models

---

##  Contributing

This is a personal learning project, but suggestions and improvements are welcome!

---
