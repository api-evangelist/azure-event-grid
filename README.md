# Azure Event Grid (azure-event-grid)

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

Azure Event Grid is a fully managed event routing service from Microsoft Azure that enables event-driven, reactive programming by ingesting events from Azure services, SaaS providers, and custom sources and delivering them to subscribers such as Azure Functions, Logic Apps, webhooks, and event hubs. It supports both Event Grid topics and the MQTT/CloudEvents-based Event Grid namespaces for IoT and pub-sub workloads. The Event Grid REST APIs and Azure SDKs use Microsoft Entra ID OAuth 2.0 bearer tokens or shared-access keys for authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/azure-event-grid/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/azure-event-grid/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Eventing
- Event Driven
- Pub Sub
- Messaging
- Webhooks
- CloudEvents
- Cloud
- Azure

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Azure Event Grid Publisher API

Data-plane REST API for publishing events and CloudEvents to Event Grid topics and domains, and for managing namespace topics, subscriptions, and event delivery. Authentication uses Microsoft Entra ID OAuth 2.0 bearer tokens or shared-access keys via the aeg-sas-key header.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/eventgrid/](https://learn.microsoft.com/en-us/rest/api/eventgrid/)
- **Base URL:** `https://{topic-endpoint}.{region}.eventgrid.azure.net`

#### Tags

- Event Grid
- Publishing
- CloudEvents
- Webhooks
- Azure

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/eventgrid/)
- [Control  Plane  A P I](https://learn.microsoft.com/en-us/rest/api/eventgrid/controlplane-version2025-02-15/)
- [Data  Plane  A P I](https://learn.microsoft.com/en-us/rest/api/eventgrid/dataplane/)
- [Postman Collection](collections/azure-event-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-event-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://azure.microsoft.com/en-us/products/event-grid/)
- [Documentation](https://learn.microsoft.com/en-us/azure/event-grid/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/event-grid/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)
- [L L Ms Txt](https://azure.microsoft.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
