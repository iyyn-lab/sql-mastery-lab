# SQL MASTERY & DATABASE ENGINEERING ROADMAP

## MySQL, PostgreSQL & Cloud Database Management

### 1. Learning Objective

To develop strong technical knowledge and practical expertise in SQL, relational database management, advanced query development, database design, performance optimization, transaction management, cloud database deployment, and production database operations.

The objective is to become capable of independently designing, implementing, managing, troubleshooting, optimizing, and maintaining relational databases for real-world client projects.

### 2. Technology Scope

**Relational Database Technologies**

- MySQL
- PostgreSQL

**Cloud Database Technologies**

- Cloud Computing Fundamentals
- Managed Relational Database Services
- Cloud Database Deployment and Management
- One Cloud Provider selected based on company and client project requirements.

**Infrastructure and Application Integration**

- Terraform Fundamentals
- Backend Application and Database Integration
- Database Migration and Automation

**Scope:** Relational databases, SQL, and cloud-based relational database engineering. No NoSQL database learning track.



---



# PART 1 – SQL AND RELATIONAL DATABASE ENGINEERING

## PHASE 1 – Relational Database Fundamentals

- Database Fundamentals
- Database Management Systems (DBMS)
- Relational Database Management Systems (RDBMS)
- Relational Model
- Tables, Rows and Columns
- Relations, Attributes and Tuples
- Domains and Relation Schema
- Relation Instances
- Degree and Cardinality
- Database Schema Concepts
- Primary Key
- Foreign Key
- Super Key
- Candidate Key
- Alternate Key
- Composite Key
- Natural Key and Surrogate Key
- Entity Integrity
- Referential Integrity
- Domain Integrity
- One-to-One Relationships
- One-to-Many Relationships
- Many-to-Many Relationships
- SQL Fundamentals
- SQL Command Categories: DDL, DML, DQL, DCL and TCL

## PHASE 2 – Database Schema and Table Management

- Database Creation and Management
- Schema Creation and Management
- CREATE DATABASE
- CREATE SCHEMA
- CREATE TABLE
- ALTER TABLE
- DROP TABLE
- TRUNCATE TABLE
- SQL Data Types
- Numeric, String and Date/Time Data Types
- Primary Key Constraints
- Foreign Key Constraints
- UNIQUE Constraints
- NOT NULL Constraints
- CHECK Constraints
- DEFAULT Constraints
- Referential Actions
- ON DELETE and ON UPDATE
- Cascading Operations
- Identity Columns
- AUTO_INCREMENT Concepts
- Sequence Fundamentals
- Generated Columns
- Schema Modification
- Database Schema Versioning
- Database Migration Fundamentals

## PHASE 3 – SQL Querying and Data Manipulation

- SELECT Statements
- INSERT Statements
- UPDATE Statements
- DELETE Statements
- WHERE Conditions
- DISTINCT
- ORDER BY
- LIMIT and OFFSET
- FETCH and Pagination Fundamentals
- Comparison Operators
- Logical Operators: AND, OR and NOT
- IN and NOT IN
- BETWEEN
- LIKE
- NULL Value Handling
- Three-Valued Logic
- IS NULL and IS NOT NULL
- CASE Expressions
- Type Casting and Data Conversion
- SQL Expressions
- Column and Table Aliases
- Built-in String Functions
- Built-in Numeric Functions
- Date and Time Functions
- SQL Query Logical Processing Order

## PHASE 4 – SQL Joins and Relationships

- JOIN Fundamentals
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- CROSS JOIN
- SELF JOIN
- NATURAL JOIN
- JOIN USING
- Multiple Table Joins
- Multi-Column Joins
- Non-Equi Joins
- Semi JOIN Patterns
- Anti JOIN Patterns
- JOIN vs Subquery
- ON vs WHERE
- Handling Duplicate Rows in JOINs
- Join Multiplication
- One-to-One Join Scenarios
- One-to-Many Join Scenarios
- Many-to-Many Join Scenarios
- JOIN with Filtering
- JOIN with Aggregation
- JOIN with Subqueries

## PHASE 5 – SQL Set Operations

- Set Operation Fundamentals
- UNION
- UNION ALL
- INTERSECT
- EXCEPT
- Set Operation Rules
- Column Compatibility
- Data Type Compatibility
- Duplicate Handling
- NULL Handling in Set Operations
- Multiple Set Operations
- Set Operations vs JOIN

## PHASE 6 – Aggregate Functions and Grouping

