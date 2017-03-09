# Relational Database with Python

This notebook is a quick introduction of how to setup and use a relational database by using python toolkit called SQLAlchemy. 

## Introduction

A relational database store data in tables. Each table contains rows and columns. Most relational database systems use Structured Query Language (**SQL**) as the language for querying and maintaining the database. There are many commercial and open-source *Relational Database Management System* (**RDMS**) such as Oracle, IBM, MySQL and PostgreSQL. 

 

These are some advantages of using  relational database system over *flat files format (CSV-format)*:
[database vs. flat files](http://stackoverflow.com/questions/2356851/database-vs-flat-files)

1. Databases can handle complitated queries without going though the whole file.
2. Databases can handle indexing tasks *(e.g. search index == something )*
3. Databases can update data easily
4. Databases can scale effortlessly


## Prerequisites

1. **postgresql**  
2. **sqlalchemy**  
3. **psycopg2**
4. **Amazon Web Services DB Instance** 

## Installation

First, install **PostgreSQL** from [the following page.](https://www.postgresql.org/download/)

Second, to install python dependencies, run 

``` pip install psycopg2 sqlalchemy sqlalchemy_utils```  

Then, AWS DB Instance from [this page](http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_GettingStarted.CreatingConnecting.PostgreSQL.html) and setup DB instance with PostgreSQL. Keep in mind that creating a new DB instance can take between 10 to 20 mins. From this, username, password, port (default=5432) and host will be obtained. Host address will be like 

```shell
******.us-west-2.rds.amazonaws.com
```
