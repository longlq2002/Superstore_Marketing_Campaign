# Superstore_Marketing_Campaign
###  1. Scenario
#### Context: A superstore is planning for the year-end sale. They want to launch a new offer - gold membership, that gives a 20% discount on all purchases, for only 499 dollars which is 999 dollars on other days. It will be valid only for existing customers and the campaign through phone calls is currently being planned for them. The management feels that the best way to reduce the cost of the campaign is to make a predictive model which will classify customers who might purchase the offer.
#### Objective: The superstore wants to predict the likelihood of the customer giving a positive response and wants to identify the different factors which affect the customer's response. The dataset has 2240 rows and 22 columns, whose name is "superstore_data.csv". We will use machine learning classification model (Logistic Regression) to achieve this goal.

### 2. Dataset
#### This data was gathered during last year's campaign.
- Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise
- ID - Unique ID of each customer
- Year_Birth - Age of the customer
- Complain - 1 if the customer complained in the last years
- Dt_Customer - date of customer's enrollment with the company
- Education - customer's level of education
- Marital - customer's marital status
- Kidhome - number of small children in customer's household
- Teenhome - number of teenagers in customer's household
- Income - customer's yearly household income
- MntFishProducts - the amount spent on fish products in the last years
- MntMeatProducts - the amount spent on meat products in the last years
- MntFruits - the amount spent on fruits products in the last years
- MntSweetProducts - amount spent on sweet products in the last years
- MntWines - the amount spent on wine products in the last years
- MntGoldProds - the amount spent on gold products in the last years
- NumDealsPurchases - number of purchases made with discount
- NumCatalogPurchases - number of purchases made using catalog (buying goods to be shipped through the mail)
- NumStorePurchases - number of purchases made directly in stores
- NumWebPurchases - number of purchases made through the company's website
- NumWebVisitsMonth - number of visits to company's website in the last month
- Recency - number of days since the last purchase
