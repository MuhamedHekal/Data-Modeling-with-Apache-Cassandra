# Data-Modeling-with-Apache-Cassandra

## Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

## Project Description
In this project, I will apply data modeling with Apache Cassandra and build the Sparkify keyspace using Python. I will preprocess the data and gather it into a single file called `event_datafile_new`. Then, I will transfer this data into tables based on specific queries. After transferring the data, I will check the data by running queries on the tables and retrieving the results.

#### 1. project.ipynb

In this file, I will apply data modeling with Apache Cassandra and build the Sparkify keyspace using Python. The process includes the following steps:

- Gather data from various CSV files and combine them into a single, cleaned file called event_datafile_new.csv .
- Create the keyspace `sparkify` and tables `[session_item, user_session, user_song]` based on specific queries.
- Transfer the data from event_datafile_new into the created tables.
- Query the data from the tables to retrieve the results and ensure the data has been correctly transferred and stored.





