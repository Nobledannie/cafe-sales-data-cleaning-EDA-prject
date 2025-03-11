# cafe-sales-data-cleaning-EDA-project
This is a data cleaning project done in SQL
About Dataset
Dirty Cafe Sales Dataset
Overview
The Dirty Cafe Sales dataset contains 10,000 rows of synthetic data representing sales transactions in a cafe. This dataset is intentionally "dirty," with missing values, inconsistent data, and errors introduced to provide a realistic scenario for data cleaning and exploratory data analysis (EDA). It can be used to practice cleaning techniques, data wrangling, and feature engineering.

File information
File Name: dirty_cafe_sales.csv
Number of Rows: 10,000
Number of Columns: 8
Columns Description
Column Name	Description	Example Values
Transaction ID	A unique identifier for each transaction. Always present and unique.	TXN_1234567
Item	The name of the item purchased. May contain missing or invalid values (e.g., "ERROR").	Coffee, Sandwich
Quantity	The quantity of the item purchased. May contain missing or invalid values.	1, 3, UNKNOWN
Price Per Unit	The price of a single unit of the item. May contain missing or invalid values.	2.00, 4.00
Total Spent	The total amount spent on the transaction. Calculated as Quantity * Price Per Unit.	8.00, 12.00
Payment Method	The method of payment used. May contain missing or invalid values (e.g., None, "UNKNOWN").	Cash, Credit Card
Location	The location where the transaction occurred. May contain missing or invalid values.	In-store, Takeaway
Transaction Date	The date of the transaction. May contain missing or incorrect values.	2023-01-01
Data Characteristics
Missing Values:

Some columns (e.g., Item, Payment Method, Location) may contain missing values represented as None or empty cells.
Invalid Values:

Some rows contain invalid entries like "ERROR" or "UNKNOWN" to simulate real-world data issues.
Price Consistency:

Prices for menu items are consistent but may have missing or incorrect values introduced.
