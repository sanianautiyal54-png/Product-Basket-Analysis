Product Basket Analysis using Python

Project Overview

This project analyzes transaction data to identify products that are frequently purchased together. The analysis uses Python and Pandas to find popular product combinations and generate product recommendations that can support cross-selling and product bundling strategies.

Objectives

- Identify frequently co-purchased product pairs.
- Analyze purchasing patterns across customer orders.
- Recommend related products based on order history.
- Suggest business strategies for product bundling and cross-selling.
- Provide insights for product placement and inventory planning.

Tools and Technologies

- Python
- Pandas
- Google Colab
- Jupyter Notebook

Dataset

The project uses the Online Retail II dataset, which contains transactional records of retail purchases.

The data was cleaned and processed before identifying product combinations.

Project Workflow

1. Load the retail transaction dataset.
2. Clean and prepare the data.
3. Identify unique customer orders and purchased products.
4. Generate product pairs from individual orders.
5. Count how frequently product pairs occur together.
6. Identify the most frequently purchased combinations.
7. Generate related-product recommendations.
8. Develop business recommendations based on the findings.

Key Findings

The analysis processed 997,479 cleaned records across 40,301 orders, according to the notebook output.

The top product combinations were:

Product Pair| Orders Together
JUMBO BAG PINK WITH WHITE SPOTS + JUMBO BAG RED WHITE SPOTTY| 1,426
JUMBO STORAGE BAG SUKI + JUMBO BAG RED WHITE SPOTTY| 1,324
RED HANGING HEART T-LIGHT HOLDER + WHITE HANGING HEART T-LIGHT HOLDER| 1,234
LUNCH BAG RED SPOTTY + LUNCH BAG BLACK SKULL| 1,202
PACK OF 72 RETRO SPOT CAKE CASES + 60 TEATIME FAIRY CAKE CASES| 1,197

Business Recommendations

- Product Bundling: Test combo offers for frequently co-purchased products.
- Cross-Selling: Recommend related products on product pages and in shopping carts.
- Product Placement: Group complementary items to improve product discovery.
- Inventory Planning: Monitor stock availability for popular product combinations.
- Performance Measurement: Evaluate conversion rate, average order value, and profit to measure the impact of recommendations.

Limitations

Frequently co-purchased products do not necessarily have a direct relationship. Pair counts alone do not establish the strength of an association or prove that a recommendation will increase sales. Further analysis using support, confidence, and lift, followed by business testing, can help validate the recommendations.

Project Files

- "Product_Basket_Analysis.ipynb" — Python analysis, product-pair results, recommendations, and business insights.
- "README.md" — Project overview, workflow, findings, and recommendations.

Conclusion

This project demonstrates how Python and Pandas can be used to analyze retail purchasing patterns and identify products frequently purchased together. The results provide a starting point for product bundling, cross-selling, and data-driven merchandising decisions.

Skills Demonstrated

Python | Pandas | Data Cleaning | Exploratory Data Analysis | Transaction Analysis | Product Recommendations | Business Insights# Product-Basket-Analysis
Analyzing retail transactions using Python and Pandas to identify frequently purchased product pairs and generate cross-selling recommendations.
