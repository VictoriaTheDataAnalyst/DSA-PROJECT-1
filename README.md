# 📊 Amazon Product Data Dashboard

This project presents an interactive Excel dashboard built from a cleaned dataset of Amazon product listings. It visualizes key product performance metrics using PivotTables, charts, and calculated fields.

## 📈 Project Overview

Using Microsoft Excel 2013, the following key business questions were answered with Pivot Tables:

1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
9. What is the total potential revenue (actual_price × rating_count) by category?
10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.

> Bonus: The dashboard includes a slicer for interactive category filtering.

## 🧩 Tools Used

- **Microsoft Excel 2013**
  - PivotTables
  - Calculated Columns
  - Manual Histogram using FREQUENCY function
  - Charts (Bar, Pie, Line)

## 📁 Files

| File Name                                | Description                            |
|------------------------------------------|----------------------------------------|
| `AMAZON PRODUCT REVIEWS ANALYSIS.xlsx`   | Original Data, Cleaned Data, Pivot     |
                                           | Table and Dashboard                    |
| `README.md`                              | Project summary and instructions       |

## 💡 Insights

- Some categories have very high discounts but low review counts.
- A few top products generate the majority of potential revenue.
- The average rating clusters between 3.5 and 4.5 for most products.

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `AMAZON PRODUCT REVIEWS ANALYSIS` in Excel.
3. Use slicers or filters to explore different views.

---

## 🚀 Author

**Ojo Victoria Olamide**  
Data Analyst

---

## 🌐 License

This project is for educational and demonstration purposes. Data used is fictional and provided for the DSA Capstone Project.
