# streamingData-to-snowflake

Faker Python script (generates fake/streaming data) hosted on EC2 Linux instance > Apache Nifi on Docker > AWS S3 > Snowflake [Snowpipe] 

### Architecture Diagram

![Architecture Diagram](https://raw.githubusercontent.com/rokusho235/streamingData-to-snowflake/main/overview.jpg)

### Services Used

1.  **AWS: EC2, S3**
3.  **Docker**
4.  **Apache: ZooKeeper, NiFi**
5.  **Snowflake: Snowpipe, Stream, Task**
