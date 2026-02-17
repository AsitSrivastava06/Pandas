# 📊 Experiment 9 – Study of Pandas Library

A comprehensive implementation of Pandas fundamentals demonstrating structured data manipulation, analysis, and real-world tabular data processing in Python.
---

## 📘 Course Information

- **Course:** Python Programming Laboratory  
- **Experiment No:** 9  
- **Title:** Study and Implementation of Pandas Data Analysis Operations  
- **Student Name:** Asit Kumar Srivastava  

---

## 🎯 Aim

To study and implement various Pandas operations including data structures, data manipulation, filtering, aggregation, and basic data analysis techniques.

---

## 📖 Objectives

- Understand Pandas Series and DataFrame structures
- Perform data selection and filtering
- Apply aggregation and statistical functions
- Handle missing data
- Perform basic data analysis operations
- Manipulate rows and columns efficiently

---

## 🧠 Theory

Pandas is an open-source Python library used for data manipulation and analysis.  
It provides powerful data structures:

- **Series** → One-dimensional labeled array  
- **DataFrame** → Two-dimensional labeled data structure  

Pandas allows:

- Fast and efficient data handling
- Data cleaning and preprocessing
- Filtering and transformation
- Aggregation and grouping
- Reading and writing data (CSV, Excel, etc.)

Pandas is widely used in:
- Data Science
- Machine Learning
- Business Analytics
- Research and Scientific Analysis

---

## ✨ Key Concepts Implemented

- Creating Series
- Creating DataFrames
- Data selection using `.loc[]` and `.iloc[]`
- Filtering data
- Aggregation (`sum()`, `mean()`, `max()`, `min()`)
- Sorting values
- Handling missing values
- Column manipulation

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- Jupyter Notebook (Google Colab)

---

## ▶️ Usage

Open the notebook file:

```bash
Experiment_9.ipynb
```

Run all cells sequentially to observe:

- DataFrame creation
- Data filtering
- Statistical analysis
- Aggregation results

---

## 💻 Sample Implementation

```python
import pandas as pd

# Creating a DataFrame
data = {
    "Name": ["A", "B", "C", "D"],
    "Marks": [85, 90, 78, 88]
}

df = pd.DataFrame(data)

print("DataFrame:")
print(df)

# Basic operations
print("Average Marks:", df["Marks"].mean())
print("Maximum Marks:", df["Marks"].max())
print("Sorted Data:")
print(df.sort_values(by="Marks"))
```

---

## 📊 Learning Outcomes

After completing this experiment, I have:

- Understood Pandas data structures
- Performed efficient data filtering and manipulation
- Applied aggregation functions
- Gained foundational knowledge in data analysis
- Improved analytical thinking using Python

---

## ⚡ Pandas vs Python Lists

| Feature | Python Lists | Pandas DataFrame |
|----------|--------------|------------------|
| Data Structure | Basic | Structured (Tabular) |
| Data Filtering | Manual | Built-in Methods |
| Aggregation | Manual Loops | Built-in Functions |
| Handling Missing Data | Difficult | Easy |

---

## 🚀 Future Enhancements

- Importing data from CSV files
- Data visualization using Matplotlib
- GroupBy operations
- Advanced filtering techniques
- Mini data analysis project

---

## 🏁 Conclusion

This experiment successfully demonstrates the implementation of Pandas for structured data handling and analysis. Pandas simplifies data manipulation and provides powerful tools for efficient and scalable data analysis in Python.

---

## 👨‍💻 Author

**Asit Kumar Srivastava**  
Electronics & Telecommunication Engineering  
Python & Data Analysis Enthusiast  

---
