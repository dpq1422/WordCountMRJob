# WordCountMRJob
Word count sample dataset processing using Map Reduce job

This is simple Map Reduce Job to process any text file and give us word with occurrences as an output

While triggering Mapreduce job ‘WordCountDriver’ will be supplied as driver class and below command will be triggered

we will push input data to hdfs on location /hdp/retail/inputData/

hdfs dfs -ls /hdp/retail/inputData/

/hdp/retail/process/news.txt

hadoop jar MaxClosingPriceByMapreduce-0.0.1-SNAPSHOT.jar com.dpq.retail.WordCountDriver /hdp/retail/process/news.txt /temp/newsOutput1
 
