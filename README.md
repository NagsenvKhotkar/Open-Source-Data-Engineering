# Awesome Open-Source Data Engineering

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This [Awesome List](https://github.com/topics/awesome-list) aims at providing an overview of [open-source](https://opensource.org/licenses) projects related to data engineering.

This is a community effort: please [contribute](https://github.com/gunnarmorling/awesome-opensource-data-engineering/blob/master/CONTRIBUTING.md) and send your pull requests for growing this list!

For a list including non-OSS tools, see this amazing [Awesome List](https://github.com/igorbarinov/awesome-data-engineering).

## Table of Contents

- [Analytics](#analytics)
- [Business Intelligence](#business-intelligence)
- [Data Lakehouse](#data-lakehouse)
- [Change Data Capture](#change-data-capture)
- [Datastores](#datastores)
- [Data Governance and Registries](#data-governance-and-registries)
- [Data Virtualization](#data-virtualization)
- [Data Orchestration](#data-orchestration)
- [Formats](#formats)
- [Integration](#integration)
- [Messaging Infrastructure](#messaging-infrastructure)
- [Specifications and Standards](#specifications-and-standards)
- [Stream Processing](#stream-processing)
- [Testing](#testing)
- [Monitoring and Logging](#monitoring-and-logging)
- [Versioning](#versioning)
- [Workflow Management](#workflow-management)
- [Related Resources](#related-resources)
- [License](#license)

## Analytics

- [Apache Spark](https://spark.apache.org/) - A unified analytics engine for large-scale data processing. Includes APIs in Scala, Java, Python (known as PySpark), and R (SparkR).
- [Apache Beam](https://beam.apache.org/) - An open-source implementation of Google DataFlow. Provides capabilities of batch and streaming data processing jobs that run on any execution engine, including Spark, Flink, or its own DirectRunner. Supports multiple APIs in Java, Python, and Go.
- [Apache Flink](https://flink.apache.org/) - Stateful computations over data streams.
- [Trino (formerly known as PrestoSQL)](https://trino.io/) - Distributed SQL Query Engine for Big Data.

## Business Intelligence

- [Apache Superset](https://superset.incubator.apache.org/) - A modern, enterprise-ready business intelligence web application.
- [HUE](https://gethue.com/) - The Hadoop User Interface. Similar to Superset, but interfaces between RDBMS, Hive, Impala, HBase, Spark, HDFS & S3, Oozie, Pig, YARN Job Explorer, and more. Offers an extensible Django environment for custom app integration.
- [Metabase](https://www.metabase.com/) - An easy way for everyone in your company to ask questions and learn from data.
- [Redash](https://redash.io/) - All the tools to unlock your data.

## Data Lakehouse

- [Delta Lake](https://delta.io/) - Open-source storage framework that enables building a lakehouse architecture with compute engines including Spark, PrestoDB, Flink, Trino, and Hive and APIs for Scala, Java, Rust, Ruby, and Python.
- [Apache Hudi](https://hudi.apache.org/) - Transactional data lake platform that brings database and data warehouse capabilities to the data lake. Hudi reimagines slow old-school batch data processing with a powerful new incremental processing framework for low latency minute-level analytics.
- [Apache Iceberg](https://iceberg.apache.org/) - High-performance format for huge analytic tables. Iceberg brings the reliability and simplicity of SQL tables to big data, while making it possible for engines like Spark, Trino, Flink, Presto, Hive and Impala to safely work with the same tables, at the same time.

## Change Data Capture

- [Debezium](https://debezium.io/) - Change data capture for MySQL, Postgres, MongoDB, SQL Server and others.
- [Maxwell](https://github.com/zendesk/maxwell) - Maxwell's daemon, a MySQL-to-JSON Kafka producer.

## Datastores

- [Apache Calcite](https://calcite.apache.org/) - SQL parser, building blocks for datastores.
- [Apache Cassandra](http://cassandra.apache.org/) - Open Source distributed wide column store, NoSQL database.
- [Apache Druid](https://druid.apache.org/) - A high performance real-time analytics database.
- [Apache HBase](https://hbase.apache.org/) - Open Source non-relational distributed database.
- [Apache Pinot](https://pinot.apache.org/) - A realtime distributed OLAP datastore.
- [ClickHouse](https://clickhouse.tech/) - Open Source distributed column-oriented DBMS.
- [InfluxDB](https://www.influxdata.com/) - Purpose-Built Open Source Time Series Database.
- [MinIO](https://min.io/) - MinIO is a high performance, distributed object storage system and AWS S3 compatible.
- [Postgres](https://www.postgresql.org/) - The World's Most Advanced Open Source Relational Database.

## Data Governance and Registries

- [Amundsen](https://github.com/lyft/amundsen) - Metadata catalogue.
- [Apache Atlas](https://atlas.apache.org) - Data governance and metadata framework for Hadoop.
- [DataHub](https://github.com/linkedin/datahub) - A Generalized Metadata Search & Discovery Tool.
- [Metacat](https://github.com/Netflix/metacat) - Unified metadata exploration API service.
- [Elementary](https://github.com/elementary-data/elementary-lineage) - Data reliability solution, starting with plug-and-play data lineage and datasets operational status.
- [Monosi](https://github.com/monosidev/monosi) - Data observability & monitoring platform.
- [OpenMetadata](https://github.com/open-metadata/OpenMetadata) - Generalized metadata, search, and lineage tool.

## Data Virtualization

- [Apache Drill](https://drill.apache.org/) - Schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage.
- [Dremio](https://github.com/dremio/dremio-oss) - A data lake engine. Provides an Apache Arrow-based query and acceleration engine together with the ability to create an IT-governed self-service layer for data scientists and analysts.
- [Teiid](http://teiid.io/) - A relational abstraction of different information sources.
- [Presto](https://prestodb.io/) - Distributed SQL Query Engine for Big Data.

## Data Orchestration

- [Alluxio](https://github.com/Alluxio/alluxio) - Scalable, multi-tiered distributed caching for HDFS, S3, Ceph, NFS, and related filestores. Provides integrations for SQL queries into a Catalog from Spark, Hive, and Presto.
- [dbt](https://www.getdbt.com/) - Empowering data analysts and engineers to apply methodologies akin to those used by software engineers for constructing applications, dbt ensures data transformation processes align with established practices.

## Formats

- [Apache Avro](https://avro.apache.org/) - A data serialization system.
- [Apache Parquet](https://parquet.apache.org/) - A columnar storage format.
- [Apache ORC](https://orc.apache.org/) - Another columnar storage format.
- [Apache Thrift](https://thrift.apache.org/) - Data type and service interface definitions and code generator.
- [Apache Arrow](https://arrow.apache.org/) - A cross-language development platform for in-memory data. It specifies a standardized, language-independent, columnar memory format for flat and hierarchical data, organized for efficient analytic operations on modern hardware. It also provides computational libraries and zero-copy IPC and streaming messaging.
- [Cap’n Proto](https://capnproto.org/) - A data interchange format and capability-based RPC system.
- [FlatBuffers](https://google.github.io/flatbuffers/) - An efficient cross-platform serialization library for C++, C#, C, Go, Java, JavaScript, Lobster, Lua, TypeScript, PHP, Python, and Rust.
- [MessagePack](https://msgpack.org/index.html) - An efficient binary serialization format. It lets you exchange data among multiple languages like JSON.
- [Protocol Buffers](https://developers.google.com/protocol-buffers) - Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data.

## Integration

- [Apache Camel](https://camel.apache.org/) - Easily integrate various systems consuming or producing data.
- [Kafka Connect](https://kafka.apache.org/documentation/#connect) - Reusable framework to handle data in-and-out of Apache Kafka.
- [Logstash](https://www.elastic.co/logstash) - Open Source server-side data processing pipeline.
- [Telegraf](https://github.com/influxdata/telegraf) - A plugin-driven server agent written in Go for collecting and sending metrics and events from databases, systems, and IoT sensors. Offers hundreds of existing plugins.

## Messaging Infrastructure

- [Apache ActiveMQ](https://activemq.apache.org/) - Flexible & Powerful Multi-Protocol Messaging.
- [Apache Kafka](https://kafka.apache.org/) - A distributed commit log with messaging capabilities.
- [Apache Pulsar](https://pulsar.apache.org/) - A distributed pub-sub messaging system.
- [Liiklus](http://github.com/bsideup/liiklus) - An
