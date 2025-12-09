# 🟡 Beginner Level – 10 Questions

What is Apache Spark?
Answer:
Apache Spark is an open-source distributed computing system for processing large-scale data with high speed and efficiency.

What is Scala?
Answer:
Scala is a high-level programming language that combines functional and object-oriented programming, often used with Spark for data processing.

What are RDDs in Spark?
Answer:
RDD (Resilient Distributed Dataset) is the fundamental data structure in Spark, allowing distributed processing of data with fault tolerance.

What is a DataFrame in Spark?
Answer:
A DataFrame is a distributed collection of data organized into named columns, similar to a table in relational databases.

What is Spark SQL?
Answer:
Spark SQL is a module for structured data processing that allows querying DataFrames using SQL syntax.

What is an Action vs. Transformation in Spark?
Answer:

Transformation: Creates a new RDD/DataFrame (e.g., map, filter)

Action: Triggers computation and returns a result (e.g., collect, count)

What is Lazy Evaluation in Spark?
Answer:
Spark delays execution of transformations until an action is called, optimizing the execution plan.

What are the 7 Wastes in Data Processing (adapted from Lean)?
Answer:
Transport, Inventory, Motion, Waiting, Overproduction, Overprocessing, Defects (applied to inefficient data pipelines).

What is a Spark Cluster?
Answer:
A Spark cluster is a collection of nodes with a master node coordinating worker nodes for distributed data processing.

What is Spark Streaming?
Answer:
A module in Spark for processing real-time streaming data in micro-batches.

# 🔵 Intermediate Level – 10 Questions

What is DAG in Spark?
Answer:
Directed Acyclic Graph (DAG) represents the sequence of transformations in Spark, ensuring optimized execution.

Difference between DataFrame and Dataset?
Answer:

DataFrame: Schema-based, type-safe for SQL-like operations.

Dataset: Combines DataFrame with strong typing and compile-time checks.

What is Spark MLlib?
Answer:
Spark’s scalable machine learning library for building models like classification, regression, clustering, and recommendation systems.

Explain Partitioning in Spark.
Answer:
Partitioning divides RDDs/DataFrames across nodes for parallel processing. Proper partitioning improves performance.

What is Broadcast Variable?
Answer:
A read-only variable shared across all worker nodes to efficiently distribute large datasets.

What is Accumulator in Spark?
Answer:
A variable used to aggregate information across worker nodes, commonly used for counters and sums.

What is Checkpointing in Spark?
Answer:
A process to save RDDs/DataFrames to reliable storage for fault tolerance and recovery.

Difference between Spark Core and Spark SQL?
Answer:

Spark Core: Handles RDDs, transformations, actions.

Spark SQL: Provides SQL interface and DataFrame APIs.

What is a Catalyst Optimizer?
Answer:
Spark SQL’s query optimization engine that generates an optimized execution plan for DataFrame queries.

What is a Shuffle in Spark?
Answer:
The process of redistributing data across partitions, often during join or aggregation operations.

# 🔴 Advanced Level – 10 Questions

What is Structured Streaming?
Answer:
Structured Streaming is Spark’s API for real-time stream processing with high-level abstractions using DataFrames/Datasets.

What is a Tungsten Execution Engine?
Answer:
Spark’s execution engine optimized for memory and CPU efficiency to improve query and task performance.

Explain Spark’s Catalyst Query Optimization Phases.
Answer:
Parsing → Analysis → Logical Optimization → Physical Planning → Code Generation → Execution.

Difference between Narrow and Wide Transformation?
Answer:

Narrow: Data required from a single partition (e.g., map)

Wide: Data required from multiple partitions (e.g., groupByKey, join)

What is Spark GraphX?
Answer:
Spark’s API for graph processing and computation like PageRank, connected components, and graph analytics.

What are Checkpointing vs Caching?
Answer:

Caching: Stores RDD/DataFrame in memory for faster access.

Checkpointing: Saves RDD/DataFrame to durable storage for fault tolerance.

What is Data Skew and How to Handle It?
Answer:
Data skew occurs when data is unevenly distributed across partitions; solutions include salting keys, repartitioning, or using custom partitioners.

What is Window Function in Spark SQL?
Answer:
A function that performs calculations across a range of rows related to the current row, e.g., ranking, running totals.

What is a Spark Job vs Stage vs Task?
Answer:

Job: Triggered by an action

Stage: Set of tasks executed together without shuffle

Task: Single unit of execution on a partition

What is Catalyst Optimizer’s Physical Plan?
Answer:
The stage where Spark decides the actual execution strategy, including join types, shuffles, and code generation.

https://www.icertglobal.com/data-science/apache-spark-and-scala
