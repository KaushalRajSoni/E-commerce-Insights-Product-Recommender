# E-commerce Insights & Product Recommender Dashboard
This project focuses on analyzing e-commerce customer and sales data to derive business insights and build a product recommender system. The goal is to help e-commerce businesses better understand customer behavior, sales performance, and product dynamics, while also offering personalized product recommendations to increase user engagement and conversions.

## Methodology:
#### Data Cleaning & Preprocessing: Cleaned and merged large datasets involving customer orders, payments, products, and reviews.
#### Collaborative Filtering: Built a product similarity matrix using implicit feedback (purchase history) and Truncated SVD for dimensionality reduction.
#### Recommendation Engine: Created a function to retrieve top 5 similar products for a given product.
#### Data Export: Saved product recommendations in a structured format for use in visualization tools.
#### Power BI Dashboard: Developed an interactive dashboard using Power BI Desktop to visualize: Sales trends by month and year, Customer distribution across states and frequency, Product category performance by total sales and quantity, KPIs like Total Sales, Total Orders, AOV (Average Order Value), and Total Customers.
  
## Results-
Successfully processed over 98,000 user-item interactions.
Built a reduced latent interaction matrix (1000 features) for similarity search.
Created a recommendation CSV file with 5 most similar products for each base product.
Developed a comprehensive Power BI Dashboard featuring:
  13.59M in total sales,
  135K total orders,
  431 distinct customers,
  Monthly and yearly trends in sales,
  Category-level product sales and revenue breakdown,
  KPI for AOV: 136.68.
