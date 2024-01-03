# Telecom Customer Churn Prediction

## Project Overview:
The "Telecom Churn Dashboard" in Tableau is a data visualization project designed to analyze and understand customer churn patterns in the telecom industry. 
The dashboard provides a comprehensive overview of customer churn, helping telecom companies identify factors that contribute to customer attrition and develop strategies to retain valuable customers.<br>

## Problem Statement:
In the telecom industry, customers have the flexibility to select from a range of service providers and frequently change operators.  This dynamic market experiences an average annual churn rate of 15-25%. Considering the significantly higher cost of acquiring new customers compared to retaining existing ones (5-10 times more), customer retention has become a top priority.
The Primary objective of telecom industry operators is the retention of high profit customers. To address customer churn, telecom companies must proactively predict which customers are at a higher risk of leaving. <br>

## Business Description:
Telecom operators are companies that provide communication services, such as voice, data, and messaging, to customers. They operate extensive networks, including cellular towers and fiber optic cables, to ensure seamless connectivity. Their primary focus is to offer reliable and high-quality services to individuals and businesses, while staying competitive in a rapidly evolving market by investing in network expansion and embracing new technologies. 
Telecom operators also play a crucial role in enabling internet connectivity and driving digital transformation across various industries. <br>

## High level architecture diagram:
![Flowcharts (1)](https://github.com/ashwinjai/Telecom-Customer-Churn-Prediction/assets/36980518/1d7a25be-fce6-4366-afa1-43ce7bdb8280)

## Data Ingestion:
The raw data is stored in the local file system, and an AWS Linux-based instance is launched to establish a connection and transfer the on-premise data to an S3 bucket. The S3 bucket serves as a storage container for the raw data. Subsequently, a connection is set up from Tableau to access the data in the S3 bucket, enabling data feeding to the Tableau engine for chart development and visualization. <br>

![Upload_Gif](https://github.com/ashwinjai/Telecom-Customer-Churn-Prediction/assets/36980518/7c8a4873-6e49-4486-a789-61cbaea7629d)





## Tableau Connection:

![S3_Bucket](https://github.com/ashwinjai/Telecom-Customer-Churn-Prediction/assets/36980518/60487c03-d76a-412c-99db-a7eec3efa055)




## Tableau Screenshot
![Screenshot 2024-01-03 064007](https://github.com/ashwinjai/Telecom-Customer-Churn-Prediction-/assets/36980518/ba3d75d7-a4fe-46bc-b3a7-f9f14977cab9)
 <br>

![ezgif com-optimize](https://github.com/ashwinjai/Telecom-Customer-Churn-Prediction/assets/36980518/c7a3eda1-29af-4549-bf67-5aaeb1425c3b)


## Key Metrices:

![image](https://github.com/ashwinjai/Telecom-Customer-Churn-Prediction-/assets/36980518/7bdc556c-a04d-49eb-9d30-7568dc72f4a4)

**1.1 Churn Rate** It's business metric that calculates the percentage of customers or subscribers who stop using a product or service over a given period of time.Churn Rate for female (27%) is higher than male(26%) and the lowest churn rate observed for Young Adult (22%), Middle-aged adult (24%), Old-Aged adult (30%). <br> 

**1.2 Customer retention Rate** This metric that measures the percentage of customers a business retains over a specific period.  Customer retention Rate is higher for young-adult (71%), followed by Middle-aged adult (68%), Old-Aged adult (65%)  <br>

**1.3 Average Revenue Per User (ARPU)** ARPU measures the average revenue generated by each customer or user over a specific period, typically on a monthly or yearly basis. Average Revenue spent per user is appox. 3,034$. Old-Aged adult spent $3,118, followed by young-adult $2,981 and  Middle-aged adult $2,922. Stayed Customer spent $3,736, followed by Churned Customer spent $1,971 and Joined customer spent $120. <br>

**1.4 Average Long Distance Charges** It measures average amount of money a customer spends on long-distance phone calls or communication services over a specific period. Middle-aged adult Spent highest $754. Stayed Customer spent $942 , Churned Customer spent $434 <br> 

![image](https://github.com/ashwinjai/Telecom-Customer-Churn-Prediction-/assets/36980518/004e4a5d-0363-4bca-8bbf-9767052b0125)


**2.1 Tenure Bins** It categorizes customers based on the length of time they have been with a company.This segmentation helps businesses analyze customer behavior, preferences, and engagement patterns at different stages of their relationship with the company. From the Dashboard we can see trend in Gender Category, Male and Female which is from 0 to 5 months Male and Female associated with company 6% each and show decreasing trend. young-adult, Middle-aged adult & Old-Aged adult Categeory associated with company for tenure for 5year is 2%, 4% & 2% Respectively. Churned Customer stayed with company 7% for period of 0 -5 months and shows decreasing trend and stayed customer show stable trend between 4% and 3%. Highest seen is 7% <br>


**Average Monthly download** <br>
**Contract Terms** <br>
**Churn Category by Age Group** <br>



