# 📊 Power BI - Global Superstore Sales Project  
Author: Nguyen Duc Thien  
Date: 2024-10-31  
Tools Used: Power BI 

---

## 📑 Table of Contents  
1. [📌 Background & Overview](#-background--overview)  
2. [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)   
3. [📊 Key Insights & Visualizations](#-key-insights--visualizations)

---

## 📌 Background & Overview  

### Objective:
### 📖 What is this project about? 
 
Global Superstore is a retail company in diverse fields such as Technology, Furniture, Office Supplies,... . Senior Manager needs more information of business performance to build and develop market expanding strategy and strategic products. 

###  ❓Business Questions:  
1. How is the business performance of company?
2. Where are the potential markets?
3. Which products can be strategic?

### 🎯Project Outcome:  
✅ Sales performance and trends: The business performance is stable, with revenue growth trends aligning with profit growth trends
✅ Market research: Keeping business in profitable Mexican market, expanding business in El Salvador where customers willing to pay for company products
✅ Strategic product: The Blinders and Paper products

---

## 📂 Dataset Description & Data Structure  

### 📊 Data Source, Data Structure & Relationships  

#### 1️⃣ Tables Used:
The dataset used in this project is the Global Superstore dataset, containing sales data from a fictional retail store with .csv format, includes 3 data tables

#### 2️⃣ Table Schema & Data Snapshot  

Table 1: Orders
- Size: 20 columns and 51291 rows
- Description: Recording information related to Sales order  

👉🏻 Insert a screenshot of table schema 

Table 2: People
- Size: 2 columns and 13 rows
- Description: Saving Salesperson and region information respectively   

👉🏻 Insert a screenshot of table schema 

Table 3: Returns
- Size: 2 columns and 1172 rows
- Description: Recording information related to Return sales order

👉🏻 Insert a screenshot of table schema 


#### 3️⃣ Data Relationships:  
To standardize data, I create an additional table called "Dim_date" and based on data of each table, I used Star Schema to execute data modeling

👉🏻 Include a screenshot of Data Modeling to visualize relationships.  

---

## 📊 Key Insights & Visualizations  

### 🔍 Dashboard Preview  

#### 1️⃣ Dashhboard 01: Business Performance Overview

👉🏻 Insert Power BI dashboard screenshots here  

📌 Insight:
1. Business Performance:
- The business performance is stable, with revenue growth trends aligning with profit growth trends.
- The company also manages cost relatively well.
- The sub-category with the highest revenue is Chairs.
- The sub-category with the highest profit is Copiers.
- Blinders, Storage, and Paper are sub-categories with both high revenue and high profit.
- The most profitable market is LATAM.
- Revenue primarily comes from the customer segment.

2. Returning goods sold:
- The value of returned goods has remained almost unchanged in recent years, despite an increase in the number of returned products.
- The product causing the highest revenue loss is Canon Fax Machine Digital.

✅ Recommendation:
- Optimize costs to achieve higher profit margins, focusing more on the consumer segment.
- Continue investigating the causes of product returns and reducing return rates in the future.

#### 2️⃣ Dashhboard 02: Market Analyst

👉🏻 Insert Power BI dashboard screenshots here

📌 Insight:
- LATAM is the market with the highest revenue and profit, Mexico being the country that has both high revenue and high profit.
- The United States does not have very high revenue but has the highest profit margins.
- El Salvador has shown significant revenue growth in recent years.

✅ Recommendation:
- Continue business in the Mexican market as it remains a profitable and potential market, where customers are willing to pay for the company’s products (highest revenue per customer).
- Expand business in El Salvador, as it has a high revenue growth rate, large order values, and customers willing to pay for company products (relatively high revenue per customer).

#### 3️⃣ Dashhboard 03: Product Analyst

👉🏻 Insert Power BI dashboard screenshots here  

📌 Insight:
- Blinders is the sub-category with the highest order volume, but it also has the highest return rate.
- Copiers is the fastest-growing sub-category in terms of order volume.
- Paper is the sub-category with the highest profit margin.

✅ Recommendation:
- Continue selling products in the Blinders category, but further investigate the causes of product returns, as this sub-category still has high-profit margins and relatively high growth rates.
- Expand sales of Paper products, as this product group has exceptionally high profit margins.