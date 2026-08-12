# SuperStore Sales Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Excel](https://img.shields.io/badge/Data-Excel-green)
![Project Type](https://img.shields.io/badge/Project-Data%20Analytics-blue)

##  Project Overview

The **SuperStore Sales Analysis Dashboard** is an interactive Power BI project created to analyze sales, profit, customers, products, regions, and order performance.

The project uses the **Sample Superstore** dataset and transforms raw transactional data into meaningful business insights through KPIs, charts, filters, and interactive visualizations.

This project demonstrates practical skills in **data cleaning, data modeling, DAX, data visualization, and business analysis**.

---

##  Objectives

- Analyze overall sales and profit performance.
- Track orders, quantity sold, and customer activity.
- Identify the best-performing categories and sub-categories.
- Compare sales and profit across regions and customer segments.
- Analyze sales trends over time.
- Understand the impact of discounts on profitability.
- Build an interactive and user-friendly Power BI dashboard.
- Generate actionable business insights from sales data.

---

##  Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and KPI calculations |
| **Microsoft Excel** | Source dataset |
| **GitHub** | Project documentation and version control |

---

##  Project Files

```text
SuperStore-Sales-Analysis/
│
├── SuperStore112.pbix
├── Superstore112.xlsx
└── README.md
```

### File Description

- **SuperStore112.pbix** — Interactive Power BI dashboard.
- **Superstore112.xlsx** — Source Superstore dataset.
- **README.md** — Project documentation.

---

##  Dataset

The main dataset contains **9,994 transaction records** and **21 columns** covering sales orders from **2014 to 2017**.

### Important Columns

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date when the order was placed |
| Ship Date | Date when the order was shipped |
| Ship Mode | Shipping method |
| Customer ID | Unique customer identifier |
| Customer Name | Customer name |
| Segment | Customer segment |
| Country | Country |
| City | Customer city |
| State | Customer state |
| Region | Sales region |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Product name |
| Sales | Sales amount |
| Quantity | Number of units sold |
| Discount | Discount applied |
| Profit | Profit generated |

---

##  Key Business Metrics

Based on the provided dataset:

| KPI | Value |
|---|---:|
| **Total Sales** | $2.30M |
| **Total Profit** | $286.40K |
| **Total Orders** | 5,009 |
| **Total Quantity** | 37,873 |
| **Customers** | 793 |
| **Profit Margin** | 12.47% |
| **Data Period** | 2014–2017 |
| **Transactions** | 9,994 |

> KPI values may vary slightly depending on the measures and filters applied inside Power BI.

---

##  Dashboard Features

The Power BI dashboard focuses on the following analytical areas:

### 1. KPI Overview

Provides a quick summary of:

- Total Sales
- Total Orders
- Total Profit
- Total Quantity
- Profit Margin
- Average Order Value

### 2. Sales Analysis

Analyzes:

- Sales trends over time
- Sales by category
- Sales by sub-category
- Sales by region
- Sales by customer segment

### 3. Profit Analysis

Helps identify:

- Most profitable categories
- Most profitable sub-categories
- Regional profitability
- Profit trends
- Low-profit or loss-making products

### 4. Customer Analysis

Examines:

- Customer segments
- Customer contribution to sales
- Order activity
- Regional customer performance

### 5. Product Analysis

Provides insights into:

- Product categories
- Sub-categories
- Top-performing products
- Sales and profit contribution

### 6. Interactive Filters

Users can explore the dashboard using filters/slicers such as:

- Year
- Region
- Category
- Sub-Category
- Segment
- Ship Mode

---

##  Example DAX Measures

### Total Sales

```DAX
Total Sales = SUM('Sample - Superstore'[Sales])
```

### Total Profit

```DAX
Total Profit = SUM('Sample - Superstore'[Profit])
```

### Total Orders

```DAX
Total Orders = DISTINCTCOUNT('Sample - Superstore'[Order ID])
```

### Total Quantity

```DAX
Total Quantity = SUM('Sample - Superstore'[Quantity])
```

### Profit Margin

```DAX
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

### Average Order Value

```DAX
Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)
```

---

##  Key Insights

- **Technology** is the highest-sales product category, generating approximately **$836K** in sales.
- **Furniture** contributes approximately **$742K** in sales.
- **Office Supplies** contributes approximately **$719K** in sales.
- The business generated approximately **$286K in total profit**.
- Overall profit margin is approximately **12.47%**.
- The dataset contains sales activity across **East, West, Central, and South** regions.
- The **Consumer** segment is one of the major customer groups and can be compared with Corporate and Home Office segments for performance analysis.
- Product-level analysis can help identify products with strong sales but weak profitability, especially where discounts are high.

---

##  Business Recommendations

1. **Focus on high-profit products**  
   Increase visibility and promotions for products that generate strong profit margins.

2. **Monitor discount levels**  
   Analyze products and regions where high discounts reduce profitability.

3. **Improve low-performing categories**  
   Investigate products with low sales or negative profit and consider pricing or inventory changes.

4. **Strengthen regional strategies**  
   Compare regional sales and profit performance to identify opportunities for growth.

5. **Target customer segments**  
   Create segment-specific offers based on purchasing behavior.

6. **Use time-based analysis**  
   Identify seasonal sales patterns and plan campaigns around high-demand periods.

---

##  Data Preparation

The data preparation workflow includes:

1. Importing the Excel dataset into Power BI.
2. Checking data types.
3. Handling missing or inconsistent values.
4. Formatting date columns.
5. Validating numerical fields.
6. Creating calculated measures using DAX.
7. Building relationships/model structure where required.
8. Creating visuals and interactive filters.
9. Validating KPI calculations against the source data.

---

##  Analytical Skills Demonstrated

This project demonstrates practical beginner-to-intermediate **Data Analyst** skills:

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Data Modeling
- DAX
- KPI Development
- Business Intelligence
- Data Visualization
- Dashboard Design
- Business Insights
- Storytelling with Data

---

##  How to Use This Project

### Step 1 — Download the Repository

Clone or download this GitHub repository.

### Step 2 — Open the Power BI File

Open:

```text
SuperStore112.pbix
```

using **Microsoft Power BI Desktop**.

### Step 3 — Check the Data Source

If Power BI asks for the Excel source, select:

```text
Superstore112.xlsx
```

### Step 4 — Explore the Dashboard

Use the available slicers and visual interactions to analyze sales, profit, customers, products, and regions.

### Step 5 — Refresh the Data

After making changes to the Excel source, use **Refresh** in Power BI to update the dashboard.

---

##  Dashboard Preview

Add screenshots of your Power BI dashboard here:

```text
![Dashboard Preview](https://postimg.cc/n9K0Bm76)
```

Recommended screenshots:

- Dashboard overview
- Sales analysis
- Profit analysis
- Product/category analysis

---

##  Project Learning Outcomes

Through this project, I practiced:

- Working with real-world transactional data.
- Creating meaningful business KPIs.
- Writing DAX measures.
- Designing interactive Power BI reports.
- Finding business trends and patterns.
- Communicating analytical insights through visualization.

---

##  Author

**Shaik Sirajuddin**

Data Analyst | Power BI | SQL | Excel | Python

---

##  If You Like This Project

If this project is useful or helpful, consider giving the repository a ** Star** on GitHub.

---

##  License

This project is created for **educational, portfolio, and data analytics practice purposes**.
