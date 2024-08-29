**Problem Statement** : Spar Nord Bank is trying to observe the withdrawal behavior and the corresponding dependent factors to optimally manage the refill frequency we have data from more than 100 banks.

**Solution** :In this ETL project, task is to build a batch ETL pipeline to read transactional data from RDS, transform and load it into target dimensions and facts on Redshift and perform analysis.

**The tasks performed in this project are:**

1]Extracting the transactional data from a given MySQL RDS server to HDFS instance using **Sqoop.**

2]Transforming the transactional data according to the given target schema using **PySpark**.

3]Transformed data is to be loaded to an **S3 bucke**t.

4]Creating the Redshift tables according to the given schema.

5]Loading the data from Amazon S3 to **Redshift** tables.

Performing the analysis queries.
