# SuperStore-EDA
An End-to-End Data Analytics, Data Science &amp; Visualization Project

# Superstore Sales Performance Analysis

## 📌 Overview

This is a complete end-to-end data analytics project focused on analyzing retail sales performance using the **Superstore Dataset**. The project includes:

- Data cleaning and preprocessing using Python
- Exploratory Data Analysis (EDA)
- Basic regression modeling (optional)
- Business insights generation
- Professional dashboard creation using Power BI

The project is designed to simulate a real-world business analytics scenario that integrates data analysis, data science, and data visualization.

---

## 🎯 Objective

To analyze sales and profit data across various product categories, regions, and customer segments in order to uncover actionable insights and present them via an interactive Power BI dashboard.

---

## 🧰 Tools & Technologies Used

### Python (via Google Colab)
- `NumPy` – Numerical operations
- `Pandas` – Data manipulation and cleaning
- `Matplotlib` and `Seaborn` – Static visualizations
- `Scikit-learn` – Basic linear regression model (optional)

### Power BI
- For interactive dashboard development with:
  - KPI Cards
  - Filters/Slicers
  - Bar, Line, Matrix, Donut, and Scatter Charts

---

## 📂 Dataset

- **Name:** Superstore Dataset  
- **Source:** [Kaggle – Superstore Dataset Final](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  
- **Records:** 9,994  
- **Features:** 21  
- **Duration:** 2014 to 2017  
- **Key Columns:**  
  - Order Date, Sales, Profit, Discount  
  - Segment, Region, Category, Sub-Category  
  - Product Name, Quantity, State

This dataset simulates real-world retail business transactions and provides a foundation for generating valuable business insights.

---

## 🔍 Project Workflow

### Step 1: Data Cleaning & Exploration
- Loaded the dataset in Google Colab using ISO-8859–1 encoding to fix UnicodeDecodeError
- Cleaned data: removed duplicates, handled missing values, converted data types
- Performed EDA using Pandas and Seaborn to:
  - Analyze sales and profit by region, category, and sub-category
  - Identify outliers
  - Examine the correlation between discount and profit

### Step 2: Optional Data Science
- Built a simple Linear Regression model to evaluate how discount percentage affects profit
- Visualized Discount vs Profit trends

### Step 3: Dashboard in Power BI
- Created visuals and layout including:
  - KPI Cards (Sales, Profit, Orders, Avg. Discount)
  - Region-wise Profit and Sales (Bar chart)
  - Category & Sub-Category Performance (Matrix)
  - Monthly Sales Trend (Line chart)
  - Segment-wise Sales (Donut chart)
  - Discount vs Profit Impact (Scatter plot)
  - Top 10 Products by Sales (Bar chart)
- Added slicers for Region, Year, and Category to enable interactivity

---

## 📈 Key Insights

- Technology category shows the highest profit margins
- Furniture category underperforms due to frequent discounting
- High discount orders often lead to negative profits
- South region has good sales but lower profit margins
- A small group of products contributes to the majority of sales
- Consumer segment is the largest in both order count and sales

---

## 📎 Deliverables

- `superstore_analysis.ipynb` – Python notebook with all analysis and EDA
- `superstore_dashboard.pbix` – Final Power BI dashboard file
- `summary_report.pdf` – Full documentation of approach, findings, and visual output
- `README.md` – This file

---

## 📌 Conclusion

This project demonstrates how businesses can use data analytics and visualization tools to gain actionable insights from their historical data. By cleaning, analyzing, and visualizing retail sales data:

- Decision-makers can re-evaluate discount strategies
- Identify underperforming product lines
- Focus marketing on profitable regions and segments

The Power BI dashboard serves as an easy-to-use, interactive tool for ongoing performance monitoring and business intelligence.

---

## 📄 License

This project is for educational and portfolio purposes. Dataset used is publicly available on Kaggle.
