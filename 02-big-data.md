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
