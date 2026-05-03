# Python-sales-eda-chocolate
Strategic Sales Audit for a Global Chocolate Chain. How can a retail chain increase profitability? This project answers that question by analyzing 1 million+ transaction records to find the "sweet spot" for marketing spend and regional expansion.
Chocolate Sales Analysis 2023–2024
Overview

Analysis of 1,000,000 sales transactions across 6 countries, 6 brands, and 4 store types (Airport, Mall, Online, Retail) over a two-year period (2023–2024).  
Objective

Identify key profit drivers, evaluate the effectiveness of the loyalty program, and assess the impact of various discount tiers on overall profitability.  
Dataset

The analysis is based on five relational tables:  
File	Description
sales.csv	

1,000,000 transactions containing revenue, profit, and discount data.  
products.csv	

200 unique products across 6 brands and 5 categories.  
stores.csv	

100 physical and online locations in 6 countries.  
customers.csv	

50,000 unique customer profiles with age and loyalty status.  
calendar.csv	

Date dimensions for seasonality tracking.  
Key Findings

    Market Leaders: Canada ($2,143,450 profit) and the UK ($2,028,217 profit) are the highest-performing markets.  

    Brand Performance: Ferrero leads in total profit ($1.87M) and transaction volume (183,603 orders). Profit is driven by volume, as all brands maintain nearly identical average unit prices (~$9.00).  

    Product Categories: Praline is the most profitable category ($2,829,380), while Milk chocolate shows the lowest performance ($1,273,506).  

    Loyalty Gap: The loyalty program shows no measurable impact on spending behavior; both members and non-members generate an average profit of approximately $10.20 per order.  

    Discount Impact: Every discount tier leads to significant profit erosion. A 20% discount reduces mean profit from $10.81 to $8.64 per item without a sufficient volume boost to compensate for the margin loss.  

    Stability over Growth: The business remains stable but stagnant, with revenue per day hovering around $34,800 across all months of 2023 and 2024.  

Tools

    Python: Core logic and processing.

    Pandas: Data manipulation and relational merging.

    Matplotlib: Data visualization and trend analysis.

How to Run

    Clone the repository to your local machine.

    Ensure pandas and matplotlib are installed in your environment.

    Place the required CSV files (sales.csv, products.csv, stores.csv, customers.csv, calendar.csv) in the same folder as the notebook.

    Open and run all cells in chocolate.ipynb.
