# Learning PySpark
This is the code repository for [Learning PySpark](https://www.packtpub.com/big-data-and-business-intelligence/learning-pyspark?utm_source=github&utm_medium=repository&utm_content=9781786463708), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

## About the book
Apache Spark is an open source framework for efficient cluster computing with a strong interface for data parallelism and fault tolerance. This book will show you how to leverage the power of Python and put it to use in the Spark ecosystem. You will start by getting a firm understanding of the Spark 2.0 architecture and how to set up a Python environment for Spark.

You will get familiar with the modules available in PySpark. You will learn how to abstract data with RDDs and DataFrames and understand the streaming capabilities of PySpark. Also, you will get a thorough overview of machine learning capabilities of PySpark using ML and MLlib, graph processing using GraphFrames, and polyglot persistence using Blaze. Finally, you will learn how to deploy your applications to the cloud using the spark-submit command.

By the end of this book, you will have established a firm understanding of the Spark Python API and how it can be used to build data-intensive applications.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter 03.

The code will look like the following:
          
        data_key = sc.parallelize( 
             [('a', 4),('b', 3),('c', 2),('a', 8),('d', 2),('b', 1), 
             ('d', 3)],4) 
        data_key.reduceByKey(lambda x, y: x + y).collect() 

### Software requirements:
For this book you need a personal computer (can be either Windows machine, Mac, or Linux). To run Apache Spark, you will need Java 7+ and an installed and conﬁgured Python 2.6+ or 3.4+ environment; we use the Anaconda distribution of Python in version 3.5, which can be downloaded from https://www.continuum.io/downloads. 

The Python modules we randomly use throughout the book come preinstalled with Anaconda. We also use GraphFrames and TensorFrames that can be loaded dynamically while starting a Spark instance: to load these you just need an Internet connection. It is ﬁ ne if some of those modules are not currently installed on your machine – we will guide you through the installation process. 

### Note:
Chapter 11 and Bouns Chapter 02 does not contain code files.

## Related Products:
* [Python Machine Learning](https://www.packtpub.com/big-data-and-business-intelligence/python-machine-learning?utm_source=github&utm_medium=repository&utm_content=9781783555130)

* [Spark for Python Developers](https://www.packtpub.com/big-data-and-business-intelligence/spark-python-developers?utm_source=github&utm_medium=repository&utm_content=9781784399696)

* [Python Data Analysis Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/python-data-analysis-cookbook?utm_source=github&utm_medium=repository&utm_content=9781785282287)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.


