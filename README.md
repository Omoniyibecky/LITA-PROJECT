# LITA-PROJECT
## Project Title: Sales Analysis for Data-Driven Decision Making

## Project Description:

This project aims to analyze sales data to identify trends, patterns, and insights that inform business decisions. The analysis will provide a comprehensive understanding of sales performance, customer behavior, and market dynamics.

## Project Objectives:

- Analyze the total sales for each product category.
- find the number of sales transactions in each region.
-  find the highest-selling product by total sales value.
- calculate total revenue per product.
- calculate monthly sales totals for the current year.
- find the top 5 customers by total purchase amount.
- calculate the percentage of total sales contributed by each region.
- identify products with no sales in the last quarter.
  
## Dataset:

The project utilizes a dataset containing sales transactions, customer information, and product data

## Tools Used
- Microsoft Ecxel, Data clearning ,pivot table
- SQL( structured query language for quering data
- Power BI Analysis and visualization

  ## Key Insights Uncovered   `
  - Total sales
  - Average sales
  - Total quantity sold
  - Total Product
  - Total revenue by quantity: identifying the pattern and fluctuation over time
  - Top region by sales: Locating geographical of high sales 
  - Top Best Selling product:Recognising the most popular purchasing 


  ```
 
 Select*
from  [dbo].[SALES CSV]

----Retreving total sales for each product category----

Select product, sum(quantity) AS Total_sales
from [dbo].[SALES CSV]
GROUP BY Product;

---- Number sale of transation in each region___

	Select region, COUNt(quantity) AS	Transation
from [dbo].[SALES CSV]
GROUP BY region;

----Highes selling product by -total sales value

select top 1 product, 
sum(Revenue) AS Top1_sales

from [dbo].[SALES CSV]

GROUP by product;


------Calculate the total revenue per product----
select  product, 
COUNT(Revenue) AS TotalRevenue

from [dbo].[SALES CSV]

GROUP by product
ORDER BY
Totalrevenue DESC;


-----5 Top customers by total purchase  amount-----
Select top 5 Customer_Id, sum(quantity) AS Top_customer
from [dbo].[SALES CSV]
GROUP BY Customer_Id;

---calculate the % of total sales contributed by each region-----

----calculate the percentage of total sales contributed by each region.---
SELECT Region, SUM(Revenue) AS RegionTotalSales,
FORMAT(ROUND((SUM(Revenue) / CAST((SELECT SUM(Revenue) FROM [dbo].[SALES CSV]) AS DECIMAL(10,2)) * 100), 1), '0.#') 
AS PercentageOfTotalSales
FROM [dbo].[SALES CSV]
GROUP BY Region
ORDER BY PercentageOfTotalSales DESC;


-----identif poducts with no sales in the last quater,
    
SELECT Product FROM [dbo].[SALES CSV]
GROUP BY Product
HAVING SUM(CASE 
WHEN OrderDate BETWEEN '2024-06-01' AND '2024-08-31' 
THEN 1 ELSE 0 END) = 0

```
## Data Visualizaion

## Expected Outcomes:*

1. Improved sales forecasting
2. Enhanced customer insights
3. Data-driven decision-making
4. Increased revenue
5. Better resource allocation

##  Project Title: CUSTOMER Analysis for Data-Driven Decision Making
Primary Aims:

1. Customer Understanding: Gain insights into customer behavior, preferences, and needs.
2. Business Growth: Inform strategies to increase revenue, customer retention, and market share.
3. Personalization: Enable tailored marketing, sales, and customer service experiences.

Specific Objectives:

1. Segmentation: Identify distinct customer groups based on demographics, behavior, or preferences.
2. Profiling: Create detailed customer profiles to inform targeted marketing.
3. Predictive Analytics: Forecast customer churn, purchase behavior, or lifetime value.
4. Customer Journey Mapping: Understand touchpoints and pain points across the customer lifecycle.
5. Market Research: Analyze customer feedback, sentiment, and satisfaction.
6. Product/Service Development: Inform development of new offerings or features.
7. Customer Retention: Identify at-risk  

By analyzing a customers' dataset, businesses can gain valuable insights to inform strategic decisions, improve customer experiences, and drive growth.









 
## Project Title: HR Analysis for Data-Driven Decision Making


Description:

The Employee Attrition dataset contains information about employees who have left the organization, including demographic, job-related, and performance data.

Analysis Goals:

1. Identify factors contributing to employee attrition
2. Predict employee turnover risk
3. Develop strategies to reduce attrition rates
4. Improve employee retention and satisfaction


Key Performance Indicators (KPIs):

1. Attrition Rate
2. Turnover Rate
3. Retention Rate
4. Average Tenure
5. Time-to-Fill (vacant positions)
6. Cost-per-Hire
7. Employee Satisfaction (eNPS)
## #Data Visualization



![LITA HR REPORT-1](https://github.com/user-attachments/assets/772eee06-4060-45ef-910e-94aa8a141b35)



Actionable Insights:

1. Identify high-risk employees for targeted interventions
2. Develop training programs to address skill gaps
3. Improve work-life balance and employee well-being
4. Enhance compensation and benefits packages
5. Foster open communication and feedback channels







