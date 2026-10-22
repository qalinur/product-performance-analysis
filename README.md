# Product Performance Analysis

### project Overview
This project analyzes Jumia dataset to identify how  price, discount, ratings and review influence product performance

The aim of this project is to generate insight from the dataset to help Jumia make better decision about pricing promotion and customer engagement

### Business Objective
The project aims to answer the following questions:

 - How do product prices, discount, ratings varies across categories ?
  
 - Do product with high discount receive high ratings ?
  
 - Which products perform best in terms of discount, ratings ,reviews ?
  
 - Do more expensive customers receive high ratings ?

### Tools
Microsoft Excel-Data cleaning, analysis ,pivotTables and dashboard development 

### Data Cleaning
The following  data cleaning were performed:
 - Removed 3 confirmed duplicate records
 - converted negative review to positive numbers using ABS function
 - Used flashed fill  to removing "out of 5" from ratings
 - retained blank rating values rather than replacing  them with 0 to avoid introducing unsupported values
 - replaced records with price range  with their calculated midpoint to obtain single estimated price
 - used find and Replace to remove "Ksh" from price column and converted the values to numbers
 -converted columns to their appropriate datatype to ensure values were suitable for analysis

### Data Analysis
- Created calculated columns to categorize price, Discount, Review, Ratings using defined threshold for product performance analysis
 - Used PivotTable to calculate Average current price, Average discount, Average Ratings and Total reviews
 - Used scatter chart to investigate relationship between Discount, Review and ratings

### Findings
The analysis reveal the following :
- Most product have low Reviews regardless of their Discount percentage
- Most products have Ratings between 4.0 and 5.0 but higher Reviews does not correspond to higher Ratings
- Higher priced product  do not consistently receive higher Ratings
- Cheap price_category had the highest number of products
- High above Discount_category had the highest number of products
- 6 In 1 Bottle Can Opener Multifunctional Easy Opener had the highest average discount of 64%
- 120W Cordless Vacuum Cleaners Handheld Electric Vacuum Cleaner achieved the highest total Reviews
- Several products achieved highest rating of 5.0

### Recommendations
Based on the findings the following are recommended:
- monitor product ratings and reviews to  understand customer satisfaction more effectively
- investigate why most products have low review and encourage customers to leave feedback
- investigate products with high reviews to identify factors associated with their higher review
- investigate whether discounts are helping products attract customers interest







