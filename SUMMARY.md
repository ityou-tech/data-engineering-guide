# Table of contents

* [🖌️ Getting started](README.md)

## INTRODUCTION

* [What is Data Engineering](introduction/what-is-data-engineering.md)
* [History and Evolution](introduction/history-and-evolution.md)
* [Importance of Data Engineering](introduction/importance-of-data-engineering.md)

## Data Systems and Architecture

* [Basics of Data Systems](data-systems-and-architecture/basics-of-data-systems/README.md)
  * [ACID](data-systems-and-architecture/basics-of-data-systems/acid.md)
  * [BASE](data-systems-and-architecture/basics-of-data-systems/base.md)
  * [CAP Theorem](data-systems-and-architecture/basics-of-data-systems/cap-theorem/README.md)
    * [Consistent and Available (CA)](data-systems-and-architecture/basics-of-data-systems/cap-theorem/consistent-and-available-ca.md)
    * [Availability and Partition tolerant (AP)](data-systems-and-architecture/basics-of-data-systems/cap-theorem/availability-and-partition-tolerant-ap.md)
    * [Consistent and Partition tolerant (CP)](data-systems-and-architecture/basics-of-data-systems/cap-theorem/consistent-and-partition-tolerant-cp.md)
* [Legacy Data Architecture](data-systems-and-architecture/legacy-data-architecture.md)
* [Modern Data Architecture](data-systems-and-architecture/modern-data-architecture.md)
* [Data Architectures](data-systems-and-architecture/data-architectures/README.md)
  * [Lambda](data-systems-and-architecture/data-architectures/lambda.md)
  * [Kappa](data-systems-and-architecture/data-architectures/kappa.md)
  * [Medallion](data-systems-and-architecture/data-architectures/medallion.md)
  * [Data Fabric](data-systems-and-architecture/data-architectures/data-fabric.md)
  * [Data Mesh](data-systems-and-architecture/data-architectures/data-mesh.md)
* [Data Management](data-systems-and-architecture/types-of-architecture/README.md)
  * [Data Lake](data-systems-and-architecture/types-of-architecture/data-lake.md)
  * [Data Warehouse](data-systems-and-architecture/types-of-architecture/data-warehouse.md)
  * [Data Lakehouse](data-systems-and-architecture/types-of-architecture/data-lakehouse.md)
  * [Data Mart](data-systems-and-architecture/types-of-architecture/data-mart.md)

## Programming languages for data engineering

* [Common choices](programming-languages-for-data-engineering/common-choices/README.md)
  * [Python](programming-languages-for-data-engineering/common-choices/python.md)
  * [SQL](programming-languages-for-data-engineering/common-choices/sql.md)
  * [Spark](programming-languages-for-data-engineering/common-choices/spark.md)
  * [Scala](programming-languages-for-data-engineering/common-choices/scala.md)
  * [R](programming-languages-for-data-engineering/common-choices/r.md)
  * [Julia](programming-languages-for-data-engineering/common-choices/julia.md)

## Data Collection and Storage

* [Unstructured](data-collection-and-storage/unstructured.md)
* [Structured](data-collection-and-storage/structured.md)
* [Data Sourcing](data-collection-and-storage/data-sourcing/README.md)
  * [Push](data-collection-and-storage/data-sourcing/push.md)
  * [Pull](data-collection-and-storage/data-sourcing/pull.md)

## Data Processing

* [Batch](data-processing/batch/README.md)
  * [Hadoop MapReduce](data-processing/batch/hadoop-mapreduce.md)
  * [Apache Hive](data-processing/batch/apache-hive.md)
  * [Apache Spark](data-processing/batch/apache-spark.md)
* [Streaming](data-processing/streaming/README.md)
  * [Apache Kafka Streams](data-processing/streaming/apache-kafka-streams.md)
  * [Apache Flink](data-processing/streaming/apache-flink.md)
  * [Apache Storm](data-processing/streaming/apache-storm.md)
* [Data Pipelines](data-processing/data-pipelines.md)
* [Compute](data-processing/compute.md)
* [Notebooks](data-processing/notebooks.md)

## Data Modeling

