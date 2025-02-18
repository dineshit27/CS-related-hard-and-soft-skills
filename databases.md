# Databases

## Important topics

- Denormalized vs. Normalized
  - Denormalized
    - contains redundant data
    - optimize read (because JOIN is expensive)
  - Normalized
    - minimize redundancy
- SQL Syntax
  - SELECT
  - min, max, count
  - FROM
  - WHERE
  - GROUP BY ... DESC
  - ORDER BY
  - AS
  - JOIN ... ON x.a = y.b
- SQL vs. NoSQL
  | SQL                                                  | NoSQL                                                               |
  | ---------------------------------------------------- | ------------------------------------------------------------------- |
  | Table based                                          | Key-value pairs, graph, wide-column                                 |
  | Fixed schema                                         | no/dynamic schema                                                   |
  | structured data                                      | unstructured/hierarchical data                                      |
  | vertical scalability                                 | horizontal scalability                                              |
  | transactional work load, definition and manipulation | read, collections of documents                                      |
  | ACID - atomicity, consistency, isolation, durability | CAP - consistency, availability, partition tolerance                |
  | MySQL, Oracle, Sqlite, Postgres, MS-SQL              | MongoDB, BigTable, Redis, RavenDB, Cassandra, Hbase, Neo4j, CouchDB |


## Database design

1. Determine requirements & handle ambiguity
2. Define core objects
3. Analyze relationships
4. Investigate actions
   - each action might require additional tables
   - how to store and retrieve data