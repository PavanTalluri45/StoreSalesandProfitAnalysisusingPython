# Store Sales and Profit Analysis using Python

## 📌 Introduction

This project performs **exploratory data analysis (EDA)** on a retail superstore dataset to uncover insights about sales performance and profitability. Using Python and interactive visualizations, the analysis identifies trends across time, product categories, sub-categories, and customer segments.

The goal of this project is to help businesses make **data-driven decisions** to optimize operations, pricing, marketing strategies, and overall revenue growth.


## Project Overview

The notebook performs:

* Data loading and inspection
* Data preprocessing and feature engineering
* Sales analysis (monthly, category, sub-category)
* Profit analysis (monthly, category, sub-category)
* Sales vs Profit comparison by customer segment
* Sales-to-Profit ratio analysis

Interactive charts are generated using **Plotly** for better visualization and business interpretation.



## Features

✔ Descriptive statistical analysis
✔ Time-based feature engineering (Month, Year, Day of Week)
✔ Monthly sales trend visualization
✔ Monthly profit trend visualization
✔ Category-wise sales and profit breakdown
✔ Sub-category performance analysis
✔ Customer segment analysis
✔ Sales-to-Profit ratio calculation

---

## Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **Plotly Express** – Interactive visualizations
* **Plotly Graph Objects** – Advanced visualizations
* **Jupyter Notebook**


## Project Workflow

### 1) Data Loading

* Imported dataset using Pandas
* Displayed first few rows
* Generated descriptive statistics

### 2) Data Preprocessing

* Converted `Order Date` and `Ship Date` to datetime
* Created:

  * `Order Month`
  * `Order Year`
  * `Order Day of Week`

### 3) Sales Analysis

* Monthly Sales Trend (Line Chart)
* Sales by Category (Donut Chart)
* Sales by Sub-Category (Bar Chart)

### 4) Profit Analysis

* Monthly Profit Trend (Line Chart)
* Profit by Category (Donut Chart)
* Profit by Sub-Category (Bar Chart)

### 5) Segment Analysis

* Sales & Profit comparison by Segment
* Sales-to-Profit Ratio calculation

---

## 📈 Key Insights

* Sales and profit vary significantly across months.
* Some categories generate high sales but lower profit margins.
* Consumer segment generates higher total profits.
* Corporate segment shows a better Sales-to-Profit efficiency ratio.
* Certain sub-categories may require pricing or cost optimization.

