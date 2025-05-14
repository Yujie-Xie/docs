---
title: Overview of Key Concepts
summary: Learn about the key concepts in TiDB Cloud.
---

# Overview of Key Concepts {#overview-of-key-concepts}

This document provides an overview of the key concepts in [TiDB Cloud](https://www.pingcap.com/tidb-cloud/). Understanding these concepts helps you better use TiDB Cloud features and capabilities.

## Architecture {#architecture}

TiDB Cloud is built on a cloud-native distributed architecture that separates computing from storage, enabling elastic scaling and high availability. [Learn more about TiDB Cloud architecture](/tidb-cloud/architecture-concepts.md).

## Database schema {#database-schema}

TiDB Cloud enables you to organize and structure your data using objects such as databases, tables, columns, indexes, and constraints. It also supports advanced features such as temporary tables, vector indexes, and cached tables. [Learn more about database schema](/tidb-cloud/database-schema-concepts.md).

## Transactions {#transactions}

TiDB provides complete distributed transactions, and the model has some optimizations on the basis of [Google Percolator](https://research.google.com/pubs/pub36726.html). [Learn more about transactions](/tidb-cloud/transaction-concepts.md).

## SQL {#sql}

TiDB is highly compatible with the MySQL protocol and the common features and syntax of MySQL 5.7 and MySQL 8.0. [Learn more about SQL in TiDB Cloud](/tidb-cloud/sql-concepts.md).

## AI features {#ai-features}

The AI features in TiDB Cloud enable you to fully leverage advanced technologies for data exploration, search, and integration. [Learn more about AI features](/tidb-cloud/ai-feature-concepts.md).

## Data Service (Beta) {#data-service-beta}

Data Service enables you to access TiDB Cloud data via an HTTPS request using a custom API endpoint. [Learn more about Data Service](/tidb-cloud/data-service-concepts.md).

## Scalability {#scalability}

TiDB Cloud Dedicated lets you adjust its compute and storage resources separately to match your data volume or workload changes. [Learn more about scalability](/tidb-cloud/scalability-concepts.md).

## High availability {#high-availability}

TiDB Cloud ensures high availability in both TiDB Cloud Serverless and TiDB Cloud Dedicated clusters:

-   [High Availability in TiDB Cloud Serverless](/tidb-cloud/serverless-high-availability.md)
-   [High Availability in TiDB Cloud Dedicated](/tidb-cloud/high-availability-with-multi-az.md)

## Monitoring {#monitoring}

TiDB Cloud provides comprehensive monitoring capabilities for cluster performance and health. [Learn more about monitoring](/tidb-cloud/monitoring-concepts.md).

## Data streaming {#data-streaming}

TiDB Cloud lets you stream data changes from your TiDB Cluster to other systems such as Kafka, MySQL, and object storage. [Learn more about data streaming](/tidb-cloud/data-streaming-concepts.md).

## Backup &#x26; Restore {#backup-x26-restore}

TiDB Cloud offers automated backup solutions and point-in-time recovery (PITR) capabilities. [Learn more about backup and restore](/tidb-cloud/backup-and-restore-concepts.md).

## Security {#security}

TiDB Cloud provides a robust and flexible security framework designed to protect data, enforce access control, and meet modern compliance standards. [Learn more about security](/tidb-cloud/security-concepts.md).
