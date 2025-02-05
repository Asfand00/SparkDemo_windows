# SparkDemo_windows

## Overwiew:
Learn how to use Apache Spark for distributed data processing and analysis. You will explore basic data manipulation using Spark’s Resilient Distributed Datasets (RDDs) or the DataFrames API.

## Instructions:
I used this guide here on notion since im using windows for my OS: https://itsmevee.notion.site/Resources-Apache-PySpark-for-Window-OS-18dc45e4348d80d894c0e8d5e3c46aa7 

Basic Reuqirements include
- Spark verison 3.5.4
- Java JDK version 8
- Py4j 0.10.9.7
- Python 3.10 when creating your enviornment
- Hadoop 3.0.0 (https://github.com/steveloughran/winutils/blob/master/hadoop-3.0.0/bin/winutils.exe), make sure to download the whole folder not just winutils.exe, best way is to clone the repo then use specifcially the hadoop 3.0.0 folder (can copy the contents into your own folder if needed)

## Explanations of each example
I outlined and explain each example in the youtube video here: https://www.youtube.com/watch?v=oDy2gzNTcPI 

Basically this covers using the Dataframe, SQL, and RDD APIs with spark with simple examples of creating tables, data manipulation, and handling unstructed data.

Essentially i follow the apache spark examples from this site: https://spark.apache.org/examples.html 
