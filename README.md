# Data Modeling with Cassandra
In this project,I will build data modeling with Apache Cassandra and complete an ETL pipeline using Python. To complete the project, I will need to model the data by creating tables in Apache Cassandra to run queries.


## Required installation:

- Jupyter Notebook:
You can follow this [link](https://jupyter.org/install) to install Jupyter Notebook , in case you have Python already installed on your machine.
Or, you can install [Anaconda](https://docs.anaconda.com/anaconda/install/), and use Jupyter Notebook through it.

- Apache Cassandra
You can follow this [link](http://cassandra.apache.org/) to install Apache Cassandra.

## Design:

Below are steps I will follow to complete each component of this project.

##### Modeling your NoSQL database or Apache Cassandra database:
 
1- Design tables to answer the queries outlined in the project template. <br/>
2- Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements. <br/>
3- Develop your CREATE statement for each of the tables to address each question. <br/>
4- Load the data with INSERT statement for each of the tables. <br/>
5- Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already exist. We recommend you also include DROP TABLE statement for each table, this way you can run drop and create tables whenever you want to reset your database and test your ETL pipeline. <br/>
6- Test by running the proper select statements with the correct WHERE clause. <br/>

##### Build ETL Pipeline:

1- Implement the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python. <br/>
2- Make necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in your data model. <br/>
3- Test by running SELECT statements after running the queries on your database. <br/>
