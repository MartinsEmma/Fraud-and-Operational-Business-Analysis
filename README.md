# Business-Performance-Dashboard
...

### Table of contents 
---
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preperation](#data-cleaning-and-preperation)
- [Data Analysis](#data-analysis)
- [Results/findings](#results/findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

### Project Overview 
This Analysis is poised at influencing decision making on this business to enhance growth and maximum revenue. 
We will investigate factors like the total revenue generated from the business, most effective payment methods, highest grossing revenue month, Active customers,
Fraud transactions and other factors aiding or affecting growth. 

### Data Sources 
Transactional Data: The Primary dataset used for this analysis is the 'transactionas_data.csv', containing detailed information about car prices. 
the data set was curated by Erikodx_IT, One of the leading tech entreprices in nigeria.

### Tools 
Structured Query Language (SQL), Ms Excel(power query), Power bi(Dashboard Creation), Ms Word(report writing) 

### Data Cleaning and Preperation
The data was extracted from a relational database using SQL. It was further cleaned, transformed and validated in Microsoft Excel, ensuring accuracy, consistency, and readiness for analysis.
While cleaning the data, the following measures were taken 
- All missing values were replaced with unknown and in columns like currency was replaced with NGN because it constitutes over 90% of the currency column
- All currencies were converted to NGN to ensure uniformity
- All data types were corrected to the appropriate format
  On Power bi, Schemas were created for modelling by creating a data table, a dimension table and relationships to help group important columns and enhanced measures

  ### Data Analysis
  This nvolved exploring the transactions data to answer key questions, such as;
  ...
  -	Which Month generates the most revenue and what merchant category was leading
<img width="257" height="85" alt="monthly revenue " src="https://github.com/user-attachments/assets/eca2b46e-cc16-4a7c-b44b-f4bc04c01d56" />

    
  -	Which merchant category was leading across all months
 <img width="681" height="346" alt="image" src="https://github.com/user-attachments/assets/4566b130-0b2b-4682-b9df-d6110e875145" />

	- Which state generated the most revenue in each month and overall best performing state
    <img width="698" height="225" alt="image" src="https://github.com/user-attachments/assets/6b00461f-722b-4e3a-954c-c91a980f84c5" />
 
    
  - Which payment channel is most effective

    <img width="628" height="360" alt="image" src="https://github.com/user-attachments/assets/8b435a37-cbd8-4e51-a40f-1124240cb149" />

  - Which state and merchant category had the highest fraud rate
 <img width="945" height="811" alt="image" src="https://github.com/user-attachments/assets/dc9f4fa2-e724-4260-9bf4-0882dd8a9639" />

### Key Findings 
There is generally a sucess rate across card transactions, and less fees across ussd transactions. Retail market generally lead in merchant category followed closely by transport, 
and there generally a market boom in the  month of January as it produces the most revenue 

### Recommendations 
-	Keep record of all transaction payment method to enhance payment system and settlement days
-	Invest more in Transport in December/January(end of year) taking advantage of the season to ensure maximum profit
-	Set up fraud detectors in high grossing states and categories to curb the fraud rate
-	Make proper preparations for January traffic to enhance customer satisfaction; it is the highest grossing month and still has one of the lowest settlement days
-	Given the relatively stable settlement performance and potentially lower transaction, costs associated with USSD, there may be an opportunity to strategically increase adoption of this channel to enhance overall margin efficiency, subject to customer behavior and operational capacity considerations.

### Limitatioins 
There were inconsistencies in payment channels and payment methods  which were replaced with unknown, there were also some mmissing currencies and difference in currency

### Refrences 
ERIKODX IT 
  
