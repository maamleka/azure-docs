---
title: Azure Resource Manager templates for Azure Cosmos DB
description: Use Azure Resource Manager templates to create and configure Azure Cosmos DB. 
author: markjbrown
ms.service: cosmos-db
ms.topic: conceptual
ms.date: 05/06/2019
ms.author: mjbrown
---

# Azure Resource Manager templates for Azure Cosmos DB

The following table includes links to Azure Resource Manager templates for Azure Cosmos DB:

|**API type** | **link to sample**| **Description** |
|---|---| ---|
|Core (SQL) API| [Create an Azure Cosmos DB account (multi-master)](manage-sql-with-resource-manager.md) | This template creates a SQL API account in two regions with multi-master enabled. The Azure Cosmos account will have two containers that share database-level throughput. |
| MongoDB API | [Create an Azure Cosmos DB account (multi-master)](manage-mongodb-with-resource-manager.md) | This template creates an account using Azure Cosmos DB's API for MongoDB in two regions with multi-master enabled. The Azure Cosmos account will have two containers that share database-level throughput. |
| Cassandra API | [Create an Azure Cosmos DB account (multi-master)](manage-cassandra-with-resource-manager.md) | This template creates a Cassandra API account in two regions with multi-master enabled. The Azure Cosmos account will have two tables that share keyspace-level throughput. |
| Gremlin API| [Create an Azure Cosmos DB account (multi-master)](manage-gremlin-with-resource-manager.md) | This template creates a Gremlin API account in two regions with multi-master enabled. The Azure Cosmos account will have two graphs that share database-level throughput. |
| Table API | [Create an Azure Cosmos DB account (multi-master)](manage-table-with-resource-manager.md) | This template  creates a Table API account in two regions with multi-master enabled. The Azure Cosmos account will have a single table. |

> [!TIP]
> To enable shared throughput when using Table API, enable account-level throughput in the Azure Portal.

See [ARM reference for Azure Cosmos DB](/azure/templates/microsoft.documentdb/allversions) page for the reference documentation.