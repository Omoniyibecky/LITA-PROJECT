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
  
## Dataset source

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


  ```SQL
 
 Select*
from  [dbo].[SALES CSV]

----Retreving total sales for each product category----
- Shoes	14402
-Jacket	5452
- Hat	15929
- Socks	7921
- Shirt	12388
- Gloves	12369

---- Numbe rof sale  transation in each region___

- North	2481
- East	2483
- South	2480
- West	2477

----Highes selling product by -total sales value

- Shoes	613380


------Calculate the total revenue per product----

- Hat	1991
- Shoes	1987
- Jacket	1488
- Shirt	1487
- Gloves	1484
- Socks	1484

-----5 Top customers by total purchase  amount----

- Cus1115	138
- Cus1249	123
- Cus1302	138
- Cus1431	138
- Cus1005	138


----calculate the percentage of total sales contributed by each region.---
- South	927820  	(44.2%)
- East	485925	 (23.1%)
- North	387000	 (18.4%)
- West	300345	 (14.3%)


-----identif poducts with no sales in the last quater,
    
- Jacket
- Socks
- Shirt ```


## Data Visualizaion
POWER BI DASHBOARD


![LITTA PROJECT-1](https://github.com/user-attachments/assets/26a005d4-2e60-41d1-ae71-e0cce5d95e5a

![image](https://github.com/user-attachments/assets/4e805c81-2a62-4c09-8b21-52297b84d091)




## RECOMMENDATION

##  Project Title: CUSTOMER Analysis for Data-Driven Decision Making


## Primary Aims:

1. Customer Understanding: Gain insights into customer behavior, preferences, and needs.
2. Business Growth: Inform strategies to increase revenue, customer retention, and market share.
3. Personalization: Enable tailored marketing, sales, and customer service experiences.

## Specific Objectives:
- retrieve the total number of customers from each region.
 - find the most popular subscription type by the number of customers.
- find customers who canceled their subscription within 6 months.
- calculate the average subscription duration for all customers.
- find customers with subscriptions longer than 12 months.
- calculate total revenue by subscription type.
- find the top 3 regions by subscription cancellations.
- find the total number of active and canceled subscription

``SQL

    SELECT*
     FROM[dbo].[Customer Data]


--- retrieving the total number of customers from each region.----

- East	5
- North	5
- South	5
- West	5



--- find the most popular subscription type by the number of customers.----

- Basic	10

---- find customers who canceled their subscription within 6 months.---

- NULL

-----calculate the average subscription duration for all customers----
- 365
 
 ------find customers with subscriptions longer than 12 months-----

 - NULL

---- calculate total revenue by subscription type.-----
- Basic	23116
- Premium	8504
- Standard	9845

----find the top 3 regions by subscription cancellations.----

 - NULL



## Data Visualizaion





![LITTA PROJECT-2](https://github.com/user-attachments/assets/55239fac-3849-4ead-bf4d-2543fbbf6eb5)


 
## Project Title: HR Analysis for Data-Driven Decision Making


Description:

The Employee Attrition dataset contains information about employees who have left the organization, including demographic, job-related, and performance data.

Analysis Goals:

1. Identify factors contributing to employee attrition
2. Predict employee turnover risk
3. Develop strategies to reduce attrition rates
4. Improve employee retention and satisfaction

## The argument used for this analysis includes:

- Total number of attrition
- Attrition count
- Current employee
- Average age
- Performance rating by gender
- Job satisfaction by attrition count
- Monthly income by attrition count
- Current employee by gender
- Monthly income by Education field
- Monthly income by department
- Job level by attrition
  
## Data Visualizaion 

![LITA HR REPORT-1](https://github.com/user-attachments/assets/4c4a26d2-6212-4220-ba19-3717897e6853)



  ## INSIGHTS AND RECOMMENDATION
  
- ﻿ Employee Count for Male (882) was higher than Female (588).﻿﻿
﻿﻿
- ﻿﻿Male accounted for 60.00%  of Employee Count.﻿﻿
﻿﻿

- Performance rating by gender: No got the highest  83% than Yes with 16%

- Job satisfaction by attrition count : No got the highest 80.4%   than Yes with 28%


- Monthly income by attrition count: No got 71.7% higher than Yes with 28%

- Monthly income by Education field: life sciences got the highest had 1.757.87%  than human resources with 19

- Monthly income by department:  sales 22%, HR 4%, research science 20%
- Job level by attrition: No got 73.2% higher than Yes with 26.8%
  
## RECOMMENDATION
The data reviewed that the employee was not satisfied with their job role, job levels, and monthly incomes,
I discovered that some of them were not promoted, which is why they didn't perform well in their task or role 
Also noticed that roles were not given based on their education field

-  I will recommend that HR  should recruit employees based on their education field to fit the roles

- HR should aslo promote employee and increase their salary.
- Identify high-risk employees for targeted interventions
-  Develop training programs to address skill gaps
-  Improve work-life balance and employee well-being
-  Enhance compensation and benefits packages
- Foster open communication and feedback chart



  ![SQL4](https://github.com/user-attachments/assets/2a1df519-8101-4938-b6cd-77107a703db9)





  
![Uploading SQL6.png…]()



![SQL1](https://github.com/user-attachments/assets/845794e9-ac86-4be4-b74d-02efea2bee9f)





![SQL2](https://github.com/user-attachments/assets/34747bc8-52e6-4895-bc48-bb7d27e537b8)



![SQL3](https://github.com/user-attachments/assets/1c8767de-ff51-4847-a498-140c6fb39629)
