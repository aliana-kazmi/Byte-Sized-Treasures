## Definition

Relational databases are based on the relational model, which ==organizes data into tables with rows and columns.== These databases have been the standard choice for many applications due to their ==robust consistency, support for complex queries, and adherence to ACID properties (Atomicity, Consistency, Isolation, Durability).== 


Popular relational databases include MySQL, PostgreSQL, Microsoft SQL Server, and Oracle. Each of these options has its unique features, strengths, and weaknesses, making them suitable for different use cases and requirements. When considering a relational database, it is essential to evaluate the specific needs of the application in terms of data consistency, support for complex queries, and scalability, among other factors.

![[Pasted image 20240520012226.png]]
[Source](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb5d5235c-260c-4cf6-969b-efa2af2265bb_1600x402.png)

#### Key features and benefits:
- **Data in relational databases is stored in tables with a predefined schema**, enforcing a consistent structure throughout the database which makes it easier to manage and maintain data, especially when dealing with large amounts of structured data.
- **The relationships between tables in a relational database are defined by primary and foreign keys, ensuring referential integrity**. This feature allows for efficient querying of related data and supports complex data relationships.
-   **Relational databases use Structured Query Language (SQL)** for querying, manipulating, and managing data. SQL is a powerful and widely adopted language that **enables developers to perform complex queries and data manipulations**.
- **Relational databases support transactions**, which are sets of related operations that either succeed or fail as a whole. This feature ensures the [[ACID properties]] are maintained, **guaranteeing data consistency and integrity**.
- Relational databases **offer various indexing techniques and query optimization strategies**, which **help improve query performance and reduce resource consumption**.

#### Drawbacks:
- **Scaling relational databases horizontally** (adding more nodes) **can be challenging**, especially when **compared to some NoSQL databases** that are designed for distributed environments.
- The **predefined schema** in relational databases **can make it difficult to adapt to changing requirements**, as altering the schema may require significant modifications to existing data and applications.
- **As the volume of data grows, relational databases may experience performance issues**, particularly when dealing with complex queries and large-scale data manipulations.
- Relational databases are designed for structured data, which **may not be suitable for managing unstructured or semi-structured data**, such as social media data or sensor data.