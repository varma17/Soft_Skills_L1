# NoSQL

   **NoSQL** databases (aka "not only SQL") are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads.

## What is NoSQL?

  When people use the term “NoSQL database”, they typically use it to refer to any non-relational database. Some say the term “NoSQL” stands for “non SQL” while others say it stands for “not only SQL.” Either way, most agree that NoSQL databases are databases that store data in a format other than relational tables.

  A common misconception is that NoSQL databases or non-relational databases don’t store relationship data well. NoSQL databases can store relationship data—they just store it differently than relational databases do. In fact, [when compared with SQL databases](https://www.mongodb.com/nosql-explained/nosql-vs-sql), many find modeling relationship data in NoSQL databases to be easier than in SQL databases, because related data doesn’t have to be split between tables.

NoSQL data models allow related data to be nested within a single data structure.

  NoSQL databases emerged in the late 2000s as the cost of storage dramatically decreased. Gone were the days of needing to create a complex, difficult-to-manage data model simply for the purposes of reducing data duplication. Developers (rather than storage) were becoming the primary cost of software development, so NoSQL databases optimized for developer productivity.

***

## Why NoSQL?

NoSQL is used because of the fundamental characteristics that give strength to it. The characteristics are - 

* It has high scalability and high availability.

* It uses the cloud so that it could deliver zero downtime.

* It can handle large volumes of data at a high speed.

* It can store unstructured, semi-structured, or structured data.

* It easy to add updates to schemas and fields and is developer-friendly.

***

## Types of NoSQL :

1. Document databases
2. Key-value databases
3. Wide-column stores 
4. Graph databases

<img src="https://cdn.guru99.com/images/1/101818_0537_NoSQLTutori5.png" width="700" height="300" />

**Document Databases** store data in documents similar to JSON (JavaScript Object Notation) objects. Each document contains pairs of fields and values. The values can typically be a variety of types including things like strings, numbers, booleans, arrays, or objects, and their structures typically align with objects developers are working with in code. Because of their variety of field value types and powerful query languages, document databases are great for a wide variety of use cases and can be used as a general purpose database. They can horizontally scale-out to accomodate large data volumes. MongoDB is consistently ranked as the world’s most popular NoSQL database according to [DB-engines](https://db-engines.com/en/ranking) and is an example of a document database. For more on document databases, visit [What is a Document Database?.](https://www.mongodb.com/document-databases)

**Key-value Databases** are a simpler type of database where each item contains keys and values. A value can typically only be retrieved by referencing its key, so learning how to query for a specific key-value pair is typically simple. Key-value databases are great for use cases where you need to store large amounts of data but you don’t need to perform complex queries to retrieve it. Common use cases include storing user preferences or caching. Redis and DynamoDB are popular key-value databases.

**Wide-column stores** store data in tables, rows, and dynamic columns. Wide-column stores provide a lot of flexibility over relational databases because each row is not required to have the same columns. Many consider wide-column stores to be two-dimensional key-value databases. Wide-column stores are great for when you need to store large amounts of data and you can predict what your query patterns will be. Wide-column stores are commonly used for storing Internet of Things data and user profile data. Cassandra and HBase are two of the most popular wide-column stores.

**Graph databases** store data in nodes and edges. Nodes typically store information about people, places, and things while edges store information about the relationships between the nodes. Graph databases excel in use cases where you need to traverse relationships to look for patterns such as social networks, fraud detection, and recommendation engines. Neo4j and JanusGraph are examples of graph databases.

## Top NoSQL Databases
 
 - **MongoDB**
 - **ElasticSearch**
 - **DynamoDB**
 - **HBase**
 - **Cassandra**

### ***MongoDB***
MongoDB is the most popular document-based NoSQL database. It is best fit for use-cases when you are planning to integrate hundreds of different data sources. Even when you are expecting read and write operations, you can use MongoDB. The database allows you to store clickstream data and use it for behavioural analysis.

### ***ElasticSearch***
This NoSQL database is used if the full-text search is part of your solution. It is used by more than 3000 companies including Udemy, Medium, and StackOverflow. Some of the popular use-cases involve chatbots which resolve most of the queries.

### ***DynamoDB***
Amazon's NoSQL database is known for its scalability. If your solutions require a database that can handle simple key-value queries in a large number, DynamoDB is the best choice. If you are working with OLTP workload, even then DynamoDB is preferred.

### ***HBase***
This is a highly scalable, open-source distributed database system. If the solution you are working on has petabytes of data, then HBase is the best choice. If you want to easily store real-time messages, it comes as an efficient solution.

### ***Cassandra***
This database solution was first built by Facebook. Cassandra is among the most scalable as it can handle petabytes of information and thousands of concurrent requests. It is the best fit for use cases requiring more writing operations than reading ones.

#### _References:-_

* https://www.mongodb.com/nosql-explained
* https://www.guru99.com/nosql-tutorial.html
* https://www.kdnuggets.com/2016/06/top-nosql-database-engines.html
