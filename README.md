# SAP Integration Suite (sap-integration-suite)

SAP Integration Suite is an enterprise integration platform as a service (iPaaS) that connects applications, processes, and people across cloud and on-premises environments. It includes capabilities for Cloud Integration, API Management, Integration Advisor, Open Connectors, Trading Partner Management, and Event Mesh as part of SAP Business Technology Platform (BTP). It enables seamless connectivity between SAP and non-SAP systems.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Management
- Cloud Integration
- Enterprise Integration
- Event Mesh
- iPaaS
- SAP
- SAP BTP

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### SAP Cloud Integration API

The SAP Cloud Integration API (Process Integration Runtime API) allows developers to deploy, monitor, and manage integration flows and artifacts on SAP Integration Suite. It provides OData V2 endpoints for runtime monitoring, message processing logs, artifact lifecycle management, integration package management, and service endpoint discovery.

- **Human URL:** [https://help.sap.com/docs/integration-suite/sap-integration-suite/cloud-integration](https://help.sap.com/docs/integration-suite/sap-integration-suite/cloud-integration)
- **Base URL:** `https://{host}/api/v1`

#### Tags

- Cloud Integration
- Integration Flows
- OData
- Runtime Monitoring

#### Properties

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/cloud-integration)
- [Reference](https://api.sap.com/api/CloudIntegrationAPI/overview)
- [OpenAPI](openapi/sap-integration-suite-cloud-integration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-integration-suite-cloud-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-cloud-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-integration-suite-integration-package-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-integration-suite-message-processing-log-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-integration-suite-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication)

### SAP API Management API

The SAP API Management API enables programmatic management of APIs, products, applications, and developer portals within SAP Integration Suite. It supports creating and publishing API proxies, managing rate plans, administering the full API lifecycle, configuring policies, and managing developer portal content. Built on REST and OData principles.

- **Human URL:** [https://help.sap.com/docs/integration-suite/sap-integration-suite/api-management-capability](https://help.sap.com/docs/integration-suite/sap-integration-suite/api-management-capability)
- **Base URL:** `https://{api-portal-host}/apiportal/api/1.0`

#### Tags

- API Gateway
- API Management
- API Proxy
- Developer Portal
- OData

#### Properties

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/api-management-capability)
- [Reference](https://api.sap.com/api/APIMgmt/overview)
- [OpenAPI](openapi/sap-integration-suite-api-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-integration-suite-api-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-api-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-integration-suite-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication)

### SAP Integration Advisor API

The SAP Integration Advisor API provides access to the library of message implementation guidelines (MIGs) and mapping guidelines (MAGs) used to simplify B2B and A2A integration scenarios. It supports querying and managing integration content including type systems, business context, and codelists in the Integration Advisor capability.

- **Human URL:** [https://help.sap.com/docs/integration-suite/sap-integration-suite/integration-advisor-capability](https://help.sap.com/docs/integration-suite/sap-integration-suite/integration-advisor-capability)
- **Base URL:** `https://{host}/api`

#### Tags

- B2B Integration
- EDI
- Integration Advisor
- Mapping Guidelines
- Message Implementation Guidelines

#### Properties

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/integration-advisor-capability)
- [Reference](https://api.sap.com/api/IntegrationAdvisor/overview)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication)
- [Postman Collection](collections/sap-integration-suite-api-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-api-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-integration-suite-cloud-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-cloud-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Open Connectors API

The SAP Open Connectors API (formerly Cloud Elements) provides a unified REST interface to connect to over 160 third-party cloud applications using pre-built connectors. It normalizes disparate API endpoints into consistent resource models for faster integration development. Connectors are available for CRM, ERP, marketing, storage, and collaboration platforms.

- **Human URL:** [https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability](https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability)
- **Base URL:** `https://api.openconnectors.ext.hana.ondemand.com`

#### Tags

- Cloud Connectors
- Normalization
- Open Connectors
- Third-Party Integration
- Unified API

#### Properties

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability)
- [Reference](https://api.sap.com/api/OpenConnectors/overview)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability)
- [Postman Collection](collections/sap-integration-suite-api-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-api-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-integration-suite-cloud-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-cloud-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Trading Partner Management API

The SAP Trading Partner Management API supports setup and management of B2B trading partner relationships, agreements, and communication channels within SAP Integration Suite. It enables automation of partner onboarding, maintenance of EDI and AS2 communication profiles, and management of certificates and agreements.

- **Human URL:** [https://help.sap.com/docs/integration-suite/sap-integration-suite/trading-partner-management-capability](https://help.sap.com/docs/integration-suite/sap-integration-suite/trading-partner-management-capability)
- **Base URL:** `https://{host}/api`

#### Tags

- AS2
- B2B
- EDI
- Trading Partner Management

#### Properties

- [Documentation](https://help.sap.com/docs/integration-suite/sap-integration-suite/trading-partner-management-capability)
- [Reference](https://api.sap.com/api/TradingPartnerManagement/overview)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication)
- [Postman Collection](collections/sap-integration-suite-api-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-api-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-integration-suite-cloud-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-cloud-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Event Mesh API

The SAP Event Mesh API provides access to the event brokering service within SAP Business Technology Platform that enables applications to communicate through asynchronous events. It supports publishing and subscribing to events across SAP and third-party applications using CloudEvents standard and AMQP/MQTT/HTTP protocols.

- **Human URL:** [https://help.sap.com/docs/event-mesh](https://help.sap.com/docs/event-mesh)
- **Base URL:** `https://enterprise-messaging.cfapps.sap.hana.ondemand.com`

#### Tags

- Asynchronous
- CloudEvents
- Event Mesh
- Messaging
- Pub/Sub

#### Properties

- [Documentation](https://help.sap.com/docs/event-mesh)
- [Reference](https://api.sap.com/api/SAPEventMesh/overview)
- [Authentication](https://help.sap.com/docs/event-mesh/sap-event-mesh/authentication-and-authorization)
- [Postman Collection](collections/sap-integration-suite-api-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-api-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-integration-suite-cloud-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-cloud-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Integration Suite Advanced Event Mesh API

The SAP Integration Suite Advanced Event Mesh (AEM) REST API provides management capabilities for event brokers, message queues, topic subscriptions, and event broker services. It enables programmatic management of messaging infrastructure including creation and monitoring of event brokers and messaging services.

- **Human URL:** [https://help.pubsub.em.services.cloud.sap/Cloud/cloud-rest-api-lp.htm](https://help.pubsub.em.services.cloud.sap/Cloud/cloud-rest-api-lp.htm)
- **Base URL:** `https://api.solacecloud.com/api/v2`

#### Tags

- Advanced Event Mesh
- Broker Management
- Event Streaming
- Messaging
- REST

#### Properties

- [Documentation](https://help.pubsub.em.services.cloud.sap/Cloud/cloud-rest-api-lp.htm)
- [Reference](https://api.sap.com/package/SAPIIntegrationSuiteAdvancedEventMesh/rest)
- [Authentication](https://help.pubsub.em.services.cloud.sap/Cloud/ght_use_rest_api_services.htm)
- [Postman Collection](collections/sap-integration-suite-api-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-api-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-integration-suite-cloud-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-integration-suite-cloud-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://api.sap.com/)
- [Documentation](https://help.sap.com/docs/integration-suite)
- [Website](https://www.sap.com/products/technology-platform/integration-suite.html)
- [Getting Started](https://help.sap.com/docs/integration-suite/sap-integration-suite/what-is-sap-integration-suite)
- [Authentication](https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication)
- [Blog](https://blogs.sap.com/tags/73554900100700002542/)
- [Community](https://community.sap.com/topics/integration-suite)
- [Support](https://support.sap.com/en/product/support-by-product/73554900100700002542.html)
- [Status Page](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [GitHub Organization](https://github.com/SAP-samples)
- [Terms of Service](https://www.sap.com/about/agreements/policies/cloud-platform.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [YouTube](https://www.youtube.com/@SAPTechnology)
- [Pricing](https://www.sap.com/products/technology-platform/integration-suite/pricing.html)
- [Tutorials](https://developers.sap.com/tutorial-navigator.html?tag=software-product%3Atechnology-platform%2Fsap-integration-suite)
- [Vocabulary](vocabulary/sap-integration-suite-vocabulary.yml)
- [Capabilities](capabilities/integration-lifecycle.yaml)
- [Spectral Rules](rules/sap-integration-suite-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
