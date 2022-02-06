# PySpark_Basics
Basics of data manipulation using PySpark.

[Instructions to install PySpark](https://computingforgeeks.com/how-to-install-apache-spark-on-ubuntu-debian/)

[How to use PySpark on Jupyter Notebook](https://opensource.com/article/18/11/pyspark-jupyter-notebook)

# My configs: After installation add these lines to ~/.bashrc (Ubuntu 20.04)

---
#>>> Spark and PySpark >>>

export SPARK_HOME=/opt/spark

export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin

export PYTHONPATH=$SPARK_HOME/python:$SPARK_HOME/python/lib/py4j-0.10.8.1-src.zip

export PYSPARK_PYTHON=python3

export PYSPARK_DRIVER_PYTHON=jupyter

export PYSPARK_DRIVER_PYTHON_OPTS='notebook'

# <<< Spark and PySpark <<<
---
