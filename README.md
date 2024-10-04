# LITA_CLASS_DOCUMENTATION

## Project Title: E commerce Sales Analysis

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

### Project Overview
---
This purpose of this project is to gain insight into the performance of sales over the past year. By carrying out queries based on various parameters we aim to analyse and draw insight to help drive decison making and tell compelling stories from our data.

### Data Sources
---
The primary source of data used is Sales.csv, which is an open souce data that can be download from Kaggle or FRED or any other data repository.

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
    1. For Data Cleaning
    2. For Analysis
    3. For Data Visualization
       
- SQL- Structured Query Language for Querying of data
- GitHub for portfolio building

### Data Cleaning and Preparations
---
In the first phase of Data Cleaning and preparations, the following actions were carried out;
1. Data loading and inspection
2. Checking missing values
3. Data Cleaning and formatting

### Exploratory Data Analysis
---
EDA involved exploring the dataset to answer some questions such as;
- What is the overall sales trend
- Which products are top sellers
- What are the products on peak sales?

### Data Analysis
---
This is includes some basic lines of code or queries used during analysis;

```SQL
Select Sum (Profit) As TotalProfit From International_Breweries
where COUNTRIES = 'Senegal'
```

