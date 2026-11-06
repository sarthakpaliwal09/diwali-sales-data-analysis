# 🛍️ Diwali Sales Data Analysis

An exploratory data analysis (EDA) project using **Python**, **Pandas**, **Matplotlib**, and **Seaborn** to analyze customer purchasing behavior during Diwali and uncover key sales insights to optimize marketing and inventory strategies.

---

## 📌 Project Overview
Understanding customer demographics and purchasing patterns is crucial for retail businesses, especially during high-volume festive seasons like Diwali. This project analyzes a customer sales dataset to answer key business questions:
* Who are the most valuable customers in terms of gender and age?
* Which states and zones generate the highest revenue?
* What are the most popular product categories and buyer occupations?

---

## 📊 Dataset Features
The cleaned dataset contains **11,239 rows** and **13 columns** after preprocessing:
* **User_ID & Cust_name**: Unique customer identifiers and names.
* **Product_ID & Product_Category**: Details on the items purchased.
* **Gender, Age, & Age Group**: Customer demographic details.
* **Marital_Status**: Customer marital status.
* **State & Zone**: Geographic location of the buyers.
* **Occupation**: Professional background of the customers.
* **Orders & Amount**: Quantity ordered and total purchase amount.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

---

## 🔍 Key Steps & Methodology

1. **Data Inspection & Cleaning:**
   * Loaded the dataset using `pandas` with appropriate encoding (`unicode_escape`).
   * Dropped redundant/unnamed columns (`Status`, `unnamed1`).
   * Handled missing values by dropping null rows in the `Amount` column.
   * Converted data types (e.g., floating-point amounts to integers) for accurate aggregation.
2. **Exploratory Data Analysis & Visualization:**
   * **Gender Analysis:** Explored order frequency and total purchasing power across genders using bar plots and count plots.
   * **Age Demographics:** Analyzed spending habits across different age brackets, segmented by gender.
   * **Geographical Analysis:** Identified top-performing states and regions driving total orders and sales revenue.
   * **Product & Occupational Insights:** Examined popular product categories and customer occupations.

---

## 📈 Key Insights & Findings

* **Gender Dominance:** Female buyers account for a significantly higher share of total orders and overall spending compared to male buyers.
* **Age Group:** The **26–35 age group** contributes the highest volume of sales and total revenue.
* **Top States:** States such as Uttar Pradesh, Maharashtra, and Karnataka lead in total transaction volume and revenue generation.

---

