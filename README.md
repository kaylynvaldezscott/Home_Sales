# Home_Sales
Submitted by Kaylyn Valdez-Scott Date: 01-FEB-2024 Project Title: Module 22 SparkSQL Big Data Challenge

Purpose of Project : Use knowledge of SparkSQL to determine key metrics about home sales data. Then use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Below are the questions that the assignment aims to answer, as well as my findings through utilizing Google Colab and SparkSQL:

1. What is the average price for a four-bedroom house sold for each year? Round off to two decimal places.

<img width="1413" alt="Screenshot 2024-02-01 at 1 28 22 PM" src="https://github.com/kaylynvaldezscott/Home_Sales/assets/141589524/683dcb48-9590-43ca-ab29-ef3aa97453c2">



2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off to two decimal places.


<img width="1404" alt="Screenshot 2024-02-01 at 1 28 46 PM" src="https://github.com/kaylynvaldezscott/Home_Sales/assets/141589524/aa5b8df8-5fe2-44c4-9a67-3dda668c5cf1">



3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off to two decimal places.

<img width="1397" alt="Screenshot 2024-02-01 at 1 29 04 PM" src="https://github.com/kaylynvaldezscott/Home_Sales/assets/141589524/4197e7df-2efd-415f-ba54-df75487ad50f">



4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off to two decimal places.

<img width="1324" alt="Screenshot 2024-02-01 at 1 29 26 PM" src="https://github.com/kaylynvaldezscott/Home_Sales/assets/141589524/eb88a25c-8de4-4b2b-ab14-1fce25393a90">



Partition by the "date_built" field on the formatted parquet home sales data.
Create a temporary table for the parquet data.

<img width="1405" alt="Screenshot 2024-02-01 at 1 35 22 PM" src="https://github.com/kaylynvaldezscott/Home_Sales/assets/141589524/5553ace9-47c7-49c5-bdd1-01f915d85051">



Cache your temporary table home_sales.
Check if your temporary table is cached.

<img width="1383" alt="Screenshot 2024-02-01 at 1 29 44 PM" src="https://github.com/kaylynvaldezscott/Home_Sales/assets/141589524/2c131435-e0d7-4b4a-b2dd-6f3b85193dea">



Uncache the home_sales temporary table.
Verify that the home_sales temporary table is uncached using PySpark.

<img width="1369" alt="Screenshot 2024-02-01 at 1 30 05 PM" src="https://github.com/kaylynvaldezscott/Home_Sales/assets/141589524/e479ab99-f84c-4513-b8e7-3f4c1fa3ab1d">


