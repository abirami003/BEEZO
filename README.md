# Bakery Data Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Recommendations](#recommendations)

### Project Overview

Analyze bakery performance to understand sales trends, customer preferences, inventory management, and operational efficiency. The goal is to improve profitability and customer satisfaction

### Data Sources

Bakery Data: The primary dataset used for this analysis is the "Bakery data.xlsx" file from kaggle, containing detailed information about bakery items and sales person

### Tools

- Excel - Database Manageemnt [Download Here](https://microsoft.com)
- Power Query Editor - Data Cleaning and Analysis
- Power BI Desktop - Creating Reports [Download Here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

### Data Cleaning/Preparation

In the initial data preparation, I performed the following tasks
1. Data Loading and Inspection
2. Handling missing values
3. Data cleaning and formatting

### Data Analysis

Some interesting code/feature worked with:

```dax
TOTAL SALES = SUM('Sales Data'[Sales Amount])
```
```dax
TOP PRODUCTS = TOPN(10, 'Sales Data', 'Sales Data'[Sales Amount], DESC)
```
```dax
TOTAL SALES = SUM('Sales Data'[Sales Amount])
```

### Results/Findings

The analysis results are summarized as follows:
- Most of the customers prefers Puff&Samosa
- November is the top-performing month in terms of sales
- Sales person Sharan generates more revenue compared to others
- Vallore District tops the sales rankings

 ### Recommendations

 - To improve performance in May and June, launch targeted promotions or special offers that cater to seasonal trends 
 - Low Perfomers are Varadarajan, Abbas, and Mohammad. To improve their performance: provide focused training tailored to their specific challenges, set clear and measurable goals, and schedule regular check-ins for progress assessment. If necessary, consider reassigning them to roles that better match their skills.
 - Low selling products are Brownies,Donuts and Pudding, To boost the sales offer with 10% discount


🍰 | 🧁 | 🍫 | 🍞 | 🥞

😃
 
⌨️ & 🖱️
