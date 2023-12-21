PySpark installation steps on MAC: https://sparkbyexamples.com/pyspark/h...

Apache Spark Installation links:

1. Download JDK: https://www.oracle.com/in/java/techno...

2. Download Python: https://www.python.org/downloads/

3. Download Spark: https://spark.apache.org/downloads.html

Winutils repo link: https://github.com/steveloughran/winu...

Environment Variables:

HADOOP_HOME- C:\hadoop
JAVA_HOME- C:\java\jdk
SPARK_HOME- C:\spark\spark-3.3.1-bin-hadoop2
PYTHONPATH- %SPARK_HOME%\python;%SPARK_HOME%\python\lib\py4j-0.10.9-src;%PYTHONPATH%

Required Paths:

%SPARK_HOME%\bin
%HADOOP_HOME%\bin
%JAVA_HOME%\bin

To start jupyter notebook
i)conda activate pyspark
ii) jupyter notebook
