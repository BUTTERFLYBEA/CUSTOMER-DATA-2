# CUSTOMER-DATA-2
# Pro
## PROJECT OVERVIEW 
##PROJECT TITTLE: CUSTOMER DATA 

This helps to Analyze customer data to understand demographics, behavior,and preference.
- Scope: customer data from specific time period 
- Deliverables: insight on customer demographics,purchase behavior and interaction channels

---
Basic Statistical Data
---
- Total customers.
- Male-Female ratio.
- Average age.
- Top 5 location 
- Average purchase value
- Purchase frequency 

---
Data Collection 
---
- Source: database name,eg SQL SERVER 
- Method: API,Web scraping, manual entry
- Time period: Start date-end date
- Data Quality Issues: list issues,eg missing values, duplicate 

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
Exploratory Data Analysis 
---
- Distribution of customers demographics (age,gender, location)

- Correlation between purchase behavior and demographics 

- Identification of outliers and anomalies

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






       
   

