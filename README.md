# Sales_Insights_Data_Analysis_Project
Data Analysis Using SQL
Show all customer records

SELECT * FROM customers;

Show total number of customers

SELECT count(*) FROM customers;

Show transactions for Chennai market (market code for chennai is Mark001)

SELECT * FROM transactions where market_code='Mark001';

Show distrinct product codes that were sold in chennai

SELECT distinct product_code FROM transactions where market_code='Mark001';

Show transactions where currency is US dollars

SELECT * from transactions where currency="USD"

Show transactions in 2020 join by date table

SELECT transactions.*, date.* FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020;

#Revenue Analysis using Tableau
![WhatsApp Image 2023-09-10 at 00 24 45](https://github.com/indu-bhushan/Sales_Insights_Data_Analysis_Project/assets/76640383/abb5bb7c-1c77-41bb-8045-29461098544a)

#Profit Analysis using Tableau
![WhatsApp Image 2023-09-10 at 13 08 07](https://github.com/indu-bhushan/Sales_Insights_Data_Analysis_Project/assets/76640383/d18a953d-4950-4dec-b589-6401d2083d6f)

