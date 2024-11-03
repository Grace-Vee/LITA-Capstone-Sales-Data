# LITA-Capstone-Sales-Data

## Project Title: LITA Human Resource Data

## Outline
[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Data Description](#data-description)

[Tools used](#tools-used)

[Data Cleaning and preparation](#data-cleaning-and-preparation) 

[Data Transformation](#data-transformation)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Table](#table)

[Insights](#insights)

[Recommendations](#recommendations)

### Project Overview
---
This project analyzed the sales performance of a retail store, aimed at addressing the issues of poor sales, and uncovering key insights such as top-selling products, regional 
performance, and monthly sales trends that could help incresae sales across all regions. The analysis includes deriving various objectives to understand the underlying issues, that 
would enable us proffer solutions, propose actionable recommendations, and directs us on products to focus on.

### Data Sources
---
Data used for this project was an excel data provided by the Incubator Hub LITA facilitators, the data was converted to CSV format, to be imported to SQL and make it eaccessible for analysis.

### Data Description
---
- The dataset includes the following fields:
    1. Customer ID : Unique identifier givemn to each customers
    2. Products: Items sold in the retail store
    3. Region: Regions sales were made from
    4. Order Date: Dates transactions were made
    5. Quantity: Quantity of products been sold
    6. Unit Price: Price per items
    7. Total Sales: Total amount of sales made for the items

### Tools used
---
-  Microsoft Excel [Download Here](https://www.microsoftexcel.com)
     1. For Data Input
     2. For Analysis
     3. For Data Cleaning
     4. For Data visualization
-  Microsoft SQL Server [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
     1. To manage and querry data 
-  Microsoft Power BI [Download Here](https://www.microsoftpowerbi.com)
     1. For Data Transformation
     2. Data modelling
     3. To Create reports and dashboards that are collections of visuals.
-  GitHub [Download Here](https://www.github.com)
     1. For Portfolio Building

### Data Cleaning and preparation
---
During the initial phase of the data entry, the folowing actions were performed
     1.  Data quality was ensured by correcting any spelling errors, removing duplicate entries, and addressing 
         missing values.
     2.  Standardization: Used find and replace to standardize certain fields
     3.  Data import from Excel to SQL and Power BI
     
### Data Transformation:
 ---
 - Data was transformed to thoroughly clean, remove issues with data and increase column quality, column distribution and profile to 100%
      1. Data Types and Formatting: This was done to ensure all data fields were assigned the correct data types, with numerical fields formatted as whole numbers, text as text
          and date fields set to date format. 
      3. Sorting: Sorted the dataset by the Date column to organize transactions chronologically.
      4. Created New Columns: Added a new column to have more calculations like Revenue

### Data Analysis
---
Some of the code used to analysed the data are:
```Excel
VLOOKUP(lookup_value,table_array,col_index-number,[range_lookup])
LEFT(text,[num_char])
SUMIF(range,criteria,[sum_range])
```
```SQL
SELECT * FROM [dbo].[LITA Capstone Dataset (1) CSV]
WHERE condition = True

select Region, count (*) As
Total_Sales_Transactions
From [dbo].[LITA Capstone Dataset (1) CSV]
group by Region
```
```Power Bi
Total Customer = COUNT('Customer Data B'[CustomerID])
Total Revenue of Sales = SUM('Sales Data B'[Total sales])
```

### Data Visualization
---
![sales data](https://github.com/user-attachments/assets/4a39c2d2-c89f-4e7c-b55d-b761ad7a5e96)

![sales Pivot](https://github.com/user-attachments/assets/0b0c1986-2ea1-470a-b2df-bd969ee7f0c2)

![Sales Visual](https://github.com/user-attachments/assets/2fd28311-13c9-49c6-bd08-e12dbc35a252)

![sales chats](https://github.com/user-attachments/assets/9fe72e3e-27fe-46d0-8c5d-fd97a2db2364)

![sales SQL 1](https://github.com/user-attachments/assets/4ba6010c-3b54-4c9d-8272-5331fad24469)

![sales SQL 3](https://github.com/user-attachments/assets/0d49d72f-04c9-4142-98bc-27416aea075f)

![sales SQL 4](https://github.com/user-attachments/assets/9d24d697-ede9-441b-9ed3-caf14fe8c8c4)

![sales SQL 5](https://github.com/user-attachments/assets/0de4d157-aa46-43a9-a524-4539ff82bc6b)

![sales SQL 6](https://github.com/user-attachments/assets/4a88e5ff-b0fd-4fed-b123-f1889dc8899a)

![sales SQL 7](https://github.com/user-attachments/assets/dc6261cd-0f81-42cf-851c-4d92ddc8f135)

![sales SQL 8](https://github.com/user-attachments/assets/8be58cd9-8c5e-4934-9f84-f8a6147ee2ba)

![sales SQL](https://github.com/user-attachments/assets/5f355db7-15a6-4f0a-9abe-0c0c0479b609)

### Insights
---
-The visual showed:
   1. Sales Revenue; Total revenue of sales is 2 million naira, while average sales is 211.8 naira,, which showed the store to be performing moderately okay, but a lot need to
     be put in place to increase the performance of the store.
   2. Top selling products: Top selling products of the store are shoes, shirts and hats, these products need to be stocked up more to increase the sales performance of the store
   3. Low Selling products: Low selling products are socks and jackets, these products should be stocked moderately to reduce having them in shelf for a long time.
   4. Regional Performance: South has the highest regional performance, followed by East, while West has the lowest performance by regions.
   5. Monthly sales Trends: February has the highest sales, followed by July then January, probably because of their dry weather condition, which would require customers to purchase 
       more light cloths like shirts and shoes, to protets their feets from the harsh rays of february sun.
 
### Recommendations
---
- The followings were recommended based on findings from the Data Analysis, which enabled us took informed decisions such as:
   1. Aggressive Marketing: Aggressive marketing should be carried out accross all regions and this should be more intense in regions with low performance, to boost sales.
   2. Product Awareness: Awareness, promotions, loyalty rewards, and targeted marketing should be carried out on products with low sales, to increase their performance and drive 
     growth.
   3. Product stock: The shop should focus on stocking more of products with high performance and stock less of low selling products, to ensure availability of these products at all 
     times, to increase sales performance
   4. Seasonal Perdformance: Seasonal trends should be studied, shirts and shoes which are the highest selling products should be well stocked up at all seasons, mostly in february.
   5. Price increment: Prices of top selling products should be increased at seasons when they are in high demands, to break even and increase sales performance
   6. Reliable suppliers of high selling products should be gotten, to ensure that these products are always available to customers to avaoid out of stock.

 ### Thank You
---
