# The-Guac-Stop-Data-Warehousing-Project

## 📌 Project Overview

This project demonstrates a full-stack data warehousing and analytics solution developed for **The Guac Stop**, a conceptual food brand. The pipeline integrates data warehousing, ETL processing, and business intelligence to help track and analyze sales performance across regions, products, and time.

This work was completed as part of a coursework project and showcases practical implementation of cloud data engineering and visualization tools.

---

## 🧰 Tech Stack

- **Oracle Cloud** – Data warehouse deployment and SQL schema management  
- **Apache Hop** – ETL development for data cleansing and loading  
- **Tableau** – Business dashboard for interactive data analysis  

---

## 🔄 Project Pipeline

### 1. 💾 Data Warehouse in Oracle Cloud

- Created a star schema with fact and dimension tables for optimized analytical queries.
- Used SQL DDL to design relationships between entities (e.g., Date, Product, Customer, City).
- Enriched the Date Dimension to support advanced time-series reporting (quarter, month, year).

### 2. 🛠️ ETL Pipeline with Apache Hop

- Developed a transformation pipeline to ingest raw data into the data warehouse.
- Addressed:
  - Column renaming for reserved keywords (`Date` ➝ `DateValue`)
  - Missing foreign keys and null handling
  - Schema mismatches across staging and final warehouse layers

### 3. 📊 Sales Performance Dashboard in Tableau

The final dashboard provides a comprehensive view of The Guac Stop's sales operations.

**Key Visualizations:**
- **KPIs**: Total Sales Amount, Total Quantity Sold, Number of Sales
- **Line Chart**: Sales by Year and Quarter for trend analysis
- **Pie Chart**: Sales distribution across cities (Buffalo vs. Rochester)
- **Bar Charts**: 
  - Sales by Product (e.g., Chocolate Chip Cookies, Rotini)
  - Sales by Category (e.g., Wheat, Dairy)
- **Scatter Plot**: Customer-wise analysis of Quantity vs. Sales
- **Summary Table**: Brand, Subcategory, Quantity, and Sales Price breakdown

> 📌 *Dashboard Screenshot:*
> ![Dashboard Screenshot](https://github.com/jathin1407/The-Guac-Stop-Data-Warehousing-Project/blob/main/Dashboard_Screenshot.png?raw=true)



---

## ✅ Key Highlights

- **End-to-End Workflow**: From data modeling to business insight delivery  
- **Clean ETL Design**: Schema-aware data transformation with Apache Hop  
- **Insightful Visualization**: Actionable insights delivered via user-friendly dashboard  
- **Business Filters**: City and category filters to enable drill-down views  


