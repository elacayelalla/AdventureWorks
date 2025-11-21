# 🧩 AdventureWorks Project – Business Data Analysis

## 📘 Overview
This project presents an end-to-end analysis of the **AdventureWorks** dataset, a sample business database provided by Microsoft that simulates the operations of a global company specializing in **sporting goods and cycling products**.  
The objective of this project is to extract valuable business insights using **SQL, Power BI, and Data Modeling** techniques to better understand sales performance, customer behavior, and operational efficiency.

---

## 🎯 Project Objectives
- Explore and transform data using **SQL and Power BI**.
- Build an optimized relational data model following the **star schema**.
- Develop interactive dashboards to analyze:
  - Best-selling products and most profitable categories.
  - Sales performance by territory and sales representative.
  - Profitability across regions and product lines.
  - Time-based trends and growth opportunities.

---

## 🏗️ Tools & Technologies
| Category | Tool |
|----------|-------|
| Database | SQL Server (AdventureWorksDW2022) |
| Query languages | SQL / DAX |
| ETL & Modeling | Power Query |
| Visualization | Power BI |
| Documentation | Markdown / GitHub |
| Version control | Git |

---

## 🧮 Analytical Workflow

### 1️⃣ Data Preparation & Cleaning
- Import of core tables:  
  `DimProduct`, `DimCustomer`, `DimSalesTerritory`,  
  `FactResellerSales`, `FactInternetSales`.
- Removal of duplicates, null records, and unneeded attributes.
- Creation of calculated columns and measures, including:
  - *Profit Margin*
  - *Total Sales*
  - *Year-to-Date (YTD) Sales*
  - *Year-over-Year Growth (YoY)*

### 2️⃣ Data Modeling
- Relationship modeling between **Fact** and **Dimension** tables.
- Building a dynamic **Date Table** using DAX (`CALENDAR()` with extended date attributes).
- Establishing product hierarchies:  
  Product → Subcategory → Category → Product Line.

### 3️⃣ Exploratory Data Analysis
- Identification of top-selling and most profitable products.
- Average revenue per customer and territory.
- Trend detection in monthly and annual sales.

### 4️⃣ Power BI Visualization
Dashboards created:

#### **Dashboard 1 – Global Sales Performance**
- Revenue by country and year.
- Profit margin by category.
- Top products by sales volume.

#### **Dashboard 2 – Customer Insights**
- Customer demographics and purchasing patterns.
- Order frequency and segment behavior.

#### **Dashboard 3 – Sales KPIs**
- Total Sales, Profit, Units Sold, YoY Growth.
- Drill-through views for territories and employees.

---

## 📊 Key Findings
- **Reseller Sales** represent the highest revenue segment.
- **North America** and **Europe** show strong sales growth and higher profit margins.
- Seasonal peaks occur during **summer months (June–August)**.
- **Bikes** dominate revenue but are less profitable than **Clothing** or **Accessories**.
- Sales representatives in the *Pacific* territory outperform those in *Southwest*.

---

## 🚀 Conclusions
This analysis provides a clear, data-driven overview of AdventureWorks’ commercial performance.  
The results can support decision-making in:

- Product inventory optimization.
- Targeted customer strategies.
- Geographic expansion planning.
- Sales team performance improvement.

The structure created can be extended easily to include additional company data, predictive models (machine learning), or automated reporting processes.

---

## 🧠 Author
**Julio César López Mendoza**  
📧 julio@juegofinanciero.com  
🎓 Data Analytics Bootcamp – Henry  
💬 *“Turning data into strategic decisions.”*
