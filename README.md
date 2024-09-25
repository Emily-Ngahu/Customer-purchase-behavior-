# Customer-purchase-behavior-
![image](https://github.com/user-attachments/assets/d5b203d7-4a7c-434d-ab95-57762f8a51f6)

## Project Aim
To conduct a comprehensive analysis of transaction and customer data, ensuring data integrity and identifying key trends and insights that will inform targeted marketing strategies. The project seeks to enhance understanding of customer purchase behavior, optimize product offerings, and ultimately drive sales growth by recommending specific customer segments for focused engagement.

## Project Overview
This project focuses on analyzing transaction and customer data to uncover actionable insights that will enhance our marketing strategies and drive sales growth. The primary objectives are to ensure data quality, identify trends in customer behavior, and develop targeted recommendations for engagement.
Key Phases:
1. Data Cleaning and Preparation:
   - Examine transaction and customer data for inconsistencies, missing values, and anomalies.
   - Clean and merge datasets to create a unified data source for analysis.
2. Data Analysis:
   - Define key metrics such as total sales, sales drivers, and customer segments.
   - Utilize visualizations (charts and graphs) to explore data trends and identify significant insights.
3. Customer Segmentation:
   - Perform a deep dive into customer segments based on purchasing behavior.
   - Analyze packet sizes and their relevance to customer preferences.
4. Recommendations:
   - Develop actionable recommendations targeting specific customer segments.
   - Formulate strategies to optimize product offerings and enhance customer engagement.
## Data
The datasets used for this project were provided by quantiam analytics and can be bothe downloaded from this repository. 
## Data description
### Trasaction data
The transaction data has the following columns:
1. DATE - The date on which the transaction occurred.
2. STORE_NBR - A unique identifier for the store where the transaction took place.
3. LYLTY_CARD_NBR - Loyalty card number associated with the customer.
4. TXN_ID - A unique identifier for each transaction.
5. PROD_NBR - Product number that identifies the specific item sold in the transaction. 
6. PROD_NAME - The name of the product sold.
7. PROD_QTY - The quantity of the product sold in the transaction. 
8. TOT_SALES - The total sales amount for the transaction.
### Purchase behavior 
The purchase behavior Data has the following columns: 
1. LYLTY_CARD_NBR - Loyalty card number associated with the customer.
2. LIFESTAGE - A categorical descriptor indicating the life stage of the customer
3. PREMIUM_CUSTOMER - This indicates the classification of customers based on their purchasing habits and spending capacity. 
## Tools used
1. Python

## Data cleaning
1. Checked for missing values - there were no missing values
2. Checked for duplicates - there were no duplicates
3. Checked for outliers - This was done by ceating box plots of the numerical columns
   - The total sales column has outliers but that is no cause for alarm since there can be very high and very low total sales. 
4. Checked for incorrect formarts, errors, and data types to ensure consistency and acuuracy of the data.
   Since the data is okay, we merge the two dataframes. 
## Exploratory Data analysis
