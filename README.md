# FNP Sales Analysis Dashboard

This project presents an interactive Sales Analysis Dashboard for FNP (Ferns N Petals), visualized using Excel. The goal of the project is to analyze sales performance, customer behavior, product performance, and ordering trends based on real-world business data.

![image alt](https://github.com/iqbal-hasan291/FNP_sales_Analysis-Excel-/blob/b96a477094d71f00b9886bbd9310da2ee8224822/FNP_Dashboard.png)

##  Project Goal

The primary objective of this project is to deliver actionable business insights through data analysis and visualization. Key goals include:

- Understanding customer purchase behavior
- Identifying high-performing products and categories
- Analyzing sales performance by date, time, city, and occasion
- Improving decision-making by leveraging data-driven insights

##  Dataset Overview

The dataset used in this project includes three main tables:

### 1. Customers Table
- Customer ID
- Name
- City
- Contract Number
- Adress
- Gender
- Email
  

### 2. Orders Table
- Order ID
- Customer ID
- Delivery Date
- Delevary Time
- Occasion
- Product ID
- Order Date
- Order Time
- Revenue
- Hour

### 3. Products Table
- Product ID
- Product Name
- Category
- Price

##  Tools & Technologies Used

- **Microsoft Excel / Power Query** – For data cleaning and transformation
- **DAX** – For calculated fields and measures

## ETL Process

1. **Extract** – Data imported from Excel files
2. **Transform** – Cleaned missing values, standardized column names, and converted data types
3. **Load** – Loaded transformed data into Power BI
4. **Modeling** – Created relationships between fact and dimension tables

##  Key Visuals in the Dashboard

- Total Revenue, Orders, Average Spend, and Delivery Time KPIs
- Revenue by Product, Category, Occasion, and City
- Monthly and Hourly Revenue Trends
- Order Count by Weekday
- Gender Filter, Occasion Slicer, and Timeline Range Filters

## 📌 Key Insights

- Total Revenue: ₹3,520,984 from 1,000 orders
- Average Customer Spend: ₹3,521
- Top Selling Products: Magnam Set, Quia Gift, Dolores Gift
- Best-Performing Categories: Colors,Soft Toys, Sweet
- Top Occasions: Anniversary, Diwali, Raksha Bandhan
- Most Active Cities: Imphal,Kavani
- Peak Order Hours: Between 4 PM and 8 PM
- Highest Sales Months: March and August
- Most Orders by Weekday: Sunday and Thusday

##  What I Learned

During this project, I gained hands-on experience with the following:

- Data Cleaning and Preparation in Power Query
- Data Transformation and Normalization
- Building an ETL workflow
- Data Modeling (Star Schema)
- DAX Functions and Measures
- Designing professional Power BI dashboards
- Extracting and interpreting key business insights

## Project Files

- `FNP_Dashboard.pbix` – Excel dashboard file
- `README.md` – Project documentation
- `Customer_Data.xlsx`, `Orders_Data.xlsx`, `Products_Data.xlsx` – Raw data files

## ✅ Conclusion

This project demonstrates how a retail company like FNP can use data analytics to monitor performance, understand customer behavior, and make strategic decisions. The dashboard offers a user-friendly interface for decision-makers to explore and act on data insights.

---

