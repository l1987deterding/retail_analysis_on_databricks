# retail_analysis_on_databricks

# Technology Used
<img src='https://github.com/kevinclee26/retail_analysis_on_databricks/blob/main/images/Databricks_Logo.png?raw=true' height='100px'>
<img src='https://github.com/kevinclee26/retail_analysis_on_databricks/blob/main/images/Apache_Spark_logo.png?raw=true' height='100px'>

# Analysis Performed
* Create a list of all countries to which orders have been shipped.

	* How many orders have been placed in total?
	Using aggregation on the orders table - we identified that there have been 830 orders placed. 

	* How many orders have been shipped to each country?
	Germany and USA have had the most orders shipped. 
	<img src='https://github.com/kevinclee26/retail_analysis_on_databricks/blob/main/images/countries_shipped.png?raw=true' height='200px'>

* For each product, list its product ID, product name, and the company name.

	* Which 5 countries have the heaviest shipments, on average?
	Australia, Ireland, and USA have the top 3 average shipment. 
	<img src='https://github.com/kevinclee26/retail_analysis_on_databricks/blob/main/images/average_shipped_by_country.png?raw=true' height='200px'>

	* Which 10 companies have placed the most orders? List the contact name of each company.
	<img src='https://github.com/kevinclee26/retail_analysis_on_databricks/blob/main/images/top_customer_contacts.png?raw=true' height='200px'>

* Sort the customers by total amount spent on orders in descending order.

* Sort customers with a total spending greater than 20,000 in descending order.
<img src='https://github.com/kevinclee26/retail_analysis_on_databricks/blob/main/images/total_spending_by_customer.png?raw=true' height='200px'>

* Sort the employees by the number of orders they sold in descending order.

	* How many employees account for about half of the orders? (You do not have to use SQL to answer this question. A rough estimate is sufficient.)

* List customers who have never placed an order.

* List the products with the highest level of discount in descending order.

This project is developed with [databricks](https://databricks.com/) and [Apache Spark](https://spark.apache.org/)

# Data Attribution
Data Used in This Analysis is Provided by 2U. You can acquire the data using below links: 
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/categories.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/customers.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/employee-territories.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/employees.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/order-details.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/orders.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/products.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/regions.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/shippers.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/suppliers.csv
* s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/territories.csv
<img src='https://github.com/kevinclee26/retail_analysis_on_databricks/blob/main/images/ERD.png?raw=true' height='600px'>
