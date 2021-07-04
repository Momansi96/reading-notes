# Class12  

[Return to home page](https://momansi96.github.io/reading-notes/). 


## SQL && NoSQL

| SQL                                | NoSQL                         |

| relational                         | non-relational                | 

| table based                        | document, key-value, graph    | 

| vertically scalable                | horizontally scalable         | 

|  better for multi-row transactions | better for unstructured data  | 



* What kind of data is a good fit for an SQL database?

data that is highly structured and associations among the program entities are clearly defined.

* Give a real world example.

if you are developing a point of sale system where you need to store customer orders and product records.

* What kind of data is a good fit a NoSQL database?

key-value stores, wide column stores, graph databases, and document databases,

* Give a real world example.

JSON files 

* Which type of database is best for hierarchical data storage?

NoSQL database

* Which type of database is best for scalability?

In most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.


* What does SQL stand for?

Structured Query Language

* What is a realational database?

it is a type of database that stores and provides access to data points that are related to one another.

* What type of structure does a relational database work with?

logical data structures

* What is a ‘schema’?

A schema is a collection of logical structures of data

* What is a NoSQL database?

NoSQL is a type of database that stores and retrieves data without needing to define its structure first . 

* How does it work?

Each type of NoSQL database would be designed with a specific customer situation in mind, and there would be technical reasons for how each kind of database would be organized. The simplest type to describe is the document database, in which it would be natural to combine both the basic information and the customer information in one JSON document. In this case, each of the SQL column attributes would be fields and the details of a customer’s record would be the data values associated with each field.

* What is inside of a Mongo database?

documents that are stored in JSON format

* Which is more flexible - SQL or MongoDB? and why.

While MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.

* What is the disadvantage of a NoSQL database?

NoSQL databases don't have the reliability functions which Relational Databases have 