Zepto Data Analysis 📊
📌 Project Overview

This project analyzes sales and product data from Zepto, focusing on pricing, discounts, stock availability, and customer behavior. 
Using SQL, I performed exploratory data analysis (EDA) to uncover patterns and generate useful business insights.

The dataset contains product details such as:

Product Name

MRP (Maximum Retail Price)

Discounted Selling Price

Discount Percent

Stock Availability

Weight

SQL (MySQL for queries)

Jupyter Notebook

🔍 Analysis Performed

Some of the key questions solved in this project:

Calculate total stock per category.

Compute potential revenue if all stock is sold at discounted price.

Find products where discounted price > 90% of MRP (low discount).

Identify products weighing less than 100 grams but having high selling prices.

Compare high discount percent products with below-average MRP.

Top 5 most expensive products by MRP.

📈 Insights

Products with very low discounts may affect sales.

Lightweight products (<100g) sometimes have premium pricing.

Potential revenue estimation helps evaluate stock valuation.

Discount strategies vary significantly across categories.

▶️ How to Run

Clone this repository:

git clone https://github.com/your-username/zepto-analysis.git
cd zepto-analysis


Open the Jupyter notebook:

jupyter notebook "Zepto_Analysis.ipynb"
