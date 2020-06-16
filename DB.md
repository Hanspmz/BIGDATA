**Team:** Saulo Acevedo, Hans Pech, Ulises Mis.
--------------------------
# Types of Databases.

## 1. Document.
The Document model database works in a non-relational way, it is created to store information and perform queries in JSON-type documents or even other formats. They structure higher developing for productivity. 

For developers Document Data Bases are flexible and natural to work since it is esier to hand better them when executing queries making way to adapt for other applications. 

The document model is used when information needs to store more in a catalogue way and even like user profiles working also with content releated to management systems where each document can be displayed and uniquely evolves over time.

The intuitive data model of document database type allows to work more naturally because the objects can be mapped on the code. The schema of a document type-model is dinamically adapeted to change so it is not necessary to predefine it in the database. JSON documents are universal readable and can structure the data as the necessity demands. The richness of indexing and expresivity of the query language is very comprehensive.


## 2. Key-value.
**What are NoSQL Key Value Databases?** 

Every one of those databases which are demonstrated in implies other than the plain relations utilized in relational databases are known as NO SQL databases. The data structure in key-value database varies from the RDBMS, and in this manner a few tasks are quicker in NoSQL and some in RDBMS. Key Value Store databases are named as Key-Value Store eventually-consistent and Key Value Store ordered databases. 
NoSQL key-value databases are the least complicated sorts of NoSQL databases. They store the data as a key or attribute name with its value. Every data item has a pointer and a unique key. The key-value sets are in form of rows of associative arrays. Key-value databases utilize arbitrary strings to represent the key and the value could be a doc file or a picture. In contrast to, customary relational databases, key-value stores don't have a particular pattern.

Some key-value databases allow users to store persistent copies of data in flash drives, hard drives and other storage devices that can store data permanently. Other key-value databases only store data in memory and are usually known as key-value cache databases. NoSQL key-value cache databases allow users to retrieved data quicker than databases that store data in disks. The cache allows users to quickly access data by reading and storing data in memory to facilitate easy retrieval when needed.
NoSQL database can be classified as Key Value Cache, Key Value Store, Key Value Store Eventually Consistent, Key Value Store Ordered, Data Structures server, Tuple Store, Object Database, Document Store, and Wide Columnar Store.

**The main features of key value DB are:**
  
  -Data Storage and Retrieval: The ability to store data is one of the primary functions of all databases. Key-value databases allow users to apply a key to each data item (value) and facilitate storage for immediate or future use.
Caching: NoSQL key-value cache databases include integrated caching capabilities so they can keep frequently-used data in memory. This feature allows database users to quickly access data. In addition to caching objects, this feature allows application nodes to share frequently-used data.
 
 -A Simple Data Structure: All key-value databases use a simple data structure and this is important because sometimes those extra features are not necessary. Database users can simply add new features when the need arises. The database’s simple associated arrays optimize its performance allowing users to quickly perform data-intensive operations.
Scalability: NoSQL key-value databases are easy to scale without disrupting operations. Users can add and remove servers depending on their needs without causing undesirable disruptions.

**Some of the benefits include:**

  -Rapid storage of data and information due to the simple data structure.

  -High performance because the integrated caching feature allows users to store and retrieve data in the shortest time possible.
    
  -Database users can make changes to the system in order to accommodate the changing needs of their organization with minimal disruptions to operations.


## 3. Ledger.
A ledger database is log-centric, in comparison to non-ledger databases which are table-centric. 

“Log” is a storage abstraction, used to refer to an append-only, totally ordered sequence of records, ordered by time. 

Currently, the only commercial ledger database available is the Amazon Web Service Quantum Ledger Database (QLDB for short).

The main concept behind Ledger databases is that they “remember the past”: when working with a non-ledger DB, if you want to update a record, the new record will overwrite the previous one, and the old data will be lost. On ledger DB, each update is stored as its own record, therefore giving this type of DB the ability to “explore the past”.

There are 3 key characteristics of ledger DBs:
  1.	Immutable. Writes cannot be changed once stored.
  2.	Transparent. Past or overwritten data can be accessed.
  3.	Verifiable. History of changes can be accessed, and it is possible to verify its authenticity.
  
--------------------------
# Types of Database Matrix

|Type of Database     |Features    |Best use   |Usage example   |Service example   |
|:-----|:----|:---|:---|:---|
|Key value |**Data Storage and Retrieval:**  Key-value databases allow users to apply a key to each data item (value) and facilitate storage for immediate or future use. **Caching:** This feature allows database users to quickly access data. **A Simple Data Structure:** The database’s simple associated arrays optimize its performance allowing users to quickly perform data-intensive operations. **Scalability:** Users can add and remove servers depending on their needs without causing undesirable disruptions.|   Applications requiring fast access to a large number of objects, such as caches or queues. Applications that require fast-changing data environments like mobile, gaming, online ads.|   Shopping cart during the holiday shopping season, an e-commerce website can receive billions of orders in seconds. Key-value databases can handle the scaling of large amounts of data and extremely high volumes of state change, while serving millions of users simultaneously through distributed storage and processing. Key-value databases also have built-in redundancy, which can handle loss of storage nodes.|  Amazon DynamoDB, Oracle NoSQL Database, InfinityDB, Redis, Aerospike, Oracle Berkeley DB, Riak KV, Voldemort| 
|Document |    The intuitive data model of document database type allows to work more naturally because the objects can be mapped on the code. The schema of a document type-model is dinamically adapeted to change so it is not necessary to predefine it in the database. JSON documents are universal readable and can structure the data as the necessity demands. The richness of indexing and expresivity of the query language is very comprehensive.|   The best use drivers depend whether you need a document database or some other type of database for managing the information. Document databases are useful for workloads that require a flexible schema for fast, iterative development.|   A document database can be used to store the results of clicks on the web. For each log file that is parsed a simple XML construct with the Page_Name, Position_Coordinates, Clicks, Keywords, Incoming and Outgoing sites, and Date_Time will create a simple model to query the number of clicks, keywords, date, and links. This processing power cannot be found in an RDBMS. If you want to expand and capture the URL data, the next version can add the field.|   Allegro graph, ArangoDB, BaseX, Caché, Cloudant, Clusterpoint Database, Couchbase server, Couch DB, CratelO, Cosmos DB, DocumentDB, Elaaticsearch, eXist, Informix.|  
|Ledger |**Log-centric:** logs allow the user to review the history of changes and access previous versions of the same record. **Immutable:** once the data is written, it cannot be modified. **Transparent:** all the data recorded will always be accessible, no matter if it is overwritten. **Verifiable:** history of changes can be accessed by user, and the authenticity of said history can be checked. |Companies or applications that work with sensitive data and their databases can be accessed by many people. Banking, government, or social network applications for example. | Nowadays, many laws aimed to protect user’s data are being approved. Companies are only allowed to have the data necessary to deliver a product or service. If a person fills a lawsuit claiming that a company did not delete unnecessary data, a ledger database is a perfect solution as it can be legally verified. | Amazon Web Service Quantum Ledger Database.|  
