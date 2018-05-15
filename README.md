# hadoop-example
Hadoop map reduce example

hdfs dfs -rm -r /user/huangzehai/wordcount/output
hadoop jar target/hadoop-example-1.0-SNAPSHOT.jar huangzehai.mr.wordcout.WordCount /user/huangzehai/wordcount/input /user/huangzehai/wordcount/output