# 🐼 Pandas Complete Revision & Hands-on Data Analysis

Welcome to my **Pandas Revision Repository**! 🚀  
This repository contains structured, beginner-to-advanced notes, practical implementations, and real-world dataset analyses using **Python Pandas** across **21 sequential Jupyter Notebooks**.

---

## 📚 Topics Covered

### 1. Core Data Structures & Inspection
* **Introduction & Data Structures** – `Series` (1D labeled array) and `DataFrame` (2D tabular structure).
* **Data Inspection Methods** – `head()`, `tail()`, `shape`, `info()`, and `describe()`.
* **Index Management** – Customizing and resetting indices using `set_index()`, `reset_index()`, and `rename()`.

### 2. Data Fetching, Filtering & Sorting
* **Row & Column Selection** – Direct column indexing `[]`, label-based `.loc[]`, and integer position-based `.iloc[]`.
* **Conditional Filtering** – Boolean masking with single and multiple conditions (`&`, `|`) and membership filtering with `isin()`.
* **Sorting & Frequency Analysis** – `value_counts()` and `sort_values(ascending=...)` along with the `inplace` parameter.

### 3. Data Cleaning & Preprocessing
* **Handling Duplicates** – Identifying and removing duplicate records with `drop_duplicates()`.
* **Handling Missing Values** – Detecting, filling, and dropping null/sentinel values (`-1` to `np.nan`) using `replace()`, `fillna()`, and `dropna()`.

### 4. Grouping, Reshaping & Visualization
* **Grouping & Aggregation** – Splitting, applying functions, and combining data using `groupby()`.
* **Pivot Tables** – Multi-level data summarization and cross-tabulation with `pivot_table()`.
* **Data Visualization** – Quick exploratory plotting directly using Pandas `.plot()`.

---

## 📊 Datasets Used
Real-world datasets analyzed across these notebooks[cite: 7]:
* `matches.csv` & `deliveries.csv` – IPL match & ball-by-ball statistics (e.g., death-overs strike rate analysis)[cite: 3, 7].
* `indian_food.csv` – Indian cuisine dataset (data cleaning & multi-index pivot tables)[cite: 5, 7].
* `Fortune_500.csv` – Corporate revenue & ranking analysis (`groupby` operations)[cite: 7].

---

## 📂 Repository Structure
```text
PANDAS/
├── deliveries.csv
├── Fortune_500.csv
├── indian_food.csv
├── matches.csv
├── part1.ipynb
├── part2.ipynb
├── ...
├── part21.ipynb
└── README.md
