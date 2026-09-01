# 🛒 Flipkart Sales Analysis Dashboard – Power BI

## 📊 Project Overview

The **Flipkart Sales Analysis Dashboard** is an interactive business intelligence project developed using **Microsoft Power BI**. The project analyzes sales transactions, customer behavior, product performance, delivery patterns, returns, and ratings to provide a clear view of overall business performance.

The dashboard transforms raw sales data into meaningful KPIs and interactive visualizations that can help identify profitable products, high-performing categories, customer trends, and operational issues.

---

## 🎯 Project Objectives

- Analyze overall sales and profit performance.
- Track total revenue, total profit, products sold, and orders.
- Identify the most profitable products.
- Compare performance across product categories and sub-categories.
- Analyze customer demographics such as age and gender.
- Understand sales performance across locations and zones.
- Analyze delivery types and order status.
- Identify return patterns and reasons for returned orders.
- Analyze customer ratings.
- Build an interactive and easy-to-understand business dashboard.

---

## 📁 Dataset

The project uses a Flipkart sales dataset containing **133,503 transaction records** and **19 columns**.

### Dataset Columns

| Column | Description |
|---|---|
| OrderDate | Date on which the order was placed |
| OrderID | Unique order identifier |
| Delivery Date | Date on which the order was delivered |
| CustomerID | Customer identifier |
| Customer Age | Age of the customer |
| Customer Gender | Customer gender |
| Location | Customer/order location |
| Zone | Geographical sales zone |
| Delivery Type | Type of delivery selected |
| Product Category | Main product category |
| SubCategory | Product sub-category |
| Product | Product name |
| Unit Price | Original/unit price of the product |
| Shipping Fee | Shipping charge |
| Order Quantity | Quantity ordered |
| Sale Price | Selling price |
| Status | Order status such as Delivered or Returned |
| Reason | Reason for returned orders |
| Rating | Customer rating from 1 to 5 |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculations
- **Microsoft Excel** – Source dataset
- **Data Visualization & Business Intelligence**

---

## 🔄 Data Preparation

The dataset was imported into Power BI and prepared using Power Query.

Key preparation activities included:

- Checking column data types
- Formatting date columns
- Reviewing missing values
- Validating numerical fields
- Checking categorical values
- Preparing fields for analysis
- Creating calculated measures using DAX
- Building relationships/data model required for dashboard analysis

---

## 📌 Key KPIs

The dashboard includes important business KPIs such as:

- **Total Revenue**
- **Total Profit**
- **Total Products Sold**
- **Total Orders**
- Top profitable products
- Sales and profit by category
- Order status and return analysis

---

## 📈 Dashboard Features

### 1. Sales Performance
- Total Revenue
- Total Profit
- Total Orders
- Total Products Sold
- Sales trends

### 2. Product Analysis
- Top profitable products
- Product/category-wise sales
- Sub-category performance
- Product quantity analysis

### 3. Customer Analysis
- Customer age analysis
- Gender-wise performance
- Customer/location analysis

### 4. Delivery Analysis
- Standard vs Express delivery
- Delivery performance
- Zone-wise analysis

### 5. Returns Analysis
- Delivered vs Returned orders
- Return reasons
- Product/category return patterns

### 6. Customer Ratings
- Rating distribution
- Rating by product/category

---

## 🧮 Example DAX Measures

```DAX
Total Products Sold = SUM(Sales[Order Quantity])
```

```DAX
Total Orders = DISTINCTCOUNT(Sales[OrderID])
```

> **Note:** The exact DAX formulas in the `.pbix` file may vary depending on the final data model and measure definitions used in the dashboard.

---

## 💡 Business Insights

The dashboard is designed to help answer questions such as:

- Which products generate the highest profit?
- Which product categories contribute the most to sales?
- How many orders are returned?
- What are the major reasons for returns?
- Which locations/zones perform better?
- Which delivery type is used more frequently?
- How does customer rating vary across products?
- Which customer segments contribute most to sales?

---

## 📂 Repository Structure

```text
Flipkart-Sales-Analysis-PowerBI/
│
├── README.md
│
├── PowerBI/
│   └── Flipkart_Sales_Report.pbix
│
├── Dataset/
│   └── Flipkart Sales Dataset.xlsx
│
├── Dashboard/
│   └── Flipkart_Sales_Dashboard.png
│
└── Documentation/
    └── Project_Report.pdf
```

---

## 🖥️ Dashboard Preview

Add your Power BI dashboard screenshot here:

```markdown
![Flipkart Sales Dashboard](Dashboard/Flipkart_Sales_Dashboard.png)
```

---

## 🚀 Project Outcome

This project demonstrates practical skills in:

- Data cleaning and transformation
- Power BI dashboard development
- DAX calculations
- KPI development
- Data visualization
- Business analysis
- Interactive reporting
- Extracting actionable insights from large datasets

---

## 👩‍💻 Author

**Khushi Chaudhary**

**MCA | Data Analytics & Business Intelligence**

### Skills Demonstrated
`Power BI` `Power Query` `DAX` `Excel` `SQL` `Data Analysis` `Data Visualization`

---

⭐ **If you find this project useful, feel free to explore the repository and dashboard.**
