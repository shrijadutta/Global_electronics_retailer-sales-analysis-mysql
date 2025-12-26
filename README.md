# Global Electronics Retailer Sales Analysis

## Project Overview
This project uses MySQL to analyze transactional data from a multinational electronics retailer, focusing on database design, data cleaning, and exploratory analysis of sales, customers, products, and stores.

## Data Source
The dataset used is sourced from Maven Analytics and includes five CSV files: `sales`, `products`, `customers`, `stores`, and `exchange_rates`. It contains transactional sales data along with product, customer, store, and currency details for a global electronics retailer.

## Tools Used
- Microsoft Excel – Used for minor preprocessing of CSV files.  
- MySQL – Used for database setup, table creation, data insertion, defining constraints, establishing relationships, and performing SQL queries.

## Data Preparation
- CSV Preprocessing: Updated date formats and replaced zero values with nulls to ensure smooth import into MySQL.  
- Database Setup: Created a new MySQL database named `electronics_retailer`.  
- Table Creation: Designed and created tables corresponding to each CSV file (`sales`, `products`, `customers`, `stores`, `exchange_rates`).  
- Data Import: Imported data from the CSV files into the respective MySQL tables.  
- Constraints & Relationships: Defined primary and foreign key constraints and established relationships between the tables to maintain data integrity.

## Exploratory Data Analysis (EDA)
This stage focused on exploring sales performance, customer behavior, product insights, and regional trends.
### 1. The company’s total revenue, profit, and overall profit margin
- **Total revenue is $55,755,479.59** with a **profit of $32,662,688.38**, giving a **profit margin of 58.58%**. 
- This shows **the company is highly profitable with strong margins** across its product range.

### 2. The yearly and monthly sales trends
- Yearly sales grew steadily from **$6.94M in 2016** to **$18.26M in 2019**, then dropped to $9.29M in 2020. Sales appear to fall to $1.04M in 2021, but this is due to insufficient data for that year.
- Monthly sales are usually **highest in December** and lowest around April, showing seasonal fluctuations each year.

### 3. Product categories generating the most revenue, profit and profit margin
- **Computers** and **Home Appliances** generate the highest revenue, while **Music,Movies and Audio Books** and **Cameras and camcorders** have the highest profit margins (around 60%).
- Overall, **Computers** is the top-performing category in both revenue and profit, showing it is the company’s strongest product segment.

### 4. The top 10 best-selling products
- The top 10 best-selling products are **desktop PCs**, with **revenue from $111,514 to $505,450** and **quantities sold between 505–550 units**.
- This shows that desktop PCs are the company’s most popular products and generate the majority of sales.

### 5. Stores generating the highest revenue, profit and profit margin, including their country and state.
- The **Online store** leads in **revenue($11.4M)** and **profit($6.67M)**, followed by top US stores in Nevada, Kansas, and Nebraska.
- Profit margins are consistently high across stores (around 58–62%), showing strong profitability regardless of country or state.

### 6. Stores with the strongest year-over-year growth
- The stores with the strongest year-over-year growth include **Flevoland (Netherlands)**, **Martinique (France)**, and **Freie Hansestadt Bremen (Germany)**, with **growth ranging from 146% to 406%**.
- This indicates that these locations are rapidly increasing sales compared to the previous year.

### 7. Products showing declining sales over the last several months
- Among these declining products, the largest drops occur in desktop PCs and cameras, with several experiencing declines of 50–75% month over month.

### 8. Underperforming stores
- Underperforming regions include **Italy (Caltanissetta, Enna)**, **Australia (Northern Territory, Victoria, Western Australia)**, **Germany (Berlin, Sachsen-Anhalt)**, and some **U.S. states (Idaho, Kansas, New Mexico)**.
- These regions show negative average monthly growth across several months.

### 9. Regions driving revenue growth
- **North America (USA)** drives most revenue, especially for **Computers and TV & Video**.
- **Europe** contributes moderately, led by **Germany, Italy and UK**, mainly in **Computers and Cell Phones**.
- Revenue growth varies by category, with **Computers** leading, followed by **Cameras and Camcorders**, **TV and Video**, and **Audio**, showing regional concentration.

### 10. Products with high-margin but low-sales
- Most of the high-margin but low-sales items are **digital cameras**, all earning margins around 67% despite very few purchases.
- Other electronic devices like **interchangeable lens, phone system, coffee makers** also show high profitability but low sales.

### 11. Products that are frequently bought together
- Customers often buy **multiple desktop PC models** together.
- **DVD players, recorders, and storage binders** are frequently purchased in combinations.
- **Handheld games, headphones, and recorder pens** commonly pair with other electronics.

### 12. Customers who are at risk of churn based on recency of purchase
- A large number of customers haven’t made a purchase in over 1800 days, putting them at high risk of churn.


## Summary
- Strong profitability with **$55.76M revenue** and a **58.6% profit margin**.
- Sales grow until 2019, dip in 2020, and **peak each December**.
- **Computers** dominate revenue, profit, and top-selling products.
- **Online store** leads performance. A few regions show rapid growth, others underperform.
- Some PC and camera products show declining sales. Several high-margin items have low volume.
- Many customers are inactive for 1800+ days, indicating churn risk.

## Recommendations
- Promote high-margin, low-sales products through targeted marketing or thoughtful bundling.
- Encourage cross-selling by highlighting popular product pairings in electronics and entertainment.
- Support fast-growing stores and regions with extra marketing, inventory, and operational focus.
- Address challenges in underperforming stores through local strategies and improvements.
- Re-engage inactive or at-risk customers with personalized offers or gentle reminders.
- Plan for seasonality by optimizing inventory and promotions during peak months and boosting sales in slower periods.

## Author
**SHRIJA DUTTA**  
• [GitHub](https://github.com/shrijadutta)  • [Email](mailto:shrijadutta19@gmail.com)
