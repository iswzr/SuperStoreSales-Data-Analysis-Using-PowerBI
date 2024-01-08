# 📊 My First Power BI Data Exploration

## INTRODUCTION:

As my inaugural foray into Power BI, I relished the opportunity to independently explore the provided SuperStoreSales dataset without any shareholder pressures or prescriptive requirements. This project allowed me to freely follow my instincts and apply my existing data skills to uncover impactful insights using Power BI's extensive analytics and visualization capabilities. 

The SuperStoreSales dataset contains sales and profitability data including metrics like revenue, units sold, and customer details across 4 years for a retail business. My analysis involved both aggregate level trends as well as drill-downs into specific regional, product and customer cohorts. Exploring this structured dataset improved my proficiency in statistical modeling, data visualization, and identifying actionable insights. Performing end-to-end analysis without defined objectives provided great exposure to the BI value chain while allowing creative freedom. This project expanded my Power BI skillset and piqued my interest in business analytics. The key findings provide data-backed growth opportunities related to sales, profitability, product portfolio, and customer engagement.

---

## PROBLEM STATEMENTS

1. How has overall sales revenue grown over the past 4 years? What is driving this growth?

2. Which regions present the biggest opportunities for sales growth?

3. What product categories have the highest sales and margins?

4. Which individual products are the top performers in sales and profit?
   
6. How do sales and profitability compare across different customer segments?

---

## DATA SOURCING

It contains 3 sheets/tables:
- ORDERS with 51,291 rows and 24 columns
- PEOPLE with 24 rows and 2 columns
- RETURNS with 1079 rows and 3 columns

---

## DATA MODELING

Power BI created a star schema model by linking related tables automatically. The model's fact table is the 'Order' table. The other two tables, 'Return' and 'People', are dimension tables that join the 'Order' table through the shared columns: 'Order_ID' and 'Region'.

---

## DATA ANALYSIS AND VISUALS
![Sales Analysis](https://github.com/iswzr/SuperStoreSales-Data-Analysis-Using-PowerBI/assets/155778216/e3dc492e-1bf2-46a5-b74e-28dc34eedb75)

## 📈 Sales Overview

- Total sales increased yearly from $2.5M in 2011 to $5.5M in 2014.

- Central region contributed the most sales at $2.8M over the period. 

- Phones ($1.71M) and Copiers ($1.51M) were the top selling sub-categories.

- Technology accounted for 37.5% of total sales, followed by Furniture (32.5%) and Office Supplies (30%).

- 10 customers generated over $300K sales each from 2011-2014.

- Tom Ashbrook was the top customer with $404K sales.

---

##📈 Profitability Analysis
![Profit Analysis](https://github.com/iswzr/SuperStoreSales-Data-Analysis-Using-PowerBI/assets/155778216/888f9192-a622-428e-ab99-3e743042322f)

### 💰 Profit Trends

- Total profit increased from $150K in 2011 to $200K in 2014.  

- Central led profitability at $310K over the period.

- Copiers were the top contributor at $259K total profit.

### 🚨 Loss-making Products

- Tables had the lowest profitability, with total losses of $64K.

- Some phone models like Samsung Smart Phone, Cordless also registered losses.

### 🤑 Most Profitable Customers

- Raymond Buch spent the most at $8,453 and had high profitability.

- Tamara Chand also had high sales of $37,453 and profit of $8,673.

- Top customers present cross-selling and loyalty program opportunities.

### 📉 Discount Impact 

- Increasing discounts negatively impacted profitability.

- Optimizing discounts and margins is needed to boost profitability.

---

## 📊 Product Performance Analysis
![Product analysis](https://github.com/iswzr/SuperStoreSales-Data-Analysis-Using-PowerBI/assets/155778216/4e8a1716-bdd0-4a10-8327-2c352089705e)

### 📈 Top Performing Products 

- Apple, Cisco, Motorola phones had highest sales.

- Executive armchairs from Hon, Office Star sold well. 

- Canon advanced copier was the top seller in its category.

- Nokia phones and SAFCO armchair also among top 10 products.

### 💰 Most Profitable Products

- Cisco and Motorola phones had high profit despite lower sales.

- Harbour Creations armchair was very profitable.

- Canon copier had solid sales and profitability. 

### 📉 Low Profit Products

- Despite good sales, Apple and Nokia phones had lower profit.

- Samsung phones registered losses due to high costs.

- Other low margin products need pricing optimization.

----

As a first hands-on Power BI project without any stakeholder objectives, I enjoyed the freedom to explore the data and unearth insights at my own pace. Performing analysis on both numeric and categorical data types gave me great experience. The growth trends and regional variances provided interesting macro insights, while product performance highlighted important micro opportunities. I'm excited to continue honing my analytics skills!

---

![_06e315de-b4a7-42ad-bd19-2828720423a7](https://github.com/iswzr/SuperStoreSales-Data-Analysis-Using-PowerBI/assets/155778216/919f5b24-da17-4078-8d63-7a311924ddc9)


