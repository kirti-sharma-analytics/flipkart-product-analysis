# Flipkart Product Analysis (Power BI)

![Dashboard Overview](dashboard-overview.png)

## Project Overview
This project analyzes a Flipkart product listings dataset (19,602 records after cleaning) to understand pricing distribution, category performance, and customer satisfaction trends.

The objective was to explore how product pricing, category concentration, and ratings vary across different segments.

---

## Dataset Information
- Source: Kaggle
- Records analyzed: 19,602
- Columns: 15
- Data Type: E-commerce product listings

---

## Data Cleaning & Preparation
The dataset required significant preprocessing before analysis:

- Removed duplicate records
- Handled null values in Retail Price
- Replaced missing Brand values with "Unknown"
- Cleaned and structured category hierarchy into 3 levels
- Converted mixed rating columns (text + numeric) into proper decimal format
- Created price buckets for segmentation analysis
- Built DAX measures for KPIs and rating segmentation

---

## Key KPIs Designed
- Total Products
- Average Retail Price
- Average Product Rating
- Number of Brands

---

## Key Insights

1. Majority of products are concentrated in the ₹1000–₹5000 price range, indicating mid-market dominance.
2. Clothing has the highest product volume but relatively lower average ratings (~3.6).
3. Premium categories such as Furniture show higher average prices but lower customer satisfaction.
4. Niche categories like E-books and Home Entertainment demonstrate stronger rating performance despite lower listing volume.

---

## Tools Used
- Power BI
- Power Query
- DAX
- Data Cleaning & Transformation
