# ngram
Simple run

1. mvn clean install
2. export HADOOP_CLASSPATH=hadoop-examples.jar
3. hadoop fs -put read.txt
4. hadoop NGram read.txt output 4

    NGram --> JobName 
    read.txt --> input in HDFS 
    ouput --> Dir in HDFS
    4 --> ngram n

5. hadoop fs -cat output/part-r-00000
