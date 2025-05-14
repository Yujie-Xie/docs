---
title: TiCDC Glossary
summary: Learn the terms about TiCDC and their definitions.
---

# TiCDC Glossary {#ticdc-glossary}

This glossary provides TiCDC-related terms and definitions. These terms appear in TiCDC logs, monitoring metrics, configurations, and documents.

For TiDB-related terms and definitions, refer to [TiDB glossary](/glossary.md).

## C {#c}

### Capture {#capture}

A single TiCDC instance on which the replication task of the cluster runs. Multiple captures form a TiCDC cluster.

### Changed data {#changed-data}

The data to be written to TiCDC from the upstream TiDB cluster, including the DML-caused data changes and the DDL-caused table schema changes.

### Changefeed {#changefeed}

An incremental replication task in TiCDC, which outputs the data change logs of several tables in a TiDB cluster to the designated downstream.

## O {#o}

### Owner {#owner}

A [capture](#capture) of a special role that manages the TiCDC cluster and schedules replication tasks of the cluster. An owner is elected by captures and there is at most one owner at any time.

## P {#p}

### Processor {#processor}

TiCDC replication tasks allocate data tables on TiCDC instances, and the processor refers to the replication processing unit of these tables. Processor tasks include pulling, sorting, restoring, and distributing changed data.