- Aggregate Function Fundamentals
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()
- GROUP BY
- HAVING
- WHERE vs HAVING
- Conditional Aggregation
- Multiple Column Grouping
- Aggregate Functions with JOINs
- Aggregate Functions with Subqueries
- NULL Handling in Aggregation
- ROLLUP
- Grouping Operations
- GROUPING SETS
- Advanced Aggregation Techniques

## PHASE 7 – Subqueries and Common Table Expressions

- Subquery Fundamentals
- Scalar Subqueries
- Single-Row Subqueries
- Multiple-Row Subqueries
- Nested Subqueries
- Correlated Subqueries
- Non-Correlated Subqueries
- EXISTS and NOT EXISTS
- IN and NOT IN
- ANY and ALL
- Derived Tables
- Common Table Expressions (CTE)
- Multiple CTEs
- Recursive CTEs
- CTE Execution Concepts
- CTE vs Subquery
- CTE vs JOIN
- Subquery Optimization
- Complex Query Construction

## PHASE 8 – SQL Window Functions

- Window Function Fundamentals
- OVER() Clause
- PARTITION BY
- ORDER BY in Window Functions
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- LAG()
- LEAD()
- FIRST_VALUE()
- LAST_VALUE()
- Aggregate Window Functions
- Running Totals
- Moving Averages
- Window Frames
- Named Windows
- Window Functions with CTEs
- Window Functions with JOINs
- Window Functions vs GROUP BY
- Advanced Ranking and Analytical Queries

## PHASE 9 – Database Design and Normalization

- Database Design Fundamentals
- Entity Relationship Diagrams (ERD)
- Entity and Attribute Design
- Relational Schema Design
- Primary Key Selection
- Foreign Key Design
- Functional Dependencies
- First Normal Form (1NF)
- Second Normal Form (2NF)
- Third Normal Form (3NF)
- Boyce-Codd Normal Form (BCNF)
- Database Normalization
- Database Denormalization
- Insert Anomalies
- Update Anomalies
- Delete Anomalies
- Natural Keys vs Surrogate Keys
- Relationship Cardinality
- Referential Integrity
- Database Constraints and Business Rules
- Database Schema Design Best Practices

## PHASE 10 – Transactions and Concurrency Control

- Database Transaction Fundamentals
- ACID Properties
- Atomicity
- Consistency
- Isolation
- Durability
- BEGIN / START TRANSACTION
- COMMIT
- ROLLBACK
- SAVEPOINT
- Autocommit
- Transaction Boundaries
- Transaction Isolation Levels
- Read Uncommitted
- Read Committed
- Repeatable Read
- Serializable
- Dirty Reads
- Non-Repeatable Reads
- Phantom Reads
- Database Locking
- Shared Locks
- Exclusive Locks
- Row-Level Locks
- Table-Level Locks
- Lock Contention
- Deadlocks and Deadlock Resolution
- Multi-Version Concurrency Control (MVCC)
- Optimistic Locking
- Pessimistic Locking
- Concurrent Transaction Management
- Transaction Retry and Idempotency Fundamentals

## PHASE 11 – Database Indexing and Storage Internals

- Index Fundamentals
- Why Indexes Are Required
- B-Tree and B+Tree Concepts
- Hash Index Concepts
- Clustered Index Concepts
- Unique Indexes
- Composite Indexes
- Covering Indexes
- Partial Index Concepts
- Expression-Based Indexes
- Index-Only Scan Concepts
- Index Selectivity
- Cardinality and Statistics
- Index Ordering
- Multi-Column Index Design
- Index Maintenance
- Index Usage Analysis
- Table Storage Fundamentals
- Pages and Storage Concepts
- Indexing Strategies
- Index Performance Trade-offs

## PHASE 12 – Query Execution and Performance Optimization

- SQL Query Execution Process
- SQL Parsing and Validation
- Query Planner and Optimizer
- Logical Query Processing
- Physical Query Execution
- Query Execution Plans
- EXPLAIN
- EXPLAIN ANALYZE
- Sequential Scans
- Index Scans
- Nested Loop Join
- Hash Join
- Merge Join
- Join Order Optimization
- Query Cost Analysis
- Index Usage Analysis
- Database Statistics
- Cost Estimation
- Query Optimization Techniques
- Query Rewriting
- JOIN Optimization
- Subquery Optimization
- Aggregation Optimization
- Pagination Optimization
- Offset vs Keyset Pagination
- N+1 Query Problem
- Sargable Queries
- Slow Query Analysis
- Query Benchmarking
- Performance Troubleshooting
- Large Dataset Query Optimization

