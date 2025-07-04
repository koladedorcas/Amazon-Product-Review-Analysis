
# Amazon Product Review Analysis
RetailTech Insights – Data Analysis Project Documentation

##   Table of Contents
- [Project Overview](#Project-Overview)
- [Project Objectives](#Project-Objectives)
- [Dataset Description](#Dataset-Description)
- [Tools used](#Tools-used)
- [Analysis Questions & Analysis Pivot Table and Pivot Chart Visuals](#Analysis-Questions-&-Analysis-Pivot-Table-and-Pivot-Chart-Visuals)
- [Final Dashboard ](#Final-Dashboard)
- [Key Insights & Results](#Key-Insights-&-Results)
- [What I Learnt](#What-I-Learnt)
- [Live files](#Live-files)

---

##  Project Overview
This project is part of a Data Analysis Capstone Project. I performed a comprehensive **Exploratory Data Analysis (EDA)** on Amazon product data to uncover insights that support product decisions, pricing strategies, and customer engagement.

---

##  Project Objective

This project analyzes Amazon product and customer review data to generate actionable insights for product improvement, marketing strategies, and customer engagement, with core objectives to: 
- Analyze product and review data to uncover trends and actionable insights.

- Answer 14 targeted business questions using pivot tables and calculated columns.

- Visualize findings in an interactive dashboard for stakeholders.
  
---

## Dataset Description

- **Source**: Amazon product scrape (provided as part of DSA capstone)
- **Rows**: 1,465 products
- **Columns**: 16 (including product name, category, price, rating, review count, discount)

---

##  Tools Used

- Microsoft Excel
- Pivot Tables and Charts
- Slicers
- Conditional Formatting
- GitHub (for version control and portfolio)

---

## Analysis Questions & Analysis Pivot Table and Pivot Chart Visuals

---
### Cleaned Amazon Product Dataset

![Cleaned Amazon dataset](https://github.com/user-attachments/assets/9022d2d4-06bf-4f1e-b00a-dc4c672713e3)

---

### 1. What is the average discount percentage by product category?

![Pivot Analysis 1](https://github.com/user-attachments/assets/151f8ff0-52dc-4b32-9fe3-71ade2c0e107)

---

### 2. How many products are listed under each category?

![pivot analysis 2](https://github.com/user-attachments/assets/54cec9b9-7501-4d1d-99ec-d7561e7072a8)

---

### 3. What is the total number of reviews per category?

![pivot analysis 3](https://github.com/user-attachments/assets/5a36bd15-3105-4866-9ef7-2fea5457ff0a)

---

### 4. Which products have the highest average ratings?

![pivot analysis 4](https://github.com/user-attachments/assets/66f68c8f-bd55-4cb2-820d-2a1060c1de94)


---

### 5. What is the average actual price vs the discounted price by category?

![pivot analysis 5a](https://github.com/user-attachments/assets/58735940-6767-44e5-8a9d-15a42d66708d)

![pivot analysis 5b](https://github.com/user-attachments/assets/6b607a7a-38aa-452b-9e6b-4b1b813ae987)

---

### 6. Which products have the highest number of reviews?

![Pivot analysis 6](https://github.com/user-attachments/assets/af05e4b0-b182-45e5-9db7-047d91a71d62)

---

### 7. How many products have a discount of 50% or more?

![Pivot analysis 7](https://github.com/user-attachments/assets/cc4711e2-72d1-45bb-bcd2-80450dc1f684)

---

### 8. What is the distribution of product ratings?

![Pivot analysis 8](https://github.com/user-attachments/assets/013ad77e-e806-4528-bda5-a54f948d5fab)

--- 

### 9. What is the total potential revenue by category?

![pivot analysis 9](https://github.com/user-attachments/assets/4907b7df-e655-48fb-8efd-13a5c129904f)

---

### 10. What is the number of unique products per price range?

![Pivot analysis 10](https://github.com/user-attachments/assets/c1152da4-6817-4ac0-b34b-d002c94416cc)

---

### 11. How does the rating relate to the level of discount?

![Pivot analysis 11](https://github.com/user-attachments/assets/1da7f37c-a328-48cd-9b0f-14d84b27efa2)

---

### 12. How many products have fewer than 1,000 reviews?

![Pivot analysis 12](https://github.com/user-attachments/assets/d0e05b37-0e38-4079-af7a-6430b56a95a0)

---

### 13. Which categories have products with the highest discounts?

![Pivot analysis 13](https://github.com/user-attachments/assets/8e1d6fd0-13c5-4f2f-962c-294e4c125e91)

---

### 14. Top 5 products by combined rating and number of reviews

![Pivot analysis 14](https://github.com/user-attachments/assets/bec3730f-1f36-435f-adee-3d48b265c9dc)

---

## Final Dashboard

Below is a snapshot of the final dashboard combining insights from the pivot tables:

![Amazon Product Review Analysis Dashboard](https://github.com/user-attachments/assets/b873b5f5-13b4-4af5-bc35-741d06df7cfe)

---

## Key Insights from the Amazon Product Review Dashboard
1. High Number of Products with Major Discounts
- 674 products (over 50% of the catalog) offer ≥50% discount, showing that aggressive pricing strategies are common.

- 85 categories contain these heavily discounted products, suggesting that competitive pricing cuts across product types.

2. Massive Potential Revenue from Discounted Products
   Products with ≥50% discount could generate over €36.9 billion in potential revenue, indicating volume-driven profit models.

3. Product Ratings Are Generally High
   Most products have a rating between 4.0 and 4.5, indicating overall customer satisfaction and quality perception.

4. Few Products Dominate Reviews
   The Top 10 most reviewed products are clustered within Electronics & Mobile Accessories, with some receiving over 600,000 reviews, highlighting best-sellers or highly marketed items.

5. Price Buckets Skew Toward Affordable Products
   A large share of products falls within the ₹200–₹500 range, suggesting that affordability is a major target for sellers.

6. Rating vs Discount Patterns Vary by Category
   In some categories, higher discounts correlate with slightly higher ratings, possibly due to increased customer expectations being met.

7. Top 5 Products (Rating × Review Volume)
   These products stand out not only for high ratings but also significant customer engagement, indicating they’re both well-loved and widely purchased.

## What I Learned from This Project
Excel Dashboards Can Tell Powerful Data Stories

- I learned how to organize and visualize complex product data clearly using Pivot Tables, Charts, and KPI Cards.

Using Slicers Makes Dashboards Interactive and Dynamic 

- Slicers enhanced user control, making it easy to filter by category, rating, discount level, and price range for real-time    analysis.

Calculated Fields Help Uncover Deeper Insights

- Creating metrics like potential revenue, rating × review score, and bucketed discount levels helped me move from raw data to strategic business questions.

Good Data Visualization Requires Balance

- I practiced choosing the right chart types for each metric and learned how to avoid clutter by arranging insights in digestible blocks.

Professional Documentation and Presentation Matter

- Beyond analysis, I learned how to present my work clearly on GitHub so others can understand my thinking and approach.
---

## Live Files

- [Click here to view the cleaned Excel file](data/amazon_reviews_cleaned.xlsx)
- [Click here to view the full analysis workbook](Amazon product review analysis workbook.xlsx)

---

