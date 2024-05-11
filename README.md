# Home_Sales
Challenge#22 HW

![Screenshot 2024-05-11 at 12 53 24 PM](https://github.com/apkaur32/Home_Sales/assets/150749167/07ebd48c-30f8-49ee-8f25-c98b9c1660ee)

Overview: \
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Instructions: 
1. Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.
2. Import the necessary PySpark SQL functions for this assignment.
3. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.
![Screenshot 2024-05-11 at 1 03 03 PM](https://github.com/apkaur32/Home_Sales/assets/150749167/e494d3c0-c57c-4119-8429-aad114fcc69f)

4. Create a temporary table called home_sales.
5. Answer the following questions using SparkSQL and round off your answer to two decimal places:\

a) What is the average price for a four-bedroom house sold for each year? 
![Screenshot 2024-05-11 at 1 03 41 PM](https://github.com/apkaur32/Home_Sales/assets/150749167/d17f0b38-f803-472f-bc7c-b71e57d5f8ac)

b) What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?  
![Screenshot 2024-05-11 at 1 04 14 PM](https://github.com/apkaur32/Home_Sales/assets/150749167/1c823780-07a9-4b57-a4c7-ae84048616da)

c) What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?  
![Screenshot 2024-05-11 at 1 04 39 PM](https://github.com/apkaur32/Home_Sales/assets/150749167/1a75c5e2-1d66-4a3e-bb71-f40df218b6f4)

d) What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query.\
![Screenshot 2024-05-11 at 1 09 38 PM](https://github.com/apkaur32/Home_Sales/assets/150749167/0eacf4ce-c7aa-4bef-992f-1bc1bb89f922)

7. Cache your temporary table home_sales.
8. Check if your temporary table is cached.
9. Using the cached data, run the last query  from step 6. Determine the runtime and compare it to uncached runtime.
![Screenshot 2024-05-11 at 1 12 12 PM](https://github.com/apkaur32/Home_Sales/assets/150749167/bd85ea6c-5610-44ec-bd25-a67fd1ea6e01)

10. Partition by the "date_built" field on the formatted parquet home sales data.
11. Create a temporary table for the parquet data.
12. Run the last query t from step 6 again. Determine the runtime and compare it to uncached runtime.
![Screenshot 2024-05-11 at 1 12 37 PM](https://github.com/apkaur32/Home_Sales/assets/150749167/96072ede-e475-4c2a-bc07-c83040b826af)

13. Uncache the home_sales temporary table.
14. Verify that the home_sales temporary table is uncached using PySpark.
15. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

Analysis: 
