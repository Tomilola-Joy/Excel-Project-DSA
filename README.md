# Excel-Project-DSA
Amazon Product Review Analysis –Project Document 

# Introduction: My Learning Journey

Embarking on this data analysis project marked a significant milestone in my journey to becoming a skilled Data Analyst. I have been building my skills in Excel, pivot tables, data visualization, and dashboard design. This project allowed me to practically apply these skills to a real-world business scenario, analyzing customer review data to drive decisions.


# Project Overview

The goal of this project is to help sellers on Amazon make informed decisions by analyzing product performance and customer sentiment data. Working as a Junior Analyst at RetailTech Insights, I evaluated product reviews and metadata to generate actionable insights that can drive product improvements, marketing strategy, and customer engagement.


# Project Topic

In this project, the central focus is Amazon Product Review Analysis, which involves exploring customer feedback, product performance, and pricing data for products listed on Amazon. The goal is to help sellers and decision-makers gain data-driven insights into what makes a product successful, where improvements are needed, and how customer sentiment aligns with product ratings and reviews.

By analyzing thousands of products across multiple categories, this project identifies: Patterns in product ratings and review volumes, price strategies (discount vs. actual price), High-performing product categories, Customer preferences and potential market gaps

The insights gathered help improve: Pricing and discounting strategies, Marketing campaigns, Inventory planning and Customer satisfaction and retention

This topic is vital in today’s data-driven retail space where platforms like Amazon are heavily influenced by customer reviews and competitive pricing. Leveraging this kind of analysis enables sellers to stay ahead in the e-commerce market.


# Case Study: Dataset Description

Source: Scraped from Amazon product pages

Records: 1,465 products

Columns: 16

Fields Include: Product name, category, price, discount %, actual vs discounted price, ratings, rating count, review count, review text/title

Each row represents a single product, with aggregated reviews and performance data.


# Tools Used

Microsoft Excel:

Data cleaning

Pivot table analysis

Visualizations

Dashboard creation


# Data Cleaning Process

Removed duplicates and blank rows

Split and transformed comma-separated values into structured columns

Standardized formats for prices and percentages

Created calculated columns for metrics like potential revenue, rating × review count, etc.

Binned products into price ranges using conditional logic


# Steps Used During Analysis

Loaded the cleaned dataset into Excel
Created calculated fields (e.g., actual revenue, price buckets)

Used pivot tables to summarize by category, rating, and discount

Applied filters and slicers for dynamic analysis

Built charts (bar, pie, column) for key metrics

Designed a dashboard with KPIs, visuals, and category breakdowns


# Business Insights Questions & Answers

1. What is the average discount percentage by product category?

Health & PersonalCare at 52.68% followed by Computers & Accessories at 52.38%.

2. How many products are listed under each category?

Electronics has 454 products, Home & Kitchen has 448, and Computers & Accessories has 319, making them the top three in volume.

3. What is the total number of reviews per category?

Health and Personal Care

4. Which products have the highest average ratings?

Redtech USB-C To Lightning, Amazon Basics Wireless Mouse, and Syncwire Ltg To USB are top-rated with a perfect 5.0 rating.

5. What is the average actual price vs the discounted price by category?

Electronics have the highest average actual price at ₹10,754 and discounted at ₹6,527. Computers & Accessories average ₹2,032 vs ₹1,055 discounted.

6. Which products have the highest number of reviews?

Amazon Basics High-Speed HDMI tops with 426,973 reviews, followed by Boat Bassheads 100 and Redmi 9A variants each with over 313,000 reviews.

7. How many products have a discount of 50% or more?

There are 583 products with a discount of 50% or greater.

8. What is the distribution of product ratings?

Most products are rated between 4.0 and 4.4, indicating high customer satisfaction across the board.

9. What is the total potential revenue by category?

Health and Personal Care at ₹6,959,700.

10. What is the number of unique products per price range bucket?

Most products are priced below ₹2,000, especially in the ₹0–₹999 and ₹1,000–₹1,999 buckets.

11. How does the rating relate to the level of discount?

There is a weak negative correlation (−0.145), indicating minimal inverse relationship between discount level and rating.

12. How many products have fewer than 1,000 reviews?

293 products have fewer than 1,000 reviews, which is about 20% of the dataset.

13. Which categories have products with the highest discounts?

Computers & Accessories has products with discounts up to 94%, followed by Electronics (91%) and Home & Kitchen (90%).

14. Identify the top 5 products in terms of rating and number of reviews combined.

Amazon Basics High-Speed HDMI, Boat Bassheads 100, and Redmi 9A Sport and Activ variants are top products by combined score of rating and review count.


# Final Dashboard

A visual dashboard was built in Excel with the following:

KPIs (total revenue potential, review counts, top-rated products).

Interactive charts (category comparisons, discount distribution, rating histograms).

Slicers for category filtering.

Product highlights section.


# Conclusion & Recommendations for Stakeholders

Focus marketing efforts on high-performing categories: Electronics.

Monitor and possibly relist low-rated products (<3 stars).

Leverage discounts strategically, as they don’t always improve ratings.

Invest more in products with high review counts, they are likely to perform better.

Keep price points competitive in the ₹200–₹500 range for volume.

