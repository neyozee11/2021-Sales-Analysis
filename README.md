# 2021 Sales Analysis

### Project Overview

This data analysis project aims to provide insight into the sales performance of a company in 2021. By analyzing various aspect of the sales data, I seek to identify trends, make data driven recommendations and gain a deeper understanding of the company's perfomance.

## Data Sources

Sales Data: The primary dataset used for this analysis are; "2021-Q1-Sales.csv", "2021-Q2-Sales.csv", "2021-Q3-Sales.csv" and "2021-Q4-Sales.csv" contaning detailed information about each sale made by the company.

### Tools

- PowerBI [Download here](https://powerbi.microsoft.com/en-us/downloads)

### Steps

1. Loaded the source files into the query editor of PowerBI
2. Cleaned data using the following steps:
- Removed blank and unwanted rows
- Used the append feature to combine information from the different source files "2021-Q1-Sales.csv", "2021-Q2-Sales.csv", "2021-Q3-Sales.csv" and "2021-Q4-Sales.csv) into a 
  single file "2021-Sales.csv"
- Gave the columns the appropriate data types
- Renamed the columns to more suitable titles
3. Using the reference, I created three new tables; "2021-Orders", "2021-Products" and "2021-Order-Dteails" from the "2021-Sales" table based on the information needed to have a 
   structured project
4. Removed unnecessary columns from all three newly created tables but also removed duplicate rows from the "2021-Orders" and "2021-Products" table
5. Used the index feature to create a new colum in the "2021-Products" table and the merge feature to create more columns to include the foreign keys into the "2021-Order-Dteails" 
   table
6. Loaded the files into the data model for modelling, analysis and reporting
7. Based on the star schema modelling technique, I connected the primary keys of the "2021-Orders" and "2021-Products" tables to the foreign keys in the "2021-Order-Dteails" table 
   so as to establish a relationship between them
8. Created visuals and reports

### Concepts Applied

- DAX Concepts: Calculated columns and Calculated Measures
- Data Modelling: Star Schema

### Exploratory Data Analysis

- What is the overall sales trend?
- Which products are top sellers?
- What are the city with top sales?

### Results/Findings

The analysis results are summarized as follows:
1. The company's sales as evident in the revenue exhibited a steady increase from January to April, followed by a decline through June, maintaining a relatively stable position until July. Subsequently, there was a further decline until September. From then on, there was a sudden upswing in sales, reaching it's peak in December.
2. The top five products, ranked in descending order based on sales and revenue, are the Macbook Pro Laptop, iPhone, ThinkPad Laptop, Google Phone and 27in 4K Gaming Monitor. Notably, the Macbook Pro Laptop outperforms the second-best product by almost twice the sales."
3. The top three cities with the best sales are; San Francisco, Los Angeles and New York City.

### Recommendations

Based on the analysis, I recommend the following actions for the company:
1. Invest in marketing and promotions

