# Task 2: Exploratory Data Analysis (EDA)

## Objective

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python.

EDA helps in understanding the structure of the dataset, distributions of variables, relationships between features, patterns, trends, and possible anomalies before applying Machine Learning algorithms.

---

## Dataset

The dataset used for this task is the **Titanic Dataset**.

The dataset contains information about passengers, including:

- Passenger class
- Age
- Gender
- Number of siblings/spouses
- Number of parents/children
- Passenger fare
- Survival status

The dataset is stored in the `dataset/` folder.

---

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab

---

## EDA Techniques Performed

The following Exploratory Data Analysis techniques were performed:

1. Dataset exploration
2. Dataset shape and column analysis
3. Data type analysis
4. Missing-value analysis
5. Descriptive statistics
6. Mean, median and standard deviation
7. Histograms
8. Boxplots
9. Count plots
10. Bivariate analysis
11. Survival analysis
12. Correlation analysis
13. Correlation heatmap
14. Pairplot
15. Skewness analysis
16. Interactive visualization using Plotly
17. Pattern and anomaly identification

---

## Analysis Performed

### 1. Dataset Exploration

The dataset was explored using:

- `head()`
- `shape`
- `columns`
- `dtypes`
- `info()`

This helped understand the size, structure and data types of the dataset.

### 2. Missing-Value Analysis

Missing values were identified using:

```python
df.isnull().sum()
