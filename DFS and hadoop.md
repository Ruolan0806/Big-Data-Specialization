## What is distributed file system? (DFS)

* Data Partitioning
* Data Replication

DFS provide:

* Data Scalability
* Fault Tolerance
* High Concurrency

### Scalable Computing over the Internet

Single Compute Node
Parallel Computer

#### Commodity Cluster

* Affordable
* Less-specialized

* Distributed Computing
* Data-paralleslim
* Fault-tolerance
* Redudant data storage + Data parallel job restart

#### Programming Models for Big Data

Data parallel scalabilty - commodity clusters

  `Programming model = abstractions`

  **runtime libraries + programming langagues**
  
1. Support Big Data Operations
	* Split volumes of data
	* Acces Data Fast
	* Distribute Computations to Nodes
2. Handle Fault Tolerance
	* Replicate data partitions
	* Recover files when needed
3. Enable Adding More Racks
4. Optimezed for specific data types


`Mapa Reduce -> A programmming model for Bid Data -> Many implementatios`


#### Foundations For Big Data Quiz

1. Which of the following is the best description of why it is important to learn about the foundations in big data?
	Foundations stand the test of time.
2. What is the benefit of a commodity cluster?
	Enables fault tolerance.
3. What is a way to enable fault tolerance?
	Redundant Data Storage
4. What is NOT a benefit specific to a distributed file system?
	Large Storage
5. Which of the following is NOT a general requirement for a programming language in order to support big data models?
	Utilize Map Reduction Methods
	
	
## Getting Started with Hadoop

1. Enable Scalability
2. Handle Falut Tolerance
3. Optimized for a Variety Data Types
4. Facilitate a Shared Environment
5. Provide value 

### Hadoop: Why, Where and Who?

### What's in the ecosystem?

### Why is it beneficial?

### Where is it used?

### Who uses it?

### How do these tools work?

## The Hadoop Ecosystem: Welcome to the zoo!

Layer Diagram

* Distributed file system as foundation
* Flexible scheduling and resource management (YARN)
* Simplified programming model
	* Map -> apply()
	* Recuce -> summarize()
* Higher-level programming models
	* Pig = dataflow scripting
 	* Hive = SQL-like queries
* Specialized models for graph processing
   * Giraph = process large sclae graphs
* Real-time and in-memory processing
   * Storm, Spark and Flink 
* Zookeeper for management

## The Hadoop Distributed File System: A Storage System for Big Data

HDFS = foudation for Hadoop ecosystem

* Scalability
* Reliability

*Store massively large data sets*

*Replication for fault tolerance*

Two key components of HDFS

1. NameNode for metadata (Usually one per cluster)
2. DataNode for block storage (Usually one por machine)

## YARN: A Resource Manager for Hadoop
