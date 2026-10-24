Retail Sales and Profitability Analysis

Project Overview

This project analyzes retail sales transactions from a synthetic multi-store Point-of-Sale (POS) dataset covering January 2024 to December 2025. The analysis was conducted in Microsoft Power BI to examine sales performance, product profitability, store performance, customer activity, and transaction and refund patterns.

The project was developed as part of my data analytics portfolio to demonstrate my ability to transform transactional data into meaningful business insights and communicate those insights through an interactive Power BI dashboard.

About the Dataset

The dataset, “A Synthetic Multi-Store Retail Point-of-Sale Transaction Dataset in Square POS Export Format,” contains simulated retail transactions from 30 stores over a two-year period.

The dataset contains:

* 970,838 sales line items
* 30 stores
* 32 items and 67 SKUs
* 6 product categories
* Payment and refund transactions
* Transaction, product, payment, location, customer, pricing, discount, tax, and profit information
* Data covering January 1, 2024 to December 31, 2025

The six product categories are Apparel, Footwear, Accessories, Electronics, Home Goods, and Beauty.

The dataset is fully synthetic and does not contain real business, customer, or personal data. It was generated using a seeded simulation designed to reproduce realistic retail transaction patterns, including sales activity, discounts, refunds, and seasonal events.

Business Problem

Retail businesses need to understand not only how much they sell, but also which products and locations contribute most to revenue and profit.

This analysis addresses questions such as:

* How did sales perform over the two-year period?
* Which product categories and individual products generated the most sales?
* Which categories contributed most to gross profit?
* What was the overall profitability of the business?
* How did sales vary across store locations?
* What payment methods were most commonly used?
* How significant were refunds relative to sales?
* Which categories experienced the highest refund activity?
* How did refund rates change over time?
* What can the transaction data reveal about customer activity?

Objectives

The main objectives of the analysis were to:

1. Evaluate overall sales performance.
2. Analyze product and category-level profitability.
3. Compare sales and profitability across store locations.
4. Examine customer purchasing activity.
5. Analyze payment methods and transaction patterns.
6. Measure refund value and refund rates.
7. Identify trends that could support retail decision-making.

Data Preparation

The dataset was imported into Power BI and prepared using Power Query.

The preparation process included:

* Reviewing the structure and quality of the dataset
* Assigning appropriate data types to columns
* Maintaining transaction-level records for analysis
* Preserving refund transactions and negative quantities
* Retaining blank customer IDs because not every transaction was associated with a customer ID
* Reviewing repeated transaction IDs, which occur because a single transaction can contain multiple item lines
* Creating measures for sales, profitability, transactions, customers, and refunds

Refund records were retained rather than removed because they provide important information about customer returns and the overall performance of the business.

Analysis and Dashboard

The final Power BI report consists of four analytical areas.

1. Sales Performance Overview

This section focuses on the overall performance of the business.

Key metrics include:

* Total Net Sales: $46.60M
* Total Quantity Sold: 1M
* Total Gross Profit: $25.78M
* Total Transactions: 586K

The analysis also examines monthly sales trends, sales by payment method, top-selling products, and sales performance across product categories.

2. Product and Profitability Analysis

This section examines how sales translate into profitability.

Key metrics include:

* Total Gross Profit: $25.78M
* Profit Margin: 55.34%
* Total Discounts: $2.67M
* Total Recorded Refunds: $429.21K

The analysis compares sales and gross profit across categories and identifies the products contributing most to gross profit.

3. Store and Customer Analysis

This section examines performance across the retail network and customer activity.

Key metrics include:

* 30 active locations
* Approximately 20K customers
* Approximately $2.33K in sales per customer

The analysis compares net sales and gross profit by location, examines payment methods across stores, and identifies customers with higher sales contributions.

4. Transaction and Refund Analysis

The final section focuses on transaction activity and refunds.

Key metrics include:

* 585.69K transactions
* $79.56 average transaction value
* $429.21K recorded refunded value
* 0.84% refund rate

Refund activity is examined by category and over time to identify periods and product categories associated with higher refund activity.

Key Findings

The analysis produced several notable findings.

Strong overall sales and profitability:
The business generated approximately $46.60 million in net sales and $25.78 million in gross profit, resulting in a 55.34% profit margin.

Apparel was the leading category by net sales:
Apparel generated approximately $17.9 million in net sales, making it the strongest-performing category in the analysis.

Running Shoes was the leading individual product by net sales:
Running Shoes generated approximately $4.9 million in net sales, making it the top individual item by sales value.

Discounts represented a significant sales consideration:
The analysis recorded approximately $2.67 million in discounts, highlighting the importance of monitoring promotional activity when evaluating retail performance.

Refunds represented a relatively small share of sales:
The recorded refunded value was approximately $429.21K, with a dashboard refund rate of 0.84%.

Sales performance varied across locations:
The store-level analysis showed differences in net sales and gross profit across the 30 locations, providing an opportunity to identify stronger-performing locations and areas requiring further investigation.

Tools Used

Microsoft Power BI

* Power Query for data preparation
* DAX for calculated measures
* Interactive dashboard design
* Data visualization and business analysis

Dataset Limitations

Because this is a synthetic dataset, the findings should not be interpreted as representing the actual performance of a real retail business.

The dataset documentation identifies several limitations, including a simplified data structure, a flat 8.25% sales tax, a static product catalogue, simplified customer identification, and the absence of factors such as weather, local events, and store-specific characteristics.

The dataset is therefore most useful for demonstrating analytical techniques, dashboard development, retail analysis, and interpretation rather than making claims about real-world retail performance.

Conclusion

This project demonstrates how transactional retail data can be transformed into actionable business insights using Power BI.

By combining sales, product, profitability, store, customer, transaction, and refund analysis, the dashboard provides a broad view of retail performance and highlights areas that could support decisions around product performance, store management, promotions, profitability, and customer activity.

Dataset Source

A Synthetic Multi-Store Retail Point-of-Sale Transaction Dataset in Square POS Export Format (30 Stores, 24 Months)

Mendeley Data, Version 2.0, 2026.

The dataset was created for analytical and educational purposes and is fully synthetic.
