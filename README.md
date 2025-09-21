# 📊 Data Analysis & Visualization Assignment

## Overview
This project demonstrates loading, analyzing, and visualizing data using **Pandas**, **Matplotlib**, and **Seaborn**.  
The classic **Iris dataset** was used for the analysis.

---

## Tasks Completed
### Task 1: Load & Explore
- Loaded dataset using `sklearn.datasets.load_iris`.
- Inspected first few rows, data types, and missing values (none found).

### Task 2: Basic Analysis
- Generated summary statistics with `.describe()`.
- Grouped data by species (`target`) and computed mean values.
- Observed that **petal length & width are key differentiators** among species.

### Task 3: Visualization
Created 4 customized plots:
1. **Line chart** – Sepal length trends across samples.
2. **Bar chart** – Average petal length per species.
3. **Histogram** – Distribution of sepal width.
4. **Scatter plot** – Sepal length vs petal length (color-coded by species).

---

## Requirements
Install the libraries:
```bash
pip install pandas matplotlib seaborn scikit-learn
