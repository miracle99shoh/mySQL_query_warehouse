<h1>Analysis of Warehouse data using SQL query</h1>

<h2>Description</h2>
<br /> Project consists of a simple analysis of couple of datasets: <a href="https://github.com/miracle99shoh/mySQL_query_warehouse/blob/main/Warehouse_Orders_Orders.csv">Orders</a> and <a href="https://github.com/miracle99shoh/mySQL_query_warehouse/blob/main/Warehouse_Orders_Warehouse.csv">Warehouse</a>. We're required to combine them and do the fulfillment analysis in order to determine how much of the orders are completed and which warehouses completed the most of the orders.
<br />

<h2>Languages and Utilities Used</h2>

- <b>SQL query language </b> 
- <b>Google MySQL query</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Analysis walk-through in MySQL:</h2>


## I started with combining two separate datasets into one using **LEFT JOIN** function: <br/>
<img src="https://github.com/miracle99shoh/mySQL_query_warehouse/blob/main/warehouse_analysis_query_01.png"/>
<br />
<br />
## Then I set up **SELECT** function for what tables to return and I renamed them to be more precise:  <br/>
<img src="https://github.com/miracle99shoh/mySQL_query_warehouse/blob/main/warehouse_analysis_query_02.png"/>
<br />
<br />
## I used **CASE** function to calculate and assign the fulfillment degree: <br/>
<img src="https://github.com/miracle99shoh/mySQL_query_warehouse/blob/main/warehouse_analysis_query_03.png"/>
<br />
<br />
## Last step is to grouping by warehouses and ordering the results according to the number of orders completed using **GROUP BY** and **ORDER BY** functions:  <br/>
<img src="https://github.com/miracle99shoh/mySQL_query_warehouse/blob/main/warehouse_analysis_query_04.png"/>
<br />
<br />
## Combination of whole query looks like this:  <br/>
<img src="https://github.com/miracle99shoh/mySQL_query_warehouse/blob/main/warehouse_analysis_query_1.png"/>
<br />
<br />
## And this is the final result:  <br/>
<img src="https://github.com/miracle99shoh/mySQL_query_warehouse/blob/main/warehouse_analysis_query_2.png"/>
<br />
## <br /> Through the analysis we can see that the most orders were completed by "MI:Lansing Fulfillment Center" warehouse and <br />4 of the warehouses are under construction.
<br />
<h2> The End. Thank You <h2>
