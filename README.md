# CUSTOMER-DATA 2
PROJECT TITTLE: CUSTOMER DATA ANALYSIS
---
- [Project overview](#project-overview)
- [Data Information](#data-information)
- [Data Collection](#data-collection)
- [Data Characteristics](#data-characteristics)
- [Basic Statistics In The Data](#basic-statistics-in-the-data)
- [Methodology](#methodology)
- [Exploratoratory Data Analysis](#exploratory-data-analysis)
- [Tools Used](#tools-used)
- [Analysis](#analysis)
- [Data Analysis and Insight Generation](#data-analysis-and-insight-generation)
- [Conclusion](#conclusion)
- [Additional Resources](#additional-resources)
  
  
---
PROJECT OVERVIEW:
---
 This report aims at analyzing customer data and understanding the subscription trends to know the best action to take for the subscription types not doing well. It presents an in-depth analysis of customer subscription service data, focusing on segmentation, cancellation trends, and overall subscription patterns. the analysis aims to understand customer behaviour, track subscription types, and identify key trends in cancellations and renewals. Using a combination of MS Excel, SQL, and Power BI, the data was cleaned, organized, analyzed, and visualized to reveal insights into customer behaviour. 
- Scope: customer data from specific time period 
- Deliverables: insight on customer demographics,purchase behavior and interaction channels
---
## DATA INFORMATION:
---
### Data sources:
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
 ## EXPLORATORY DATA ANALYSIS (EDA)
---
After cleaning the data in excel and making pivot tables for analysis, it was exported to SQL for further analysis and finally to power BI for creation of dashboard. The following were carried out:
---
### Excel Analysis : Used for initial exploration and basic calculations.

1. Data Preparation
* Data cleaning : Eliminated duplicated records to ensure Data Quality.
* New columns calculated : Calculated the time between subscription start and subscription end date for each subscriber.
2. Basic Subscription Statistics
* Summary table : Presented subscriber count, average subscription duration, average monthly revenue, and most popular subscription type.
3. Customer Distribution and Segmentation
* Subscription count by type : Created pivot tables to display counts for each subscription type (e.g., monthly, quarterly, annual)
* Subscriber segmentation : used pivot tables to segment subscribers based on activity (retained, canceled)

### SQL Analysis : Used for in-depth data queries and subscriber insights.

1. Retrieved the total number of customers from each region.
2. Found the most popular subscription type by the number of customers.
3. Found customers who canceled their subscription within 6 months.
4. Calculated the average subscription duration for all customers.
5. Found customers with subscriptions longer than 12 months.
6. Calculated total revenue by subscription type.
7. Found the top 3 regions by subscription cancellations.
8. Found the total number of active and canceled subscriptions.

### Power BI Analysis : Offers interactive dashboards and visuals for exploring subscription trends.

1. Key Metrics Dashboards 
* KPI Cards : Displayed key metrics()
* Interactive slicers : Added slicers for regions and subscription types, allowing viewers to filter insights by their area of interest.
2. Subscriber Distribution and Segment Analysis
* Subscrption count by region and type : Visualized using interactive bar charts, showing which regions have the highest subscriptions and subscription types are most popular.
* Customer segmentation dashboard : Created visuals to differentiate segments by region and subscription type.
 
## TOOLS USED
1. Microsoft Excel: Used for data cleaning, analysis and creating pivot visualization [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/MICROSOFT-365/EXCEL)
2. MIcrosoft SQL server (SMSS): Used for pre-processing [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/SQL-SERVER/SQL-SERVER-DOWNLOADS)
3. Microsoft Power BI desktop: Used for creating dashboards and visualization [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/DOWNLOAD/DETAILS.ASPX?ID=58494)
---
## ANALYSIS:
---
### Dashboard Overview:

![customer 1](https://github.com/ButterflyBea/LITA-PROJECTS/blob/main/customer%201.png?raw=true)
![customer 2](https://github.com/ButterflyBea/LITA-PROJECTS/blob/main/customer%202.png?raw=true)
---
## Data Analysis and Insight Generation:
---
This Visualization reveals some intriguing patterns and trend from understanding customer behavior, tracking subscription types, and identifying key trends in cancellations and renewals of the various subcription types available in the company.
1. SUBSCRIPTION TREND : Subscription numbers showed fluctuations over time, monnthly, quarterly and yearly. There was a steady flow of revenue monthly until it declined in the month of september, it droped from 6.75 Million in August to 3.37 Million in September. Quarterly, there was a steady trend from the first to the second quarter but by the third quarter it declined from 20 Million to 16 Million and to 10 MIllion by the forth quarter. And finally yearly, from 2022 to 2023 there was a decline from 40 Million to 27 Million. This implies the purchases decline after a period of time.
   RECOMMENDATION : Increase marketing efforts during peak periods to capitalize on natural customer interest. And introduce targeted promotions and membership discounts during slower periods to encourage new sign-ups.
2. TYPE PERFORMANCE : The bar chart reveals that the basic subscription type which accounts for 50% of all subscriptions emerges as the most sort out by the subscribers generating over 17 Million more than preminum and standard and it is also the subscription type with the no cancellation records. This shows that more subscribers appreciate the simplicity and affordability of the basic subscription type than they do the other types.
   RECOMMENDATION : Perform targeted marketing on the benefits of the basic subscription type while making adjustments to the other subscription types. promotions such as discounts and memberships can be very effective in driving the purchase of other subscription types.
3. REGIONAL BREAKDOWN : the Visuals presenting the regions showed two things, the first being that each region had the same amount of revenue generated but with different sales rate with the East having the highest (25.11%) and the North having the lowest (24.90%). the second being that the East unlike every other region where on occations subscribers would cancel their subscriptions, there was no record of cancellations in the East which might be as a result of higher customer engagements or effective local marketing.
   RECOMMENDATION : Strengthen marketing efforts in the other regions, using strategies that have worked in the East region. 
4. AVERAGE SUBSCRIPTION DURATION : The average subscription duration each year is 365 days which implies that the subscribers are satisfied with the services rendered as they renew their  subscriptions yearly on average. 
   RECOMMENDATION : Seeing that the average duration per year is good, implement engagement tatics like surveys and periodic check-ins to keep the subscriber engaged over time.

## CONCLUSION:
The analysis provides valuable insights into customer behaviour, preferences, and regional trends. Key findings reveal diverse customer needs across regions, varying product preferences, and distinct demographic characteristics that impact purchasing behaviour. In conclusion, the analysis of customer data emphasizes the importance of a customer-centric approach. Adapting strategies to meet the needs of distinct customer segments will position the company for continued success, ensuring it remains responsive to evolving customer expectations and competitive within the market. 
---
## ADDITIONAL RESOURCES:
---
1. My Excel Worksheet [Click Here](https://github.com/ButterflyBea/LITA-PROJECTS/blob/main/My%20LITA%20Capstone%20Dataset.xlsx)
2. My SQL [Click Here for sales data](https://github.com/ButterflyBea/LITA-PROJECTS/blob/main/Capstone%201.sql)
   [Click Here for Customer data](https://github.com/ButterflyBea/LITA-PROJECTS/blob/main/Capstone%202.sql)
3. My Power BI [Click Here for sales data](https://github.com/ButterflyBea/LITA-PROJECTS/blob/main/MY%20PROJECT%201.pbix)
   [Click Here for Customer data](https://github.com/ButterflyBea/LITA-PROJECTS/blob/main/PROJECT%202.pbix)
