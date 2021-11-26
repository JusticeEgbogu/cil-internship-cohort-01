## Do an extensive comparison on the different use cases 
## for different kinds of databases.
_{Database is a collection, or a set of tables. The table is the most basic building of a database.
Tables are composed of rows and columns,each column describes a piece of data so does every row.}_

There are four common types of database model that are
useful for different types of data or information.

## 1. Hierarchical databases:
_{In a hierarchical database model is one of the oldest database models, the data is organized into a tree-like structure with nodes representing records and branches representing fields, this database model typically has a Parent-child relationship with single parent and multiple child states. A use case of hierarchical database model is the global Domain Name Service (DNS).}_
_{DNS servers form a global tree. The root name servers are at the “root zone” at the base of the tree; individual DNS entries form the leaves. www.internship.com points to the internship.com DNS database, which is part of the dot com (.com) top level domain (TLD), which is part of the global DNS (root zone). From the root, you may go back down another branch. It is based on logical dependencies, that is one field comes before the other}_
Advantages of Hierarchical databases include:
* The model allows us easy addition and deletion of new information.
* Data at the top of the Hierarchy is very fast to access.
* It worked well with linear data storage mediums such as tapes.
* It relates well to anything that works through a one to many relationships

Disadvantages of Hierarchical databases include:
* It requires data to be repetitively stored in many different entities.
* Now a day there is no longer use of linear data storage mediums such as tapes.
* Searching for data requires the DBMS to run through the entire model from top to bottom until the required information is found, making   queries very slow.
* This model support only one to many relationships, many to many relationships are not supported.

## 2. Network databases:
_{Network databases are similar to the hierarchical database model. The Network database model organises data in a graph-like manner and can have more than one parent node. The network model is a database model conceived as a flexible way of representing objects and their relationships.}_
_{This model is used in fraud detection,business events and customer data, such as new accounts, loan applications and credit card transactions can be modelled in a graph in order to detect fraud.}_
_{Entities are extracted from a large database of business activities, and relationships are made between them, and this is modelled into a network. Techniques such as “Entity Link Analysis” are used to identify suspicious links between types of entities that may indicate fraudulent behaviour.}_

Advantages of Network databases:
* The network model is conceptually simple and easy to design.
* The network model can represent redundancy in data more effectively than in the hierarchical model.
* The network model can handle the one to many and many to many relationships which is real help in modelling the real-life situations.
* The data access is easier and flexible than the hierarchical model.
* The network model is better than the hierarchical model in isolating the programs from the complex physical storage details.

Disadvantages of Network databases:
* All the records are maintained using pointers and hence the whole database structure becomes very complex.
* The insertion, deletion and updating operations of any record require the large number of pointers adjustments.
* The structural changes to the database is very difficult.

## 3. Relational databases.
_{Relational database model organises data in rows and column structure i.e., two-dimensional tables and the relationship is maintained by storing a common field. It consists of three major components; relations, attributes, and domains.}_
_{The various software systems used to maintain relational databases are known as a relational database management system (RDBMS).Common RDBMS include Oracle, MySQL, Microsoft SQL Server, PostgreSQL, DB2.}_
_{Relational Database as a developers tool is most suitable under certain conditions, these conditions include}_
- When growing fixed format data
- When developers wish to track historical changes,i.e when data changes.
- When the data is so large than can fit into memory e.g a 100GB relational table is more accessible than a 100GB flat file.
- In the case of app development, whin workloads need to be processed fast, as RDBMS is faster at data processing than other systems
- RDBMS products offer various encryption, auditing and alerting features which makes it suitable for sensitive Data
- RDBMS adds complexity, hence is not suitable for a project in exploratory phase.

Advantages of Relational databases:
* Relational model is one of the most popular used database model.
* In relational model, changes in the database structure do not affect the data access.
* The revision of any information as tables consisting of rows and columns is much easier to understand.
* The relational database supports both data independence and structure independence concept which makes the database design, maintenance, administration and usage much easier than the other models.
* In this we can write complex query to accesses or modify the data from database.
* It is easier to maintain security as compare to other models.

Disadvantages of Relational databases:
* Mapping of objects in relational database is very difficult.
* Object oriented paradigm is missing in relation model.
* Data Integrity is difficult to ensure with Relational database.
* Relational Model is not suitable for huge database but suitable for small database.
* Hardware overheads are incurred which make it costly.
* Ease of design can lead to bad design.
* Relational database system hides the implementation complexities and the physical data storage details from the users.

## 4. Object-oriented databases.
_{Object database management systems (ODBMSs) are based on objects in object-oriented programing (OOP). In OOP, an entity is represented as an object and objects are stored in memory.}_
_{Object databases are commonly used in applications that require high performance, calculations, and faster results. Some of the common applications that use object databases are real-time systems, architectural & engineering for 3D modeling, telecommunications, and scientific products, molecular science, and astronomy.}_

Advantages of Object-Oriented databases.
* Persistent storage to objects.
* Easy to save and retrieve data quickly.
* Seamless integration with object-oriented programming languages.
* Easier to model the adanced real world problems.

Disadvantages of Object-Oriented databases.
* Object databases are not as popular as RDBMS. Hence, there is scarcity of manpower.
* Not many programming language support object databases. 
* RDBMS have SQL as a standard query language. Object databases do not have a standard. 
* Object databases are difficult to learn for non-programmers.