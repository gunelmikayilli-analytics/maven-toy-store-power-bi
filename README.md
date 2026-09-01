# 🧸 Maven Toy Store Sales Analysis | Power BI

## 📌 Project Overview

This project presents an interactive **Power BI dashboard** developed to analyze the sales performance of Maven Toy Store.

The main objective of the project is to evaluate revenue, profitability, product performance, inventory levels, seasonal sales trends, and store performance.

The dashboard helps identify key business opportunities and supports data-driven decision-making related to products, inventory, and store expansion.

---

## 🎯 Business Questions

The analysis was designed to answer several key business questions:

- Which products are the most profitable?
- Which products generate the highest sales?
- Which products have the highest number of units sold?
- Which product categories perform best?
- Which store locations generate the highest profit?
- Which cities perform best?
- When is the best time of year to open a new store?
- Are there opportunities for store expansion?
- How much inventory is currently available?

---

## 📊 Key Performance Indicators

The dashboard tracks the following main KPIs:

| KPI | Result |
|---|---:|
| Total Revenue | $14.44M |
| Total Profit | $4.01M |
| Average Gross Profit Margin | 31.23% |
| Units Sold | 1.09M |
| Stock on Hand | 29.74K |

---

## 📈 Dashboard Pages

### 1. Sales Overview

The Sales Overview dashboard provides a high-level view of business performance.

It includes:

- Total Revenue
- Total Profit
- Average Gross Profit Margin
- Total Units Sold
- Stock on Hand
- Product profitability analysis
- Top 5 products by sales
- Top 5 products by units sold
- Monthly revenue and profit trends
- Product category performance
- Interactive filters by year, product category, and store location

![Sales Overview](images/01-sales-overview.png)

---

### 2. Store & Product Analysis

This page provides a deeper analysis of product profitability, inventory, store performance, and geographic sales distribution.

It includes:

- Profit margin by product
- Stock on hand by product
- Gross profit by city
- Revenue breakdown by store and product category
- Geographic store analysis
- Interactive filtering by year, category, and store location

![Store and Product Analysis](images/02-store-product-analysis.png)

---

### 3. Detailed Analysis

The final page summarizes the most important findings from the dashboard and provides business recommendations based on the analysis.

![Detailed Analysis](images/03-detailed-analysis.png)

---

## 🔎 Key Insights

### 🏆 Product Performance

The most profitable products include:

- Jenga
- Mini Basketball Hoop
- Playfoam

The top-performing products by total sales include:

- Lego Bricks
- Colorbuds
- Magic Sand
- Action Figure
- Rubik's Cube

**Lego Bricks** generated approximately **$2.4M in sales**, making it the highest-selling product.

---

### 📦 Units Sold

The products with the highest number of units sold include:

- Colorbuds — approximately 104K units
- Magic Sand — approximately 61K units
- Lego Bricks — approximately 60K units
- Action Figure — approximately 58K units
- Rubik's Cube — approximately 46K units

---

### 🏪 Store Performance

The analysis shows that the most profitable store location types are:

- Airport
- Downtown

Some of the strongest-performing cities include:

- Ciudad de Mexico
- Guadalajara
- Monterrey

---

### 📅 Seasonal Trends

Sales and profit performance is stronger during the **spring and summer months**.

Lower performance was observed toward **October–December**.

Based on this trend, opening a new store during **spring or early summer** may provide a stronger launch period and higher initial customer traffic.

---

### 🌍 Expansion Opportunity

The analysis identified potential expansion opportunities in:

- Hermosillo
- Guanajuato

These cities currently do not have Airport-format stores.

Since Airport locations demonstrate strong profitability, introducing this store format in these cities could represent a potential growth opportunity.

---

### 🧸 Product Category Performance

The **Toys** category is the strongest-performing product category.

The **Sports & Outdoors** category recorded the lowest profit at approximately **$0.51M**, indicating an opportunity for further investigation and optimization.

---

## 💡 Business Recommendations

Based on the analysis:

1. Prioritize high-performing products such as Lego Bricks, Colorbuds, Jenga, and Mini Basketball Hoop.

2. Maintain sufficient inventory levels for products with high sales volume.

3. Investigate the performance of the Sports & Outdoors category and identify opportunities to improve profitability.

4. Consider spring or early summer when planning new store openings.

5. Explore opportunities to introduce Airport-format stores in cities such as Hermosillo and Guanajuato.

6. Continue monitoring product profitability together with sales volume instead of evaluating revenue alone.

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **Business Intelligence**
- **Data Analysis**

---

## 🗂️ Data Model

The Power BI model includes data related to:

- Sales
- Products
- Stores
- Inventory
- Calendar

A dedicated measure table was also used to organize calculated metrics and KPIs.

---

## ⚙️ Power BI Features Used

- Data cleaning and transformation
- Data modeling
- DAX measures
- KPI cards
- Bar charts
- Line and area charts
- Donut charts
- Maps
- Decomposition Tree
- Tables
- Slicers
- Tooltips
- Interactive filtering

---

## 📁 Repository Structure

```text
maven-toy-store-power-bi/
│
├── Maven-Toy-Store-Analysis.pbix
├── README.md
│
├── images/
│   ├── 01-sales-overview.png
│   ├── 02-store-product-analysis.png
│   └── 03-detailed-analysis.png
│
└── data/
    └── dataset files
