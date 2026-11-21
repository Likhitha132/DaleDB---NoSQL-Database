# DaleDB — NoSQL Database Simulation

**Java | HashMap | AVL Trees | TreeMap | LRU Eviction | Data Structures & Algorithms**

## Overview
DaleDB is a Java-based simulation of a NoSQL database that organizes and manages records across multiple data partitions. Inspired by concepts used in databases like Amazon DynamoDB, this project demonstrates how custom data structures can support efficient data storage, retrieval, and management.

The application models a wildlife activity database, tracking events across different ponds, including animal movements and fishing reports.

## Data Structures & Technical Implementation

### HashMap — Data Partitioning
- Implemented a custom HashMap using linear probing for collision resolution.
- Used hash-based indexing to organize data by unique partition keys.
- Supported average-case O(1) lookup, dynamic resizing, and load-factor management.

### AVL Tree & TreeMap — Ordered Data Storage
- Implemented self-balancing AVL tree operations and adapted the structure into a TreeMap.
- Organized records using timestamp-based keys for efficient retrieval.
- Supported sorted traversal and range queries, with O(log n) key-based operations.

### LRU Eviction — Data Management
- Applied Least Recently Used (LRU) eviction to manage partitions based on access history.
- Prioritized removal of the least recently accessed partitions.
- Explored how access patterns influence database storage and retention.

## Key Features
- **Record Management:** Insert, update, retrieve, and delete database records.
- **Partitioned Storage:** Organize records into separate groups using unique identifiers.
- **Timestamp-Based Retrieval:** Retrieve records chronologically or within specified time ranges.
- **LRU Eviction:** Remove least recently accessed partitions.
- **Activity Analysis:** Calculate peak occupancy and identify frequent visitors.
- **Record Consolidation:** Merge related fishing reports to reduce redundant records.

## Key Learning Outcomes
- Implemented custom HashMap and AVL-backed TreeMap data structures in Java.
- Applied hashing, collision resolution, tree balancing, and ordered indexing to database operations.
- Practiced analyzing time and space complexity to improve algorithmic efficiency.
- Explored foundational NoSQL concepts, including partition keys, sort keys, and data eviction.

## Source Code
This project was completed as part of Georgia Tech's CS 1332 Data Structures & Algorithms course. The implementation is maintained in a private repository in accordance with course academic integrity policies. This public repository contains a high-level project overview only.
  
