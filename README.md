# Pandas Learning Notebook 🐼

## 📌 About the Project

This repository contains my hands-on practice with **Pandas**, a powerful Python library used for data manipulation and analysis.

The notebook explores fundamental Pandas concepts through practical coding examples, including Series, DataFrames, data selection, missing value handling, grouping, merging, and working with CSV and Excel files.

This project is part of my learning journey in Python and Data Analytics, helping me develop practical skills for working with structured datasets.

## 🎯 Objectives

- Understand Pandas Series and DataFrames.
- Learn how to select, add, modify, and delete data.
- Practice handling missing values in datasets.
- Perform data grouping and aggregation.
- Combine datasets using merging and concatenation.
- Read and work with CSV and Excel files.
- Develop a foundation for real-world data analysis.

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**
- **CSV and Excel datasets**

## 📚 Topics Covered

### 1. Pandas Series
- Creating Series from lists, arrays, and dictionaries
- Custom indexing
- Accessing and slicing elements
- Arithmetic operations on Series

### 2. DataFrames
- Creating DataFrames from lists and dictionaries
- Selecting rows and columns
- Adding and deleting columns
- Row selection, addition, and deletion
- Resetting and setting indexes

### 3. Basic DataFrame Operations
- Exploring DataFrame properties
- Understanding axes and indexes
- Inspecting and summarizing data

### 4. Handling Missing Data
- Identifying missing values with `isnull()` and `isna()`
- Removing missing values with `dropna()`
- Replacing missing values with `fillna()`
- Filling missing numerical values using mean and median

### 5. Reading Data Files
- Importing CSV files using `pd.read_csv()`
- Working with Excel files using `pd.read_excel()`
- Inspecting and processing tabular data

### 6. Grouping and Aggregation
- Grouping records using `groupby()`
- Accessing individual groups
- Calculating sum, mean, and standard deviation
- Applying aggregation functions

### 7. Merging and Concatenation
- Combining DataFrames using `merge()`
- Understanding inner, outer, left, and right joins
- Combining datasets using `concat()`
- Concatenating rows and columns

### 8. Date and Time Operations
- Working with Python datetime values
- Creating date ranges
- Converting columns into datetime format

### 9. Descriptive Statistics
- Calculating summary statistics
- Exploring numerical correlations
- Using `describe()` to understand data distributions
- Working with categorical data

## 💻 Sample Code

```python
import pandas as pd

# Create a sample DataFrame
data = {
    "Name": ["Anu", "Rahul", "Meera", "Arun"],
    "Age": [22, 24, 21, 23],
    "Marks": [85, 90, 78, 88]
}

df = pd.DataFrame(data)

# Display the DataFrame
print(df)

# Calculate average marks
print("Average Marks:", df["Marks"].mean())

# Display summary statistics
print(df.describe())
```

## ▶️ How to Run the Notebook

1. Clone or download this repository.
2. Install Python on your computer.
3. Install the required libraries:

   ```bash
   pip install pandas numpy notebook openpyxl
   ```

4. Open a terminal in the project directory.
5. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `pandas_notebook.ipynb` and execute the cells.

You can also upload the notebook to [Google Colab](https://colab.research.google.com/) to run it online.

**Note:** Some notebook cells use sample CSV and Excel files. Make sure the required datasets are available at the file paths used in those cells.

## 🎓 Learning Outcomes

Through this notebook, I am developing practical knowledge of:

- Data manipulation using Pandas
- Data cleaning and missing value treatment
- DataFrame operations and indexing
- Data aggregation and statistical analysis
- Combining multiple datasets
- Working with structured data for analytics

## 🚀 Future Learning

I plan to apply these concepts to real-world datasets and continue improving my skills in data cleaning, exploratory data analysis, visualization, SQL, and Power BI.

## 👩‍💻 Author

**Anagha Sajeev**

Aspiring Data Analyst | Python | Pandas | NumPy | SQL | Power BI

---

⭐ This repository documents my learning progress in Pandas and data analysis. Feedback and suggestions are welcome!
