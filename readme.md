### Modeling applications as Airport - 8:00 AM Thursday in Guava

7 Patterns

1. Queue Manager/Dispatcher - manage workers to maintain SLA

2. Infinite Scalability - ??? queue size/worker management?

3. Prioritized items - the haves

4. Arbitrary Prioritization - Every man for himself 

5. Re-insertion - cutting in line

6. Throughput measurement - metric mule

7. Begetting - you had one job

### Big Data Zoo - 9:15 AM Thursday in Indigo Bay

1. Hadoop
 *  HDFS - distributed (sharded) and replicated - S3 is another DFS
 *  Map Reduce - parallel computation on data
    * functional, Java
    * map phase - each doc is processed in place
    * shuffle
    * reduce phase - tuples are aggregated
 * Cloudera - Impala
 * Hortonworks
2. Apache Hive
  * SQL over HDFS using HiveQL
  * higher level, no Java
  * translates to MapReduce or DAG(Tez)
3. Apache Pig
  * Not SQL. Procedural, not declarative.
4. Workflow schedulers
  * Apache oozie
  * LinkedIn's Azkaban
  * Spotify's Luigi (python)
5. YARN (MapReduce 2.0)
6. Apache Spark
  * better, faster MapReduce
