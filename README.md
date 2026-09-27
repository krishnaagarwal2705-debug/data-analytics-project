Project title
Customer Orders Analysis Using Python

Objective/business problem
Analyze e-commerce orders to identify customer spending levels, popular products, category sales performance, and cross-selling opportunities for better inventory and marketing decisions.

Dataset used
An illustrative dataset of 17 customer orders from 8 customers. Each order includes customer name, product, price, and category. Categories are Electronics, Clothing, and Home Essentials.

Tools/technologies used
Python 3 in Jupyter Notebook, using built-in data structures and modules:
- Lists and tuples for order records
- Dictionaries for customer and product mappings
- Sets for category and customer comparisons
- Loops and conditional statements for calculations
- collections.Counter and defaultdict for frequency and sales summaries

Key steps performed  
1. Stored customer and order data.
2. Mapped products to categories and identified unique categories.
3. Calculated total spending per customer.
4. Classified customers as high-value (over $100), moderate ($50-$100), or low-value (below $50).
5. Calculated revenue by category and product purchase frequency.
6. Found high-value customers, top three spenders, and most frequently purchased products.
7. Used set operations to identify multi-category shoppers and customers buying both Electronics and Clothing.

Results/insights  
- Total sales: $2,520 across 17 orders.
- Electronics generated the highest revenue: $2,000.
- Ava Patel, Divya Shah, and Henry Brooks are the top three customers by spending.
- Five customers are high-value buyers.
- Headphones and T-Shirts are the most frequently purchased products.
- Several customers purchase from multiple categories, making them strong cross-sell targets.
