# Plant Co. Sales Performance Analysis

The objective of this project is to analyze the sales performance of Plant Co. over the year of 2024 across different countries and product types. The goal is to identify trends, evaluate the company's performance in terms of sales, quantity, and gross profit, and provide insights into account profitability.

## Questions Addressed
### Sales Trends:

How have sales performed year-to-date (YTD) compared to the previous year-to-date (PYTD)?
Which countries are the top and bottom performers in terms of sales?
How do sales vary across different product types (indoor, landscape, outdoor)?
### Quantity Trends:

How has the quantity of products sold changed over the months?
Are there specific countries or products where the quantity sold has significantly increased or decreased?
### Gross Profit Analysis:

What is the gross profit percentage (GP%) across different countries and product types?
How does account profitability vary in relation to sales and GP%?
## Data and Methods
The analysis was conducted using data from Plant Co.'s sales database, which includes information on sales amount (USD), quantity sold, cost of goods sold (COGS), product details, and account information. The data model includes the following tables:

Fact_Sales: Contains sales transactions with details like account ID, product ID, sales amount, quantity, and COGS.
Dim_Accounts: Contains account information including country and geographical details.
Dim_Products: Contains product information including product family, group, and type.
Dim_Date: Contains date information for time-based analysis.

## Results

![image](https://github.com/user-attachments/assets/6d2ac41b-1260-4858-8c4e-3e709adc75e9)


### Sales Performance
YTD Sales: The total sales for the year-to-date (YTD) are $3.57 million, with a decrease of $135.8 thousand compared to the previous year-to-date (PYTD), which was $3.71 million.
Top Performers: The top countries in terms of sales performance include Thailand and the Philippines.
Bottom Performers: The bottom 10 countries in sales performance include Brazil, Sweden, Netherlands, American Samoa, Mexico, Poland, China, Australia, and Bulgaria.
### Quantity Sold
The quantity of products sold showed fluctuations across the months, with the highest quantity sold in February and a notable drop in April.
There is a variation in sales quantities across different product types, with indoor and landscape products showing higher sales volumes.
### Gross Profit
The gross profit percentage (GP%) stands at 0.39.
Account profitability segmentation reveals a diverse range of profitability across different accounts, with some accounts achieving high sales and GP% while others underperform.
## Conclusion
The analysis provides valuable insights into Plant Co.'s sales performance, highlighting key trends and areas for improvement. By understanding the sales trends, quantity fluctuations, and gross profit margins, Plant Co. can make informed decisions to optimize their sales strategy and improve overall profitability.
