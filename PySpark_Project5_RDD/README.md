# PySpark_Project5_RDD 
![SparkRDD](https://github.com/Lunczer93/PySpark_Project5_RDD/assets/65483365/d0d8d32f-943a-4f76-8305-d398df6b3113)
# INTRODUCTION
<br>***Spark*** is a unified analytics engine for large-scale data processing. It provides high-level APIs in _Scala, Java, Python and R_.
<br>It also supports ***pandas API on Spark*** for _pandas workloads_.
<br> In addition, Spark revoles around the concept of a ***Resilient Distributed Dataset (RDD)***. It is a fault-tolerant collection of elements that can be operated on in parallel.
# PURPOSE OF PROJECT
<br>The main goal of this project was to create RDD and use transformations and actions in order to practise these ones.
<br>_All steps are described in the project._
# USE OF TRANSFORMATIONS & ACTIONS
1. These **actions**, which are supported by Spark, were used: collect(), glom(),first(),take(), reduce(func) with lambda, fold(), max(), min(), mean(), std(),countByKey(),countByValue(),sorted(),sortBy() and sample().
2. These **transformations**, which are supported by Spark, were used: map(func) with lambda, filter(func) with lambda, flatmap(func) with lambda, reduceByKey(func) with lambda, sortByKey(), groupByKey(), groupBy(func) with lambda, union(), intersection(), cartesian(), subtract(), collectAsMap() and mapValues().
3. Python functions were created and then compared with reduce() actions to indicate that the same result was obtained.
4. Python functions were created and then compared with map() transformations to indicate that the same result was obtained. Python funcions were also used in map() transformations.

<br>In-depth analysis and the usage of these transformations and actions with detailed information were included in **PySpark_Project5_RDD.ipynb**





###### To create this projects, these sites were used [Spark](https://github.com/apache/spark) & [PySpark](https://spark.apache.org/docs/latest/api/python/) & [RDD Programming Guide](https://spark.apache.org/docs/latest/rdd-programming-guide.html).
