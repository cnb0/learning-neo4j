1. Your First Query with Neo4j

            Thinking in graphs for SQL developers
            Comparing SQL and Cypher
            Evolving graph structures from SQL models
            Licensing and configuring – Neo4j
            Licensing – Community Edition
            Licensing – Enterprise Edition
            Installing Neo4J Community Edition on Linux/Unix
            Installing as a Linux tar / standalone application
            Installing as a Linux service
            Installing Neo4j Enterprise Edition on Unix/Linux
            Using the Neo4j shell
            Introducing the Neo4j REST interface
            Authorization and authentication
            CRUD operations
            Running queries from the Neo4j browser
     
2. Querying the Graph with Cypher

            Basic anatomy of a Cypher query
            Brief details of Cypher
            Cypher execution phases
            Parsing, validating, and generating the execution plan
            Locating the initial node(s)
            Selecting and traversing the relationships
            Changing and/or returning the values
            The structure of Cypher
            The read operations
            MATCH
            OPTIONAL MATCH
            START
            AGGREGATION
            The create or update operations
            Create
            SET
            MERGE
            The delete operation
            Pattern and pattern matching
            Sample dataset
            Pattern for nodes
            Pattern for labels
            Pattern for relationships
            Pattern for properties
            Using the where clause with patterns
            Using patterns in the where clause
            Using general clauses with patterns
            The order by clause
            The limit and skip clauses
            The WITH clause
            The UNION and UNION ALL clauses
            Working with nodes and relationships
     
3. Mutating Graph with Cypher

            Creating nodes and relationships
            Working with nodes
            Single node
            Multiple nodes
            Node with labels
            Node with properties
            Working with relationships
            Single relationships
            Multiple relationships
            Relationships with properties
            Nodes and relationships with full paths
            Creating unique nodes and relationships
            CREATE UNIQUE and MERGE
            Working with constraints
            Transforming nodes and relationships
            Updating node properties
            Updating a label
            Updating relationships
            Cypher query optimizations
            Indexes
            Index sampling
            Understanding execution plans
            Analyzing and optimizing queries
     
4. Getting Python and Neo4j to Talk Py2neo

            Installing and configuring py2neo
            Prerequisites
            Installing py2neo
            Exploring the py2neo APIs
            Graph
            Authentication
            Node
            Relationship
            Cypher
            Transactions
            Paths
            Creating a social network with py2neo
            Batch imports
            Unit testing
     
5. Build RESTful Service with Flask and Py2neo

            Introducing (and installing) Flask
            Setting up web applications with Flask and Flask-RESTful
            Your first Flask application
            Displaying static content
            Displaying dynamic content
            Your first Flask RESTful API
            JSON processing
            REST APIs for social network data using py2neo
            ORM for graph databases py2neo – OGM
            Social network application with Flask-RESTful and OGM
            Creating object model
            Creating REST APIs over data models
     
6. Using Neo4j with Django and Neomodel

            Installing and configuring Neomodel
            Declaring models and properties
            Defining nodes
            Defining properties
            Persisting and querying a social data model
            Adding relationships to models
            Running Cypher queries
            Using Neomodel in a Django app
            Signals in Neomodel
     
7. Deploying Neo4j in Production

            Neo4j logical architecture
            Disk/filesystem
            Record files
            Transaction logs
            Caches
            Core Java API
            Traversal framework
            REST API
            Neo4j physical architecture
            High availability
            Fault tolerance
            Data replication and data locality
            Advanced settings
            Monitoring the health of the Neo4J nodes
            Neo4j browser
            Webadmin
            JMX beans
            Backup and recovery