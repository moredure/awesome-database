<div align="center">
	<!--<div>
		<a href="https://github.com/agarcialeon/awesome-database/">
			<img width="500" src="awesome-unity.png" alt="Awesome Database">
		</a>
	</div>-->
  <br>
	<div>
		<h1>Awesome Database</h1>		
		<a href="https://github.com/sindresorhus/awesome"> 
			<img src="https://awesome.re/badge-flat.svg" alt="Awesome">
		</a>					
		<p>
			A categorized community-driven collection of amazingly awesome database resources.
			<br><br>
			Free assets and resources are prioritized over paid when possible.
			<br><br>
			Suggestions and contributions are always welcome!
			<br>			
			Make sure to read the <a href="https://github.com/agarcialeon/awesome-database/blob/master/CONTRIBUTING.md"> contribution guidelines </a> for more information before submitting a pull request.

<!--[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)-->
<!--[![forthebadge](https://forthebadge.com/images/badges/made-with-c-sharp.svg)](https://forthebadge.com) -->
[![forthebadge](https://forthebadge.com/images/badges/cc-0.svg)](https://forthebadge.com)
		</p>
	</div>
</div>

# :bookmark_tabs: Contents

- [Motivation](#motivation)
- [Considerations](#considerations)
- [Legend](#legend)
	- [Icons](#icons)
	- [Tags](#tags)
- [Categories](#categories)
	- [Databases](#databases)
	- [Scripting](#scripting)
		- [SQL Languages](#sql-languages)
		- [Algorithms](#algorithms)
		- [Patterns](#patterns)
		- [Libraries](#libraries)
		- [Utilities](#utilities)
		- [Tools](#tools)
		- [Plugins](#plugins) 
		- [Snippets & Gists](#snippets-&-gists)
		- [Dynamic SQL](#dynamic-sql)
	- [Integrated Development Environment (IDE)](#ide)
  - [VCS (Version Control Systems)](#vcs)
  - [Continuous Integration (CI)](#continuous-integration)
  - [Testing](#testing)
  - [Documentation](#documentation)
  - [Database Development](#db-development)
  - [Benchmarks](#benchmarks)
  - [Customization](#customization)
  - [Extensibility](#extensibility)
  - [Miscellaneuous](#miscellaneous)  
- [Learning Resources](#learning-resources)
  - [Tips and Tricks](#tips-tricks)
  - [Books](#books)
  - [Research Papers](#research-papers)
  - [Blogs](#blogs)
  - [Videos](#videos)
  	- [Youtube Channels](#youtube-channels)
  - [Tutorials](#tutorials)
  - [Best Practices](#best-practices)
  - [Shortcuts](#shortcuts)  
  - [Other References](#other-references)
- [Recommended](#recommended) 
- [Projects](#projects)
- [Communities](#communities)
  - [Chat Servers](#chat-servers)
  - [Forums](#forums)
  - [Groups](#groups)
  - [People to Follow](#people-to-follow)
- [Frequently Asked Questions (FAQ)](#faq)
- [Contributors to this repository](#contributors)
- [Contributing](#contributing)
- [Code of Conduct](#code-of-conduct)
- [To be done](#to-do)

# Motivation <a name="motivation"></a>

:construction:

# Considerations <a name="considerations"></a>

<!-- There is always a posibility that this repository becomes outdated, mostly because new packages from the asset store and repositories appear in the future. This is because of the nature of technlogy and this can be avoided, so in order to keep this project as updated as possible with what other users know, please create a new issue to include or remove what you think is necessary.

Another point is the categorization of the resources provided here. Since some of them can be included in different categories at the same time a cross reference will be created in the form of a hastag to notify you (the visitor) that maybe you need to look in a different place of this repository or in other external site to find more info.

Finally, you need to know that this is not the only repository on Github that gathers Unity related repositories. This is just another try to get the best of all the existing content out there for Unity developers. So please, be grateful with all the other developers that put effort collection their respective lists of resources by visiting their repositories (they will be listed below).

I hope all of you find this helpful. Let's go with the contents. -->

# Legend <a name="legend"></a>

## Icons <a name="icons"></a>

Free resource: :free:

Paid resource: :moneybag:

Interesting resource: :cool: 

<!-- 
:new:
-->

## Tags <a name="tags"></a>

(UNMAINTAINED) - The repository hasn't been updated for a long time.

(DEPRECATED) - Another solution or package has been released that does the same and it's more recent.

(ARCHIVED) - The repository is read only for learning purposes.

#[CATEGORY] - Where [CATEGORY] represents a category of the document. Means that the resource is related with another category too.

# :bookmark: Categories <a name="categories"></a>

## Databases <a name="databases"></a>

### Relational Databases

#### Oracle

* [SQL Developer](http://www.oracle.com/technetwork/developer-tools/sql-developer/overview/index.html) - Oracle's Free IDE for PL/SQL development and administration of Oracle databases.
* [SQL Tools for Oracle](http://sourceforge.net/projects/sqlt/) - Lightweight frontend for Oracle DB development.
* [Oracle Database 11g Express Edition](http://www.oracle.com/technetwork/database/database-technologies/express-edition/overview/index.html) - Free entry level database to develop and deploy applications.
* [Alexandria PL/SQL Utility Library](https://github.com/mortenbra/alexandria-plsql-utils) - Collection of utility packages for PL/SQL
* [PLSQL-JSON](https://github.com/doberkofler/PLSQL-JSON) - PL/SQL library to encode/decode JSON
* [utPLSQL](https://utplsql.github.io/) - Unit testing framework for PL/SQL.

#### SQL Server

* [SQL Server Express Edition](http://www.microsoft.com/en-us/server-cloud/products/sql-server-editions/sql-server-express.aspx) - Free SQL Server Database to develop and deploy applications.
* [SQL Server Data Tools](http://msdn.microsoft.com/en-us/data/tools.aspx) - Integrated environment for developers to design and build database and other business intelligence solutions for MS SQL Server stack.
* [tSQLt](http://tsqlt.org/) - Unit testing framework for SQL Server.

##### Monitoring

* [Monitor CPU Usage](https://github.com/SqlAdmin/AwesomeSQLServer/blob/master/T-SQL%20Scripts/CPU%20Monitoring.sql)
* [Monitor Memory Usage](https://github.com/SqlAdmin/AwesomeSQLServer/blob/master/T-SQL%20Scripts/Memory%20Monitoring.sql)
* [Monitor Disk Usgae](https://github.com/SqlAdmin/AwesomeSQLServer/blob/master/T-SQL%20Scripts/Disk%20Space%20Monitoring.sql)
* [Session Monitoring](https://github.com/SqlAdmin/AwesomeSQLServer/blob/master/T-SQL%20Scripts/Session%20Monitoring.sql)
* [Blocking, Deadlock Monitoring](https://github.com/SqlAdmin/AwesomeSQLServer/blob/master/T-SQL%20Scripts/Blocking%20Monitoring.sql)
* [IO Monitoring](https://github.com/SqlAdmin/AwesomeSQLServer/blob/master/T-SQL%20Scripts/IO%20Monitoring.sql)
* [Wait stat Monitoring](https://github.com/SqlAdmin/AwesomeSQLServer/blob/master/T-SQL%20Scripts/Wait%20stat%20Monitoring.sql)

#### [MariaDB](https://mariadb.org/)

_An enhanced, drop-in replacement for MySQL._

#### [MySQL](http://mysql.com)

_MySQL is the world's most popular open source database._

* [TokuDB Engine](https://github.com/Tokutek/tokudb-engine) - TokuDB is a high-performance, write optimized, compressing, transactional storage engine for MySQL and MariaDB. (#C/C++)

#### [PostgreSQL](http://www.postgresql.org/)

_A powerful, open source object-relational database system._

* [PostgreSQL](https://github.com/postgres/postgres) - Mirror of the official PostgreSQL Git repository. (#C/C++)
* [Cstore FDW](https://github.com/citusdata/cstore_fdw) - Fast columnar store for analytics with PostgreSQL. [Website](http://citusdata.github.io/cstore_fdw/). (#C/C++)

#### [SQLite](http://www.sqlite.org/)

_A completely embedded, full-featured relational database in a few 100k that you can include right into your project._

* [Awesome SQLite](https://github.com/mindreframer/awesome-sqlite) - All things around SQLite.


#### [DB2](https://www.ibm.com/es-es/analytics/db2/tools)

_Database management products developed by IBM_

* [Awesome DB2](https://github.com/angoca/awesome-db2) - A curated list of awesome Db2 resources, tools and documentation to develop in that database.

#### Other Databases

* [VoltDB](https://github.com/VoltDB/voltdb/) - VoltDB is a horizontally-scalable, in-memory SQL RDBMS designed for applications that have extremely high read and write throughput requirements.

### NoSQL Databases

* [Redis](https://github.com/antirez/redis) - Redis is an in-memory database that persists on disk. The data model is key-value, but many different kind of values are supported: Strings, Lists, Sets, Sorted Sets, Hashes.[Website](http://redis.io). (#C/C++)
* [Redis NDS](https://github.com/mpalmer/redis/tree/nds-2.6) - This is a version of Redis patched to implement NDS (the Naive Disk Store). (#C/C++)
* [SSDB](https://github.com/ideawu/ssdb) - A fast NoSQL database, an alternative to Redis. [Website](http://ssdb.io). (#C/C++)
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) - An open-source distributed JSON document database with a pleasant and powerful query language. [Website](http://www.rethinkdb.com). (#C/C++)
* [CouchDB](https://github.com/apache/couchdb) - Apache CouchDB™ is a database that uses JSON for documents,JavaScript for MapReduce indexes, and regular HTTP for its API [Website] (http://couchdb.apache.org/). (#JAVASCRIPT)
* [MongoDB](https://github.com/mongodb/mongo) - MongoDB is a document database that provides high performance, high availability, and easy scalability. Documents (objects) map nicely to programming language data types. Embedded documents and arrays reduce need for joins. Dynamic schema makes polymorphism easier. [Website] (https://www.mongodb.org/). (#JAVASCRIPT)
* [TokuMX](https://github.com/Tokutek/mongo) - TokuMX is a high-performance, concurrent, compressing, drop-in replacement engine for MongoDB. (#C/C++)
* [PouchDB](https://github.com/pouchdb/pouchdb) - PouchDB is a pocket-sized database.
* [Aerospike Database Server](https://github.com/aerospike/aerospike-server) - Flash-optimized, in-memory, noSQL database. Previously [AlchemyDB](https://github.com/JakSprats/Alchemy-Database). See [more](http://www.aerospike.com).

#### Key-Value Cache 

* Coherence  
* eXtreme Scale  
* GigaSpaces  
* GemFire  
* Hazelcast  
* Infinispan  
* JBoss Cache  
* **Memcached**  
* Repcached  
* Terracotta  
* Velocity  
  
#### Key-Value Store

* Flare  
* Keyspace  
* RAMCloud  
* SchemaFree  
* Hyperdex  
* Aerospike  
 
#### Key-Value Store (Eventually-Consistent)

* DovetailDB  
* **Oracle NoSQL Database**  
* Dynamo  
* Riak  
* Dynomite  
* MotionDb  
* Voldemort  
* SubRecord  
  
#### Key-Value Store (Ordered)

* Actord  
* FoundationDB  
* Lightcloud  
* LMDB  
* Luxio  
* **MemcacheDB**  
* NMDB  
* Scalaris  
* TokyoTyrant  
  
#### Data-Structures server

* **Redis**  
 
#### Tuple Store

* Apache River  
* Coord  
* GigaSpaces  
 
#### Object Database

* DB4O  
* Objectivity/DB  
* Perst  
* Shoal  
* ZopeDB  
 
#### Document Store

* Clusterpoint  
* Couchbase  
* CouchDB  
* DocumentDB  
* Lotus Notes  
* MarkLogic  
* **MongoDB**  
* Qizx  
* XML-databases  
 
### Wide Columnar Store

* **BigTable**  
* **Cassandra**  
* Druid  
* **HBase**  
* Hypertable  
* KAI  
* KDI  
* OpenNeptune  
* Qbase  

### Graph Databases

* [Neo4j](https://github.com/neo4j/neo4j) - The world’s leading Graph Database. [Website](http://neo4j.org). (#JAVA)
* [FlockDB](https://github.com/twitter/flockdb) - A distributed, fault-tolerant graph database
- [Titan](https://github.com/thinkaurelius/titan) - Distributed Graph Database [Website](http://titandb.io). (#JAVA)
* [OrientDB](https://github.com/orientechnologies/orientdb) - OrientDB document graph NoSQL dbms (database)
* [ArangoDB](https://github.com/triAGENS/ArangoDB) - ArangoDB is a multi-purpose, open-source database with flexible data models for documents, graphs, and key-values. Build high performance applications using a convenient SQL-like query language or JavaScript/Ruby extensions. Use ACID transaction if you require them. Scale horizontally and vertically with a few mouse clicks.

### Embedable engines

* [Derby](https://db.apache.org/derby/) - Open source relational database implemented entirely in Java.
* [H2](https://github.com/h2database/h2database) - An embeddable RDBMS written in Java.
* [LevelDB](https://github.com/google/leveldb) - LevelDB is a fast key-value storage library written at Google. See [more](https://code.google.com/p/leveldb/).
* [PalDB](https://github.com/linkedin/PalDB) - Embeddable write-once key-value store written in Java.
* [RocksDB](https://github.com/facebook/rocksdb) - Embedded key-value store for fast storage. [Website](http://rocksdb.org). (#C/C++)
* [MapDB](https://github.com/jankotek/mapdb/) - Fast and easy to use embedded Java database engine.
* [Xodus](https://github.com/JetBrains/xodus/) - JetBrains Xodus is a Java transactional schema-less embedded database.




## Clojure

 * [Datomic](http://www.datomic.com/)
 * [Clojure.jdbc](https://github.com/niwibe/clojure.jdbc)
 * [CravenDB](https://github.com/robashton/cravendb)

## C / C++

* [LMDB](http://symas.com/mdb/) - Very fast embedded key/value store with full ACID semantics.
* [memcache](https://github.com/memcached/memcached) - Free & open source, high-performance, distributed memory object caching system.
* [MonetDB](https://github.com/snaga/monetdb) - [Website](https://www.monetdb.org/).
* [Facebook/MySQL-5.6](https://github.com/facebook/mysql-5.6) - Facebook's branch of the Oracle MySQL v5.6 database.
* [Twitter/MySQL](https://github.com/twitter/mysql) - MySQL fork maintained and used at Twitter. See its [wiki](https://github.com/twitter/mysql/wiki).

## .NET

* [RavenDB](https://github.com/ravendb/ravendb) - A linq enabled document database for .NET http://ayende.com/Blog/.
* [OrigoDB](http://dev.origodb.com) - An in-memory embedded database engine for NET/Mono.

## Erlang

* [Riak](https://github.com/basho/riak) - Riak is a decentralized datastore from Basho Technologies.
* [PulseDB](http://pulsedb.io) - PulseDB is a time series database server and library.

## Go

* [Bolt](https://github.com/boltdb/bolt) - A low-level key/value database for Go.
* [Diskv](https://github.com/peterbourgon/diskv) - A home-grown disk-backed key-value store.
* [Go Cache](https://github.com/pmylund/go-cache) - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [Go LevelDB](https://github.com/syndtr/goleveldb) - An implementation of the [LevelDB](https://code.google.com/p/leveldb/) key/value database in the Go.
* [Groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [InfluxDB](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [LedisDB](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [Roshi](https://github.com/soundcloud/roshi/) - Roshi is a large-scale CRDT set implementation for timestamped events.
* [SkyDB.io](https://github.com/skydb/sky) - Sky is an open source database used for flexible, high performance analysis of behavioral data.
* [Tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.

## Java

* [Cassandra](https://github.com/apache/cassandra) - Cassandra is a partitioned row store. Rows are organized into tables with a required primary key.
* [Elasticsearch](https://github.com/elasticsearch/elasticsearch) - Open Source, Distributed, RESTful Search Engine [Website](http://elasticsearch.org).
* [Lmdbjni](https://github.com/deephacks/lmdbjni) - LMDB for Java, which is a very fast embedded key/value store with full ACID semantics.
* [MapDB](https://github.com/jankotek/MapDB) - MapDB provides concurrent Maps, Sets and Queues backed by disk storage or off-heap-memory. It is a fast and easy to use embedded Java database engine. [Website](http://www.mapdb.org).
* [OrientDB](https://github.com/orientechnologies/orientdb) - OrientDB is an Open Source NoSQL DBMS with the features of both Document and Graph DBMSs.
* [Voldemort](https://github.com/voldemort/voldemort) - An open source clone of Amazon's Dynamo. [Website](http://project-voldemort.com)

## Scala

* [BlinkDB](https://github.com/sameeragarwal/blinkdb) - BlinkDB: Sub-Second Approximate Queries on Very Large Data [Website]	(http://blinkdb.cs.berkeley.edu/).

## Frameworks <a name="frameworks"></a>

:construction:

## Services <a name="services"></a>

:construction:

## :pencil2: Scripting <a name="scripting"></a>

### SQL Languages <a name="sql-languages"></a>

:construction:

### :chart_with_upwards_trend: Algorithms <a name="algorithms"></a>

:construction:

### :straight_ruler: Patterns <a name="patterns"></a>

:construction:

### :orange_book: Libraries <a name="libraries"></a>

:construction:

### :nut_and_bolt: Utilities <a name="utilities"></a>

:construction:

### :wrench: Tools <a name="tools"></a>

* [PixQL](https://github.com/Phildo/pixQL) - Command-line image processing tool in SQL.
* [SQL Fiddle](http://sqlfiddle.com/) - Easly test and share database problems and their solutions. Can use different backend DBMS's (MySQL, PostgreSQL, MS SQL Server, Oracle, and SQLite).
* [SqlPad](http://rickbergfalk.github.io/sqlpad/) - A web app for running SQL queries and visualizing the results.
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - ERAlchemy generates Entity Relation (ER) diagram from databases.
* [BigBash](https://github.com/zalando/bigbash) - Open-source converter that generates a bash one-liner from an SQL Select query, no database necessary.
* [Flyway](https://flywaydb.org/) - Database migration tool.
* [Liquibase](http://www.liquibase.org/) - Source Control for your database.
* [Liquibase](http://www.liquibase.org/) - Source Control for your database.

* [Awesome DB Tools](https://github.com/mgramin/awesome-db-tools) - a community driven list of database tools (ide, cli, managing, monitoring, migrations, modelers, visualization etc)

## Formatters <a name="formatters"></a>

- [SQL Format](http://www.dpriver.com/pp/sqlformat.htm) - Instant SQL Formatter.
- [Poor SQL](http://poorsql.com/) - A small free .Net and JS library (with demo UI, command-line bulk formatter, SSMS/VS add-in, notepad++ plugin, winmerge plugin, and demo webpage) for reformatting and coloring T-SQL code to the user's preferences.
See more on [Github](https://github.com/TaoK/PoorMansTSqlFormatter).
- [T-SQL Tidy](http://www.tsqltidy.com/Default.aspx) - Online T-SQL formatting with Webservice and Plugins for SSMS.

## :electric_plug: Plugins <a name="plugins"></a>

:construction:

### Snippets & Gists <a name="snippets-&-gists"></a>

:construction:

### Dynamic SQL <a name="dynamic-sql"></a>

:construction:

### Integrated Development Environment (IDE) <a name="ide"></a>

:construction:

## VCS (Version Control Systems) <a name="vcs"></a>

:construction:

## Continuous Integration <a name="continuous-integration"></a>

:construction:

## Testing <a name="testing"></a>

:construction:

## Documentation <a name="documentation"></a>

:construction:

## Database Development <a name="db-development"></a>

* [Awesome DB Dev](https://github.com/huachaohuang/awesome-dbdev) - Awesome materials about database development.

## Benchmarks <a name="benchmarks"></a>

* [Awesome DB Benchmarks](https://github.com/benstopford/awesome-db-benchmarks) - Community driven list of database benchmarks.

## :sunglasses: Customization <a name="customization"></a>

:construction:

## Extensibility <a name="extensibility"></a>

:construction:

## Misc. <a name="miscellaneous"></a>

:construction:

# :mortar_board: Learning Resources <a name="learning-resources"></a>

## :rocket: Tips and Tricks <a name="tips-tricks"></a>

:construction:

## :books: Books <a name="books"></a>

:construction:

## Research Papers

* [db-readings](https://github.com/rxin/db-readings) - A list of papers essential to understanding databases and building new data systems.

## :newspaper: Blogs <a name="blogs"></a>

:construction:

## :tv:  Videos <a name="videos"></a>

### :vhs: Youtube Channels <a name="youtube-channels"></a>

:construction:

## :beginner: Tutorials <a name="tutorials"></a>

- [Curated SQL Learning Resources on Hackr.io](https://hackr.io/tutorials/learn-sql) - Programming Community Curated Resources for learning SQL.

## :star: Best Practices <a name="best-practices"></a>

### :abcd: Coding Practices <a name="coding-practices"></a>

:construction:

### :capital_abcd: Organizational Practices <a name="organizational-practices"></a>

:construction:

## :triangular_ruler: Style Guide <a name="style-guide"></a>

:construction:

## :key: Shortcuts <a name="shortcuts"></a>

:construction:

## :paperclip: Other references <a name="other-references"></a>

* [Awesome DB Tools](https://github.com/mgramin/awesome-db-tools) - A community driven list of database tools (ide, cli, managing, monitoring, migrations, modelers, visualization, etc...).
* [Awesome SQL](https://github.com/danhuss/awesome-sql) - List of tools and techniques for working with relational databases.
* [Awesome Databases](https://github.com/dhamaniasad/awesome-databases) - A curated list of awesome databases.
* [Awesome DB](https://github.com/pditommaso/awesome-db) - A curated list of awesome DBs.
* [Awesome SQL Server](https://github.com/SqlAdmin/AwesomeSQLServer) - A big collection of SQL Server Queries and documeantations to fix your SQL Server's bottle neck.
* [Awesome SQLite](https://github.com/planetopendata/awesome-sqlite) - A collection of awesome sqlite tools, scripts, books, etc.
* [Awesome PostgresSQL](https://github.com/dhamaniasad/awesome-postgres) - A curated list of awesome PostgreSQL software, libraries, tools and resources, inspired by awesome-mysql.
* [Awesome DB2](https://github.com/angoca/awesome-db2) - A curated list of awesome Db2 resources, libraries, tools and applications.

# :trophy: Recommended <a name="recommended"></a>

:construction:

# Projects <a name="projects"></a>

:construction:

# :busts_in_silhouette: Communities <a name="communities"></a>

## :speech_balloon: Chat Servers <a name="chat-servers"></a>

:construction:

## Forums <a name="forums"></a>

:construction:

## Groups <a name="groups"></a>

:construction:

## :name_badge: People to follow <a name="people-to-follow"></a>

:construction:

# :question: Frequently Asked Questions (FAQ) <a name="faq"></a>

:construction:

# :clap: :tada: Contributors to this repository <a name="contributors"></a>

:guardsman: [@agarcialeon](https://github.com/agarcialeon) -  Owner of the repository

# Contributing <a name="contributing"></a>

Please see [CONTRIBUTING](https://github.com/agarcialeon/awesome-unity/blob/master/CONTRIBUTING.md) for details.

Thanks to all the [contributors](https://github.com/agarcialeon/awesome-unity/graphs/contributors), this wouldn't be possible without you! 

<!--<a href="https://github.com/agarcialeon/awesome-unity/graphs/contributors">
	 <img src="https://opencollective.com/vuejs/contributors.svg?width=890" /> 
</a>-->

# Code of Conduct <a name="code-of-conduct"></a>

See [Code of Conduct](https://github.com/agarcialeon/awesome-unity/blob/master/CODE-OF-CONDUCT.md).

# :memo: To be done <a name="to-do"></a>

:warning: NOTE: Following list of tasks is written without any order of preference.

* Fill Open Issue template file to help providing new resources.
* Add license file.
* Add awesome sqlite repository resources. (not commercial ones)
* Add awesome postgres repository resources.
* Add repository logo.
* Add contributing file.
* Move language-related resources to its category and add language tags to filter them.
* The logo image should be high-DPI. Set it to maximum half the width of the original image.
* Wait 30 days from first commit to make the pull request to awesome lists topic.
* Add tags for free and paid resources.
* Add better icons for sections.
* Use tags to classify a resource instead of using a category.
* Reorder category resources by most well known resources if possible.
* Starter kit section with all the things needed or recommended for beginners.
* Include resources for recommended packages section (well tested, most voted and so on).
* Fill up continuous integration section.
* Fill up people to follow.
* Fill up communities section.
* Fill snippets and gists under scripting section.
* Create more categories for specific resources that don't combine well.
* Add category for error reporting, logging and debugging.
* Mark deprecated packages (:x:).
* Change introduction at the beginning ot the readme file to indicate better the visitors how its organized.
* Do shortcut png image with IDE shortcuts.
* Create open collective to show the image with the contributors if necessary.
* Review items by category to select one between similar ones in order to select the most complete. Reference the others in another section or repository.

And many more...

[:top: Back to Top](#awesome-database)
