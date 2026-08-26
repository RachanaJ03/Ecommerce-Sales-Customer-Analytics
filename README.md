# 🛒 E-Commerce Customer & Order Analytics

## 📌 Project Overview

This project analyzes e-commerce customer and order data to understand purchasing behavior, order trends, customer engagement, repeat purchases, and retention patterns.

The project uses **Python, Pandas, SQL, and Power BI** to transform raw data into actionable business insights.

---

## 🎯 Business Objectives

The main objectives of this project are:

* Analyze overall order activity
* Identify monthly order trends
* Analyze order status distribution
* Understand geographic order patterns
* Identify repeat and one-time customers
* Analyze customer purchasing frequency
* Measure 30/60/90-day repeat-purchase behavior
* Segment customers based on engagement
* Build an interactive Power BI dashboard

---

## 🗂️ Dataset

The project contains three datasets:

### Customers

Contains customer information including:

* `customer_id`
* `country`
* `signup_date`

### Orders

Contains order information including:

* `order_id`
* `customer_id`
* `order_date`
* `status`

### Products

Contains product catalog information including:

* `product_id`
* `product_name`
* `category`

> **Note:** The available orders dataset does not contain `product_id`, quantity, price, or revenue fields. Therefore, the analysis focuses on order, customer, geographic, engagement, and retention analytics rather than revenue or product-sales analysis.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **SQL**
* **Power BI**
* **Jupyter Notebook**
* **Git & GitHub**

---

## 🔄 Project Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Data Validation
   ↓
Data Integration
   ↓
Exploratory Data Analysis
   ↓
Customer Analysis
   ↓
Retention Analysis
   ↓
Customer Segmentation
   ↓
SQL Analysis
   ↓
Power BI Dashboard
```

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Checked dataset dimensions
* Inspected column names and data types
* Checked missing values
* Checked duplicate records
* Converted date columns to datetime format
* Validated customer IDs
* Joined customer and order data
* Created date-based analytical features
* Prepared processed datasets for Power BI

---

## 📊 Analysis Performed

### Order Analytics

* Total orders
* Completed orders
* Order status distribution
* Monthly order trends
* Orders by country
* Geographic order activity

### Customer Analytics

* Registered customers
* Active customers
* One-time customers
* Repeat customers
* Repeat customer rate
* Customer order frequency
* Top customers by order frequency

### Retention & Engagement

* 30-day repeat behavior
* 60-day repeat behavior
* 90-day repeat behavior
* Customer recency
* Customer frequency
* Customer engagement segmentation

---

## 📈 Power BI Dashboard

The Power BI dashboard includes:

* Total Orders KPI
* Total Customers KPI
* Repeat Customer Rate KPI
* Completed Orders KPI
* Monthly Order Trend
* Orders by Country
* Order Status Distribution
* Customer Engagement Segments
* Customer Signup Trend
* Top Customers
* Interactive slicers

---

## 📁 Project Structure

```text
ecommerce-customer-order-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── ecommerce_dashboard.pbix
│
└── README.md
```


## 🚀 Future Improvements

Future versions of the project could include:

* Product-level order analysis
* Revenue and profit analysis
* Average Order Value
* Product/category performance
* Customer Lifetime Value
* Churn prediction
* RFM scoring with monetary value
* Automated Power BI data refresh

---

## 👩‍💻 Author

**Rachana Jogale**

B.Tech Computer Science & Engineering

**Skills:** Python | SQL | Power BI | Pandas | Data Analytics
