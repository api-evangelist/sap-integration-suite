# SAP Integration Suite

SAP Integration Suite is an enterprise integration platform as a service (iPaaS) that connects applications, processes, and people across cloud and on-premises environments. It includes capabilities for Cloud Integration, API Management, Integration Advisor, Open Connectors, Trading Partner Management, and Event Mesh as part of SAP Business Technology Platform (BTP).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/apis.yml)

- **Website:** https://www.sap.com/products/technology-platform/integration-suite.html
- **Documentation:** https://help.sap.com/docs/integration-suite
- **API Portal:** https://api.sap.com/
- **Community:** https://community.sap.com/topics/integration-suite

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Enterprise Integration, iPaaS, SAP, API Management, Cloud Integration, Event Mesh, SAP BTP

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## APIs

### SAP Cloud Integration API

The SAP Cloud Integration API (Process Integration Runtime API) provides OData V2 endpoints for deploying, monitoring, and managing integration flows, artifacts, packages, message processing logs, and service endpoints.

**Human URL:** https://help.sap.com/docs/integration-suite/sap-integration-suite/cloud-integration

**Tags:** Cloud Integration, Integration Flows, OData, Runtime Monitoring

**Properties**

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/cloud-integration)
- [Reference](https://api.sap.com/api/CloudIntegrationAPI/overview)
- [OpenAPI](openapi/sap-integration-suite-cloud-integration-openapi.yml)
- [JSONSchema](json-schema/sap-integration-suite-integration-package-schema.json)
- [JSONSchema](json-schema/sap-integration-suite-message-processing-log-schema.json)
- [JSONLD](json-ld/sap-integration-suite-context.jsonld)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication)

### SAP API Management API

The SAP API Management API enables programmatic management of APIs, products, applications, and developer portals within SAP Integration Suite. Supports creating and publishing API proxies, managing rate plans, and administering the full API lifecycle.

**Human URL:** https://help.sap.com/docs/integration-suite/sap-integration-suite/api-management-capability

**Tags:** API Management, API Gateway, Developer Portal, API Proxy, OData

**Properties**

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/api-management-capability)
- [Reference](https://api.sap.com/api/APIMgmt/overview)
- [OpenAPI](openapi/sap-integration-suite-api-management-openapi.yml)
- [JSONLD](json-ld/sap-integration-suite-context.jsonld)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication)

### SAP Integration Advisor API

The SAP Integration Advisor API provides access to the library of message implementation guidelines (MIGs) and mapping guidelines (MAGs) for B2B and A2A integration scenarios.

**Human URL:** https://help.sap.com/docs/integration-suite/sap-integration-suite/integration-advisor-capability

**Tags:** Integration Advisor, B2B Integration, EDI, Mapping Guidelines, Message Implementation Guidelines

