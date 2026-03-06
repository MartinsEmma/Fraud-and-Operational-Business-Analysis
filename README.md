# Fraud and Operational Business Analysis
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
Structured Query Language (SQL), Ms Excel(power query), Power bi(Dashboard Creation) 

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
KEY INSIGHTS

A. Transaction Success Rate Stands at 71% with  Consistent Settlements

<img width="252" height="135" alt="pjm" src="https://github.com/user-attachments/assets/3adc74d4-ba0b-4342-aa98-15fdc8c03dee" />

The overall transaction success rate was 71.46% (3,571 successful), with failed, pending, and reversed transactions making up the remainder.Card and Bank Transfer channels achieved approximately 72% success rates, while Wallet and USSD showed slightly lower efficiency. The “Unknown” channel performed best at 75% success, though its volume was minimal. 
Average settlement days remained stable at 0.98 across all payment channels throughout the year, indicating operational consistency despite fraud exposure.


B. Card Payments Drive Highest Revenue but Face Greater Fraud Risk

<img width="266" height="95" alt="chan" src="https://github.com/user-attachments/assets/8dd11a02-ae94-448e-8856-32a927d67bd6" />

 Card transactions generated over ₦35M in revenue, leading all channels, but also carried the highest fraud exposure due to their large transaction volume. Bank transfers followed with nearly ₦27M, while Wallet and USSD contributed smaller shares.

C. Retail Sector Accounts for 36.45% of All Fraudulent Revenue

<img width="173" height="140" alt="ret" src="https://github.com/user-attachments/assets/502c6b16-c3cf-4786-846d-b3211e751df7" />

Among merchant categories, Retail led fraudulent revenue at 36.45% (₦1.65M), followed by E-commerce at 21.94% (₦0.99M), Transport at 16.11% (₦0.73M), Utilities at 13.13% (₦0.59M), and Hospitality at 9.86% (₦0.45M). Retail and E-commerce together account for over 58% of all fraud losses.



D. Lagos Dominates Both Revenue and Fraud Concentration

<img width="206" height="148" alt="hp" src="https://github.com/user-attachments/assets/af505e41-9e7f-4d4c-857d-c4bd1f2f2d06" />
<img width="253" height="84" alt="frd" src="https://github.com/user-attachments/assets/8f4828ff-cf7c-4282-b54b-2bd692db8b1c" />

Lagos State recorded the highest total revenue and simultaneously emerged as the leading fraud concentration zone, followed by Abuja, Port Harcourt, London, and Manchester. This geographic clustering suggests that high-volume markets require stronger fraud controls.




E. Fraud Rate Peaks in January and November

<img width="251" height="86" alt="RAT" src="https://github.com/user-attachments/assets/cc98a104-8e75-4257-a2ac-92b0a71572d4" />

Monthly fraud rate analysis revealed peaks in January (0.063) and November (0.055), with the lowest rates in March (0.038) and October (0.034). This seasonal pattern suggests fraudulent activity intensifies around holiday and year-end periods, a critical insight for scheduling fraud monitoring resources.


F. Top Customer Analysis

<img width="220" height="143" alt="cust" src="https://github.com/user-attachments/assets/67235d9e-ece6-4786-93bd-fed84836e584" />

The top revenue-contributing customers table revealed that CUST1213 led with ₦339,773.44 across 12 transactions, while CUST1691 followed at ₦328,802.18 with only 9 transactions,indicating higher average transaction values. However, CUST1213 was involved in a fraudlent transaction which ought to be investigated.
Total revenue across top customers reached ₦101,175,737.25 from 5,000 transactions 

### Recommendations 
-	Keep record of all transaction payment method to enhance payment system and settlement days
-	Invest more in Transport in December/January(end of year) taking advantage of the season to ensure maximum profit
-	Strengthen Fraud Defenses Across High‑Risk Channels, Categories, and Regions Since the majority of fraudulent revenue originates from Retail and E‑commerce, card payments carry the highest exposure, and Lagos/Abuja record the greatest fraud concentration, a unified strategy is needed. This should include deploying dedicated fraud scoring models for vulnerable merchant categories, implementing velocity checks, spending limits, and anomaly detection for card transactions, and enforcing stricter, real‑time monitoring with enhanced verification (such as two‑factor authentication) in high‑volume regions. Together, these measures create a layered defense that protects revenue while reducing systemic fraud risk.
-	Improve Overall Transaction Success Rate
A 71% success rate means nearly 3 in 10 transactions fail, are pending, or are reversed. Investigating the root causes, which may be network failures, declined cards, or fraud flags could recover significant revenue.
-	Make proper preparations for January traffic to enhance customer satisfaction; it is the highest grossing month and still has one of the lowest settlement days
-	Leverage Top Customer Data for Loyalty Strategy
High-value customers represent disproportionate revenue contribution. A targeted loyalty or retention programme like discounts and promotional packages for top-tier customers could protect and grow this revenue base.


### Limitatioins 
There were inconsistencies in payment channels and payment methods  which were replaced with unknown, there were also some mmissing currencies and difference in currency

### Refrences 
ERIKODX IT 
  
