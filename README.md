# spark-java-getting-started
A Getting started example with Spark and Java

Base reference from https://www.baeldung.com/apache-spark  
Created a separate repo for easy usage and testing

## Steps
1. git clone   
2. mvn package  
3. Execute in the Spark local cluster or single node   
   Copy the jar and input file to your local directory where spark-shell was executed  
spark-submit --class com.baeldung.WordCount --master local spark-java-getting-started-1.0-SNAPSHOT.jar spark_example.txt
