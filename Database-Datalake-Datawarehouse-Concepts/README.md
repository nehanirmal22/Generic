
3 major cloud providers - Azure, AWS, GCP
These cloud providers provide multiple service offering raning from compute, storage, databases, Network, Management tools, Analytics, Security, App Integration

| Topic | Database | Datawarehouse | Datalake|
|-------|----------|----------|--------------|
|Definition | A database is a storage location that houses structured data. | A data warehouse is a system that stores highly structured information from various sources. Data warehouses typically store current and historical data from one or more systems. Simply Put - "Is a data warehouse a database?" Yes, a data warehouse is a giant database that is optimized for analytics. | A data lake is a repository of data from disparate sources that is stored in its original, raw format. Like data warehouses, data lakes store large amounts of current and historical data. What sets data lakes apart is their ability to store data in a variety of formats including JSON, BSON, CSV, TSV, Avro, ORC, and Parquet. |
| Use Case | Creating reports for financial and other data, Analyzing relatively small datasets, Automating business processes, Auditing data entry | The goal of using a data warehouse is to combine disparate data sources in order to analyze the data, look for insights, and create business intelligence (BI) in the form of reports and dashboards. | Typically, the primary purpose of a data lake is to analyze the data to gain insights. However, organizations sometimes use data lakes simply for their cheap storage with the idea that the data may be used for analytics in the future. |
| Examples | •	Relational databases: Oracle, MySQL, Microsoft SQL Server, and PostgreSQL
•	Document databases: MongoDB and CouchDB
•	Key-value databases: Redis and DynamoDB
•	Wide-column stores: Cassandra and HBase
•	Graph databases: Neo4j and Amazon Neptune | •	Amazon Redshift
•	Google BigQuery
•	IBM Db2 Warehouse
•	Microsoft Azure Synapse
•	Oracle Autonomous Data Warehouse
•	Snowflake
•	Teradata Vantage | The following are examples of technology that provide flexible and scalable storage for building data lakes:

•	AWS S3
•	Azure Data Lake Storage Gen2
•	Google Cloud Storage

Other technologies enable organizing and querying data in data lakes, including:


•	MongoDB Atlas Data Lake
•	AWS Athena
•	Presto
•	Starburst
•	Databricks SQL Analytics | 







