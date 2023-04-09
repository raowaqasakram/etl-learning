# Fetch newly created data from MongoDB - Talend (Part 1)

## Overview
In this article, author Rao Waqas Akram explains how to extract only the newly created data from a MongoDB source database and load it into a MySQL target database using Talend Open Studio for Big Data 8.0. The article provides step-by-step instructions for setting up the environment, inserting data into MongoDB, creating a table in MySQL, designing an ETL job, and testing the job.

## Requirements
- Talend Open Studio for Big Data 8.0
- MongoDB (source database)
- MySQL 8.0 (target database)
- MySQL Workbench (for graphical interaction with MySQL server)
- MongoDB Compass (for graphical interaction with MongoDB server)
- Docker (for running containers of MySQL and MongoDB)

## Solution
The article suggests an efficient solution to the problem of data inconsistency, duplication, and time consumption caused by extracting all data from the source database on every job run. The solution involves loading the timestamp of the last row from the target database and storing it in the globalMap in Talend job. Then, querying the source database to return only the rows created after this timestamp.

## Steps
The article provides detailed instructions for the following steps:
1. Environment Setup
2. Inserting data into MongoDB
3. Creating a table in MySQL Database
4. Designing the ETL Job
5. Testing the Job

## Conclusion
The article provides a clear and concise guide for fetching newly created data from MongoDB using Talend Open Studio for Big Data 8.0. By following the step-by-step instructions, readers can efficiently extract only the required data from the source database and load it into the target database, avoiding data inconsistency, duplication, and time consumption.

## Article Link
[Fetch Latest Data from MongoDB using Talend](https://blog.devgenius.io/fetch-latest-data-from-mongodb-talend-1f21ba7b98b5)

