# TASK5-PYTHON
# Task 5: Data Analysis on CSV Files

## 📌 Objective

Analyze sales data using **Pandas** and generate basic insights +
charts.

------------------------------------------------------------------------

## 📁 Files Included

-   `sales.csv` --- Sample sales dataset\
-   `analysis.py` --- Python script for data analysis\
-   `README.md` --- Documentation (this file)

------------------------------------------------------------------------

## 🛠 Tools Used

-   Python\
-   Pandas\
-   Matplotlib\
-   VS Code / Jupyter Notebook / Colab

------------------------------------------------------------------------

## 🚀 Steps to Run

### 1️⃣ Install required libraries

``` bash
pip install pandas matplotlib
```

### 2️⃣ Ensure `sales.csv` is in the same folder as your Python file.

### 3️⃣ Run the analysis script:

``` bash
python analysis.py
```

------------------------------------------------------------------------

## 📊 What the Script Does

### ✔ 1. Reads CSV File

``` python
df = pd.read_csv('sales.csv')
```

### ✔ 2. Displays:

-   First 5 rows\
-   Data info (types, null values)\
-   Statistical summary

### ✔ 3. Performs Groupby

``` python
df.groupby('Category')['Sales'].sum()
```

### ✔ 4. Generates Bar Chart

Shows total sales per category.

------------------------------------------------------------------------

## 📈 Output Example

-   Total Sales by Category\
-   Insights from describe()\
-   Clean chart visualizing category-wise sales

------------------------------------------------------------------------

## 💡 Interview Questions Covered

1.  What is Pandas used for?\
2.  What is a DataFrame?\
3.  How to read a CSV file?\
4.  What is groupby()?\
5.  Filtering rows\
6.  Difference between loc\[\] and iloc\[\]

------------------------------------------------------------------------

## 👩‍💻 Author

Generated automatically as per user request.
