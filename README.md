# 🛍️ New Year Sales Data Analysis

This project performs an end-to-end analysis of a New Year sales dataset using Python and popular data science libraries. It includes data cleaning, exploratory data analysis (EDA), and visual insights into customer behavior.

---

## 📦 Dataset

- **File**: `New_Year_Sales_Data.csv`
- **Description**: The dataset contains customer transaction records including demographics, product category, occupation, state, and purchase amount.

---

## 🧰 Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Step-by-Step Workflow

### ✅ 1. Import Libraries
Essential libraries like NumPy, Pandas, Matplotlib, and Seaborn are imported.

### ✅ 2. Load & Explore Dataset
- The CSV file is loaded with encoding `latin1`.
- Initial exploration includes checking shape, datatypes, and previewing rows.

### ✅ 3. Data Cleaning
- Null values are identified and handled.
- Unnecessary columns (`Status`, `unnamed1`, `Cust_name`) are dropped.
- `Amount` column is converted to integer type.

### ✅ 4. Summary Overview
- Descriptive statistics are generated.
- Unique value counts for each column are reviewed.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Gender Analysis
- Count of purchases by gender.
- Total purchase amount comparison.

### 🔹 Age Group Analysis
- Most active age groups in purchases.
- Spending trends across age groups.

### 🔹 State Analysis
- Top 10 states by number of orders and total revenue.

### 🔹 Marital Status Analysis
- Purchase behavior based on marital status and gender.

### 🔹 Occupation Analysis
- Count of customers by occupation.
- Revenue contribution by occupation.

### 🔹 Product Category Analysis
- Popular product categories.
- Top revenue-generating product categories.

---

## 📌 Key Insights

- High purchasing customers are typically:
  - Aged between 26–35
  - Female
  - Married
  - From Maharashtra or Karnataka
  - Working in Healthcare or IT sectors

---

## ❓ Further Exploration Questions

1. Which age group contributes most to each product category, and how does it vary by gender?
2. How does spending vary by marital status across age groups?
3. Which states show the highest growth in orders and revenue (requires date)?
4. Are there occupation-based preferences for specific product categories?
5. What's the correlation between age and spending, and does it differ by gender?

---

## 📁 Files Included

- `New Year Sales Data Analysis.ipynb` – Main analysis notebook
- `New_Year_Sales_Data.csv` – Source dataset
- `README.md` – Project summary and documentation

---

## 🚀 How to Run

1. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

2. Open the notebook:
    ```bash
    jupyter notebook "New Year Sales Data Analysis.ipynb"
    ```

3. Follow step-by-step cells and visualize insights.

---

## 📬 Contact

Created by **Krishna Nakrani**  
