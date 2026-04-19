# Google Cloud Storage (gcp-cloud-storage)
Object storage service offering high durability, availability, and scalability for storing and accessing data on Google Cloud Platform.

**URL:** [Visit APIs.json URL](https://cloud.google.com/storage)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Archival, Backup, Blob Storage, Cloud Storage, Data, File Storage, Google Cloud, Object Storage, Storage

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Google Cloud Storage JSON API
RESTful API for interacting with Google Cloud Storage buckets and objects.

**Human URL:** [https://cloud.google.com/storage/docs/json_api](https://cloud.google.com/storage/docs/json_api)

#### Tags:

 - Buckets, Objects, Access Control, IAM, Storage

#### Properties

- [Documentation](https://cloud.google.com/storage/docs/json_api)
- [OpenAPI](openapi/gcp-cloud-storage-json-api-openapi.yml)
- [Authentication](https://cloud.google.com/storage/docs/authentication)
- [Pricing](https://cloud.google.com/storage/pricing)
- [RateLimits](https://cloud.google.com/storage/quotas)
- [APIReference](https://cloud.google.com/storage/docs/json_api/v1)

### Google Cloud Storage XML API
Amazon S3-compatible XML API for Google Cloud Storage.

**Human URL:** [https://cloud.google.com/storage/docs/xml-api](https://cloud.google.com/storage/docs/xml-api)

#### Tags:

 - S3 Compatible, XML, Interoperability

#### Properties

- [Documentation](https://cloud.google.com/storage/docs/xml-api/overview)
- [Authentication](https://cloud.google.com/storage/docs/authentication/hmackeys)
- [APIReference](https://cloud.google.com/storage/docs/xml-api/reference-methods)

## Common Properties

- [GettingStarted](https://cloud.google.com/storage/docs/quickstarts)
- [SDK](https://cloud.google.com/storage/docs/reference/libraries)
- [Console](https://console.cloud.google.com/storage)
- [Blog](https://cloud.google.com/blog/products/storage-data-transfer)
- [ChangeLog](https://cloud.google.com/storage/docs/release-notes)
- [BestPractices](https://cloud.google.com/storage/docs/best-practices)
- [Security](https://cloud.google.com/storage/docs/security)
- [Compliance](https://cloud.google.com/security/compliance)
- [CLI](https://cloud.google.com/storage/docs/discover-object-storage-gsutil)

## Features

| Name | Description |
|------|-------------|
| Multi-Regional Storage | Store data across multiple regions for high availability and low-latency access worldwide. |
| Object Lifecycle Management | Automatically transition objects between storage classes or delete them based on configurable rules. |
| Versioning | Maintain multiple versions of objects for data protection and recovery. |
| Fine-Grained Access Control | Control access using IAM policies, ACLs, and signed URLs for secure data sharing. |
| Object Composition | Compose multiple objects into a single object without downloading and re-uploading data. |
| Change Notifications | Watch for changes to objects in a bucket and receive push notifications. |
| Retention Policies | Lock retention policies to prevent object deletion for regulatory compliance. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Lake Storage | Store structured and unstructured data at scale for analytics and machine learning pipelines. |
| Backup and Disaster Recovery | Store backups with configurable retention and cross-region replication for business continuity. |
| Static Website Hosting | Serve static web content directly from Cloud Storage buckets with custom domains. |
| Media Content Delivery | Store and serve media assets with CDN integration for low-latency content delivery. |

## Integrations

| Name | Description |
|------|-------------|
| BigQuery | Load data directly from Cloud Storage into BigQuery for analytics and data warehousing. |
| Cloud Functions | Trigger serverless functions on object creation, deletion, or metadata changes. |
| Dataflow | Process data stored in Cloud Storage using Apache Beam pipelines. |
| Transfer Service | Transfer data between on-premises storage, other clouds, and Cloud Storage. |
| Cloud CDN | Cache and serve Cloud Storage content through Google's global edge network. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [GCP Cloud Storage JSON API OpenAPI](openapi/gcp-cloud-storage-json-api-openapi.yml)

### JSON Schema

- [Bucket Schema](json-schema/gcp-cloud-storage-bucket-schema.json)
- [Object Schema](json-schema/gcp-cloud-storage-json-object-schema.json)
- [Policy Schema](json-schema/gcp-cloud-storage-json-policy-schema.json)

### JSON-LD

- [GCP Cloud Storage Context](json-ld/gcp-cloud-storage-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Google Cloud Storage JSON API](capabilities/shared/cloud-storage-json.yaml) — 11 operations for bucket, object, and IAM management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cloud Storage Management](capabilities/cloud-storage.yaml) | Cloud Storage JSON API | 11 | Cloud Engineer |

## Vocabulary

- [GCP Cloud Storage Vocabulary](vocabulary/gcp-cloud-storage-vocabulary.yaml)

## Rules

- [GCP Cloud Storage Spectral Rules](rules/gcp-cloud-storage-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
