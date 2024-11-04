# LITA_CLASS-DOCUMENTATION FOR EXCEL

## PROJECT TITTLE: Sales Data Analysis Project

[PROJECT OVERVIEW](#project-overview)

[DATA SOURCES](#data-sources)

[TOOLS USED](#tools-used)

[DATA CLEANING AND PREPARATIONS](#data-cleaning-and-preparations)

[EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)

[DATA ANALYSIS](#data-analysis)

[DATA SUMMARIZATION](#data-summarization)

[DATA VISUALIZATION](#data-visualization)

[INFERENCES](#inferences)

[CONCLUSION](#conclusion)

### PROJECT OVERVIEW
This Data analysis Project aims to generate insight into the sales performance, the sales categories; to detemine the rate of the sales in each regions using low, medium and high categories. it is also aimed to determine the following: 
   -Revenue by the regions, market and model and trade dates.
   - Region by unit sold
   - Region by average revenue.
---

### DATA SOURCES
The primary source of data used in the projects are data.sales.cv and this is an open source data that can be freely downloaded from open source online such as kaggle or FRED or any other data respository site.

----

### TOOLS USED
- Microsoft Excel [Download Here](https://www.microsoft.com) 
   1. For Data cleaning
   2. For Data Analysis
   3. For Data visualization
      
----

### DATA CLEANING AND PREPARATIONS
In the initial phase of the data cleaning and preparation, the following actions was performed;
   1. Data loading and inspection
   2. Handling missing variables
   3. Data cleaning and formatting
   4. Removing duplicate

### EXPLORATORY DATA ANALYSIS
This analysis is meant to answer the followimg questions:
   - The average revenue 
   - Total revenue generated in each region
   - The highest selling locations
   - Sales performance of each region
   - Revenue by month

----

### DATA ANALYSIS
```
Sales categories = IF(J2<=20,"low",IF(J2<=50,"Medium","High"))
```
----

### DATA SUMMARIZATION
###### Pivot Table

##### 1. Revenue By Region

![image](https://github.com/user-attachments/assets/ba54d1ad-67f1-413f-a88b-a6691e85fa2f)


##### 2. Unit Sold by Region

![image](https://github.com/user-attachments/assets/ec21a2ba-aeda-425c-9568-7ea246668b62)

##### 3. Top Ten Stores by Revenue
![image](https://github.com/user-attachments/assets/16382979-3fd1-43e6-a0c1-bb357173b64f)

----

### DATA VISUALIZATION
##### 1. Filter Chart for 2014
![image](https://github.com/user-attachments/assets/9317e60c-2d52-48a5-b88a-42d5296dc76f)

##### 2. Filter Chart for 2015
![image](https://github.com/user-attachments/assets/1613f3bc-fafa-437f-9265-daf1b13b95e1)

----

### INFERENCES
1. REGIONAL PERFORMANCE: NorthEast has the high sales performance with the sum of 18.64bn for the year 2014 and 2015.
   North Central has the lowest sales performance for two years with the sum of  6.49bn.
   The sales performance of North East Region decrease from 12.64bn in 2014 to 6.00bn in 2015. This might be as a result of some market challenges faced by the business in the year 2015.
   This drastical decrease in the North East was evident in the other regions.

2. STORE PERFORMANCE: Using the pivort table to summarize the data, the top ten stores was listed in respect to the revenue. Ankpa Store was the top of list with revenue of 1.71bn, and Askira/Uba Store was the last in the list with revenue of 909.54m.

----

### CONCLUSION
At the end of the analysis, the result gotten showed that the sales petrformance in the year 2014 was higher than the sales in the year 2015 in all regions.

   



















   




