# Marketing-Campaign-Insight-Analysis
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSg1Ww_wwUfgcooxvxmP15ErJPBl3_zIaHp5A&s)
![](images/marketing.png)

## 1. Introduction
The Marketing Campaign Insight Analysis Dashboard, built in Power BI using data from marketing_campaign.csv file, provides a clear, centralized view of campaign results. This dashboard helps business what works, make smarter marketing decisions and boost their marketing ROI.
## 2. Data description
Before analyzing, please read the data description below:

Attributes

**People**
- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise
  
**Products**
  
- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years
  
**Promotion**
  
- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
  
**Place**

- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to company’s website in the last month

## 3. Insights & Actionable Insights
### Overall (Cards)
![](images/marketing_1.png)
- Total Spending: **1 Million**
  - Total spending of all customers in last 2 years
  - Significant spend => it is promising for further optimization or expansion
- Number of Customers: **2237**
  - Large enough sample size for analysis
- Average of Recency: **49.10**
  - Average number of days since the last purchase of customers
  - Quite high => it means that customers have returned less recently
- Average of Age: **55.10**
  - Relatively older customer base => The business should choose appropriate messages, products

### Accepted Campaigns (Pie Chart)
![](images/marketing_2.png)
- Insights:
  - Campaign 2 was clearly a failure, with significantly lower adoption rates (only **4.5%**, **30**)
  - Campaign 3,4 and 5 performed similarly and really well (over **24%**)
- Actionable Insights:
  - Using A/B Testing for Campaign 2 content with 2 versions: 1 version that re-uses the message from Campaign 3 (which is performing well), 1 version that adjusts the current content (e.g changes the offer, language, delivery channel...) => **Objective**: Evaluate whether ppor performance is due to content or timing/channel.
  - For Campaign 3,4 and 5, group of customers who accepted these campaigns, analyze common characteristics: age, income, marital status, number of purchases... From there, build effective target customer portraits for the following campaigns. Re-use content from these campaigns for customer groups with similar features => **Objective**: Increase ROI by targeting more precisely, leveraging proven effective content.

### Income and Spending by Customer (Scatter Plot)
![](images/marketing_3.png)
- Insights:
  - Positive correlation between Income and Spending, when income increases, spending also increases.
  - Most customers are in the 100K–400K income group, spending under 6K.
  - Some customers have high income but low spending → have not fully exploited their potential.
  - There are customers who spend unusually high despite not having a very high income → a potential heavy spender group.
- Actionable Insights:
  - Focus the campaign on the 200K–400K income group: large, spends quite a bit → easy to convert.
  - Design special offers for the high income but low spending group: stimulate demand with VIP services, premium offers.
  - Retain the unusually high spending group with loyalty points and promotions.
  - Segment by demographic characteristics (gender, education, marriage...) to deeply understand spending behavior by each segment.

### 
