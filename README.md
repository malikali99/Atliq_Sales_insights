# **`AtliQ (Hardware Company) Sales Insights`**

<p align="center">
<img src="./Atliq_logo_for_dashboard.png" alt="Atliq" width="300" height="200">

**`Author Name:`** Malik Hasnain Ali\
**`Email ID:`** 512yaali@gmai.com\
**`Linkedin profile:`** [hasnainali99](https://www.linkedin.com/in/hasnainali99/)


**`Company Introduction:`**
- Atliq hardware is a electronic accessories company. AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

**`Current Callenge:`**
- The Challenge is to create a dashboard according to the requirements provided by stakeholders in the business review meeting.

<p align="center">
<img src="./sales.gif" alt="Atliq" width="800" height="400">

**`Data Source:`**\
It is a secondary data which is collected from the following [link](https://www.kaggle.com/datasets/mohdsuhailmasroor/atliq-hardware)

**`Data Collection:`**\
Data collected can be seen as a raw SQL text file here

**`Data Storage:`**\
The collected data has been stored in the SQL database named as db_ump_version_2.

**`Data Publish Year:`**
- 2022
  
**`Tools:`**
- Power BI
- Kaggle
- MySQL
- EXcel
- Powerpoint
- Data Modeling(Power BI)
- Data Cleaning(Power BI)

**`Data Cleaning/Preparation:`**\
In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection
2. Handling Missing values
3. Handling Outliers
4. Data Cleaning and formating

##### **`Features:`**
---------------------------------------------------------------------------------------------

**dim_customers:**
1. customer_id: Unique ID is given to each customer
2. customer_name: Name of the customer
3. city: It is the city where the customer is present

---------------------------------------------------------------------------------------------------

**dim_products:**
1. product_name: It is the name of the product
2. product_id: Unique ID is given to each of the products
3. category: It is the class to which the product belongs

---------------------------------------------------------------------------------------------------

**dim_date:**
1. date: date at the daily level
2. mmm_yy: date at the monthly level
3. week_no: week number of the year as per the date column

---------------------------------------------------------------------------------------------------

**`Acknowledgements`:**
I would like to thank [Ashish Yadav](https://www.kaggle.com/ashishyadav1993) for helping me collecting data
