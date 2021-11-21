1. Getting Started with Neo4j

            Graphs and their utilities
            Introducing NoSQL databases
            Dynamic schemas
            Automatic sharding
            Built-in caching
            Replication
            Types of NoSQL databases
            Key-value stores
            Column family stores
            Document databases
            Graph databases
            Graph compute engines
            The Neo4j graph database
            ACID compliance
            Characteristics of Neo4j
            The basic CRUD operations
            The Neo4j setup and configurations
            Modes of setup – the embedded mode
            Modes of setup – the server mode
            Neo4j high availability
            Machine #1 – neo4j-01.local
            Machine #2 – neo4j-02.local
            Machine #3 – neo4j-03.local
            Configure Neo4j for Amazon clusters
            Cloud deployment with Azure
     
2. Querying and Indexing in Neo4j

            The Neo4j interface
            Running Cypher queries
            Visualization of results
            Introduction to Cypher
            Cypher graph operations
            Cypher clauses
            More useful clauses
            Advanced Cypher tricks
            Query optimizations
            Graph model optimizations
            Gremlin – an overview
            Indexing in Neo4j
            Manual and automatic indexing
            Schema-based indexing
            Indexing benefits and trade-offs
            Migration techniques for SQL users
            Handling dual data stores
            Analyzing the model
            Initial import
            Keeping data in sync
            The result
            Useful code snippets
            Importing data to Neo4j
            Exporting data from Neo4j
     
3. Efficient Data Modeling with Graphs

            Data models
            The aggregated data model
            Connected data models
            Property graphs
            Design constraints in Neo4j
            Graph modeling techniques
            Aggregation in graphs
            Graphs for adjacency lists
            Materialized paths
            Modeling with nested sets
            Flattening with ordered field names
            Schema design patterns
            Hyper edges
            Implementing linked lists
            Complex similarity computations
            Route generation algorithms
            Modeling across multiple domains
     
4. Neo4j for High-volume Applications

            Graph processing
            Big data and graphs
            Processing with Hadoop or Neo4j
            Managing transactions
            Deadlock handling
            Uniqueness of entities
            Events for transactions
            The graphalgo package
            Introduction to Spring Data Neo4j
     
5. Testing and Scaling Neo4j Applications

            Testing Neo4j applications
            Unit testing
            Using the Java API
            GraphUnit-based unit testing
            Unit testing an embedded database
            Unit testing a Neo4J server
            Performance testing
            Benchmarking performance with Gatling
            Scaling Neo4j applications
     
6. Neo4j Internals

            Introduction to Neo4j internals
            Working of your code
            Node and relationship management
            Implementation specifics
            Storage for properties
            The storage structure
            Migrating to the new storage
            Caching internals
            Cache types
            AdaptiveCacheManager
            Transactions
            The Write Ahead log
            Detecting deadlocks
            RWLock
            RAGManager
            LockManager
            Commands
            High availability
            HA and the need for a master
            The master election
     
7. Administering Neo4j

            Interfacing with the tools and frameworks
            Using Neo4j for PHP developers
            The JavaScript Neo4j adapter
            Neo4j with Python
            Admin tricks
            Server configuration
            JVM configurations
            Caches
            Memory mapped I/O configuration
            Traversal speed optimization example
            Batch insert example
            Neo4j server logging
            Server logging configurations
            HTTP logging configurations
            Garbage collection logging
            Logical logs
            Open file size limit on Linux
            Neo4j server security
            Port and remote connection security
            Support for HTTPS
            Server authorization rules
            Setup server authorization rules enforcement
            Security rules targeting with wildcards
            Other security options
     
8. Use Case – Similarity-based Recommendation System

            The why and how of recommendations
            Collaborative filtering
            Content-based filtering
            The hybrid approach
            Building a recommendation system
            Recommendations on map data
            Visualization of graphs