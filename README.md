# Google Cloud Storage (gcp-cloud-storage)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Object storage service offering high durability, availability, and scalability for storing and accessing data on Google Cloud Platform.

**APIs.json:** [https://cloud.google.com/storage](https://cloud.google.com/storage)

## Tags

- Archival
- Backup
- Blob Storage
- Cloud Storage
- Data
- File Storage
- Google Cloud
- Object Storage
- Storage

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Google Cloud Storage JSON API

RESTful API for interacting with Google Cloud Storage buckets and objects.

- **Human URL:** [https://cloud.google.com/storage/docs/json_api](https://cloud.google.com/storage/docs/json_api)
- **Base URL:** `https://storage.googleapis.com/storage/v1`

#### Tags

- Buckets
- Objects
- Access Control
- IAM
- Storage

#### Properties

- [Documentation](https://cloud.google.com/storage/docs/json_api)
- [OpenAPI](https://storage.googleapis.com/$discovery/rest?version=v1) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/gcp-cloud-storage-json-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcp-cloud-storage-json-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcp-cloud-storage-json-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://cloud.google.com/storage/docs/authentication)
- [Pricing](https://cloud.google.com/storage/pricing)
- [Rate Limits](https://cloud.google.com/storage/quotas)
- [Status Page](https://status.cloud.google.com/)
- [Terms of Service](https://cloud.google.com/terms)
- [API Reference](https://cloud.google.com/storage/docs/json_api/v1)
- [JSON Schema](json-schema/gcp-cloud-storage-bucket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-bucket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-bucket-access-control-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-bucket-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-channel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-compose-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-object-access-control-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-object-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gcp-cloud-storage-json-rewrite-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/gcp-cloud-storage-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/gcp-cloud-storage-json-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Google Cloud Storage XML API

Amazon S3-compatible XML API for Google Cloud Storage.

- **Human URL:** [https://cloud.google.com/storage/docs/xml-api](https://cloud.google.com/storage/docs/xml-api)
- **Base URL:** `https://storage.googleapis.com`

#### Tags

- S3 Compatible
- XML
- Interoperability

#### Properties

- [Documentation](https://cloud.google.com/storage/docs/xml-api/overview)
- [Authentication](https://cloud.google.com/storage/docs/authentication/hmackeys)
- [API Reference](https://cloud.google.com/storage/docs/xml-api/reference-methods)
- [Pricing](https://cloud.google.com/storage/pricing)
- [Rate Limits](https://cloud.google.com/storage/quotas)
- [Terms of Service](https://cloud.google.com/terms)
- [Postman Collection](collections/gcp-cloud-storage-json-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcp-cloud-storage-json-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/GoogleCloudPlatform)
- [Getting Started](https://cloud.google.com/storage/docs/quickstarts)
- [SDK](https://cloud.google.com/storage/docs/reference/libraries)
- [Console](https://console.cloud.google.com/storage)
- [Blog](https://cloud.google.com/blog/products/storage-data-transfer)
- [Changelog](https://cloud.google.com/storage/docs/release-notes)
- [Best Practices](https://cloud.google.com/storage/docs/best-practices)
- [Security](https://cloud.google.com/storage/docs/security)
- [Compliance](https://cloud.google.com/security/compliance)
- [API Reference](https://cloud.google.com/storage/docs/apis)
- [C L I](https://cloud.google.com/storage/docs/discover-object-storage-gsutil)
- [Spectral Rules](rules/gcp-cloud-storage-spectral-rules.yml)
- [Vocabulary](vocabulary/gcp-cloud-storage-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://cloud.google.com/marketplace)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
