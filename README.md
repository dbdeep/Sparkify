# Sparkify
## Sparkify Sql data modelling

In this project, I modelled user activity data for a music streaming
app called Sparkify, created a relational database and ETL
pipeline designed to optimize queries for understanding what songs
users are listening to. In PostgreSQL, defined Fact and
Dimension tables and inserted data into the new tables.


## Sparkify NoSql data modelling

Modelled data in Apache cassandra to run specific queries for analysis.

## Sparkify Dara Warehosung

Built ELT pipeline that extracted their data from S3, staged them in Redshift, and transformed
data into a set of dimensional tables for their analytics team to
continue finding insights in what songs their users are listening to.

## Sparkify Data lake

Loaded data which resides in S3, in a directory of JSON logs of user activity on the app,
as well as a directory with JSON metadata of the songs in the app, processed the data into analytics tables
using Spark, and loaded them back into S3 and finally deployed this Spark
process on a cluster using AWS.

## Sparkify Airflow

Scheduled, automated, and monitored  data pipelines using Apache Airflow
