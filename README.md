# Data Engineering Terms

Terms are classified according to data engineering lifecycle

## Data Generation

| Terms | Meaning |
|-------|---------|


## Data Ingestion

| Terms | Meaning |
|-------|---------|
| [ETL (Extract - Transform - Load)](https://www.databricks.com/discover/etl/vs-elt) | The process involves extracting data from its source first, followed by transformation into a usable format in a staging area, and finishing with the transfer of the usable data to a storage repository where it can be accessed for analysis |
| [ELT (Extract - Load - Transform)](https://www.databricks.com/discover/etl/vs-elt) | The process that data is loaded as soon as it is extracted, without being transformed first. It is then transformed into a usable format as needed, directly from the data repository |
| [Data Connector](https://airbyte.com/data-engineering-resources/data-connectors) | Software components or tools that facilitate data transfer between different systems or applications. They establish a bridge between disparate data sources and destinations |
| Schema Evolution ||

## Data Storage

| Terms | Meaning |
|-------|---------|
| [Data Warehouse](https://www.databricks.com/discover/data-warehouse) | A data management system that stores current and historical data from multiple sources in a business-friendly manner for easier insights and reporting |
| [Data Lake](https://www.databricks.com/discover/data-lakes) | A central location that holds a large amount of data in its native, raw format. A data lake uses a flat architecture and object storage to store the data |
| [Data Lakehouse](https://www.databricks.com/blog/what-is-data-lakehouse) | A new, open data management architecture that combines the flexibility, cost-efficiency, and scale of data lakes with the data management and ACID transactions of data warehouses, enabling business intelligence (BI) and machine learning (ML) on all data |
| [Staging Area](https://www.startdataengineering.com/post/what-and-why-staging/) | An area where the raw/unprocessed data lives, before being transformed for downstream use. Staging areas can be database tables, files in a cloud storage system, etc.|
| [Schema](https://www.databricks.com/blog/what-is-database-schema) | The structural framework that defines how data is organized, stored and accessed within a database |
| [Schema Evolution](https://www.dremio.com/wiki/schema-evolution/) | The process of modifying the schema of a database system in a way that preserves existing data and maintains its compatibility with the old schema |
| [Schema-on-Read](https://www.dremio.com/wiki/schema-on-read-vs-schema-on-write/) | Data processing approach that the schema is applied when reading the data |
| [Schema-on-Write](https://www.dremio.com/wiki/schema-on-read-vs-schema-on-write/) | Data processing approach that applies a schema to data before writing it into the database |

## Data Transformation

| Terms | Meaning |
|-------|---------|
| [Star Schema](https://www.databricks.com/blog/what-is-star-schema) | A multi-dimensional data model used to organize data in a database so that it is easy to understand and analyze |

## Data Serving

| Terms | Meaning |
|-------|---------|

## Undercurrents

### Security

| Terms | Meaning |
|-------|---------|

### Data Management

| Terms | Meaning |
|-------|---------|

### DataOps

| Terms | Meaning |
|-------|---------|

### Data Architecture

| Terms | Meaning |
|-------|---------|
| [MPP (Massively Parallel Processing)](https://www.dremio.com/wiki/massively-parallel-processing/) | A computing model that uses numerous processors (or computers) to execute tasks simultaneously. With MPP, complex problems can be divided into smaller, independent tasks, allowing for faster completion of data-intensive operations |

### Data Orchestration

| Terms | Meaning |
|-------|---------|
| [DAG (Directed Acyclic Graph)](https://www.databricks.com/blog/what-is-dag) | A type of graph that has three defining properties: it is directed, acyclic and composed of nodes connected by edges. These properties make DAGs ideal for describing processes that must occur in a controlled sequence, such as Tasks in Ariflow |

### Software Engineering

| Terms | Meaning |
|-------|---------|