## PHASE 13 – Advanced SQL Database Objects

- Views
- Materialized View Concepts
- Temporary Tables
- Stored Procedures
- User-Defined Functions
- Triggers
- BEFORE and AFTER Trigger Concepts
- Cursors
- Exception Handling
- Dynamic SQL
- Procedural SQL Fundamentals
- Database Object Dependencies
- Stored Program Execution
- Database Object Management
- Reusable Database Logic

## PHASE 14 – Advanced Database Features

- JSON Data Types and Handling
- JSON Querying and Manipulation
- Full-Text Search Fundamentals
- Full-Text Indexing Concepts
- Table Partitioning
- Partitioning Strategies
- Range Partitioning
- List Partitioning
- Hash Partitioning
- Partition Pruning
- Character Sets
- Collations
- Unicode Fundamentals
- Date and Time Zone Handling
- Advanced Data Type Handling
- Spatial Data Fundamentals
- Advanced SQL Functions and Operators

## PHASE 15 – Database Security and Administration

**Database Security**

- Database Users and Roles
- Authentication and Authorization
- GRANT and REVOKE
- Database Permissions and Privileges
- Least Privilege Principle
- Row-Level Security Concepts
- SQL Injection Prevention
- Prepared Statements
- Parameterized Queries
- Secure Database Access
- Database Audit Logging
- Sensitive Data Protection

**Database Administration**

- Database Server Administration Fundamentals
- Database Configuration
- INFORMATION_SCHEMA
- System Catalogs
- Database Backup Fundamentals
- Database Restore Fundamentals
- Database Maintenance
- Database Monitoring Fundamentals
- Database Logs
- Database Version Upgrades
- Database Replication Fundamentals
- High Availability Fundamentals
- Database Troubleshooting
- Database Capacity and Resource Monitoring

## PHASE 16 – MySQL and PostgreSQL Specific Features and Comparison

*Deferred until the common SQL concepts have been thoroughly understood.*

- MySQL Architecture and PostgreSQL Architecture
- SQL Syntax Differences
- Data Type Differences
- Identity Columns and AUTO_INCREMENT
- Sequence Management
- Upsert Operations
- JOIN Support Differences
- FULL OUTER JOIN Implementation
- Indexing Differences
- MySQL InnoDB Storage Engine
- PostgreSQL Storage and Index Internals
- PostgreSQL Index Types: B-tree, Hash, GiST, SP-GiST, GIN and BRIN
- Materialized Views and Platform-Specific Alternatives
- JSON vs JSONB
- PostgreSQL Arrays
- Stored Procedures and Functions
- MySQL Event Scheduler
- PostgreSQL PL/pgSQL
- Trigger and Cursor Differences
- Transaction Isolation Differences
- Query Planner Differences
- EXPLAIN and EXPLAIN ANALYZE Differences
- Character Set and Collation Differences
- Date and Time Handling Differences
- Database Catalog and Administration Differences
- VACUUM, ANALYZE and Autovacuum (PostgreSQL)
- Database Backup and Restore Tools
- Replication and High Availability Differences
- Database-Specific Functions and Operators
- Cross-Database SQL Implementation



---



# PART 2 – CLOUD COMPUTING AND DATABASE ENGINEERING

## PHASE 17 – Cloud Computing Fundamentals and Architecture

**Cloud Computing Fundamentals**

- Cloud Computing Concepts
- Cloud Service Models: IaaS, PaaS and SaaS
- Database as a Service (DBaaS)
- Public, Private and Hybrid Cloud
- Cloud Deployment Models
- Shared Responsibility Model
- Managed vs Self-Managed Infrastructure
- Cloud Accounts, Projects and Subscriptions
- Cloud Resource Management
- Cloud Regions and Availability Zones
- Cloud Resource Lifecycle
- Cloud Architecture Fundamentals

**Cloud Networking Fundamentals**

- IP Addressing
- CIDR and Subnet Fundamentals
- DNS Fundamentals
- Routing Fundamentals
- Public and Private Network Concepts
- Network Isolation
- Secure Network Connectivity

**Cloud Architecture Principles**

- Availability
- Reliability
- Security
- Performance Efficiency
- Scalability
- Cost Optimization
- Fault Tolerance
- Resilience
- Shared and Dedicated Infrastructure Concepts

## PHASE 18 – Cloud Database Deployment and Management

**Cloud Database Services**

