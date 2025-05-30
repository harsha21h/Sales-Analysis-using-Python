# 🛍️ Sales Data Analysis using Python

## 📌 Project Objective

To analyze a retail sales dataset and determine which customer segments spend more on shopping. The analysis provides insights across multiple demographics such as **Gender**, **Age Group**, **State**, **Occupation**, **Product Category**, and **Marital Status**.

---

## 🧠 Key Questions Answered

- Who spends more money based on **Gender**?
- Which **Age Group** contributes the most to sales?
- Which **State** shows the highest customer spend?
- How does **Occupation** influence spending?
- Which **Product Categories** are the top-performing?
- Are **Married or Single** individuals spending more?

---

## 📁 Dataset

- Format: CSV <a href="https://github.com/harsha21h/Sales-Analysis-using-Python/blob/main/sales_data.csv">Data Set</a>
- Contains fields such as Customer ID, Gender, Age, State, Product Category, Marital Status, and Purchase Amount.

---

## ⚙️ Process Overview

### 📥 Data Preprocessing

- Loaded dataset using `pandas`
- Dropped unnecessary columns: `Status`, `Unnamed: 1`
- Handled null values in the `Amount` column
- Renamed `Marital_Status` to `Marital`
- Replaced values:
  - `Marital`: `0 ➝ Single`, `1 ➝ Married`
  - `Gender`: `F ➝ Female`, `M ➝ Male`

### 📊 Data Analysis & Visualization

- Used `seaborn` to visualize:
  - Gender distribution
  - Spending distribution by all categorical fields
- Grouped and aggregated data for:
  - Gender
  - Age Group
  - State
  - Occupation
  - Product Category
  - Marital Status

---

## 📉 Tools & Libraries Used

<img width="654" alt="sales py" src="https://github.com/user-attachments/assets/d6644c50-5fd6-4598-9baa-7ee536d8d732" />


- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 📌 Key Insights

- **Females** tend to spend more than males.
- Customers in the **26–35 age group** show the highest spending.
- **Maharashtra** leads in customer spending among all states.
- **Healthcare and IT professionals** are top spenders.
- **Clothing and Food** are the top product categories.
- **Married individuals** spend more on average compared to singles.
