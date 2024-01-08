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


