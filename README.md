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
The datasets used for this project were provided by quantiam analytics and can be both  be downloaded from this repository. 
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
1. Define Metrics and Explore Key Statistics
   - The total sales were 1934415.0000000002
   - Sales by LIFESTAGE and PREMIUM_CUSTOMER: Group data by LIFESTAGE and PREMIUM_CUSTOMER to analyze purchasing patterns.
     LIFESTAGE             PREMIUM_CUSTOMER  TOT_SALES
0   MIDAGE SINGLES/COUPLES           Budget   35514.80
1   MIDAGE SINGLES/COUPLES       Mainstream   90803.85
2   MIDAGE SINGLES/COUPLES          Premium   58432.65
3             NEW FAMILIES           Budget   21928.45
4             NEW FAMILIES       Mainstream   17013.90
5             NEW FAMILIES          Premium   11491.10
6           OLDER FAMILIES           Budget  168363.25
7           OLDER FAMILIES       Mainstream  103445.55
8           OLDER FAMILIES          Premium   81958.40
9    OLDER SINGLES/COUPLES           Budget  136769.80
10   OLDER SINGLES/COUPLES       Mainstream  133393.80
11   OLDER SINGLES/COUPLES          Premium  132263.15
12                RETIREES           Budget  113147.80
13                RETIREES       Mainstream  155677.05
14                RETIREES          Premium   97646.05
15          YOUNG FAMILIES           Budget  139345.85
16          YOUNG FAMILIES       Mainstream   92788.75
17          YOUNG FAMILIES          Premium   84025.50
18   YOUNG SINGLES/COUPLES           Budget   61141.60
19   YOUNG SINGLES/COUPLES       Mainstream  157621.60
20   YOUNG SINGLES/COUPLES          Premium   41642.10

   - Products driving the highetst sales
     PROD_NAME
Dorito Corn Chp     Supreme 380g            40352.0
Smiths Crnkle Chip  Orgnl Big Bag 380g      36367.6
Smiths Crinkle Chips Salt & Vinegar 330g    34804.2
Kettle Mozzarella   Basil & Pesto 175g      34457.4
Smiths Crinkle      Original 330g           34302.6
Cheezels Cheese 330g                        34296.9
Doritos Cheese      Supreme 330g            33390.6
Kettle Sweet Chilli And Sour Cream 175g     33031.8
Kettle Original 175g                        32740.2
Kettle Sea Salt     And Vinegar 175g        32589.0
    - Products driving the least sales
      PROD_NAME
WW Original Stacked Chips 160g              5323.8
WW Sour Cream &OnionStacked Chips 160g      5323.8
WW D/Style Chip     Sea Salt 200g           5249.7
Woolworths Cheese   Rings 190g              5169.6
Snbts Whlgrn Crisps Cheddr&Mstrd 90g        5076.2
WW Crinkle Cut      Chicken 175g            4702.2
Sunbites Whlegrn    Crisps Frch/Onin 90g    4600.2
WW Crinkle Cut      Original 175g           4532.2
Woolworths Mild     Salsa 300g              4234.5
Woolworths Medium   Salsa 300g              4050.0

2. Data visualization
   1. Top 10 Products by Sales

      ![image](https://github.com/user-attachments/assets/3081fa65-0b8f-4a4b-bd18-07bed55a75db)

   2. Total Sales by Segment (LIFESTAGE and PREMIUM_CUSTOMER)

      ![image](https://github.com/user-attachments/assets/917b6936-8645-4f17-b308-2d4d192235d2)




