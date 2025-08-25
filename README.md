# Distributed Key-Value Store using C++
This project involves creating a simplified version of a distributed key-value store, similar to Amazon's DynamoDB or Apache Cassandra.

## Key Concepts to Implement:

Consistent Hashing: For distributing data across multiple nodes and handling node additions/removals gracefully.

Data Replication: Implement a replication strategy (e.g., N-way replication) to ensure data durability and availability.

Eventual Consistency: Design the system to achieve eventual consistency, handling conflicts and data synchronization.

Basic Fault Tolerance: Implement mechanisms to detect node failures and re-replicate data or elect new coordinators.

Communication: Use a high-performance communication library (like gRPC or a custom TCP-based solution) for inter-node communication.