* [Types of Data Models](data-modeling/types-of-data-models/README.md)
  * [Conceptual](data-modeling/types-of-data-models/conceptual.md)
  * [Logical](data-modeling/types-of-data-models/logical.md)
  * [Physical](data-modeling/types-of-data-models/physical.md)
* [Types of Data Modeling](data-modeling/types-of-data-modeling/README.md)
  * [Hierarchical](data-modeling/types-of-data-modeling/hierarchical.md)
  * [Relational](data-modeling/types-of-data-modeling/relational/README.md)
    * [Entity-relationship (ER)](data-modeling/types-of-data-modeling/relational/entity-relationship-er.md)
    * [Object-oriented](data-modeling/types-of-data-modeling/relational/object-oriented.md)
    * [Dimensional](data-modeling/types-of-data-modeling/relational/dimensional.md)
* [Data Modeling Process](data-modeling/data-modeling-process.md)

## Data Quality

* [101](data-quality/101.md)

## Data Operations

* [DataOps](data-operations/dataops.md)
* [Clustering](data-operations/clustering.md)
* [Partitioning](data-operations/partitioning.md)
* [Pruning](data-operations/pruning.md)
* [Sharding](data-operations/sharding.md)
* [CI/CD](data-operations/ci-cd.md)

## Database Systems

* [Hierarchical](database-systems/hierarchical.md)
* [Relational](database-systems/relational.md)
* [Non-relational (noSQL)](database-systems/non-relational-nosql.md)
* [Document](database-systems/document.md)
* [Key-value](database-systems/key-value.md)
* [Column-oriented](database-systems/column-oriented.md)
* [Graph](database-systems/graph.md)
* [Vector](database-systems/vector.md)
* [Online Analytical Processing (OLAP)](database-systems/online-analytical-processing-olap.md)
* [Online Transactional Processing (OLTP)](database-systems/online-transactional-processing-oltp.md)

## Data Analysis and Reporting

* [CRUD](data-analysis-and-reporting/crud.md)
* [Tools for Data Analysis](data-analysis-and-reporting/tools-for-data-analysis/README.md)
  * [SQL](data-analysis-and-reporting/tools-for-data-analysis/sql.md)
  * [Common Functions](data-analysis-and-reporting/tools-for-data-analysis/common-functions/README.md)
    * [Coalesce](data-analysis-and-reporting/tools-for-data-analysis/common-functions/coalesce.md)
    * [Repartition](data-analysis-and-reporting/tools-for-data-analysis/common-functions/repartition.md)
* [Building Reports](data-analysis-and-reporting/building-reports.md)

## Data Formats

* [Open source](data-formats/open-source/README.md)
  * [Delta Lake](data-formats/open-source/delta-lake.md)
  * [Apache Iceberg](data-formats/open-source/apache-iceberg.md)
* [Closed source](data-formats/closed-source.md)

## Big Data Technologies

* [Introduction to Big Data](big-data-technologies/introduction-to-big-data.md)
* [Popular Big Data Tools](big-data-technologies/popular-big-data-tools/README.md)
  * [Hadoop](big-data-technologies/popular-big-data-tools/hadoop.md)

## Cloud Data Solutions

* [Cloud Providers Overview](cloud-data-solutions/cloud-providers-overview.md)
* [Benefits of Cloud for Data Engineering](cloud-data-solutions/benefits-of-cloud-for-data-engineering.md)

## Data Security and Compliance

* [Security Best Practices](data-security-and-compliance/security-best-practices.md)
* [Regulations and Compliance](data-security-and-compliance/regulations-and-compliance.md)
* [Data Goverance](data-security-and-compliance/data-goverance.md)

## Case Studies and Real-world Applications

* [Industry Examples](case-studies-and-real-world-applications/industry-examples.md)
* [Lessons Learned](case-studies-and-real-world-applications/lessons-learned.md)

## Getting Started in Data Engineering

* [Skills and Qualifications](getting-started-in-data-engineering/skills-and-qualifications.md)
* [Career Pathways](getting-started-in-data-engineering/career-pathways.md)

## Resources

* [Further Reading](resources/further-reading.md)
* [Online Courses and Certifications](resources/online-courses-and-certifications.md)
