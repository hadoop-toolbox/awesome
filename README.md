# awesome

## Hadoop Ökosystem

http://hadoop.apache.org/

The Apache Hadoop software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures.

http://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html

The fundamental idea of YARN is to split up the functionalities of resource management and job scheduling/monitoring into separate daemons. The idea is to have a global ResourceManager (RM) and per-application ApplicationMaster (AM). An application is either a single job or a DAG of jobs.

https://flink.apache.org/

Apache Flink® is an open-source stream processing framework for distributed, high-performing, always-available, and accurate data streaming applications.

http://kafka.apache.org/

Apache Kafka™ is a distributed streaming platform

[Spark™](https://spark.apache.org/): 

A fast and general compute engine for Hadoop data. Spark provides a simple and expressive programming model that supports a wide range of applications, including ETL, machine learning, stream processing, and graph computation.


http://storm.apache.org/

Apache Storm is a free and open source distributed realtime computation system. Storm makes it easy to reliably process unbounded streams of data, doing for realtime processing what Hadoop did for batch processing. Storm is simple, can be used with any programming language, and is a lot of fun to use!

http://samza.apache.org/

Apache Samza is a distributed stream processing framework. It uses Apache Kafka for messaging, and Apache Hadoop YARN to provide fault tolerance, processor isolation, security, and resource management.


[Ambari™](http://incubator.apache.org/ambari/):

A web-based tool for provisioning, managing, and monitoring Apache Hadoop clusters which includes support for Hadoop HDFS, Hadoop MapReduce, Hive, HCatalog, HBase, ZooKeeper, Oozie, Pig and Sqoop. Ambari also provides a dashboard for viewing cluster health such as heatmaps and ability to view MapReduce, Pig and Hive applications visually alongwith features to diagnose their performance characteristics in a user-friendly manner.

[Avro™](http://avro.apache.org/):

A data serialization system.

[Cassandra™](http://cassandra.apache.org/):

A scalable multi-master database with no single points of failure.

[Chukwa™](http://incubator.apache.org/chukwa/):

A data collection system for managing large distributed systems.

HBase™: 

A scalable, distributed database that supports structured data storage for large tables.

Hive™: 

A data warehouse infrastructure that provides data summarization and ad hoc querying.

Mahout™: 

A Scalable machine learning and data mining library.

Pig™: 

A high-level data-flow language and execution framework for parallel computation.

Tez™: 

A generalized data-flow programming framework, built on Hadoop YARN, which provides a powerful and flexible engine to execute an arbitrary DAG of tasks to process data for both batch and interactive use-cases. Tez is being adopted by Hive™, Pig™ and other frameworks in the Hadoop ecosystem, and also by other commercial software (e.g. ETL tools), to replace Hadoop™ MapReduce as the underlying execution engine.
ZooKeeper™: A high-performance coordination service for distributed applications.

## Links
https://hub.docker.com/r/sequenceiq/hadoop-docker/


## Blog's
[How-to: Install a Virtual Apache Hadoop Cluster with Vagrant and Cloudera Manager](https://blog.cloudera.com/blog/2014/06/how-to-install-a-virtual-apache-hadoop-cluster-with-vagrant-and-cloudera-manager/)

[Descrption](link)
