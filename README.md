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
   - Mllib : Machine learning libraries built on top of Spark  
   - Graphx : Graph computation engine  
  
### History of Spark APIs:  
   - RDD (2011)  
     - Distribute collection of JVM objects  
     - Functional Operators  
   - DataFrame (2013)
     - Distribute collection of Row objects  
     - Expression-based operations and UDFs  
     - Logical plans and optimizer  
     - Fast/efficient internal representations  
   - DataSet (2015)  
     - Internally rows, externally JVM objects  
     - Type safe + fast
     - But slower than DF. Not as good for interactive analysis  
### Spark & Clusters:  
   Spark supports the following resource/cluster managers:  
   - Spark Standalone – a simple cluster manager included with Spark  
   - Apache Mesos – a general cluster manager that can also run Hadoop applications  
   - Apache Hadoop YARN – the resource manager in Hadoop  
   - Kubernetes – an open source system for automating deployment, scaling, and management of containerized applications  
   - Spark also has a local mode, where the driver and executors run as threads on your computer instead of a cluster, which is useful for developing your applications from a personal computer.  

### Important Terms:  
   - RDD : Resilient Distributed Dataset
   - Transformation : Spark operation that produces an RDD
   - Action : Spark operation that produces a local object
   - Spark Job: Sequence of transformations on data with a final action 
  
### Spark setup for Windows&Anaconda:  
   - Install pyspark using pip install pyspark  
   - Install Java
   - Set environment variables:  
    - PYSPARK_PYTHON = python3  
    - SPARK_HOME = C:\Users\Pc\Anaconda3\Lib\site-packages\pyspark  
   
 ### Pyspark repositories :  
 *[1.NLP using pyspark in Jupyter notebook](/NLP_basics.ipynb)  
 *[1.K-means Clustering using pyspark in Jupyter notebook](/Kmeans_clustering.ipynb) 
 ### Spark & Hadoop :  
 *[1.Brief information about Hadoop ](/Brief_Hadoop.md)
 ### References:  
   - spark.apache.org
   - pypi.org  
   - databricks.com