# Financial-Analysis-using-SQL-Power-BI

The main objective of this project was to clean and analyze financial data using SQL techniques and to gain hands-on experience with Power BI for data visualization. An Exploratory Data Analysis (EDA) was conducted in SQL prior to importing the data into Power BI to identify key insights for visualization.

The financial data used for this project was sourced from Kaggle: https://www.kaggle.com/datasets/atharvaarya25/financials/data?select=Financials.csv

**Financial Data - Cleaning & Exploration**

The dataset was loaded into an SQL server (DB Browser for SQLite), where data cleaning and transformation were performed using SQL queries. An exploratory analysis followed, structured into three main areas:

1. Sales Analysis
- Total sales figures by year
- Breakdown of sales by country, product, and segment
- Identification of top-performing products by sales and units sold
- Insights into the top segments by sales

2. Profit Analysis
- Profit and profit margin calculations
- Identification of the region/country with the highest profit margins
- Analysis of the highest margin products
- Exploration of segment profitability, including identifying loss-making segments

3. Impact of Discounts on sales and Profit
- Analysis of the impact of discounts on both sales and profit
- Examination of which customer segments received the highest discounts and how it affected profitability
- Assessment of the effect of discounts on individual product profitability

*[SQL queries for Data Cleaning](https://github.com/PhiBui77/Financial-Analysis-using-SQL-Power-BI/blob/main/Data%20Cleaning.txt)*

*[SQL queries for Data Analysis](https://github.com/PhiBui77/Financial-Analysis-using-SQL-Power-BI/blob/main/Data%20Analysis.txt)*



**Data Vizualisation Using Power BI dashboard**

After data cleaning and EDA, the dataset was loaded into Power BI where general checking of column formats was conducted. Additionally, for better structure, a date table was created which consisted of columns Date, Month No, Month Name, Year, and YearQuarter. The columns were created with DAX expressions related to dates. Similarly, for better structure, another table with analysis calculations was made. Calculations were made using common DAX expressions such as SUM and DIVIDE, but also to calculate the lagging numbers (e.g., Last Year Sales), DATEADD was also used.


**Key Insights**
1. Sales Performance
 - Sales by year and month show consistent growth patterns, with notable peaks in Oct 2014 and Dec 2014, where sales reached 12M.
2. Performance by Country
- Germany and France have the highest profit margins, with 15.7% and 15.5% respectively.
- The United States has the lowest profit margin at 12%. However, in terms of units sold, the US ranks third, behind France (241K) and Canada (247K).
3. Segment performance
- Among segments, Channel Partners is the highest performing segment with a profit margin of 73.1%.
- Midmarket is second and Government third with 27.7% and 21.7% in profit margin, respectively.
- The Enterprise segment has a negative profit margin of -3.1% across all products.
  - Filtering for the Enterprise segment, 33.3% of total sales have been sold with a high discount band, indicating a notable effect on profit margin.
4. Impact of Discount on Sales and profit
- High and Medium discount bands, with 31.5% and 32.7% of total sales respectively, are the most commonly used strategies.
5. Top Product Performers:
- Paseo is the leading product with an average sale of 33.0M, followed by VTT and Velo. These products significantly contribute to overall sales, with Paseo also showing strong profit margin performance.


**Dashboard Overview**
![image](https://github.com/user-attachments/assets/23dc6066-a9b7-4de1-b372-fccd8b5ff62d)





