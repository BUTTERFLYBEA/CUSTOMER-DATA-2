# CUSTOMER-DATA 2
PROJECT TITTLE: CUSTOMER DATA ANALYSIS
---
- [Project overview](#project-overview)
- [Basic Statistics In The Data](#basic-statistics-in-the-data)
- [Data Collection](#data-collection)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Cleaning And Preparation](#data-cleaning-and-preparation)
- [Data Visualization](#data-visualization)
- [SQL Query](#sql-query)
  
  
---
PROJECT OVERVIEW:
---
 This report aims at analyzing customer data and understanding the subscription trends to know the best action to take for the subscription types not doing well. It presents an in-depth analysis of customer subscription service data, focusing on segmentation, cancellation trends, and overall subscription patterns. the analysis aims to understand customer behaviour, track subscription types, and identify key trends in cancellations and renewals. Using a combination of MS Excel, SQL, and Power BI, the data was cleaned, organized, analyzed, and visualized to reveal insights into customer behaviour. 
- Scope: customer data from specific time period 
- Deliverables: insight on customer demographics,purchase behavior and interaction channels
---
## DATA INFORMATION:
---
### Data sources
The data used in this project was obtained from the Incubator Hub. It includes detailed records of transactions, customer demographics, product information and regional sales distribution.
---
### Data Collection:
---
The data used was collected and complied through transaction logging. This ensures that the dataset represents an accurate record of customer interactions and purchasing patterns over a year and eight months.
---
### Data Characteristics:
---
The dataset includes the following variables:
1. CustomerID : A uniques identification of each customer
2. Customer Name : Names of the customers
3. Region : 
4. Subscription Type : Type of subscription purchased
5. Subscription Start: The date of subscription
6. Subscription End : the date of subscription expiration
7. Canceled : If the subscription was canceled or not
8. Revenue : The revenue generated from each purchased
9. Subscription Duration : The duration of each purchased subscription.
---
## BASIC STATISTICS IN THE DATASET:
---
1. Total Revenue : 67.5 Million
2. Average Revenue : 1999
3. Average Duration : 365.35
4. Total Customer : 33787
5. Total Order : 33787
---
## METHODOLOGY:
---
### Data Cleaning:
* Removing duplicates
Eliminated duplicated records to ensure Data Quality

* Adding New Columns
Added new columns sales and revenue by multipling the quantity of the product purchased by the respective unit price, added an average column for the sales/revenue of products purchased and also added a calculated column for the Marginal profit made in the company over the space of a year and eight months.

---
Tools Used
---
- Data Analysis 
- Data visualization: POWER BI 
- Database management: SQL SERVER 
- SQL Client: SQL Client Tool
- Data Preprocessing: tools used, eg.,
Excel, Google Sheets 

---
### Exploratory Data Analysis:
 

---
Data Cleaning and Preparation 
---
1. Handling missing values
2. Data normalization 
3. Data transformation 
4. Data quality checks
5. Removal of duplicates

---
Data Analysis 
---
1. Customer segmentation (RFM Analysis)
2. Purchase behavior Analysis (frequency, average order value)
3. Interaction channels analysis (websites,social media,email)
4. Customer lifetime value (CLV) Analysis 

---
Data visualization 
---
- customer demographics dashboard 
- purchase behavior dashboard 
- interaction channels dashboard 
- CLV Analysis dashboard 

---
SQL QUERY:
---

SELECT
     Region,count(distinct CustomerID)as total_sales

FROM 
    dbo.lita customer data

GROUP BY 
       REGION

ORDER BY
       Total customers DESC;


---
SQL QUERIES:
- CUSTOMER DEMOGRAPHICS 

SELECT
     Age,
     Gender,
     Location 
     COUNT(*)AS Customer count

FROM
   CUSTOMERS

GROUP BY
       Age,
       Gender,
       Location;
 
- Purchase Behavior 

SELECT 
     Customer ID,
     Recency,
     Frequency,
     Monetary Value 

FROM
    Customer 

ORDER BY
       Recency DESC;






       
   

