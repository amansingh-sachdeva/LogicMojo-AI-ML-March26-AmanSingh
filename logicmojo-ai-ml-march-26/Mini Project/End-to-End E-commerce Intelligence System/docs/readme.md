# End-to-End E-commerce Intelligence System: Building a Customer 360 Analytics Framework

## Business Problem Statement
In modern e-commerce ecosystems, data is generated across multiple independent systems such as customer management, order processing, payments, product catalogs, seller networks, and customer feedback platforms. These datasets are typically fragmented and stored in separate tables, making it difficult to extract unified insights.

The objective of this project is to simulate a real-world data analytics scenario where you are required to:
- Integrate multiple data sources into a unified analytical dataset 
- Construct a Customer 360 View 
- Analyze customer behavior, revenue patterns, and operational performance 
- Identify key drivers of business growth and customer satisfaction 
- Generate actionable, data-driven business recommendations 

This project reflects how data analysts and data scientists work in real organizations, where raw data must be transformed into meaningful insights before applying machine learning models.

---

## Dataset Overview
You are provided with a multi-table e-commerce dataset consisting of the following files (renamed for simplicity):

### Core Tables:
- customers.csv
Contains customer demographic and location information
- orders.csv
Central table containing order lifecycle details (purchase, delivery, timestamps) 
- order_items.csv
Contains product-level details for each order 
- payments.csv
Payment information including type and value 
- reviews.csv
Customer feedback and review scores 

### Supporting Tables
- products.csv
Product details and categories 
- sellers.csv
Seller-level information 
- geolocation.csv
Geographic information (optional for advanced analysis) 
- category_translation.csv
Mapping of product categories to English names 

---

## Project Objectives
By completing this project, students will:
- Develop the ability to work with multi-table datasets 
- Learn data cleaning and preprocessing techniques 
- Perform data integration (joins/merges) 
- Conduct exploratory data analysis (EDA) 
- Apply feature engineering techniques 
- Build strong data visualization skills 
- Generate business insights from raw data 

---

## Key Analyses & Insights

### 1. Revenue-driving factors
- **Top 10 products** contribute **63.27% of revenue** out of 71 categories.  
  -- Recommendation: Ensure adequate inventory of these products.
- **High-value customers** identified above the 0.75 quantile of CLV.  
  ➝ Recommendation: Focus retention strategies (loyalty programs, personalized offers).
- **Top 100 sellers** contribute **45.52% of revenue** out of 2,970 sellers.  
  ➝ Recommendation: Strengthen partnerships with top sellers, but diversify to reduce dependency.

### 2. Customer Behavior Patterns
- Revenue from **new customers** = 14,554,876.59 (~94%).  
- Revenue from **repeat customers** = 864,057.68 (~6%).  
  -- Insight: Heavy reliance on new customers; retention strategies are critical.

### 3. Operational Inefficiencies
- **Approval delays**: 0 days (efficient).  
- **Carrier delays**: 2 days (moderate inefficiency).  
- **Carrier Delivery Delays**: 9 days (significant inefficiency).  
  -- Recommendation: Optimize logistics, reduce carrier pickup lag, and shorten delivery times via regional hubs or express shipping.

---

## Recommendations
- **Customer Strategy**: Build loyalty programs, and personalized marketing for high-value customers.
- **Product Strategy**: Prioritize inventory for top categories; explore bundles and premium offerings.
- **Seller Strategy**: Incentivize top sellers, support mid-tier sellers.
- **Operational Strategy**: Improve carrier SLAs, invest in delivery.

---

## Tech Stack
- **Python** (pandas, NumPy, matplotlib, seaborn)  
- **Jupyter Notebook** for analysis and visualization

---
