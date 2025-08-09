## 🍏 Apple Retail Sales & Warranty Analysis 📊

## 📁 Project Overview

This project showcases advanced SQL querying techniques by analyzing over 1 million rows of sales and warranty data from a global retail business. The dataset includes details on products, stores, sales transactions, and warranty claims across multiple locations.

By leveraging SQL, this project provides solutions to real-world business problems, such as:  
✅ Identifying top-selling and least-selling products per store and country.  
✅ Analyzing warranty claims trends to detect potential product quality issues.  
✅ Tracking year-over-year sales growth for each store.  
✅ Evaluating store performance based on sales and claim ratios.  
✅ Understanding the relationship between product pricing and warranty claims.  

## 🎯 Project Objectives

This project analyzes Apple retail sales and warranty data to solve key business challenges using advanced SQL. It provides data-driven insights to optimize sales, improve product quality, and enhance customer service.

🔑 **Key Business Problems Solved:**  
✅ Sales & Inventory Optimization – Identifies top-selling products, sales trends, and high-performing stores.  
✅ Store & Business Growth Analysis – Tracks year-over-year sales growth and regional store performance.  
✅ Product Quality & Warranty Insights – Detects high-claim products, early failures, and defect trends.  
✅ Customer Service Improvement – Analyzes warranty response times and repair costs to enhance service.  

## 🗂 About the Data

This project utilizes a large-scale Apple retail dataset containing over 1 million rows of sales, product, store, and warranty claim records. The dataset provides granular insights into sales performance, customer purchases, and product reliability across different regions.

## 📌 Key Data Components:

🔹 Sales Data – Contains transaction details, including product purchases, store locations, and sales dates.  
🔹 Product Information – Includes product names, categories, launch dates, and pricing details.  
🔹 Store Data – Covers store locations, country-wise performance, and regional sales trends.  
🔹 Warranty Claims – Tracks product failures, claim filing dates, and repair statuses (e.g., paid repairs, replacements).  

This dataset enables deep business analysis, helping to uncover sales trends, product performance issues, and customer service insights.

🔗 Entity-Relationship (ER) Diagram

Your database includes the following entities and relationships based on your queries:

ERD.png

## 📌 Entities & Attributes:

📌 **Products** (product_id, product_name, category_id, price, launch_date)  
📌 **Categories** (category_id, category_name)  
📌 **Stores** (store_id, store_name, country)  
📌 **Sales** (sale_id, store_id, product_id, sale_date, quantity)  
📌 **Warranty** (claim_id, sale_id, claim_date, repair_status)  




