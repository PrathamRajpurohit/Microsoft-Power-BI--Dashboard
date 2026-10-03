# Microsoft-Power-BI--Dashboard

# 📱 Mobile Sales Analysis Dashboard | Power BI

## 📌 Project Overview

This project is an **interactive Mobile Sales Analysis Dashboard** created using **Microsoft Power BI**.

The dashboard analyzes mobile phone sales data to understand **sales performance, customer behavior, brand performance, payment methods, geographical sales, mobile models, and customer ratings**.

The project uses a dataset containing **3,835 mobile sales transactions** and provides interactive visualizations and KPIs to support data-driven decision-making.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze overall mobile sales performance
* Identify top-performing mobile brands and models
* Analyze units sold across different cities
* Understand customer purchasing behavior
* Analyze different payment methods
* Study customer age distribution
* Analyze customer ratings
* Identify sales trends based on day, month, and year
* Compare mobile brands and models based on sales
* Create an interactive and user-friendly business dashboard

---

## 📊 Dataset

The dataset contains **3,835 records** with the following fields:

| Column           | Description                    |
| ---------------- | ------------------------------ |
| Transaction ID   | Unique ID for each transaction |
| Day              | Day of the transaction         |
| Month            | Month of the transaction       |
| Year             | Year of the transaction        |
| Day Name         | Name of the day                |
| Brand            | Mobile phone brand             |
| Units Sold       | Number of mobile units sold    |
| Price Per Unit   | Price of each mobile unit      |
| Customer Name    | Name of the customer           |
| Customer Age     | Age of the customer            |
| City             | Customer/sales city            |
| Payment Method   | Method used for payment        |
| Customer Ratings | Rating given by the customer   |
| Mobile Model     | Name/model of the mobile phone |

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Microsoft Excel**
* **Data Modeling**
* **Data Visualization**

---

## 🔄 Project Workflow

### 1. Data Import

The mobile sales dataset was imported from an Excel file into Power BI.

### 2. Data Cleaning & Transformation

Using **Power Query**, the data was prepared for analysis by:

* Checking data types
* Cleaning columns
* Handling data inconsistencies
* Preparing date-related fields
* Structuring data for visualization

### 3. Data Modeling

The dataset was structured in Power BI to support analysis across:

* Brands
* Mobile Models
* Cities
* Customers
* Payment Methods
* Dates
* Sales metrics

### 4. DAX Calculations

DAX measures were created to calculate important business metrics such as:

* Total Sales
* Total Units Sold
* Average Selling Price
* Average Customer Rating
* Number of Transactions

### 5. Dashboard Development

Interactive visuals were created using:

* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Pie/Donut Charts
* Tables
* Slicers
* Filters

---

## 📈 Key KPIs

The dashboard focuses on important mobile-sales KPIs such as:

* 💰 **Total Sales**
* 📱 **Total Units Sold**
* 🧾 **Total Transactions**
* 💵 **Average Price Per Unit**
* ⭐ **Average Customer Rating**
* 👥 **Customer Analysis**

---

## 📊 Dashboard Analysis

The dashboard provides analysis of:

### 📱 Brand Analysis

Compare sales performance across different mobile brands and identify the brands with the highest number of units sold.

### 📲 Mobile Model Analysis

Analyze individual mobile models to identify popular and high-performing products.

### 🌍 City-wise Sales Analysis

Analyze sales across different cities and identify locations contributing significantly to mobile sales.

### 💳 Payment Method Analysis

Understand customer preferences for different payment methods, such as:

* UPI
* Credit Card
* Debit Card
* Cash
* Other available payment methods

### 👥 Customer Analysis

Analyze customers based on:

* Customer Age
* Customer Name
* Purchase behavior
* Customer Ratings

### ⭐ Customer Rating Analysis

Analyze customer ratings to understand customer satisfaction and identify highly rated products or brands.

### 📅 Time-based Analysis

Analyze sales based on:

* Day
* Day Name
* Month
* Year

This helps identify sales trends and patterns over time.

---

## 🎛️ Interactive Features

The dashboard allows users to dynamically analyze the data using filters and slicers such as:

* 📅 Year
* 📅 Month
* 🏷️ Brand
* 📱 Mobile Model
* 🌍 City
* 💳 Payment Method
* ⭐ Customer Rating

Users can select different values and instantly analyze the corresponding sales performance.

---

## 📷 Dashboard Preview

### Main Dashboard

Add your Power BI dashboard screenshot here:

```markdown
![Mobile Sales Dashboard](Screenshots/mobile-sales-dashboard.png)
```

---

## 💡 Business Insights

The dashboard can help businesses:

* Identify high-performing mobile brands
* Identify best-selling mobile models
* Understand customer purchasing patterns
* Determine major sales locations
* Understand preferred payment methods
* Monitor customer satisfaction
* Identify sales trends over time
* Make better inventory and sales decisions

---

## 📂 Project Structure

```text
Mobile-Sales-PowerBI/
│
├── 📊 Mobile_Sales_Dashboard.pbix
│
├── 📁 Dataset/
│   └── Mobile_Sales_Data.xlsx
│
├── 📁 Screenshots/
│   └── mobile-sales-dashboard.png
│
└── 📄 README.md
```

---

## 🧮 Example DAX Measures

```DAX
Total Units Sold =
SUM('Mobile Sales'[Units Sold])
```

```DAX
Total Sales =
SUMX(
    'Mobile Sales',
    'Mobile Sales'[Units Sold] *
    'Mobile Sales'[Price Per Unit]
)
```

```DAX
Average Price =
AVERAGE('Mobile Sales'[Price Per Unit])
```

```DAX
Average Rating =
AVERAGE('Mobile Sales'[Customer Ratings])
```

```DAX
Total Transactions =
DISTINCTCOUNT('Mobile Sales'[Transaction ID])
```

> Note: The table name in the DAX formulas should be changed to match the table name in your Power BI file.

---

## 🚀 How to Use the Project

1. Clone or download this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. If required, update the Excel data source path.
4. Refresh the dataset.
5. Use the available slicers and filters to explore the dashboard.
6. Analyze the different sales, customer, brand, city, and payment insights.

---

## 📚 Skills Demonstrated

* **Power BI**
* **Power Query**
* **DAX**
* **Data Cleaning**
* **Data Transformation**
* **Data Modeling**
* **Data Visualization**
* **Exploratory Data Analysis**
* **KPI Development**
* **Business Intelligence**
* **Dashboard Development**
* **Business Data Analysis**

---

## 👨‍💻 Author

**Pratham Rajpurohit**

B.Tech Computer Science & Engineering Student

### ⭐ Project

**Mobile Sales Analysis Dashboard using Power BI**

---

⭐ If you found this project useful, consider giving the repository a star!

👆 [Click Here View Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMzEwYzYzOTYtOWRkNC00ZWM5LTkwM2MtNWE2YmI2YzkzNWY0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
<br><br>
<img src="https://github.com/SatishDhawale/Power_BI_Dashboard/blob/0192a63d87dda50ea2f26bca02ba048dd883b9d1/Dashboard.jpg" alt="Image Description" width="300">
<img src="https://github.com/SatishDhawale/Power_BI_Dashboard/blob/0192a63d87dda50ea2f26bca02ba048dd883b9d1/MTD%20Report.jpg" width="300">
<img src="https://github.com/SatishDhawale/Power_BI_Dashboard/blob/0192a63d87dda50ea2f26bca02ba048dd883b9d1/Same%20Period%20Last%20Year%20report.jpg" alt="Image Description" width="300">
