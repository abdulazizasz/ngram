# ngram

Instructions for run

1. mvn clean install
2. hadoop fs -put read.txt
3. hadoop jar hadoop-examples.jar NGram read.txt output 4

    NGram --> JobName  <br />
    read.txt --> input in HDFS <br /> 
    ouput --> Dir in HDFS <br />
    4 --> ngram n <br />

4. hadoop fs -cat output/part-r-00000
