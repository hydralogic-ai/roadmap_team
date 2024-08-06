
## Test L1: CRUD Operations with Multiple Databases

### Objective

This test evaluates your understanding of various database systems by implementing basic CRUD operations. You'll work with relational, document, vector, graph, key-value pair, and time-series databases, demonstrating your knowledge of their use cases and capabilities.

### Task Overview

You will implement CRUD operations using one database from each category:

1. **Relational Database**: Choose one of the following:
   - MySQL
   - PostgreSQL
   - SQLite

2. **Document Database**: Choose one of the following:
   - MongoDB
   - CouchDB
   - Amazon DocumentDB

3. **Vector Database**: Choose one of the following:
   - Pinecone
   - Weaviate
   - Qdrant

4. **Graph Database**: Choose one of the following:
   - Neo4j
   - ArangoDB
   - Amazon Neptune

5. **Key-Value Pair Database**: Choose one of the following:
   - Redis
   - Memcached
   - Amazon DynamoDB

6. **Time-Series Database**: Choose one of the following:
   - InfluxDB
   - TimescaleDB
   - Amazon Timestream

Each section includes a specific use case to guide your implementation.

### Requirements

1. **Environment**: Use Jupyter Notebook or Google Colab to implement your solutions in Python.
2. **Documentation**: Include comments and explanations in your code.
3. **Testing**: Provide test cases to validate your implementations.
4. **Libraries**: Use appropriate libraries for connecting to and interacting with each database.

### Instructions

For each category, choose **one** database and implement the CRUD operations based on the given use case.

#### 1. Relational Database

**Use Case**: **User Management System**

- Implement CRUD operations for a `users` table with the following fields:
  - `id`: Primary Key
  - `name`: String
  - `email`: String (unique)
  - `created_at`: Timestamp

**Tasks**:
- Create a new user
- Read user details by ID
- Update user's email
- Delete a user by ID

**Considerations**:
- Discuss the strengths and weaknesses of the chosen relational database.
- Explain how to handle scalability beyond 10TB of data, including techniques like partitioning and sharding.

---

#### 2. Document Database

**Use Case**: **Product Catalog**

- Implement CRUD operations for a `products` collection with the following fields:
  - `product_id`: String (unique)
  - `name`: String
  - `description`: String
  - `price`: Float

**Tasks**:
- Add a new product
- Retrieve product details by `product_id`
- Update product description
- Remove a product by `product_id`

**Considerations**:
- Justify the choice of the document database for this use case.
- Discuss strategies for scaling and distributing data across multiple nodes.

---

#### 3. Vector Database

**Use Case**: **Semantic Search for Text Documents**

- Index a set of text documents and perform semantic search queries.

**Tasks**:
- Index documents with a unique ID and content
- Perform a semantic search to retrieve similar documents based on a query
- Update the content of a document
- Delete a document from the index

**Considerations**:
- Explain why a vector database is suitable for semantic search.
- Consider handling large volumes of data and scaling your solution.

---

#### 4. Graph Database

**Use Case**: **Organizational Hierarchy**

- Model and query an organizational hierarchy with employees and departments.

**Tasks**:
- Create nodes for employees and departments
- Establish relationships between employees and their departments
- Retrieve all employees in a specific department
- Update an employee's department
- Remove an employee from the graph

**Considerations**:
- Discuss the advantages of using a graph database for hierarchical data.
- Address scalability and performance for large-scale graphs.

---

#### 5. Key-Value Pair Database

**Use Case**: **Session Management**

- Implement basic session management using key-value storage.

**Tasks**:
- Create a session with a unique session ID and user data
- Retrieve user data by session ID
- Update session data
- Delete a session by session ID

**Considerations**:
- Justify the use of a key-value database for session management.
- Explain how to manage large amounts of data and maintain performance.

---

#### 6. Time-Series Database

**Use Case**: **Monitoring and Metrics**

- Implement CRUD operations for storing and retrieving time-series data, such as server metrics.

**Tasks**:
- Insert new metric data points
- Retrieve metrics within a specific time range
- Update existing metric data
- Delete old metric data

**Considerations**:
- Explain the benefits of using a time-series database for this use case.
- Discuss how to efficiently store and query large volumes of time-series data.

---

### Submission

- **Format**: Submit your solution via a GitHub repository.
  - Include a `README` file explaining your database choices, how to run your code, and any assumptions made.
  - Ensure all code is functional and well-documented.

### Evaluation Criteria

- **Understanding of Database Features**: Evaluate the reasoning behind choosing specific databases for given use cases.
- **Scalability Considerations**: Assess the proposed solutions for handling more than 10TB of data.
- **Correctness and Completeness**: Ensure all CRUD operations are implemented accurately.
- **Code Organization and Readability**: Evaluate code structure and clarity.
- **Proper Use of Database-Specific Features**: Assess the effective utilization of each database's unique capabilities.
- **Testing and Validation**: Verify the thoroughness of testing and validation processes.

---

This version of the test provides a comprehensive evaluation of candidates' understanding of various database technologies, emphasizing scalability and the ability to choose the right tool for the job. Let me know if there's anything else you'd like to add or modify!