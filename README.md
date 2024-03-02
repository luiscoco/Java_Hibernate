# Java Hibernate integration

Introduction to Hibernate framework
Piyush Lovanshi
1 de marzo de 2024

Hibernate is a open-source persistence framework that simplifies the interaction between Java applications and databases.

Hibernate is an open-source project meaning that its code is available publicly for all to inspect and is open to improvements via open-source contributions, is lightweight with a small installation package that doesn’t require heavy containers, and is a powerful ORM (Object-Relational Mapping) tool making it much easier for user to interact with the database.

Hibernate adheres to the specifications of JPA (Jakarta Persistence API), which is a standardized API for managing relational data in Java applications. JPA provides a set of interfaces and annotations for defining entities, relationships, and queries. 

By conforming to JPA standards, Hibernate ensures portability and interoperability across different JPA-compliant ORM frameworks.

Hibernate follows a non-invasive approach, which means that our domain model classes remain independent of the Hibernate framework. This loose coupling allows developers to focus on domain modeling and business 
logic without being tied to specific ORM implementations.

It provides mapping of Java classes to database tables and columns. Hibernate also provides built-in transaction management and caching capabilities.

Reasons to use hibernate:

Overcoming old school JDBC Limitations: 

Database Dependency: JDBC code is tied to the specific database software being used. Changing the database mid-project can be costly.

Boilerplate Code: JDBC requires repetitive boilerplate code for connection handling, exception management, and query execution.

Lack of Object-Level Relationships: JDBC lacks support for object-level relationships.

Hibernate’s Abstraction: 

Hibernate provides an abstraction layer due to which we do not need to worry about low-level implementations.

Hibernate handles tasks like establishing database connections and writing CRUD (Create, Read, Update, Delete) queries internally.

Where:

Where can we use hibernate:

Web applications.

Enterprise applications.

Small console-based java application.

Or any project where data persistence matters.

When:

Use hibernate instead of classic JDBC when you want:

Implicit Object-Relational Mapping (ORM): Hibernate facilitates the automatic translation of data retrieved from the database into Java objects representing the tables. This seamless conversion from rows to 

objects simplifies data handling and enhances code readability.

Simplified Connection Management: Hibernate eliminates the need for manual management of database connections. It automates connection handling, including connection pooling, relieving developers of the burden of 
managing connections explicitly.

Streamlined Database Access: Hibernate streamlines database access by automating repetitive tasks such as connection management, SQL generation, and result set processing. This automation significantly reduces development time and effort compared to writing and maintaining JDBC code.

Efficient Data Caching: Hibernate offers built-in support for caching, enabling data to be cached in memory for improved performance. By reducing the frequency of database queries, caching optimizes application performance and enhances user experience.

Simplified Transaction Management: Hibernate simplifies transaction management through its declarative transaction support. Developers can define transaction boundaries using annotations or XML configuration, eliminating the need for manual transaction management. This simplification reduces the complexity of transaction-related code and enhances maintainability.

