# 📊 Power BI - Global Superstore Sales Project  
Author: Nguyen Duc Thien  
Date: 2024-10-31  
Tools Used: Power BI 

---

## 📑 Table of Contents  
1. [📌 Background & Overview](#-background--overview)  
2. [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)
3. [🧠 Design Thinking Process](#-design-thinking-process)
4. [📊 Key Insights & Visualizations](#-key-insights--visualizations)

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

![image](https://github.com/user-attachments/assets/35ace842-1863-4895-b328-2fd94d44a429)

Table 2: People
- Size: 2 columns and 13 rows
- Description: Saving Salesperson and region information respectively   

![image](https://github.com/user-attachments/assets/b6c8f0e6-944a-4139-b01b-303ee5d51519)
 
Table 3: Returns
- Size: 2 columns and 1172 rows
- Description: Recording information related to Return sales order

![image](https://github.com/user-attachments/assets/9121ca12-a904-49ee-973e-7eb33621753a)

#### 3️⃣ Data Relationships:  
To standardize data, I create an additional table called "Dim_date" and based on data of each table, I used Star Schema to execute data modeling

![image](https://github.com/user-attachments/assets/d1d560d8-b5ae-4b36-8bc6-fa21b338d7a4)

---

## 🧠 Design Thinking Process  

1️⃣ Empathize

![image](https://github.com/user-attachments/assets/2f78155d-f71a-4116-b35b-bc466f7c54d8)

2️⃣ Define point of view

![image](https://github.com/user-attachments/assets/a24c3f94-de4e-44d9-8186-6931cb8970e2)

3️⃣ Ideate

![image](https://github.com/user-attachments/assets/cb251496-68e4-479d-9138-5d1798f710d2)

4️⃣ Prototype and review  

![image](https://github.com/user-attachments/assets/825a6100-234f-4480-934b-c83deb4818e9)

---
## 📊 Key Insights & Visualizations  

### 🔍 Dashboard Preview  

#### 1️⃣ Dashhboard 01: Business Performance Overview

![image](https://github.com/user-attachments/assets/c973b2e7-7f3f-4b91-93d4-6f786665b863)
 
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

![image](https://github.com/user-attachments/assets/bd71d022-8796-4cc7-b69b-168875c91a94)

📌 Insight:
- LATAM is the market with the highest revenue and profit, Mexico being the country that has both high revenue and high profit.
- The United States does not have very high revenue but has the highest profit margins.
- El Salvador has shown significant revenue growth in recent years.

✅ Recommendation:
- Continue business in the Mexican market as it remains a profitable and potential market, where customers are willing to pay for the company’s products (highest revenue per customer).
- Expand business in El Salvador, as it has a high revenue growth rate, large order values, and customers willing to pay for company products (relatively high revenue per customer).

#### 3️⃣ Dashhboard 03: Product Analyst

![image](https://github.com/user-attachments/assets/a04d2154-4f99-4478-b64b-299e2f31bc99)

📌 Insight:
- Blinders is the sub-category with the highest order volume, but it also has the highest return rate.
- Copiers is the fastest-growing sub-category in terms of order volume.
- Paper is the sub-category with the highest profit margin.

✅ Recommendation:
- Continue selling products in the Blinders category, but further investigate the causes of product returns, as this sub-category still has high-profit margins and relatively high growth rates.
- Expand sales of Paper products, as this product group has exceptionally high profit margins.