**Properties**

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/integration-advisor-capability)
- [Reference](https://api.sap.com/api/IntegrationAdvisor/overview)

### SAP Open Connectors API

The SAP Open Connectors API provides a unified REST interface to connect to over 160 third-party cloud applications using pre-built connectors.

**Human URL:** https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability

**Tags:** Open Connectors, Third-Party Integration, Unified API, Cloud Connectors, Normalization

**Properties**

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability)
- [Reference](https://api.sap.com/api/OpenConnectors/overview)

### SAP Trading Partner Management API

The SAP Trading Partner Management API supports setup and management of B2B trading partner relationships, agreements, EDI and AS2 communication channels.

**Human URL:** https://help.sap.com/docs/integration-suite/sap-integration-suite/trading-partner-management-capability

**Tags:** Trading Partner Management, B2B, EDI, AS2

**Properties**

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/trading-partner-management-capability)
- [Reference](https://api.sap.com/api/TradingPartnerManagement/overview)

### SAP Event Mesh API

The SAP Event Mesh API provides access to the event brokering service on BTP for asynchronous event-driven communication using CloudEvents, AMQP, and MQTT.

**Human URL:** https://help.sap.com/docs/event-mesh

**Tags:** Event Mesh, Messaging, Pub/Sub, Asynchronous, CloudEvents

**Properties**

- [Documentation](https://help.sap.com/docs/event-mesh)
- [Reference](https://api.sap.com/api/SAPEventMesh/overview)

### SAP Integration Suite Advanced Event Mesh API

The SAP Integration Suite Advanced Event Mesh REST API provides management capabilities for event brokers, message queues, and topic subscriptions.

**Human URL:** https://help.pubsub.em.services.cloud.sap/Cloud/cloud-rest-api-lp.htm

**Tags:** Advanced Event Mesh, Broker Management, Event Streaming, Messaging

**Properties**

- [Documentation](https://help.pubsub.em.services.cloud.sap/Cloud/cloud-rest-api-lp.htm)
- [Reference](https://api.sap.com/package/SAPIIntegrationSuiteAdvancedEventMesh/rest)

## OpenAPI Specifications

- [openapi/sap-integration-suite-cloud-integration-openapi.yml](openapi/sap-integration-suite-cloud-integration-openapi.yml) — SAP Cloud Integration OData V2 API
- [openapi/sap-integration-suite-api-management-openapi.yml](openapi/sap-integration-suite-api-management-openapi.yml) — SAP API Management REST API

## Capabilities

### Shared Definitions

- [capabilities/shared/cloud-integration.yaml](capabilities/shared/cloud-integration.yaml) — Cloud Integration consumed definition with 9 operations
- [capabilities/shared/api-management.yaml](capabilities/shared/api-management.yaml) — API Management consumed definition with 8 operations

### Workflow Capabilities

| Capability | Description | APIs | Tools |
|-----------|-------------|------|-------|
| [integration-lifecycle.yaml](capabilities/integration-lifecycle.yaml) | Complete integration lifecycle management: artifact deployment, monitoring, API proxy governance, developer portal | Cloud Integration + API Management | 16 |

## Rules

- [rules/sap-integration-suite-rules.yml](rules/sap-integration-suite-rules.yml) — Spectral ruleset enforcing SAP OData naming conventions and documentation standards

## JSON Schema

- [json-schema/sap-integration-suite-integration-package-schema.json](json-schema/sap-integration-suite-integration-package-schema.json)
- [json-schema/sap-integration-suite-message-processing-log-schema.json](json-schema/sap-integration-suite-message-processing-log-schema.json)

## JSON Structure

- [json-structure/sap-integration-suite-integration-package-structure.json](json-structure/sap-integration-suite-integration-package-structure.json)

## JSON-LD

- [json-ld/sap-integration-suite-context.jsonld](json-ld/sap-integration-suite-context.jsonld)

## Examples

- [examples/sap-integration-suite-list-integration-packages-example.json](examples/sap-integration-suite-list-integration-packages-example.json)
- [examples/sap-integration-suite-list-message-processing-logs-example.json](examples/sap-integration-suite-list-message-processing-logs-example.json)

## Vocabulary

- [vocabulary/sap-integration-suite-vocabulary.yml](vocabulary/sap-integration-suite-vocabulary.yml)

## Common Properties

- [Portal](https://api.sap.com/)
- [Documentation](https://help.sap.com/docs/integration-suite)
- [Website](https://www.sap.com/products/technology-platform/integration-suite.html)
- [Getting Started](https://help.sap.com/docs/integration-suite/sap-integration-suite/what-is-sap-integration-suite)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication)
- [Blog](https://blogs.sap.com/tags/73554900100700002542/)
- [Community](https://community.sap.com/topics/integration-suite)
- [Support](https://support.sap.com/en/product/support-by-product/73554900100700002542.html)
- [Status](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [GitHub Organization](https://github.com/SAP-samples)
- [Terms of Service](https://www.sap.com/about/agreements/policies/cloud-platform.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [YouTube](https://www.youtube.com/@SAPTechnology)
- [Pricing](https://www.sap.com/products/technology-platform/integration-suite/pricing.html)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
