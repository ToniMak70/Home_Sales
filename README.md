# Home_Sales
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.


## Instructions
Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Import the necessary PySpark SQL functions for this assignment.

Read the home_sales_revised.csv from the provided AWS S3 bucket location into a PySpark DataFrame.

Create a temporary table called home_sales.

Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

Cache your temporary table home_sales.

Check if your temporary table is cached.

Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Partition by the "date_built" field on the formatted parquet home sales data.

Create a temporary table for the parquet data.

Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncache the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.

Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.


## Acknowledgements
* Classmates: I recieved coding and debuging help from multiple classmates during breakout sessions.
* Internet Search: I utilized Google Search and slack overflow to research coding concepts, algorithms, and best practices.
* Support Staff: I recieved help from my instructor and class TA during office hours for help with debugging errors and further explanation for complex code segments.
* AI support: I leveraged Gemini AI and ChatGPT to generate code suggestions, debug errors, and provide explanations for complex code segments.
* Please note: While these tools were invaluable in my development process, the final code is the result of my analysis, testing, and refinement.