# Introduction to Relational Databases
## What is a Relational Database?
When the databases are represented as multiple related tables, they are called Relational Databases.
- Each row represents a record and each column represents a field.

#### _Properties of Relational Databases_
1. Each table stores some information, either about an entity or a relationship between entities.
2. Each row is unique. No two rows can be identical.
3. Each column has a unique name. No two columns can have the same name.
4. All the values in a column are of the same type.
5. All values in a column are atomic. They cannot be further divided.
6. The order of rows and columns is not guaranteed. SQL does not guarantee the order of rows and columns, although MySQL does.
   - Hence it is recommended to not rely on the order of either.
   - If you need to retrieve data in a specific order, you should use the ORDER BY clause.

#### _Advantages of Relational Databases_
- **Data Integrity**: The data is consistent and accurate.
- **Data Normalization**: Data is normalized to reduce redundancy and improve data integrity.
- **Data Security**: Access to data can be controlled.
- **Data Consistency**: Data is consistent across the database.
- **Data Independence**: Data is independent of the applications that use it.
- **Data Flexibility**: Data can be queried in many ways.
- **Data Scalability**: Data can be scaled up or down as needed.
- **Data Recovery**: Data can be recovered in case of a failure.

## Non-Relational Databases
Non-relational databases are databases that do not use the relational model. They are also known as NoSQL databases.
- They are used when the data is not structured or when the data is not relational.
- They are used in scenarios where the data is not structured or when the data is not relational.
- Examples of non-relational databases include MongoDB, Cassandra, and Redis.

#### _Advantages of Non-Relational Databases_
- **Scalability**: Non-relational databases can scale horizontally.
- **Flexibility**: Non-relational databases can store unstructured data.
- **Performance**: Non-relational databases can handle large amounts of data.
- **Availability**: Non-relational databases can be highly available.
- **Cost**: Non-relational databases can be cost-effective.
- **Ease of Use**: Non-relational databases are easy to use.
- **Schema-less**: Non-relational databases do not require a schema.

## Keys in Relational Databases
Keys are the most important part of a relational database. 
Keys are primarily used to: 
1. uniquely identify a row in a table: `Primary Key`, `Super Key` and `Candidate Key`
2. establish and identify relationships between tables: `Foreign Key` and `Composite Key`.
Among these, the `Primary Key` and `Foreign Key` are the most important keys.

