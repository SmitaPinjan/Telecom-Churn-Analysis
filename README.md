# Telecom Churn Analysis

Analysis of Telecom customer's data using the Python and Tableau tool

### Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Visualization](#visualization)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [References](#references)

---
### Project Overview 
---
The churn rate is the rate at which customers stop doing business with a company.  Even though the company may gain a new customer base but will not increase revenue if existing customers are leaving the company. It's easier to retain customers than attract new customers. Therefore, Churn Analysis is a crucial aspect of understanding customer behaviour and improving retention.
By analyzing various aspects of the Telecom data, I seek to identify the churn rate, causes, customer behaviour, and trends using Python and Tableau.

### Problem Statement
The telecom company has been facing high customer churn over the past few years.  Through marketing and different promotion campaigns, the company attracted new customers but was not able to generate revenue. So, as a data analyst, I am trying to identify the churn rate and possible causes and provide an effective way to find answers to their day-to-day questions and provide insights.

### Data Sources 
Telecom Data: The primary dataset used for this analysis is the "Telecom-Data.xlsx" file,
Containing telecom customer information. The dataset is used from Kaggle.com and can be downloaded from here-
https://www.kaggle.com/datasets/lampubhutia/telecomcustomer-churn
The dataset contains 21 different data type columns and 7043 unique customer records.

### Tools 
Tools used for Data Cleaning, EDA, and Visualization :
- Python
- Tableau (Dashboard)

### Data Cleaning
In the initial data preparation phase, I performed the following tasks using Python:
- Data loading and inspection,
- Describing and checking data frame,
- Changing data values and types from Categorical (object, Boolean) to Numerical those containing numeric values in,
- Optimizing and handling the dataset by replacing empty values,
- Standardizing abbreviations used in the dataset,
- Data cleaning and formatting,
- EDA & Visualization

### Exploratory Data Analysis

EDA involved exploring the Telecom data to answer key questions, such as:

- What are the churn rate, customer behaviour, and demographic segmentation trends?
- What are other factors that can affect the churn rate like Contract Length and billing payment behavior?
- What are Service Usage patterns?
  
### Visualization
Also, performed the visual analysis using Python libraries like Matplotlib and Seaborn.
Visualized and Created a customized dashboard in Tableau using a cleaned data file.

![image](https://github.com/SmitaPinjan/Telecom-Churn-Analysis/assets/152721562/66f2629a-b957-4a5a-ba47-7b2056756628)

![image](https://github.com/SmitaPinjan/Telecom-Churn-Analysis/assets/152721562/ff8e98cb-ead7-460a-85f2-4da10c3bfc09)

![image](https://github.com/SmitaPinjan/Telecom-Churn-Analysis/assets/152721562/ab4bb5da-dd02-4f66-bd7d-a7f4acecb2c1)

The presentation file is included here for reference - [Telecom Churn Analysis.pptx](https://github.com/SmitaPinjan/Telecom-Churn-Analysis/files/15052666/Telecom.Churn.Analysis.pptx)

Tableau Dashboard link - https://public.tableau.com/views/Telecom_ChurnAnalysis/TelecoChurnAnalysis?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

### Insights

To Summarize:
-	Recent customers with a monthly rate of 75 or more with a ‘Month to month’ contract were showing high trends of churn.
-	Young to mid-age customers with no partner or dependent who had ‘Phone Service’, ‘Streaming TV’, and ‘Streaming Movies’ had high churn rates.
-	Customers who are comfortable using online payment methods are more likely to churn. 

Detailed analysis results are summarized below:
 #### Demographic Segmentation
- The company had 7043 unique customer records. Churned customers count was 1869 (27%) and loyal customers were 5174 (73%).
- A 27% Churn rate is a very bad rate and can make the company go bankrupt.
- Interestingly, the young or non-elderly customers had a 75% churn rate compared to elderly customers who left the company.
- Gender did not impact the churn rate.
- Recent customers have had a high churn rate ranging from 20-41% with a tenure of 1-6 months. Indicating that recent customers are more prone to leave the company within a few months. 
- Customers living with their partners or dependents are less likely to churn than compare to those who are living alone (60% churn rate)

#### Service Usage pattern 
- Customers with just a “Phone service” had the highest churn rate of 91%.
- Customers with muli-line service are less likely to churn especially customers having ‘Online Security’, ‘Tech Support’, and ‘Online Behaviour’. However, customers having ’Streaming TV’ and ‘Streaming Movies’ had a 44% churn rate.
- Interestingly, Customers having Fibre Optic Internet had the highest (69%) churn rate compared to those slow network services like DLS.

#### Monthly charges, Contract, Payment, and Billing Method 
- Customers having monthly charges of 75 or more are more prone to churn. 
- Customers who had total charges pending up to 3,000 shown high churn rate than those with high total charges.
- Customers with short-term contracts like ‘Month-to-month’ had higher churn behaviour than long-term contracts.
- Customers who pay using online portals had a high churn rate especially those who pay bills using ‘Electronic checks’.
- Surprisingly, customers who pay using ‘Mailed checks’ had fewer monthly charges, low tenure, and a 16% churn rate.
- Customers who opted for paperless billing had shown more trends of leaving the company.

### Recommendations

Based on the analysis, I recommend the following actions:
- The company must focus on retaining recent and non-elderly customers with short-term contracts. 
- Management can probably deploy some new programs, perks, or benefits for existing customers, especially those paying using online portals and had ‘Phone Sevice’,  ‘Streaming TV’, and ‘Streaming Movies’  to ensure they will not leave the company.
- Management can look and investigate competitors' pricing and promotions and market trends to further analyze why customers are churning.
- Need to further analyze why there were low payments and low total charges for customers who pay using ‘Mailed checks’. It might give some underlying issues.

### References
- Kaggle
- Coursera Capstone Project

|Heading1|Heading2|
|--------|--------|
|Content |Content2|
|Data Analysis| Python|
|Visual Analysis| Tableau|

