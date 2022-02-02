
Reference Article - https://www.mongodb.com/databases/data-lake-vs-data-warehouse-vs-database#:~:text=A%20database%20stores%20the%20current,to%20easily%20analyze%20the%20data.


### Difference between a database, datawarehouse and a datalake

| Topic | Database | Datawarehouse | Datalake|
|-------|----------|----------|--------------|
|Definition | A database is a storage location that houses structured data. | A data warehouse is a system that stores highly structured information from various sources. Data warehouses typically store current and historical data from one or more systems. Simply Put - "Is a data warehouse a database?" Yes, a data warehouse is a giant database that is optimized for analytics. | A data lake is a repository of data from disparate sources that is stored in its original, raw format. Like data warehouses, data lakes store large amounts of current and historical data. What sets data lakes apart is their ability to store data in a variety of formats including JSON, BSON, CSV, TSV, Avro, ORC, and Parquet. |
| Use Case | Creating reports for financial and other data, Analyzing relatively small datasets, Automating business processes, Auditing data entry | The goal of using a data warehouse is to combine disparate data sources in order to analyze the data, look for insights, and create business intelligence (BI) in the form of reports and dashboards. | Typically, the primary purpose of a data lake is to analyze the data to gain insights. However, organizations sometimes use data lakes simply for their cheap storage with the idea that the data may be used for analytics in the future. |
| Examples | •	Relational databases: Oracle, MySQL, Microsoft SQL Server, and PostgreSQL •	Document databases: MongoDB and CouchDB •	Key-value databases: Redis and DynamoDB •	Wide-column stores: Cassandra and HBase •	Graph databases: Neo4j and Amazon Neptune | •	Amazon Redshift •	Google BigQuery •	IBM Db2 Warehouse •	Microsoft Azure Synapse •	Oracle Autonomous Data Warehouse •	Snowflake •	Teradata Vantage | The following are examples of technology that provide flexible and scalable storage for building data lakes:•	AWS S3 •	Azure Data Lake Storage Gen2 •	Google Cloud Storage Other technologies enable organizing and querying data in data lakes, including •	MongoDB Atlas Data Lake •	AWS Athena •	Presto •	Starburst •	Databricks SQL Analytics |
| Who Uses It? | If your application needs to store data (and nearly every interactive application does), your application needs a database. | Data warehouses are a good option when you need to store large amounts of historical data and/or perform in-depth analysis of your data to generate business intelligence. Due to their highly structured nature, analyzing the data in data warehouses is relatively straightforward and can be performed by business analysts and data scientists. | The primary users of a data lake can vary based on the structure of the data. Business analysts will be able to gain insights when the data is more structured. When the data is more unstructured, data analysis will likely require the expertise of developers, data scientists, or data engineers. The flexible nature of data lakes enables business analysts and data scientists to look for unexpected patterns and insights. The raw nature of the data combined with its volume allows users to solve problems they may not have been aware of when they initially configured the data lake. | 
| Type of Workload | Databases are typically accessed electronically and are used to support Online Transaction Processing (OLTP). | Both data warehouses and data lakes are meant to support Online Analytical Processing (OLAP). OLAP systems are typically used to collect data from a variety of sources. The data is then used to power a range of analytical use cases ranging from business intelligence and reporting (e.g., quarterly sales reports by store) to forecasting (e.g., predicting home sales for the next six months based on historical trends). |  Both data warehouses and data lakes are meant to support Online Analytical Processing (OLAP). OLAP systems are typically used to collect data from a variety of sources. The data is then used to power a range of analytical use cases ranging from business intelligence and reporting (e.g., quarterly sales reports by store) to forecasting (e.g., predicting home sales for the next six months based on historical trends). |



### Is Hadoop a Datalake?

To put it simply, Hadoop is a technology that can be used to build data lakes. A data lake is an architecture, while Hadoop is a component of that architecture. In other words, Hadoop is the platform for data lakes.







