# Home_Sales
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Deliverables
This challenge will be executed using Google Colab and completed by performing the following all the steps per challenge instructions:
* Load the data and perform any necessary preprocessing to clean and transform the data if needed.
* Demonstrate your ability to execute sparksql queries to answer the questions.
* Demonstrate your ability to cache and uncache tables.
* Demonstrate your ability to partition data and store it in parquet format.

### Instructions
Start by uploading `Home_Sales_colab.ipynb` to Google Colab, follow the instructions below to complete the preprocessing steps.
1) Import the necessary dependencies
2) Read the `home_sales_revised.csv`from the provided AWS S3 bucket location into a PySpark DataFrame.
3) Create a temporary table called `home_sales`.
4) Answer the following questions using SparkSQL:
    * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    * What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    * What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    * What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
5) Cache your temporary table `home_sales`.
6) Check if your temporary table is cached.
7) Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
8) Partition by the `date_built` field on the formatted parquet home sales data.
9) Create a temporary table for the parquet data.
10) Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
11) Uncache the `home_sales` temporary table.
12) Verify that the `home_sales` temporary table is uncached using PySpark.
13) Download your `Home_Sales.ipynb` file and upload it into your `Home_Sales` GitHub repository.

***Taken from UOM Bootcampspot module21 challenge instructions***

## File Structure
Home_Sales/
├── Home_Sales_colab.ipynb
├── LICENSE
└── README.md


## Acknowledgements
* Classmates: I recieved coding and debuging help from multiple classmates during breakout sessions.
* Internet Search: I utilized Google Search and slack overflow to research coding concepts, algorithms, and best practices.
* Support Staff: I recieved help from my instructor and class TA during office hours for help with debugging errors and further explanation for complex code segments.
* AI support: I leveraged Gemini AI and ChatGPT to generate code suggestions, debug errors, and provide explanations for complex code segments.
* Please note: While these tools were invaluable in my development process, the final code is the result of my analysis, testing, and refinement.