- Managed Relational Database Services
- Cloud Database Architecture
- Cloud Database Provisioning
- Database Engine and Version Selection
- Database Instance Configuration
- CPU and Memory Configuration
- Storage Types and Capacity
- IOPS and Throughput
- Storage Autoscaling
- Database Parameter Configuration
- Database Maintenance Windows
- Database Version Upgrades

**Cloud Networking and Connectivity**

- Virtual Private Cloud (VPC) / Virtual Network (VNet)
- CIDR and Subnet Configuration
- Public and Private Subnets
- Route Tables
- Internet and NAT Gateways
- Security Groups and Network Security Groups
- Network ACLs and Firewalls
- Public and Private Database Access
- Private Endpoints
- Private DNS
- VPC / VNet Peering
- VPN Connectivity
- Secure Administrative Access
- Database Network Isolation
- Network Troubleshooting

**Cloud Identity and Security**

- Cloud Identity and Access Management (IAM)
- IAM Users, Groups and Roles
- IAM Policies
- Service Accounts and Managed Identities
- Least Privilege Access
- Database Authentication
- Secrets Management
- Credential Rotation
- Encryption at Rest
- Encryption in Transit
- TLS / SSL Certificates
- KMS and Encryption Key Management
- Cloud Audit Logging

**Infrastructure as Code and Automation**

- Infrastructure as Code Fundamentals
- Terraform Fundamentals
- Terraform Providers
- Terraform Variables and Outputs
- Terraform State Management
- Terraform Modules
- Infrastructure Provisioning
- Infrastructure Version Control
- Terraform Plan and Apply
- Infrastructure Change Management
- Cloud CLI Fundamentals
- Cloud Resource Automation

**Application and Database Integration**

- Backend Application Hosting Fundamentals
- Application-to-Database Connectivity
- Database Endpoints and Connection Strings
- Secure Application Connectivity
- Environment Configuration
- Secrets Integration
- Database Connection Pooling
- Database Connection Proxies
- Connection Timeouts
- Retry Mechanisms
- Exponential Backoff
- Connection Failure Handling
- Application Compatibility During Maintenance and Failover

**Cloud Database Migration**

- Local-to-Cloud Database Migration
- On-Premises-to-Cloud Migration
- Database Schema Migration
- Database Data Migration
- Homogeneous Migration
- Heterogeneous Migration
- Full Load Migration
- Change Data Capture (CDC)
- Continuous Data Replication
- Data Validation and Reconciliation
- Migration Cutover
- Downtime Management
- Migration Rollback
- Migration Troubleshooting

**Cloud Backup and Disaster Recovery**

- Automated Database Backups
- Manual Database Snapshots
- Backup Retention Policies
- Point-in-Time Recovery (PITR)
- Database Export and Import
- Database Restoration
- Recovery Point Objective (RPO)
- Recovery Time Objective (RTO)
- Cross-Region Backup
- Disaster Recovery Planning
- Backup Restoration Testing

**Cloud High Availability and Replication**

- High Availability Architecture
- Multi-AZ / Zone Redundancy
- Primary and Standby Database Concepts
- Read Replicas
- Synchronous and Asynchronous Replication
- Replication Lag
- Automatic and Manual Failover
- Cross-Region Replication
- Read and Write Traffic Separation
- Failover Testing
- Database Resilience

**Cloud Monitoring and Maintenance**

- Cloud Database Monitoring
- Cloud Metrics and Logs
- Database Performance Metrics
- CPU and Memory Monitoring
- Storage and I/O Monitoring
- Active Connection Monitoring
- Slow Query Monitoring
- Replication Monitoring
- Alert and Notification Configuration
- Database Maintenance Operations
- Database Patching
- Minor and Major Version Upgrades
- Database Parameter Updates
- Cloud Database Troubleshooting

**Cloud Scaling and Cost Management**

- Vertical Scaling
- Storage Scaling
- Compute and Memory Scaling
- Read Scaling
- Read Replica Scaling
- Workload and Capacity Analysis
- Cloud Resource Sizing
- Cost Estimation
- Cloud Budget Management
- Resource Tagging
- Data Transfer Costs
- Storage and Backup Costs
- Cloud Cost Monitoring
- Resource Cleanup and Cost Optimization

## PHASE 19 – Production Database Engineering and End-to-End Implementation

**Production Database Environments**

- Development, Staging and Production Environments
- Environment Configuration
- Database Configuration Management
- Production Database Readiness
- Database Deployment Strategies

**Production Database Migrations**

