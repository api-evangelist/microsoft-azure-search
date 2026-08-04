# Azure AI Search (microsoft-azure-search)

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

Azure AI Search (formerly Azure Cognitive Search) is a cloud search service with built-in AI capabilities for enriching content and enabling vector and semantic search over heterogeneous data. It indexes content from Azure data sources and supports full-text, faceted, geospatial, vector, and hybrid retrieval.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-azure-search/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-search/refs/heads/main/apis.yml)

## Tags

- AI Search
- Cognitive Search
- Hybrid Search
- Search
- Semantic Search
- Vector Search

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Azure AI Search REST API

Azure AI Search provides REST APIs for creating and managing search indexes, loading documents, running full-text and vector queries, configuring AI enrichment pipelines with skillsets, and managing indexers for automatic data ingestion from Azure data sources.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/searchservice/](https://learn.microsoft.com/en-us/rest/api/searchservice/)
- **Base URL:** `https://{search-service}.search.windows.net/`

#### Tags

- Indexers
- Indexes
- Search
- Skillsets
- Vector Search

#### Properties

- [OpenAPI](openapi/microsoft-azure-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-azure-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/searchservice/)
- [Authentication](https://learn.microsoft.com/en-us/azure/search/search-security-api-keys)
- [Versioning](https://learn.microsoft.com/en-us/rest/api/searchservice/search-service-api-versions)

### Azure AI Search Management REST API

The management REST API provides operations for creating and managing Azure AI Search service instances, scaling replicas and partitions, and managing keys and shared private link resources.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/searchmanagement/](https://learn.microsoft.com/en-us/rest/api/searchmanagement/)
- **Base URL:** `https://management.azure.com/`

#### Tags

- Management
- Provisioning
- Search

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/searchmanagement/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-flows-app-scenarios)
- [Postman Collection](collections/microsoft-azure-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Azure)
- [Portal](https://portal.azure.com/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/search/)
- [Documentation](https://learn.microsoft.com/en-us/azure/search/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/search/search-get-started-portal)
- [S D Ks](https://learn.microsoft.com/en-us/azure/search/search-howto-dotnet-sdk)
- [Status Page](https://azure.status.microsoft/en-us/status)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://support.microsoft.com/)
- [Blog](https://azure.microsoft.com/en-us/blog/product/azure-cognitive-search/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-cognitive-search)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
