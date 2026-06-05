# Azure Event Grid (azure-event-grid)

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
