# Supermarket Sales Analytics & Interactive Dashboard

An interactive supermarket sales analytics project that transforms raw transaction data into meaningful business insights using Excel, Julius AI, HTML, CSS, JavaScript, and Chart.js.

## 📊 Project Overview

The **Supermarket Sales Analytics & Interactive Dashboard** analyzes supermarket transaction data to understand sales performance across branches, cities, products, categories, months, payment methods, and customer segments.

The project follows a complete data analytics workflow:

**Dataset → Data Cleaning → Data Validation → AI-Assisted Analysis → Visualization → Interactive Dashboard → Business Insights → Recommendations**

The project was developed independently as a practical data analytics and business intelligence project.

---

## 🎯 Project Objectives

- Analyze supermarket sales transaction data.
- Clean and validate the dataset.
- Calculate important sales KPIs.
- Compare performance across branches and cities.
- Identify high-revenue products and categories.
- Analyze monthly sales trends.
- Understand payment method usage.
- Analyze customer segments.
- Build an interactive dashboard.
- Generate useful business insights and recommendations.

---

## 📁 Dataset

The dataset contains **40 verified supermarket sales transactions** covering:

- **Locations:** Hyderabad, Vijayawada, Visakhapatnam
- **Branches:** A, B, C
- **Period:** January 1, 2025 – March 12, 2025
- **Product Categories:** Electronics, Clothing, Food
- **Customer Types:** Member, Normal
- **Payment Methods:** Credit Card, UPI, Cash

### Main Dataset Fields

- Invoice ID
- Date
- Branch
- City
- Customer Type
- Gender
- Product Category
- Product
- Quantity
- Unit Price
- Payment Method
- Total Sales

Additional calculated fields were also used for validation and analysis.

---

## 🧹 Data Cleaning & Validation

The dataset was prepared before performing the analysis.

### Validation performed

The sales value was checked using:

**Total Sales = Quantity × Unit Price**

A `Sales_Check` field was used to verify the calculated sales amount against the recorded sales value.

The dataset contains **40 verified orders**, and the sales calculations were validated before dashboard development.

---

## 📈 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Sales | ₹1,86,100 |
| Total Orders | 40 |
| Total Quantity | 201 |
| Average Order Value | ₹4,652.50 |

### AOV Calculation

**Average Order Value = Total Sales ÷ Total Orders**

**₹1,86,100 ÷ 40 = ₹4,652.50**

---

## 🏢 Branch Analysis

Sales by branch:

| Branch | Sales |
|---|---:|
| Branch A | ₹89,400 |
| Branch C | ₹53,600 |
| Branch B | ₹43,100 |

Branch A recorded the highest sales value in the dataset.

---

## 🌆 City Analysis

Sales by city:

| City | Sales |
|---|---:|
| Hyderabad | ₹89,400 |
| Visakhapatnam | ₹53,600 |
| Vijayawada | ₹43,100 |

Hyderabad recorded the highest sales value in the analyzed dataset.

---

## 🛍️ Product Analysis

The products were analyzed based on revenue generated.

| Product | Sales |
|---|---:|
| Monitor | ₹48,000 |
| Rice | ₹28,800 |
| Jeans | ₹23,400 |
| Dress | ₹17,600 |
| Headphones | ₹16,500 |

The **Monitor** generated the highest revenue among the products analyzed.

---

## 📦 Category Analysis

| Category | Sales |
|---|---:|
| Electronics | ₹89,400 |
| Clothing | ₹53,600 |
| Food | ₹43,100 |

Electronics generated the highest sales value in the dataset.

---

## 📅 Monthly Sales Analysis

| Month | Sales |
|---|---:|
| January | ₹76,150 |
| February | ₹50,800 |
| March | ₹59,150 |

January recorded the highest sales among the available monthly data.

**Note:** March contains data only up to March 12, 2025, so it represents a partial month.

---

## 💳 Payment Method Analysis

| Payment Method | Sales |
|---|---:|
| Credit Card | ₹86,600 |
| UPI | ₹63,050 |
| Cash | ₹36,450 |

Credit Card transactions generated the highest sales value in the dataset.

---

## 👥 Customer Analysis

### Customer Type

| Customer Type | Sales |
|---|---:|
| Normal | ₹106,500 |
| Member | ₹79,600 |

### Gender

| Gender | Sales |
|---|---:|
| Male | ₹106,300 |
| Female | ₹79,800 |

These values describe the distribution observed in this dataset and should not be treated as general customer behavior beyond the analyzed data.

---

## 🤖 AI-Assisted Analysis

**Julius AI** was used as an AI-assisted analytical tool to explore the supermarket dataset and identify useful patterns and relationships.

It supported the analysis and helped with data exploration and visualization.

The overall project was not generated solely by Julius AI. The final dashboard and project structure were developed as part of the complete analytics workflow.

### Julius Dashboard

🔗 **[Open Live Julius Dashboard](https://steady-spatula-hzz.julius.site)**

---

## 🖥️ Interactive Dashboard

The project includes a web-based interactive dashboard developed using:

- HTML
- CSS
- JavaScript
- Chart.js

### Dashboard Filters

Users can interact with the data using filters for:

- Date
- City
- Branch
- Category
- Product
- Gender
- Customer Type
- Payment Method

### Dashboard KPIs

The dashboard displays:

- Total Sales
- Total Orders
- Total Quantity
- Average Order Value

### Dashboard Visualizations

The dashboard includes:

1. Branch Revenue Comparison
2. Sales by City
3. Top 10 Products by Sales
4. Sales by Category
5. Monthly Sales Trend
6. Payment Method Mix
7. Customer Segments

---

## 🔄 Project Workflow

```text
Raw Sales Dataset
       ↓
Data Cleaning
       ↓
Data Validation
       ↓
KPI Calculation
       ↓
Exploratory Data Analysis
       ↓
Julius AI Analysis
       ↓
Dashboard Development
       ↓
Interactive Visualization
       ↓
Business Insights
       ↓
Recommendations
