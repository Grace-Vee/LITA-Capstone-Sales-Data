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

![Sales Visual](https://github.com/user-attachments/assets/58222fc8-b20c-44b5-91dd-953efeafb668)


