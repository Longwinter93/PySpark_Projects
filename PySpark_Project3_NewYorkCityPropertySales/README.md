# PySpark_Project3_NewYorkCityPropertySales
# INTRODUCTION 
<br>Residential buildings and other buildings in the New York City are highly popular.
<br>New York City is composed of five boroughs in particular  The Bronx, Brooklyn, Manhattan, Queens, and Staten Island.
<br> **This analysis was performed to find out about the feature of buildings regarding building class, residential and commercial units, land & gross square feet, year built and sale from these boroughs**
<br>Analysis was  performed by using ***Apache Spark***.
<br>***Spark*** is a unified analytics engine for large-scale data processing. It provides high-level APIs in _Scala, Java, Python and R_.
<br>It also supports ***pandas API on Spark*** for _pandas workloads_.
# ANALYSIS
<br>Analysis was perfomed by **PySpark**. **PySpark** is the **Python API** for _Apache Spark_. 
<br>***Advanced functions for ETL/ELT transformations were used to create this project.***
<br>Before analysis, data was cleaned using advanced **PySpark functions & methods**
<br>All steps with detailed information is also described in [PySpark_Project3_NewYorkCityPropertySales.ipynb](https://github.com/Longwinter93/PySpark_Projects/blob/main/PySpark_Project3_NewYorkCityPropertySales/PySpark_Project3_NewYorkCityPropertySales.ipynb)

# MAIN CONCLUSIONS

<br>1. Statistical methods such as sum, average, maximum and minimum values of Sales were calculated for all boroughs
<br>2. The most expensive bulding from each neighborhood was calculated for each borough.
<br>3. Cummulative Sum of Sales from 2003 to 2019 was calculated for each borough. 
<br>3a. Cummulative Sum of Sales for _Bronx_ is $59392997918, while sum of sales is $4514707976
<br>3b. Cummulative Sum of Sales for _Brooklyn_ is $238664892191, while sum of sales is $20128917053
<br>3c. Cummulative Sum of Sales for _Manhattan_ is $791911487849, while sum of sales is $41408544863
<br>3d. Cummulative Sum of Sales for _Queens_  is $197878260661, while sum of sales is $16262013320
<br>3e. Cummulative Sum of Sales for _StatenIsland_  is $44226510928, while sum of sales is $2324542019
<br>4. Year-over-Year Growth Rate for Sales was also calculated between 2003 and 2019 for each borough
<br>5. The most expensive building belongs to COOPS - ELEVATOR APARTMENTS and costs $1491996676 from a Riverdale neighborhood from a _Bronx_ borough, while the most cheapest belongs to ASYLUMS AND HOMES and costs $1 from a Co-op city neighborhood. The cost of the building was calculated based on the sum of the sales between 2003-2019
<br>6. The most expensive building belongs to CONDOS - ELEVATOR APARTMENTS and costs $2413396614.00 from a Williamsburg-north neighborhood from a _Brooklyn_ borough, while the most cheapest belongs to RENTALS - ELEVATOR APARTMENTS and costs $1 from a Downtown-metrotech neighborhood. The cost of the building was calculated based on the sum of the sales between 2003-2019
<br>7. The most expensive building belongs to OFFICE BUILDINGS  and costs $33801303759 from a Midtown cbd neighborhood from a _Manhattan_ borough, while the most cheapest belongs to TAX CLASS 1 CONDOS and costs $1 from a Soho neighborhood. The cost of the building was calculated based on the sum of the sales between 2003-2019
<br>8. The most expensive building belongs to ONE FAMILY HOMES  and costs $2984584627 from a Flushing-north neighborhood from a _Queens_  borough, while the most cheapest belongs to RENTALS - ELEVATOR APARTMENTS and costs $1 from a Forest hills  neighborhood. The cost of the building was calculated based on the sum of the sales between 2003-2019
<br>9. The most expensive building belongs to ONE FAMILY HOMES  and costs $1283228296 from a Great kills  neighborhood from a _StatenIsland_  borough, while the most cheapest belongs to RENTALS - ELEVATOR APARTMENTS and costs $1 from a West new brighton  neighborhood. The cost of the building was calculated based on the sum of the sales between 2003-2019

<br>In-depth analysis with detailed information is included in **PySpark_Project3_NewYorkCityPropertySales.ipynb**





###### To create this projects, these sites were used [Spark](https://github.com/apache/spark) & [PySpark](https://spark.apache.org/docs/latest/api/python/).