- Database Migration Versioning
- Migration Version Management
- Forward and Backward-Compatible Migrations
- Zero-Downtime Migration Concepts
- Expand-and-Contract Migration Pattern
- Online Schema Changes
- Large Table Data Backfilling
- Migration Rollback and Recovery
- CI/CD for Database Migrations
- Automated Migration Testing
- Production Schema Deployment

**Database Reliability and Operations**

- Production Database Monitoring
- Database Incident Management
- Root Cause Analysis
- Database Runbooks and Playbooks
- Production Troubleshooting
- Operational Readiness
- Change Management
- Maintenance Planning
- Database Availability Management
- Service Level Indicators (SLIs)
- Service Level Objectives (SLOs)
- Disaster Recovery Exercises
- Backup and Restore Validation
- Failover Testing

**Advanced Performance and Scale**

- Large Dataset Processing
- Bulk Data Import and Export
- Batch Processing
- Large Table Optimization
- Workload Analysis
- Load Testing
- Stress Testing
- Concurrent Workload Testing
- Query Benchmarking
- Database Capacity Planning
- Data Growth Management
- Data Archiving
- Data Retention Policies
- Production Performance Troubleshooting

**Production Security and Data Governance**

- Production Access Control
- Database Permission Reviews
- Secrets and Credential Rotation
- Audit and Activity Monitoring
- Sensitive Data Masking
- Personal Data Protection
- Data Retention and Secure Deletion
- Data Integrity Verification
- Data Reconciliation

**Database Workload and Architecture**

- OLTP Fundamentals
- OLAP Fundamentals
- Read-Heavy and Write-Heavy Workloads
- Read/Write Separation
- Primary and Replica Architecture
- Change Data Capture (CDC)
- Database Scalability Fundamentals
- Database Architecture Design

### End-to-End Practical Capstone Project

**Relational E-Commerce Database Engineering Project**

- Design a complete relational database schema.
- Create an Entity Relationship Diagram.
- Implement normalized tables and relationships.
- Define primary keys, foreign keys and constraints.
- Generate and manage realistic large datasets.
- Implement JOINs across multiple large tables.
- Develop complex subqueries and CTEs.
- Implement window functions and analytical queries.
- Build advanced aggregation queries.
- Implement transaction-based order processing.
- Handle concurrent order and inventory updates.
- Create appropriate indexes.
- Analyse execution plans.
- Benchmark queries before and after optimization.
- Implement secure backend database connectivity.
- Use parameterized queries.
- Implement database migration versioning.
- Deploy the database to the cloud using the company-selected provider.
- Establish secure private database connectivity.
- Configure database permissions and secrets.
- Migrate local database data to the cloud.
- Configure automated backups and recovery.
- Implement monitoring and alerts.
- Configure high availability and replication where supported.
- Perform failover and recovery testing.
- Perform load and performance testing.
- Analyse database resource utilization and costs.
- Prepare database architecture documentation.
- Prepare production operations and recovery runbooks.



---



# PART 3 – NOVEMBER 2026 TO JANUARY 2027 LEARNING EXECUTION PLAN

### Target Period

November 3, 2026 – January 31, 2027

### Daily Learning Commitment

4 hours per day.

### Total Available Learning Time

90 calendar days × 4 hours = 360 hours.

### Phase-wise Execution Schedule



**Schedule Note:**

The schedule below is a rough estimate and may change depending on my learning progress and practical requirements. I am not completely sure whether I can complete everything within the planned timeline, but I will try my best to follow the schedule and achieve the learning goals by January 31, 2027.

For Phases 1, 2 and 3, I will focus only on the essential topics required for my learning goals rather than covering every topic in depth. Therefore, these phases may take less time than currently allocated, and the remaining time can be adjusted based on my progress.









| **Period**      | **Learning phases**                        | **Hours**   |
| --------------- | ------------------------------------------ | ----------- |
| Nov 3 – Nov 16  | Phase 1, 2 and 3                           | 56          |
| Nov 17 – Nov 30 | Phase 4, 5 and 6                           | 56          |
| Dec 1 – Dec 14  | Phase 7 and 8                              | 56          |
| Dec 15 – Dec 21 | Phase 9 and 10                             | 28          |
| Dec 22 – Jan 4  | Phase 11 and 12                            | 56          |
| Jan 5 – Jan 11  | Phase 13, 14 and 15                        | 28          |
| Jan 12 – Jan 18 | Phase 17                                   | 28          |
| Jan 19 – Jan 25 | Phase 18                                   | 28          |
| Jan 26 – Jan 31 | Phase 19 final implementation and revision | 24          |
| **Total**       | **360 hours**                              | **90 days** |

