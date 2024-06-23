# Unit 7, Day 58: Introduction to Cloud SQL with Next.js 14 Lesson Plan

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the differences between Firestore and Cloud SQL
2. Set up a Cloud SQL instance and connect it to a Next.js application
3. Perform basic CRUD operations using Cloud SQL in a Next.js environment
4. Design relational database schemas for web applications
5. Implement database migrations and versioning
6. Use an ORM (Prisma) with Cloud SQL for improved developer experience
7. Understand when to choose Cloud SQL over Firestore (and vice versa)

## Content Chunks

### Chunk 1: Introduction to Cloud SQL and Comparison with Firestore (60 minutes)

#### Information to Present:
- Overview of Cloud SQL and its features
- Differences between NoSQL (Firestore) and SQL databases
- Use cases for Cloud SQL vs Firestore
- Setting up a Cloud SQL instance on Google Cloud Platform
- Connecting Cloud SQL to a Next.js application

#### Comprehension Check Questions:
1. What are the main differences between Firestore and Cloud SQL?
2. In what scenarios would you choose Cloud SQL over Firestore?

#### Practical Task:
Guide the user through setting up a Cloud SQL instance on Google Cloud Platform and connecting it to their Next.js application. They should ensure they can establish a connection and perform a simple query.

### Chunk 2: Basic CRUD Operations with Cloud SQL (45 minutes)

#### Information to Present:
- SQL basics (SELECT, INSERT, UPDATE, DELETE)
- Executing SQL queries in a Next.js environment
- Handling query results and error management
- Prepared statements and query parameterization
- Transaction management in Cloud SQL

#### Comprehension Check Questions:
1. How do CRUD operations in SQL differ from those in Firestore?
2. Why is it important to use prepared statements when working with SQL databases?

#### Practical Task:
Ask the user to implement basic CRUD operations for a simple entity (e.g., "User") in their Task Board application using Cloud SQL. They should create API routes in Next.js to handle these operations.

### Chunk 3: Designing Relational Database Schemas (60 minutes)

#### Information to Present:
- Principles of relational database design
- Normalization and denormalization in SQL databases
- Creating tables and defining relationships
- Indexing in SQL databases
- Best practices for schema design in web applications

#### Comprehension Check Questions:
1. What are the benefits of normalizing a database schema?
2. How do you represent one-to-many and many-to-many relationships in a relational database?

#### Practical Task:
Guide the user through designing a relational schema for their Task Board application. They should create tables for users, teams, boards, and tasks, defining appropriate relationships between these entities.

### Chunk 4: Database Migrations and Versioning (45 minutes)

#### Information to Present:
- Concept of database migrations
- Implementing migrations in a Next.js project
- Tools for managing SQL migrations (e.g., Prisma Migrate)
- Versioning database schemas
- Handling data transformations during migrations

#### Comprehension Check Questions:
1. Why are database migrations important in a production environment?
2. How can you ensure safe execution of migrations without data loss?

#### Practical Task:
Ask the user to set up a migration system for their Cloud SQL database. They should create migrations to set up their schema, and then create a migration to add a new field to an existing table.

### Chunk 5: Using Prisma ORM with Cloud SQL (60 minutes)

#### Information to Present:
- Introduction to ORMs and their benefits
- Setting up Prisma with Next.js and Cloud SQL
- Defining models and relationships in Prisma
- Performing CRUD operations with Prisma
- Prisma's type safety and auto-completion features

#### Comprehension Check Questions:
1. What are the advantages of using an ORM like Prisma over raw SQL queries?
2. How does Prisma help in maintaining type safety in a TypeScript environment?

#### Practical Task:
Guide the user through setting up Prisma in their Next.js application. They should define models for their Task Board entities, generate the Prisma client, and refactor their CRUD operations to use Prisma instead of raw SQL.

## Extended Coding Challenge (90 minutes)

Enhance the "Real-time Collaborative Task Board" application by adding Cloud SQL integration:

1. Set up a Cloud SQL database with tables for users, teams, boards, and tasks
2. Implement CRUD operations for all entities using Prisma ORM
3. Create a migration system for the database schema
4. Implement a hybrid approach where real-time data (e.g., active users, live updates) is still handled by Firestore, but persistent data is stored in Cloud SQL
5. Add a new feature that requires complex SQL queries (e.g., advanced reporting or analytics)
6. Implement proper error handling and transaction management
7. Ensure the application can switch between Firestore and Cloud SQL smoothly for different features

The project should demonstrate:
- Effective use of Cloud SQL in a Next.js environment
- Proper database schema design and relationship modeling
- Implementation of a migration system
- Efficient use of Prisma ORM
- Integration of SQL and NoSQL databases in a single application
- Consideration of performance and scalability in database operations

Evaluation Criteria:
- Correct implementation of Cloud SQL connection and operations
- Appropriate schema design for the Task Board application
- Successful implementation and use of database migrations
- Effective use of Prisma for database operations
- Implementation of complex SQL queries for new features
- Smooth integration of Cloud SQL alongside existing Firestore functionality
- Proper error handling and transaction management
- Clean, efficient, and well-organized code structure
- Appropriate use of TypeScript for type safety
- Consideration of security in database access and operations

## Additional Resources
- Cloud SQL Documentation: https://cloud.google.com/sql/docs
- Prisma Documentation: https://www.prisma.io/docs/
- SQL vs NoSQL Databases: https://www.mongodb.com/nosql-explained/nosql-vs-sql
- Database Migration Strategies: https://martinfowler.com/articles/evodb.html
- Next.js API Routes: https://nextjs.org/docs/api-routes/introduction

## Notes for LLM Instructor
- Emphasize the differences and trade-offs between SQL and NoSQL databases
- Encourage students to think about data consistency and ACID properties in relational databases
- Provide real-world examples of when to use SQL vs NoSQL databases
- Be prepared to explain complex SQL concepts like joins, indexes, and transactions
- Highlight the benefits of using an ORM like Prisma, especially in a TypeScript environment
- Adapt explanations based on the user's familiarity with SQL and relational databases
- Be ready to provide guidance on optimizing SQL queries and database performance
- Discuss how the choice of database can impact application architecture and scalability
- Relate the day's lessons to best practices in building robust, scalable web applications
