# Churn_Data_Analysis_with_Prediction_Model
This project aims to demonstrate the seamless use of SQL, Python and Power BI for analyzing customer churn data, training and testing a prediction model and finally reporting findings in a visually appealing way to management

### INTRODUCTION
The company in question is an internet service provider looking to understand why their customers "churn".
"Churn" is the term used to describe when a customer of a company chooses to either discontinue their service or patronize a competing company instead for the same service. There are several reasons why a customer may decide to "churn" and some of these reasons include(but not limited to):

a. Pricing of the Product or service being too high

b. Competing companies having a better product or offer

c. Attitude of the customer care team

d. Poor Quality of Service/Product

e. Other Personal reasons

The Company in this Project is an online entertainment provider looking to figure out why their customers choose competing businesses instead of theirs.

The dataset in this project is called "Customer_Data.csv" and it has the following features:
[Customer_ID,
Gender,	
Age,
Married,	
State,
Number_of_Referrals,	
Tenure_in_Months,	
Value_Deal,	
Phone_Service,	
Multiple_Lines,	
Internet_Service,	
Internet_Type,
Online_Security,	
Online_Backup.
Device_Protection_Plan,	
Premium_Support,
Streaming_TV,	
Streaming_Movies,	
Streaming_Music,	
Unlimited_Data,
Contract,	
Paperless_Billing,	
Payment_Method,	
Monthly_Charge,	
Total_Charges,
Total_Refunds,	
Total_Extra_Data_Charges,	
Total_Long_Distance_Charges,	
Total_Revenue,	
Customer_Status,
Churn_Category,	
Churn_Reason]

### DATASET PREVIEW
![image](https://github.com/user-attachments/assets/3a94e7e6-5597-47dd-974b-22875597636a)

![image](https://github.com/user-attachments/assets/bb81a43b-dbb7-424c-99cc-9982164424f3)

![image](https://github.com/user-attachments/assets/cab94917-3778-438b-ae04-e2be30da61d9)

### TECHNOLOGIES USED
1. Microsoft SQL Server (MSSQL19)
2. Python(Pandas) - python3
3. Microsoft Power BI Desktop

### WORK FLOW
The workflow will be summarized into 10 simple steps:
#### STEP 1: LOAD DATA INTO MSSQL
#### STEP 2: CARRY OUT BASIC EDA
#### STEP 3: LOAD DATA INTO POWER BI
#### STEP 4: TRANSFORM DATA AND BUILD DASHBOARD
#### STEP 5: LOAD DATA INTO PYTHON AND PERFORM DATA PREPARATION
#### STEP 6: SPLIT DATA AND TRAIN MODEL FOR CHURN PREDICTION
#### STEP 7: EVALUATE MODEL 
#### STEP 8: TEST MODEL ON NEW DATASET
#### STEP 9: ADD REPORTS FROM MODEL TESTING TO THE EXISTING DASHBOARD IN POWER BI
#### STEP 10: DOCUMENT AND DELIVER INSIGHTS TO MANAGEMENT

### FINAL INSIGHTS AND RECOMMENDATIONS
DASHBOARD SUMMARY PREVIEW

![summary snapshot](https://github.com/user-attachments/assets/5f719c58-1dcc-4fd2-9283-9f474d3eb56a)


CHURN PREDICTION DASHBOARD PREVIEW

![prediction snapshot](https://github.com/user-attachments/assets/50cb34e1-12ae-473b-8550-6664915afade)


#### INSIGHTS AND RECOMMENDATIONS

1. ﻿for the *Total Customers and Churn Rate by Age Group* customers > 50 years had the highest Total Customers(2,729) and was 2,232.48% higher than < 20, which had the lowest Total Customers at 117.﻿﻿ The two major reasons for this age group churning is that they believe our competitors have better offers and better products. Our offers and products should be reviewed and improved upon to better suit the needs of a family since most of the customers > 50 years are in the married category

2. Our product and offers do not seem to attract customers younger than 20 years of age and this might be a problem because younger customers are usually the biggest consumers of internet and streaming services.We can test with smaller, more affordable data offers catered to younger customers to see if their interest improves
   
3. Internet_service(93.71%),Phone_service(90.59%),﻿﻿Unlimited_data(80.08%) and Paperless_billing(74.60%) customers are churning the most. These might be the major services that we need to review and improve on the most since the data shows a high amount of skew in this direction.
   
4. ﻿﻿Fiber Optics(41.1%) and cable (25.7%) internet type users account for a significant portion(67%) of total churners. These products need to be looked into and improved on in terms of download speed and data offers, however, more analysis should be done to ensure that our data offers are similar or better than those of the competitors or at least our download speeds are higher to make up for average data offers(a better data offer will likely have more positive impact than a faster download speed).
   


﻿


﻿
