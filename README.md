## Udemy Python and Spark for Big Data

Does not actually have grading.  I do not know if this is a universal quality of all Udemy courses but it does make the 'certificate' less impressive.  However, going thru this class puts together a great cook-book for current abilities of Spark 2.4.4 circa 2020.  Also, running thru these exercises will quickly show if a given Spark installation is valid and complete.

The great thing about these examples and the bad thing about these examples are that the exercises are based on clean small data.  These small 100-2000 dependent examples cases with up to a dozen independent fields will not address tuning, how to determine required memory or executors.  No one would really fire up spark for something this small.  That said, the examples run fast.  Working through them does not mean meandering into extensive data cleanup.  The concepts presented are shown clearly and concisely.  

This body serves so nicely as a cook-book I added in examples to connect to Oracle and S3.  

## Material from Udemy Python and Spark for Big Data.

NB: Directories "SparkStreaming" and "DataGenerator" were originally named "Spark Streaming" and "Data Set Generator (remove me the future!)".  Spaces in Linux directories can be cumbersome and an exclamation mark is interpretted as run the last command.  I consider these really bad choices for directory names on a Linux system. For those reasons, I renamed the directories, which will require modification of source code.

Most of the workbooks have been ran on my work Mac {'OS': 'Mohave', 'OS-vers': '10.14.5', 'Python': '3.7.4', 'Spark':'2.4.4').  Running thru jupyter-notebooks requires a clear path to spark so I have added a block:

import findspark
findspark.init()
from pyspark.sql import SparkSession

to notebooks I actually ran and tested or wrote from scratch.  

Generally, I did my own 'Consulting Project' and did not run his 'Consultant Solution' but did listen to him present it.  

# Python-and-Spark-for-Big-Data
Course Notebooks for Python and Spark for Big Data

Course Outline:

* Course Introduction
    * Promo/Intro Video
    * Course Curriculum Overview
    * Introduction to Spark, RDDs, and Spark 2.0
    
* Course Set-up
    * Set-up Overview
    * EC2 Installation Guide
    * Local Installation Guide with VirtualBox
    * Databricks Notebooks
    * Unix Command Line Basics and Jupyter Notebook Overview
    
* Spark DataFrames
    * Spark DataFrames Section Introduction
    * Spark DataFrame Basics
    * Spark DataFrame Operations
    * Groupby and Aggregate Functions
    * Missing Data
    * Dates and Timestamps
    
* Spark DataFrame Project
    * DataFrame Project Exercise
    * DataFrame Project Exercise Solutions
    
* Machine Learning
    * Introduction to Machine Learning and ISLR
    * Machine Learning with Spark and Python and MLlib
    * Consulting Project Approach Overview
    
* Linear Regression
    * Introduction to Linear Regression 
    * Discussion on Data Transformations
    * Linear Regression with PySpark Example (Car Data)
    * Linear Regression Consulting Project (Housing Data)
    * Linear Regression Consulting Project Solution

* Logistic Regression
    * Introduction to Logisitic Regression 
    * Logistic Regression Example
    * Logistic Regression Consulting Project (Customer Churn)
    * Logistic Regression Consluting Project Solution
    
* Tree Methods
    * Introduction to Tree Methods
    * Decision Tree and Random Forest Example
    * Random Forest Classification Consulting Project - Dog Food Data
    * RF Classification Consulting Project Solutions
    * RF Regression Project - (Facebook Data)
    
* Clustering
    * Introduction to K-means Clustering
    * Clustering Example - Iris Dataset
    * Clustering Consulting Project - Customer Segmentation (Fake Data)
    * Clustering Consulting Project Solutions
    
* Recommender System
    * Introduction to Recommender Systems and Collaborative Filtering
    * Code Along Project - MovieLens Dataset
    * Possible Consulting Project ? Company Service Reviews
    
* Natural Language Processing
    * Introduction to Project/NLP/Naive Bayes Model
    * What are pipelines?
    * Code Along 
    
* Spark Streaming
    * Introduction to Spark Streaming 
    * Spark Streaming Code-along!
 
    
    
    

 
