
# ![Apple Logo](https://github.com/yaswanth3488/AppleRetail/blob/main/Apple_Image.jpg) Apple Retail Sales Analysis SQL Project - Analyzing Million Rows Data



## Project Overview

In this project, I learned advanced SQL querying techniques by analyzing over 1 million rows of Apple retail sales data. The dataset included information about products, stores, sales transactions, and warranty claims across various Apple retail locations globally. By tackling a variety of questions, from basic to complex, I demonstrated my ability to write sophisticated SQL queries that extracted valuable insights from large datasets.

This project was ideal for me as a data analyst looking to enhance my SQL skills by working with a large-scale dataset and solving real-world business questions.

## Entity Relationship Diagram (ERD)

![ERD](https://github.com/yaswanth3488/AppleRetail/blob/main/ERD.png)


## Database Schema

The project uses five main tables:

1. **stores**: Contains information about Apple retail stores.
   - `store_id`: Unique identifier for each store.
   - `store_name`: Name of the store.
   - `city`: City where the store is located.
   - `country`: Country of the store.

2. **category**: Holds product category information.
   - `category_id`: Unique identifier for each product category.
   - `category_name`: Name of the category.

3. **products**: Details about Apple products.
   - `product_id`: Unique identifier for each product.
   - `product_name`: Name of the product.
   - `category_id`: References the category table.
   - `launch_date`: Date when the product was launched.
   - `price`: Price of the product.

4. **sales**: Stores sales transactions.
   - `sale_id`: Unique identifier for each sale.
   - `sale_date`: Date of the sale.
   - `store_id`: References the store table.
   - `product_id`: References the product table.
   - `quantity`: Number of units sold.

5. **warranty**: Contains information about warranty claims.
   - `claim_id`: Unique identifier for each warranty claim.
   - `claim_date`: Date the claim was made.
   - `sale_id`: References the sales table.
   - `repair_status`: Status of the warranty claim (e.g., Paid Repaired, Warranty Void).





### Solved Business Problems

1. Find the number of stores in each country.
2. Calculate the total number of units sold by each store.
3. Identify how many sales occurred in December 2023.
4. Determine how many stores have never had a warranty claim filed.
5. Calculate the percentage of warranty claims marked as "Warranty Void".
6. Identify which store had the highest total units sold in the last year.
7. Count the number of unique products sold in the last year.
8. Find the average price of products in each category.
9. How many warranty claims were filed in 2020?
10. For each store, identify the best-selling day based on highest quantity sold.
11. Calculate how many warranty claims were filed within 180 days of a product sale.
12. Determine how many warranty claims were filed for products launched in the last two years.
13. List the months in the last three years where sales exceeded 5,000 units in the USA.
14. Identify the product category with the most warranty claims filed in the last two years.
15. Identify the least selling product in each country for each year based on total units sold.


## Project Focus

This project primarily focuses on developing and showcasing the following SQL skills:

- **Complex Joins and Aggregations**: Demonstrating the ability to perform complex SQL joins and aggregate data meaningfully.
- **Window Functions**: Using advanced window functions for running totals, growth analysis, and time-based queries.
- **Data Segmentation**: Analyzing data across different time frames to gain insights into product performance.
- **Real-World Problem Solving**: Answering business-related questions that reflect real-world scenarios faced by data analysts.


## Dataset

- **Size**: 1 million+ rows of sales data.
- **Period Covered**: The data spans multiple years, allowing for long-term trend analysis.
- **Geographical Coverage**: Sales data from Apple stores across various countries.

## Conclusion

By completing this project, I developed advanced SQL querying skills, improved my ability to handle large datasets, and gained practical experience in solving complex data analysis problems that are crucial for business decision-making. This project was an excellent addition to my portfolio and demonstrated my expertise in SQL to potential employers.


---
