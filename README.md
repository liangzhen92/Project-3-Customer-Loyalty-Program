# Project 3: Customer Categorization

### Background: 
Categorize customers to help merchants to offer promotions or discounts to cardholders. 

### Focus:
1. Uncover signal in customer loyalty to identify the most 'valuable' individuals. 
2. Create the right experience for customers. Provide specifically tailored promotions on most relevant merchant.

### Data:

Data is available on Kaggle: [link to Kaggle Competition](https://www.kaggle.com/c/elo-merchant-category-recommendation/data)
All data is simulated and fictitious, and is not real customer data. 

##### Data File Descriptions: 

* train.csv - the training set
* test.csv - the test set
* historical_transactions.csv - up to 3 months' worth of historical transactions for each card_id
* merchants.csv - additional information about all merchants / merchant_ids in the dataset.
* new_merchant_transactions.csv - two months' worth of data for each card_id containing ALL purchases that card_id made at merchant_ids that were not visited in the historical data.

### Other Features: 
Number of Observations: ~ 20 million

Features/ Predicting Variables: Around 30

###### Highlight of Key Features:
 
* Card_id - prime key
* Target_binned - loyalty category: good, bad, neutral
* Month of first purchase
* Authorized_flag - Y: Approved, N: Denied
* Purchase_amount
* State_id
* Merchant_id
