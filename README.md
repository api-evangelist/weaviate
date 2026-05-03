# Weaviate (weaviate)
Weaviate is an open-source, AI-native vector database that enables developers to build semantic search and AI-powered applications. It stores data as vector embeddings alongside structured properties, enabling lightning-fast similarity search using HNSW or flat indexes. Weaviate supports multi-tenancy, automatic vectorization via configurable modules, GraphQL and REST APIs, and enterprise features including authentication, authorization, backups, and replication.

**URL:** [https://weaviate.io/developers/weaviate/api/rest](https://weaviate.io/developers/weaviate/api/rest)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Vector Database, AI, Machine Learning, Semantic Search, Open Source, GraphQL, Kubernetes

## Timestamps

- **Created:** 2024-06-18
- **Modified:** 2026-05-03

## APIs

### Weaviate REST API
The Weaviate REST API provides full programmatic access to vector database operations including object CRUD, schema management, GraphQL vector search, multi-tenancy, backups, authentication, authorization, and cluster management.

**Human URL:** [https://weaviate.io/developers/weaviate/api/rest](https://weaviate.io/developers/weaviate/api/rest)

#### Tags:

 - Vector Database, Objects, Schema, GraphQL, Search, AI

#### Properties

- [Weaviate OpenAPI](openapi/weaviate-openapi.yml)
- [Documentation](https://weaviate.io/developers/weaviate/api/rest)
- [Getting Started](https://weaviate.io/developers/weaviate/quickstart)

## Common Properties

- [Documentation](https://weaviate.io/developers/weaviate/api/rest)
- [GitHub Repository](https://github.com/weaviate/weaviate)
- [GitHub Organization](https://github.com/weaviate)
- [Getting Started](https://weaviate.io/developers/weaviate/quickstart)
- [Learn](https://weaviate.io/developers/academy)
- [Blog](https://weaviate.io/blog)
- [Community](https://weaviate.io/community)
- [Forum](https://forum.weaviate.io/)
- [Slack](https://weaviate.io/slack)
- [Pricing](https://weaviate.io/pricing)
- [Podcast](https://weaviate.io/podcast)
- [Newsletter](https://newsletter.weaviate.io/)
- [Events](https://weaviate.io/community/events)
- [Terms of Service](https://github.com/weaviate/weaviate/blob/master/LICENSE)
- [Security](https://weaviate.io/security)
- [Change Log](https://github.com/weaviate/weaviate/blob/master/CHANGELOG.md)
- [Support](https://github.com/weaviate/weaviate/issues)

## Features

| Name | Description |
|------|-------------|
| Vector Storage | Stores data objects alongside their vector embeddings for high-performance similarity search using HNSW or flat indexes. |
| GraphQL Search API | Powerful GraphQL interface for vector similarity search (nearVector, nearText, nearObject, nearImage), hybrid search, and filtered queries. |
| Automatic Vectorization | Pluggable vectorizer modules (text2vec, img2vec, etc.) automatically generate embeddings from object properties at write time. |
| Multi-Tenancy | Native multi-tenancy support with tenant isolation, allowing a single Weaviate instance to serve multiple customers with separate data. |
| Schema Management | Flexible schema with class and property definitions, cross-references, vector index configuration, and property-level vectorization settings. |
| Backup and Restore | Backup data to S3, GCS, Azure Blob Storage, or local filesystem and restore on demand for disaster recovery. |
| Authorization and RBAC | Role-based access control with fine-grained permissions for collections, objects, and operations. Supports API key and OIDC/JWT authentication. |
| Kubernetes and Cloud Native | Production-ready Kubernetes Helm chart with support for horizontal scaling, high availability, and major cloud providers. |

## Use Cases

| Name | Description |
|------|-------------|
| Semantic Search | Build semantic and hybrid search applications using vector similarity and BM25 keyword search combined. |
| RAG Applications | Power Retrieval Augmented Generation (RAG) pipelines by storing and retrieving relevant context for large language model prompts. |
| Multi-Modal Search | Search across text, images, and other modalities using unified vector representations. |
| AI-Powered Recommendations | Build recommendation engines using object similarity search to find related items based on vector proximity. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Weaviate REST API OpenAPI](openapi/weaviate-openapi.yml)

### JSON Schema

108 JSON Schema files covering Weaviate objects, schema, backup, node, classification, and authentication schemas.

### JSON Structure

108 JSON Structure files (json-structure.org) converted from JSON Schema.

### JSON-LD

- [Weaviate JSON-LD Context](json-ld/weaviate-context.jsonld) — 108 type declarations and 294 property mappings

### Examples

108 example JSON files generated from schemas.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Weaviate REST API](capabilities/shared/weaviate-api.yaml) — 12 operations covering objects, schema, GraphQL, backups, and cluster management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Vector Database](capabilities/vector-database.yaml) | Weaviate REST API | 12 | AI Engineer, Platform Operator, Data Engineer |

## Vocabulary

- [Weaviate Vocabulary](vocabulary/weaviate-vocabulary.yml) — Unified taxonomy mapping 12 resources, 15 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Weaviate Spectral Rules](rules/weaviate-spectral-rules.yml) — 22 rules across 8 categories enforcing Weaviate API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
