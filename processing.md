## Apache Hadoop

* Apache Hadoop is a programming framework for distributed processing across cluster of computers

* It can scale up from single server to housands of machines each offering local computarion and storage

* The library itself is designed to detect and handle failures ar the application layer

* Modules

  * Hadoop Common
  * Hadoop Distributed File System (HDFS)
  * Hadoop YARN
  * Hadoop MapReduce

* Hadoop Common

  * Libraries and utilities using by other Hadoop modules
  * Considered the core of Hadoop
  * Abstraction of the underlying operating system and its file system
  * Contents JAR files and scripts required to start Hadoop

* Hadoop Distributed File System

  * Distributed file system
  * Fault-tolerant
  * Data Replication
  * High throughput to data

* Hadoop YARN

  * Yet another Resource negotiator
  * Cluster resource manager and job scheduling

* Hadoop MapReduce

  * Processing very large data sets
  * Parallel distributed algorithm on a cluster
  * Filesystem (unstructured)
  * Database (structured)
  * Data locality

* MapReduce Task

  * Map
    * Split data into smaller chunks
    * Proccessed in parallel
  * Reduce
    * Outputs of map task become input for the reduce task
    * Data is reduced to create an output file

* Hadoop Architecture

  * Diagrams here!!

* MapReduce Job Tasks

  