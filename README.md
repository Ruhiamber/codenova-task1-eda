# CodeNova AI/ML Internship - Task 1: Exploratory Data Analysis (EDA)

## 📌 Project Overview
This repository contains the Exploratory Data Analysis (EDA) for **Task 1** of the **CodeNova AI/ML Internship (Batch 01)**. The objective of this project is to analyze a Kaggle dataset containing over 9,000 records to extract meaningful insights, evaluate data quality, analyze column distributions, and inspect feature relationships.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Environment:** Google Colab / Jupyter Notebook
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

---

## 📊 Summary of Analysis & Insights

1. **Dataset Structure & Inspection:**
   * Loaded raw dataset (`kaggle-raw.csv` / `kaggle-preprocessed.csv`) consisting of **9,158 records**.
   * Inspected column types, schema, and overall dataset statistics using `df.info()` and `df.describe()`.

2. **Data Quality & Missing Values:**
   * Evaluated data completeness; the dataset is exceptionally clean with almost **0 missing values** across all columns (only 2 missing values found in `Type_of_file`).

3. **Categorical Distribution:**
   * Analyzed file categories and observed that **CSV** is the most dominant file type in the dataset (5,772+ entries), followed by 'other' and various combination types.
   * Visualized top file formats using Seaborn bar charts.

4. **Numerical Feature Distribution:**
   * Analyzed key numerical features such as `Upvotes`, `No_of_files`, and `Usability`.
   * Discovered that `Upvotes` exhibits a heavy **right-skewed distribution**, showing that a small percentage of datasets receive high engagement while most have modest engagement.

5. **Correlation Analysis:**
   * Generated a feature correlation heatmap.
   * Identified minimal linear correlation between features (e.g., `No_of_files` vs `Upvotes` at ~0.00), demonstrating feature independence among numerical variables.

---

## 🚀 How to Run the Notebook
1. Open Google Colab or your local Jupyter Notebook environment.
2. Clone this repository or download the `.ipynb` file.
3. Upload the dataset archive (`archive.zip`) and extract it using `!unzip /archive.zip`.
4. Execute all code cells sequentially.
