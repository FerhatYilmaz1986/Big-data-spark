# Handling Big Data with Spark  
  
### What is Spark?  
  Spark is defined as "a fast and general engine for large-scale data processing" in Spark's website. It is built around one main  
  concept: Resilient Distributed Dataset(RDD)  
    
### Advantages of Spark:  
   - Power and speed  
   ![Running Time Comparison](/image/runningtime.png)  
   - Language flexibility(python,java,scala)  
   - Faster than map/reduce  
   - Scalibility  
     
### Components of Spark:  
  ![Spark Architecture](/image/sparkarcht.png)  
   - Spark Streaming : Process live streaming data    
   - Spark Sql : Run queries on Hadoop deployment    
   - Mllib : Machine learning lbraries built on top of Spark  
   - Graphx : Graph compoutation engine  
  
### Spark setup for Windows&Anaconda:  
   - Install pyspark using pip install pyspark  
   - Install Java
   - Set environment variables:  
    - PYSPARK_PYTHON = python3  
    - SPARK_HOME = C:\Users\Pc\Anaconda3\Lib\site-packages\pyspark  
   
 ### Example data analysis using Pyspark :  
 *[1.Pyhton codes in Jupyter notebook](/Pyspark.ipynb)  
   
 ### Spark & Hadoop :  
 *[1.Brief information about Hadoop ](/Brief_Hadoop.md)
 ### References:  
   - spark.apache.org