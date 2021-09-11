# Storage

Storage fundamentals:
Factors affecting choice of storage:
1. Structured vs Un-structured data
2. Query patterns
3. Scale/Volume of data

Storage based on use case:
1. Caching - Redis
2. Blob.Photos/Videos - Amazon S3
3. Text Search/ Fuzzy search - Elastic search
4. Time series/telemetry/metric data - Open TSDB
5. Bulk data for analytics, offline reporting - Hadoop/hdfs

SQL vs NoSQL
1. Structured + ACID -> RDBMS like MySQL, Oracle PostGres etc.
2. Structure + No ACID -> Sql or NoSql any
3. Unstructured + diverse variety data and queries - document db like Mongo, couchbase
4. Unstructured + huge volume of data but less queries or ever increasing data - Cassandra, HBASE, Dynamo
