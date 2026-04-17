
📌 Project Title
**COVID-19 Data Analysis using Python (Pandas, Seaborn, Matplotlib)**

## 📖 Project Overview

This project analyzes a COVID-19 dataset to examine confirmed, death, and recovered cases across different regions. Using Python libraries like Pandas, Seaborn, and Matplotlib, the data was cleaned, processed, and visualized. Key operations included handling missing values, grouping data, filtering records, and sorting for insights. The project demonstrates fundamental data analysis and visualization skills applied to real-world data.


---

## 🎯 Key Features

* 📂 Data Loading from CSV
* 🧹 Data Cleaning & Preprocessing
* 🔍 Missing Value Detection
* 📊 Data Visualization (Heatmaps)
* 🧮 Grouping & Aggregation
* 🔎 Filtering Records
* 🔃 Sorting Data
* 🌍 Region-wise Analysis

---

## 📂 Dataset Description

The dataset contains:

* **Region**
* **Confirmed**
* **Deaths**
* **Recovered**

---

## ⚙️ Project Workflow

### Step 1: Import Libraries

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
```

### Step 2: Load Dataset

```python
df = pd.read_csv("Covid_19_data.csv")
```

### Step 3: Data Inspection

```python
df.count()
df.isnull().sum()
```

### Step 4: Missing Values Visualization

```python
sns.heatmap(df.isnull())
plt.show()
```

---

## 📊 Key Operations

### Filtering

```python
df = df[df['Confirmed'] >= 10]
```

### Grouping

```python
df.groupby('Region')[['Confirmed', 'Deaths', 'Recovered']].sum()
```

### Sorting

```python
df.sort_values(by='Confirmed')
df.sort_values(by='Recovered', ascending=False)
```

---

## 🛠️ Technologies Used

### 🔹 Python Libraries

#### 1. Pandas

```python
import pandas as pd
```

* `pd.read_csv()` → Load dataset
* `df.count()` → Count non-null values
* `df.isnull().sum()` → Detect missing values
* `df.groupby()` → Group data
* `df.sort_values()` → Sort data

---

#### 2. Seaborn

```python
import seaborn as sns
```

* `sns.heatmap()` → Visualize missing values

---

#### 3. Matplotlib

```python
import matplotlib.pyplot as plt
```

* `plt.show()` → Display plots

---
## 📚 Key Learnings

* Data cleaning and preprocessing
* Handling missing values
* Data filtering and sorting
* Grouping and aggregation
* Data visualization basics

---

## 🚀 Future Enhancements

* Advanced visualizations
* Time-series analysis
* Interactive dashboards
* Machine learning predictions

---

## 📌 Conclusion

This project demonstrates how Python tools can be used to analyze real-world datasets and extract meaningful insights about COVID-19 trends.

---
## 👩‍💻 Author

**Pureti Sri Uma Maheswari**
Aspiring Data Analyst

