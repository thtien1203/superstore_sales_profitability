## Superstore Sales and Profitability Analysis

## Dataset
Superstore dataset from Kaggle (https://www.kaggle.com/datasets/binib1997/superstore) — 9,994 order-line transactions (2014–2017), 21 columns

Analyzing why some products, regions, and customers at Superstore generate more sales but less profit
Tools: Python (pandas), SQLite (SQL), Excel, Power BI

## Question: Why do some products and regions generate more sales but less profit?
Superstore looks healthy on the surface — millions in sales every year. But revenue and profit don't always move together, and this project traces that gap back to its root cause

## Key findings:
Discount is the primary driver of profit loss - margin turns negative past 30% discount, and collapse to -180% profit margin at 80% discount. 
Furniture underperforms despite strong sales, driven by two sub-categories (Tables, Bookcases) that lose money once discounted past 20%.
The Central region's weak margin (7.92%) comes down to just two states, Texas and Illinois, both driven heavily discounted Office Supplies.
Sales grew every year (2014-2017), but profit margin peaked in 2016 and slightly declined in 2017.
High sales volume doesn't guarantee profitability (e.g Cisco TelePresence lose the money despite strong revenue)

## Methodology
Inspect -> Clean (Python) -> Analyze (SQL) -> Visualize (Excel + Power BI) -> Report findings