**Important Schedule Notes**

- Phase 16 (MySQL and PostgreSQL comparison) is deliberately deferred to avoid confusion while learning common SQL concepts.
- Capstone implementation must start progressively during database design, querying, optimization and cloud learning. The final phase is for integration, testing and documentation, not for starting the entire project from scratch.
- Phase 19 production engineering topics will be covered at foundation and practical introduction level within this period.
- Schedule assumes four hours of learning on every calendar day.



---



## LEARNING METHODOLOGY

Every important concept will follow this learning process:

1. Technical Definition and Fundamentals.
2. Why the Concept Is Required.
3. Internal Working and Execution Flow.
4. Architecture Diagrams and Illustrations.
5. Practical Examples and Sample Tables.
6. Hands-on SQL Queries and Expected Outputs.
7. Real-World Backend and Database Scenarios.
8. Performance Considerations and Limitations.
9. Common Mistakes and Troubleshooting.
10. Advanced Technical Questions.
11. Independent Practical Assignments.
12. Knowledge Assessment and Meeting Explanation.

## PRACTICAL LEARNING STANDARDS

- Do not skip intermediate concepts.
- Understand technical fundamentals before moving to advanced topics.
- Practice SQL independently instead of only reading queries.
- Work with realistic datasets of increasing size.
- Learn indexing and execution plans through actual experiments.
- Implement transaction and concurrency scenarios.
- Practice database backup and restoration.
- Deploy one relational database to a cloud environment.
- Connect a backend application securely to the cloud database.
- Perform practical monitoring and troubleshooting.
- Explain technical decisions without relying entirely on notes.



---



## EXPECTED LEARNING OUTCOMES

By the end of the learning period, the target is to achieve the following capabilities:

- Strong understanding of relational database concepts and SQL.
- Ability to write basic, complex and advanced SQL queries independently.
- Ability to handle JOINs and complex queries on large datasets.
- Ability to analyse and optimize database performance.
- Ability to design normalized and scalable relational database schemas.
- Strong understanding of transactions, ACID properties and concurrency control.
- Ability to troubleshoot locking, deadlocks and transaction-related problems.
- Understanding of database indexing and query execution internals.
- Ability to manage relational databases using MySQL and PostgreSQL.
- Understanding of database security, backup and recovery.
- Ability to deploy and configure cloud-based relational databases.
- Ability to integrate cloud databases with backend applications.
- Ability to migrate databases between environments.
- Ability to monitor, troubleshoot and maintain production databases.
- Understanding of database scalability, high availability and disaster recovery.
- Ability to explain database-related technical concepts and decisions confidently in meetings.
- Practical ability to take ownership of relational database-related responsibilities in real-world client projects.



---



## OFFICIAL LEARNING AND REFERENCE RESOURCES

**Database Documentation**

- MySQL Reference Manual:[ https://dev.mysql.com/doc/refman/8.4/en/](https://dev.mysql.com/doc/refman/8.4/en/)
- PostgreSQL Documentation:[ https://www.postgresql.org/docs/18/](https://www.postgresql.org/docs/18/)

**Cloud Database Documentation**

- AWS Amazon RDS:[ https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/)
- AWS Database Migration Service:[ https://docs.aws.amazon.com/dms/latest/userguide/](https://docs.aws.amazon.com/dms/latest/userguide/)
- Microsoft Azure Database for PostgreSQL:[ https://learn.microsoft.com/en-us/azure/postgresql/](https://learn.microsoft.com/en-us/azure/postgresql/)
- Google Cloud SQL:[ https://docs.cloud.google.com/sql/docs](https://docs.cloud.google.com/sql/docs)

**Infrastructure and Security**

- Terraform Documentation:[ https://developer.hashicorp.com/terraform/docs](https://developer.hashicorp.com/terraform/docs)
- OWASP SQL Injection Prevention:[ https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)
- AWS Well-Architected Framework:[ https://docs.aws.amazon.com/wellarchitected/latest/framework/](https://docs.aws.amazon.com/wellarchitected/latest/framework/)



---



## FINAL LEARNING GOAL

**SQL MASTERY + DATABASE ENGINEERING + CLOUD DATABASE MANAGEMENT + PRODUCTION DATABASE OWNERSHIP**

The objective is to build the technical knowledge, practical skills and confidence required to independently handle database-related responsibilities and contribute effectively to future client projects.
