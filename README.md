# Adobe Experience Cloud
Adobe Experience Cloud is an integrated suite of applications and services for digital marketing, analytics, advertising, and commerce. It provides tools for content management, personalization, customer journey orchestration, audience segmentation, real-time customer data platforms, offer decisioning, and cross-channel campaign execution, enabling organizations to deliver personalized customer experiences at scale.

**URL:** [https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Customer Experience, Digital Marketing, Personalization, Campaign Management, Journey Orchestration

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Adobe Analytics 2.0 API
The Adobe Analytics 2.0 API provides programmatic access to Adobe Analytics reporting, management, and configuration capabilities. It enables developers to retrieve report data, manage report suites, configure calculated metrics, segments, and dimensions, and administer users and permissions within Adobe Analytics.

**Human URL:** [https://developer.adobe.com/analytics-apis/docs/2.0/](https://developer.adobe.com/analytics-apis/docs/2.0/)

#### Tags:

 - Analytics, Digital Marketing, Reporting

#### Properties

- [Documentation](https://developer.adobe.com/analytics-apis/docs/2.0/)
- [OpenAPI](openapi/adobe-analytics-api-openapi.yml)

### Adobe Experience Platform API
The Adobe Experience Platform API provides RESTful access to core platform services including data ingestion, unified profile management, identity resolution, dataset management, schema registry, query service, and segmentation for building real-time customer profiles and orchestrating data workflows.

**Human URL:** [https://developer.adobe.com/experience-platform-apis/](https://developer.adobe.com/experience-platform-apis/)

#### Tags:

 - Customer Profiles, Data Management, Platform

#### Properties

- [Documentation](https://developer.adobe.com/experience-platform-apis/)
- [OpenAPI](openapi/adobe-experience-platform-api-openapi.yml)

### Adobe Target API
The Adobe Target API provides programmatic access to Adobe Target for managing A/B tests, experience targeting, multivariate tests, automated personalization activities, audiences, offers, and real-time content delivery for website and application personalization.

**Human URL:** [https://developer.adobe.com/target/](https://developer.adobe.com/target/)

#### Tags:

 - Optimization, Personalization, Testing

#### Properties

- [Documentation](https://developer.adobe.com/target/)
- [OpenAPI](openapi/adobe-target-api-openapi.yml)

### Adobe Journey Optimizer API
The Adobe Journey Optimizer API enables programmatic management of customer journeys, campaigns, messages, offers, placements, and content templates across email, push, SMS, and in-app channels for orchestrating personalized multi-channel customer experiences.

**Human URL:** [https://developer.adobe.com/journey-optimizer-apis/](https://developer.adobe.com/journey-optimizer-apis/)

#### Tags:

 - Journey Orchestration, Messaging, Offer Decisioning

#### Properties

- [Documentation](https://developer.adobe.com/journey-optimizer-apis/)
- [OpenAPI](openapi/adobe-journey-optimizer-api-openapi.yml)

### Adobe Campaign API
The Adobe Campaign API provides RESTful access to Adobe Campaign for managing subscriber profiles, subscription services, marketing workflows, email deliveries, and real-time transactional messaging across email, SMS, and push notification channels.

**Human URL:** [https://developer.adobe.com/campaign-standard-apis/](https://developer.adobe.com/campaign-standard-apis/)

#### Tags:

 - Campaign Management, Email Marketing, Transactional Messaging

#### Properties

- [Documentation](https://developer.adobe.com/campaign-standard-apis/)
- [OpenAPI](openapi/adobe-campaign-api-openapi.yml)

### Adobe I/O Events
Adobe I/O Events enables developers to receive near-real-time notifications from Adobe services via webhooks and journal polling. Events are emitted when significant changes occur across Adobe Experience Cloud products for building reactive integrations and automated workflows.

**Human URL:** [https://developer.adobe.com/events/docs/](https://developer.adobe.com/events/docs/)

#### Tags:

 - Events, Integration, Webhooks

#### Properties

- [Documentation](https://developer.adobe.com/events/docs/)
- [AsyncAPI](asyncapi/adobe-io-events-asyncapi.yml)

## Common Properties

- [Portal](https://developer.adobe.com/)
- [Documentation](https://developer.adobe.com/developer-console/docs/guides/)
- [Documentation](https://developer.adobe.com/apis/)
- [Blog](https://blog.developer.adobe.com/)
- [Support](https://experienceleague.adobe.com/)
- [TermsOfService](https://www.adobe.com/legal/terms.html)
- [PrivacyPolicy](https://www.adobe.com/privacy.html)
- [StatusPage](https://status.adobe.com/)
- [Console](https://developer.adobe.com/console/)
- [SignUp](https://developer.adobe.com/)
- [GettingStarted](https://developer.adobe.com/developer-console/docs/guides/getting-started/)
- [GitHubOrganization](https://github.com/adobe)
- [YouTube](https://www.youtube.com/user/AdobeDeveloperTV)
- [ChangeLog](https://developer.adobe.com/events/docs/whats_new/)
- [SpectralRules](rules/adobe-experience-cloud-spectral-rules.yml)
- [NaftikoCapability](capabilities/customer-data-platform.yaml)
- [NaftikoCapability](capabilities/digital-marketing.yaml)
- [Vocabulary](vocabulary/adobe-experience-cloud-vocabulary.yaml)
- [JSON-LD](json-ld/adobe-experience-cloud-analytics-api-context.jsonld)
- [JSON-LD](json-ld/adobe-experience-cloud-campaign-api-context.jsonld)
- [JSON-LD](json-ld/adobe-experience-cloud-context.jsonld)
- [JSON-LD](json-ld/adobe-experience-cloud-experience-platform-api-context.jsonld)
- [JSON-LD](json-ld/adobe-experience-cloud-io-events-context.jsonld)
- [JSON-LD](json-ld/adobe-experience-cloud-journey-optimizer-api-context.jsonld)
- [JSON-LD](json-ld/adobe-experience-cloud-target-api-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Real-Time Customer Profiles | Build and query unified customer profiles from multiple data sources using the Experience Platform APIs. |
| Analytics Reporting | Retrieve dimensional reports, calculated metrics, and segment data from Adobe Analytics via REST API. |
| A/B and Multivariate Testing | Create, manage, and retrieve results for A/B tests and automated personalization activities via Adobe Target API. |
| Multi-Channel Campaign Execution | Orchestrate email, SMS, push, and in-app campaigns programmatically using Adobe Campaign and Journey Optimizer APIs. |
| Webhook Event Streaming | Subscribe to near-real-time events from all Adobe Experience Cloud products via Adobe I/O Events. |
| Offer Decisioning | Manage offers, placements, and decisioning rules for personalized content delivery using Journey Optimizer APIs. |
| Data Ingestion and Schema Registry | Ingest batch and streaming data and register schemas using Experience Platform APIs. |
| Identity Resolution | Resolve customer identities across devices and channels using Experience Platform Identity Service API. |
| Audience Segmentation | Create and evaluate audience segments using Experience Platform Segmentation Service API. |
| OAuth 2.0 and JWT Authentication | Secure all APIs using OAuth 2.0 server-to-server credentials via Adobe Developer Console. |

## Use Cases

| Name | Description |
|------|-------------|
| Customer Data Platform | Ingest data from multiple sources, resolve identities, and activate unified customer profiles for personalization. |
| Marketing Automation | Automate campaign creation, scheduling, and execution across email, SMS, and push channels using Campaign and Journey Optimizer APIs. |
| Digital Analytics Reporting | Extract Adobe Analytics data into custom dashboards, BI tools, and data warehouses via the Analytics 2.0 API. |
| Real-Time Personalization | Deliver personalized content and offers in real time using Adobe Target and Journey Optimizer APIs. |
| Event-Driven Workflows | Build reactive integrations that respond to Experience Cloud events such as profile updates, campaign completions, and audience changes. |
| Audience Activation | Create and activate audiences across paid media, email, and on-site channels using Experience Platform Segmentation API. |

## Integrations

| Name | Description |
|------|-------------|
| Salesforce | Sync customer data and campaign results between Adobe Experience Cloud and Salesforce CRM. |
| Microsoft Azure | Ingest data from Azure Data Lake and Blob Storage into Adobe Experience Platform. |
| Google BigQuery | Connect Google BigQuery datasets to Adobe Experience Platform for data ingestion and activation. |
| Workfront | Integrate Workfront project management with Adobe Experience Cloud for content workflow automation. |
| Marketo Engage | Sync lead data and campaign activities between Marketo Engage and Adobe Experience Cloud. |
| ServiceNow | Connect ServiceNow customer data with Adobe Experience Cloud for unified customer service experiences. |
| Snowflake | Connect Snowflake data warehouse to Experience Platform for federated audience composition. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Adobe Analytics Api Openapi](openapi/adobe-analytics-api-openapi.yml)
- [Adobe Campaign Api Openapi](openapi/adobe-campaign-api-openapi.yml)
- [Adobe Experience Platform Api Openapi](openapi/adobe-experience-platform-api-openapi.yml)
- [Adobe Journey Optimizer Api Openapi](openapi/adobe-journey-optimizer-api-openapi.yml)
- [Adobe Target Api Openapi](openapi/adobe-target-api-openapi.yml)

### AsyncAPI

- [Adobe Io Events Asyncapi](asyncapi/adobe-io-events-asyncapi.yml)

### JSON Schema

- [Adobe Experience Cloud Campaign.Json](json-schema/adobe-experience-cloud-campaign.json)
- [Adobe Experience Cloud Event.Json](json-schema/adobe-experience-cloud-event.json)
- [Adobe Experience Cloud Journey.Json](json-schema/adobe-experience-cloud-journey.json)
- [Adobe Experience Cloud Offer.Json](json-schema/adobe-experience-cloud-offer.json)
- [Adobe Experience Cloud Profile.Json](json-schema/adobe-experience-cloud-profile.json)
- [Adobe Experience Cloud Segment.Json](json-schema/adobe-experience-cloud-segment.json)
- [Analytics Api Calculated Metric List](json-schema/analytics-api-calculated-metric-list-schema.json)
- [Analytics Api Calculated Metric](json-schema/analytics-api-calculated-metric-schema.json)
- [Analytics Api Date Range List](json-schema/analytics-api-date-range-list-schema.json)
- [Analytics Api Dimension](json-schema/analytics-api-dimension-schema.json)
- [Analytics Api Metric](json-schema/analytics-api-metric-schema.json)
- [Analytics Api Project List](json-schema/analytics-api-project-list-schema.json)
- [Analytics Api Project](json-schema/analytics-api-project-schema.json)
- [Analytics Api Report Request](json-schema/analytics-api-report-request-schema.json)
- [Analytics Api Report Response](json-schema/analytics-api-report-response-schema.json)
- [Analytics Api Report Suite List](json-schema/analytics-api-report-suite-list-schema.json)
- [Analytics Api Report Suite](json-schema/analytics-api-report-suite-schema.json)
- [Analytics Api Segment List](json-schema/analytics-api-segment-list-schema.json)
- [Analytics Api Segment](json-schema/analytics-api-segment-schema.json)
- [Analytics Api User List](json-schema/analytics-api-user-list-schema.json)
- [Analytics Api User](json-schema/analytics-api-user-schema.json)
- [Campaign Api Email List](json-schema/campaign-api-email-list-schema.json)
- [Campaign Api Email](json-schema/campaign-api-email-schema.json)
- [Campaign Api Profile Input](json-schema/campaign-api-profile-input-schema.json)
- [Campaign Api Profile List](json-schema/campaign-api-profile-list-schema.json)
- [Campaign Api Profile](json-schema/campaign-api-profile-schema.json)
- [Campaign Api Service Input](json-schema/campaign-api-service-input-schema.json)
- [Campaign Api Service List](json-schema/campaign-api-service-list-schema.json)
- [Campaign Api Service](json-schema/campaign-api-service-schema.json)
- [Campaign Api Transactional Message Request](json-schema/campaign-api-transactional-message-request-schema.json)
- [Campaign Api Transactional Message Response](json-schema/campaign-api-transactional-message-response-schema.json)
- [Campaign Api Workflow List](json-schema/campaign-api-workflow-list-schema.json)
- [Campaign Api Workflow](json-schema/campaign-api-workflow-schema.json)
- [Experience Platform Api Batch](json-schema/experience-platform-api-batch-schema.json)
- [Experience Platform Api Class List](json-schema/experience-platform-api-class-list-schema.json)
- [Experience Platform Api Dataset Input](json-schema/experience-platform-api-dataset-input-schema.json)
- [Experience Platform Api Dataset](json-schema/experience-platform-api-dataset-schema.json)
- [Experience Platform Api Identity Namespace Input](json-schema/experience-platform-api-identity-namespace-input-schema.json)
- [Experience Platform Api Identity Namespace](json-schema/experience-platform-api-identity-namespace-schema.json)
- [Experience Platform Api Profile Entity](json-schema/experience-platform-api-profile-entity-schema.json)
- [Experience Platform Api Query List](json-schema/experience-platform-api-query-list-schema.json)
- [Experience Platform Api Query](json-schema/experience-platform-api-query-schema.json)
- [Experience Platform Api Sandbox List](json-schema/experience-platform-api-sandbox-list-schema.json)
- [Experience Platform Api Sandbox](json-schema/experience-platform-api-sandbox-schema.json)
- [Experience Platform Api Schema Input](json-schema/experience-platform-api-schema-input-schema.json)
- [Experience Platform Api Schema List](json-schema/experience-platform-api-schema-list-schema.json)
- [Experience Platform Api Schema](json-schema/experience-platform-api-schema-schema.json)
- [Experience Platform Api Segment Definition Input](json-schema/experience-platform-api-segment-definition-input-schema.json)
- [Experience Platform Api Segment Definition List](json-schema/experience-platform-api-segment-definition-list-schema.json)
- [Experience Platform Api Segment Definition](json-schema/experience-platform-api-segment-definition-schema.json)
- [Journey Optimizer Api Campaign Input](json-schema/journey-optimizer-api-campaign-input-schema.json)
- [Journey Optimizer Api Campaign List](json-schema/journey-optimizer-api-campaign-list-schema.json)
- [Journey Optimizer Api Campaign](json-schema/journey-optimizer-api-campaign-schema.json)
- [Journey Optimizer Api Collection Input](json-schema/journey-optimizer-api-collection-input-schema.json)
- [Journey Optimizer Api Collection List](json-schema/journey-optimizer-api-collection-list-schema.json)
- [Journey Optimizer Api Collection](json-schema/journey-optimizer-api-collection-schema.json)
- [Journey Optimizer Api Content Template Input](json-schema/journey-optimizer-api-content-template-input-schema.json)
- [Journey Optimizer Api Content Template List](json-schema/journey-optimizer-api-content-template-list-schema.json)
- [Journey Optimizer Api Content Template](json-schema/journey-optimizer-api-content-template-schema.json)
- [Journey Optimizer Api Decision Rule Input](json-schema/journey-optimizer-api-decision-rule-input-schema.json)
- [Journey Optimizer Api Decision Rule List](json-schema/journey-optimizer-api-decision-rule-list-schema.json)
- [Journey Optimizer Api Decision Rule](json-schema/journey-optimizer-api-decision-rule-schema.json)
- [Journey Optimizer Api Journey Input](json-schema/journey-optimizer-api-journey-input-schema.json)
- [Journey Optimizer Api Journey List](json-schema/journey-optimizer-api-journey-list-schema.json)
- [Journey Optimizer Api Journey](json-schema/journey-optimizer-api-journey-schema.json)
- [Journey Optimizer Api Message Input](json-schema/journey-optimizer-api-message-input-schema.json)
- [Journey Optimizer Api Message List](json-schema/journey-optimizer-api-message-list-schema.json)
- [Journey Optimizer Api Message](json-schema/journey-optimizer-api-message-schema.json)
- [Journey Optimizer Api Offer Input](json-schema/journey-optimizer-api-offer-input-schema.json)
- [Journey Optimizer Api Offer List](json-schema/journey-optimizer-api-offer-list-schema.json)
- [Journey Optimizer Api Offer](json-schema/journey-optimizer-api-offer-schema.json)
- [Journey Optimizer Api Placement Input](json-schema/journey-optimizer-api-placement-input-schema.json)
- [Journey Optimizer Api Placement List](json-schema/journey-optimizer-api-placement-list-schema.json)
- [Journey Optimizer Api Placement](json-schema/journey-optimizer-api-placement-schema.json)
- [Target Api Activity Input](json-schema/target-api-activity-input-schema.json)
- [Target Api Activity List](json-schema/target-api-activity-list-schema.json)
- [Target Api Activity](json-schema/target-api-activity-schema.json)
- [Target Api Audience Input](json-schema/target-api-audience-input-schema.json)
- [Target Api Audience List](json-schema/target-api-audience-list-schema.json)
- [Target Api Audience](json-schema/target-api-audience-schema.json)
- [Target Api Delivery Request](json-schema/target-api-delivery-request-schema.json)
- [Target Api Delivery Response](json-schema/target-api-delivery-response-schema.json)
- [Target Api Environment List](json-schema/target-api-environment-list-schema.json)
- [Target Api Offer Input](json-schema/target-api-offer-input-schema.json)
- [Target Api Offer List](json-schema/target-api-offer-list-schema.json)
- [Target Api Offer](json-schema/target-api-offer-schema.json)
- [Target Api Property List](json-schema/target-api-property-list-schema.json)

### JSON Structure

- [Adobe Experience Cloud Campaign.Json](json-structure/adobe-experience-cloud-campaign.json)
- [Adobe Experience Cloud Event.Json](json-structure/adobe-experience-cloud-event.json)
- [Adobe Experience Cloud Journey.Json](json-structure/adobe-experience-cloud-journey.json)
- [Adobe Experience Cloud Offer.Json](json-structure/adobe-experience-cloud-offer.json)
- [Adobe Experience Cloud Profile.Json](json-structure/adobe-experience-cloud-profile.json)
- [Adobe Experience Cloud Segment.Json](json-structure/adobe-experience-cloud-segment.json)
- [Analytics Api Calculated Metric List](json-structure/analytics-api-calculated-metric-list-structure.json)
- [Analytics Api Calculated Metric](json-structure/analytics-api-calculated-metric-structure.json)
- [Analytics Api Date Range List](json-structure/analytics-api-date-range-list-structure.json)
- [Analytics Api Dimension](json-structure/analytics-api-dimension-structure.json)
- [Analytics Api Metric](json-structure/analytics-api-metric-structure.json)
- [Analytics Api Project List](json-structure/analytics-api-project-list-structure.json)
- [Analytics Api Project](json-structure/analytics-api-project-structure.json)
- [Analytics Api Report Request](json-structure/analytics-api-report-request-structure.json)
- [Analytics Api Report Response](json-structure/analytics-api-report-response-structure.json)
- [Analytics Api Report Suite List](json-structure/analytics-api-report-suite-list-structure.json)
- [Analytics Api Report Suite](json-structure/analytics-api-report-suite-structure.json)
- [Analytics Api Segment List](json-structure/analytics-api-segment-list-structure.json)
- [Analytics Api Segment](json-structure/analytics-api-segment-structure.json)
- [Analytics Api User List](json-structure/analytics-api-user-list-structure.json)
- [Analytics Api User](json-structure/analytics-api-user-structure.json)
- [Campaign Api Email List](json-structure/campaign-api-email-list-structure.json)
- [Campaign Api Email](json-structure/campaign-api-email-structure.json)
- [Campaign Api Profile Input](json-structure/campaign-api-profile-input-structure.json)
- [Campaign Api Profile List](json-structure/campaign-api-profile-list-structure.json)
- [Campaign Api Profile](json-structure/campaign-api-profile-structure.json)
- [Campaign Api Service Input](json-structure/campaign-api-service-input-structure.json)
- [Campaign Api Service List](json-structure/campaign-api-service-list-structure.json)
- [Campaign Api Service](json-structure/campaign-api-service-structure.json)
- [Campaign Api Transactional Message Request](json-structure/campaign-api-transactional-message-request-structure.json)
- [Campaign Api Transactional Message Response](json-structure/campaign-api-transactional-message-response-structure.json)
- [Campaign Api Workflow List](json-structure/campaign-api-workflow-list-structure.json)
- [Campaign Api Workflow](json-structure/campaign-api-workflow-structure.json)
- [Experience Platform Api Batch](json-structure/experience-platform-api-batch-structure.json)
- [Experience Platform Api Class List](json-structure/experience-platform-api-class-list-structure.json)
- [Experience Platform Api Dataset Input](json-structure/experience-platform-api-dataset-input-structure.json)
- [Experience Platform Api Dataset](json-structure/experience-platform-api-dataset-structure.json)
- [Experience Platform Api Identity Namespace Input](json-structure/experience-platform-api-identity-namespace-input-structure.json)
- [Experience Platform Api Identity Namespace](json-structure/experience-platform-api-identity-namespace-structure.json)
- [Experience Platform Api Profile Entity](json-structure/experience-platform-api-profile-entity-structure.json)
- [Experience Platform Api Query List](json-structure/experience-platform-api-query-list-structure.json)
- [Experience Platform Api Query](json-structure/experience-platform-api-query-structure.json)
- [Experience Platform Api Sandbox List](json-structure/experience-platform-api-sandbox-list-structure.json)
- [Experience Platform Api Sandbox](json-structure/experience-platform-api-sandbox-structure.json)
- [Experience Platform Api Schema Input](json-structure/experience-platform-api-schema-input-structure.json)
- [Experience Platform Api Schema List](json-structure/experience-platform-api-schema-list-structure.json)
- [Experience Platform Api Schema](json-structure/experience-platform-api-schema-structure.json)
- [Experience Platform Api Segment Definition Input](json-structure/experience-platform-api-segment-definition-input-structure.json)
- [Experience Platform Api Segment Definition List](json-structure/experience-platform-api-segment-definition-list-structure.json)
- [Experience Platform Api Segment Definition](json-structure/experience-platform-api-segment-definition-structure.json)
- [Journey Optimizer Api Campaign Input](json-structure/journey-optimizer-api-campaign-input-structure.json)
- [Journey Optimizer Api Campaign List](json-structure/journey-optimizer-api-campaign-list-structure.json)
- [Journey Optimizer Api Campaign](json-structure/journey-optimizer-api-campaign-structure.json)
- [Journey Optimizer Api Collection Input](json-structure/journey-optimizer-api-collection-input-structure.json)
- [Journey Optimizer Api Collection List](json-structure/journey-optimizer-api-collection-list-structure.json)
- [Journey Optimizer Api Collection](json-structure/journey-optimizer-api-collection-structure.json)
- [Journey Optimizer Api Content Template Input](json-structure/journey-optimizer-api-content-template-input-structure.json)
- [Journey Optimizer Api Content Template List](json-structure/journey-optimizer-api-content-template-list-structure.json)
- [Journey Optimizer Api Content Template](json-structure/journey-optimizer-api-content-template-structure.json)
- [Journey Optimizer Api Decision Rule Input](json-structure/journey-optimizer-api-decision-rule-input-structure.json)
- [Journey Optimizer Api Decision Rule List](json-structure/journey-optimizer-api-decision-rule-list-structure.json)
- [Journey Optimizer Api Decision Rule](json-structure/journey-optimizer-api-decision-rule-structure.json)
- [Journey Optimizer Api Journey Input](json-structure/journey-optimizer-api-journey-input-structure.json)
- [Journey Optimizer Api Journey List](json-structure/journey-optimizer-api-journey-list-structure.json)
- [Journey Optimizer Api Journey](json-structure/journey-optimizer-api-journey-structure.json)
- [Journey Optimizer Api Message Input](json-structure/journey-optimizer-api-message-input-structure.json)
- [Journey Optimizer Api Message List](json-structure/journey-optimizer-api-message-list-structure.json)
- [Journey Optimizer Api Message](json-structure/journey-optimizer-api-message-structure.json)
- [Journey Optimizer Api Offer Input](json-structure/journey-optimizer-api-offer-input-structure.json)
- [Journey Optimizer Api Offer List](json-structure/journey-optimizer-api-offer-list-structure.json)
- [Journey Optimizer Api Offer](json-structure/journey-optimizer-api-offer-structure.json)
- [Journey Optimizer Api Placement Input](json-structure/journey-optimizer-api-placement-input-structure.json)
- [Journey Optimizer Api Placement List](json-structure/journey-optimizer-api-placement-list-structure.json)
- [Journey Optimizer Api Placement](json-structure/journey-optimizer-api-placement-structure.json)
- [Target Api Activity Input](json-structure/target-api-activity-input-structure.json)
- [Target Api Activity List](json-structure/target-api-activity-list-structure.json)
- [Target Api Activity](json-structure/target-api-activity-structure.json)
- [Target Api Audience Input](json-structure/target-api-audience-input-structure.json)
- [Target Api Audience List](json-structure/target-api-audience-list-structure.json)
- [Target Api Audience](json-structure/target-api-audience-structure.json)
- [Target Api Delivery Request](json-structure/target-api-delivery-request-structure.json)
- [Target Api Delivery Response](json-structure/target-api-delivery-response-structure.json)
- [Target Api Environment List](json-structure/target-api-environment-list-structure.json)
- [Target Api Offer Input](json-structure/target-api-offer-input-structure.json)
- [Target Api Offer List](json-structure/target-api-offer-list-structure.json)
- [Target Api Offer](json-structure/target-api-offer-structure.json)
- [Target Api Property List](json-structure/target-api-property-list-structure.json)

### JSON-LD

- [Adobe Experience Cloud Analytics Api Context](json-ld/adobe-experience-cloud-analytics-api-context.jsonld)
- [Adobe Experience Cloud Campaign Api Context](json-ld/adobe-experience-cloud-campaign-api-context.jsonld)
- [Adobe Experience Cloud Context](json-ld/adobe-experience-cloud-context.jsonld)
- [Adobe Experience Cloud Experience Platform Api Context](json-ld/adobe-experience-cloud-experience-platform-api-context.jsonld)
- [Adobe Experience Cloud Io Events Context](json-ld/adobe-experience-cloud-io-events-context.jsonld)
- [Adobe Experience Cloud Journey Optimizer Api Context](json-ld/adobe-experience-cloud-journey-optimizer-api-context.jsonld)
- [Adobe Experience Cloud Target Api Context](json-ld/adobe-experience-cloud-target-api-context.jsonld)

### Examples

- [Adobe Experience Cloud Campaign.Json](examples/adobe-experience-cloud-campaign.json)
- [Adobe Experience Cloud Event.Json](examples/adobe-experience-cloud-event.json)
- [Adobe Experience Cloud Journey.Json](examples/adobe-experience-cloud-journey.json)
- [Adobe Experience Cloud Offer.Json](examples/adobe-experience-cloud-offer.json)
- [Adobe Experience Cloud Profile.Json](examples/adobe-experience-cloud-profile.json)
- [Adobe Experience Cloud Segment.Json](examples/adobe-experience-cloud-segment.json)
- [Analytics Api Calculated Metric](examples/analytics-api-calculated-metric-example.json)
- [Analytics Api Calculated Metric List](examples/analytics-api-calculated-metric-list-example.json)
- [Analytics Api Date Range List](examples/analytics-api-date-range-list-example.json)
- [Analytics Api Dimension](examples/analytics-api-dimension-example.json)
- [Analytics Api Metric](examples/analytics-api-metric-example.json)
- [Analytics Api Project](examples/analytics-api-project-example.json)
- [Analytics Api Project List](examples/analytics-api-project-list-example.json)
- [Analytics Api Report Request](examples/analytics-api-report-request-example.json)
- [Analytics Api Report Response](examples/analytics-api-report-response-example.json)
- [Analytics Api Report Suite](examples/analytics-api-report-suite-example.json)
- [Analytics Api Report Suite List](examples/analytics-api-report-suite-list-example.json)
- [Analytics Api Segment](examples/analytics-api-segment-example.json)
- [Analytics Api Segment List](examples/analytics-api-segment-list-example.json)
- [Analytics Api User](examples/analytics-api-user-example.json)
- [Analytics Api User List](examples/analytics-api-user-list-example.json)
- [Campaign Api Email](examples/campaign-api-email-example.json)
- [Campaign Api Email List](examples/campaign-api-email-list-example.json)
- [Campaign Api Profile](examples/campaign-api-profile-example.json)
- [Campaign Api Profile Input](examples/campaign-api-profile-input-example.json)
- [Campaign Api Profile List](examples/campaign-api-profile-list-example.json)
- [Campaign Api Service](examples/campaign-api-service-example.json)
- [Campaign Api Service Input](examples/campaign-api-service-input-example.json)
- [Campaign Api Service List](examples/campaign-api-service-list-example.json)
- [Campaign Api Transactional Message Request](examples/campaign-api-transactional-message-request-example.json)
- [Campaign Api Transactional Message Response](examples/campaign-api-transactional-message-response-example.json)
- [Campaign Api Workflow](examples/campaign-api-workflow-example.json)
- [Campaign Api Workflow List](examples/campaign-api-workflow-list-example.json)
- [Experience Platform Api Batch](examples/experience-platform-api-batch-example.json)
- [Experience Platform Api Class List](examples/experience-platform-api-class-list-example.json)
- [Experience Platform Api Dataset](examples/experience-platform-api-dataset-example.json)
- [Experience Platform Api Dataset Input](examples/experience-platform-api-dataset-input-example.json)
- [Experience Platform Api Identity Namespace](examples/experience-platform-api-identity-namespace-example.json)
- [Experience Platform Api Identity Namespace Input](examples/experience-platform-api-identity-namespace-input-example.json)
- [Experience Platform Api Profile Entity](examples/experience-platform-api-profile-entity-example.json)
- [Experience Platform Api Query](examples/experience-platform-api-query-example.json)
- [Experience Platform Api Query List](examples/experience-platform-api-query-list-example.json)
- [Experience Platform Api Sandbox](examples/experience-platform-api-sandbox-example.json)
- [Experience Platform Api Sandbox List](examples/experience-platform-api-sandbox-list-example.json)
- [Experience Platform Api Schema](examples/experience-platform-api-schema-example.json)
- [Experience Platform Api Schema Input](examples/experience-platform-api-schema-input-example.json)
- [Experience Platform Api Schema List](examples/experience-platform-api-schema-list-example.json)
- [Experience Platform Api Segment Definition](examples/experience-platform-api-segment-definition-example.json)
- [Experience Platform Api Segment Definition Input](examples/experience-platform-api-segment-definition-input-example.json)
- [Experience Platform Api Segment Definition List](examples/experience-platform-api-segment-definition-list-example.json)
- [Journey Optimizer Api Campaign](examples/journey-optimizer-api-campaign-example.json)
- [Journey Optimizer Api Campaign Input](examples/journey-optimizer-api-campaign-input-example.json)
- [Journey Optimizer Api Campaign List](examples/journey-optimizer-api-campaign-list-example.json)
- [Journey Optimizer Api Collection](examples/journey-optimizer-api-collection-example.json)
- [Journey Optimizer Api Collection Input](examples/journey-optimizer-api-collection-input-example.json)
- [Journey Optimizer Api Collection List](examples/journey-optimizer-api-collection-list-example.json)
- [Journey Optimizer Api Content Template](examples/journey-optimizer-api-content-template-example.json)
- [Journey Optimizer Api Content Template Input](examples/journey-optimizer-api-content-template-input-example.json)
- [Journey Optimizer Api Content Template List](examples/journey-optimizer-api-content-template-list-example.json)
- [Journey Optimizer Api Decision Rule](examples/journey-optimizer-api-decision-rule-example.json)
- [Journey Optimizer Api Decision Rule Input](examples/journey-optimizer-api-decision-rule-input-example.json)
- [Journey Optimizer Api Decision Rule List](examples/journey-optimizer-api-decision-rule-list-example.json)
- [Journey Optimizer Api Journey](examples/journey-optimizer-api-journey-example.json)
- [Journey Optimizer Api Journey Input](examples/journey-optimizer-api-journey-input-example.json)
- [Journey Optimizer Api Journey List](examples/journey-optimizer-api-journey-list-example.json)
- [Journey Optimizer Api Message](examples/journey-optimizer-api-message-example.json)
- [Journey Optimizer Api Message Input](examples/journey-optimizer-api-message-input-example.json)
- [Journey Optimizer Api Message List](examples/journey-optimizer-api-message-list-example.json)
- [Journey Optimizer Api Offer](examples/journey-optimizer-api-offer-example.json)
- [Journey Optimizer Api Offer Input](examples/journey-optimizer-api-offer-input-example.json)
- [Journey Optimizer Api Offer List](examples/journey-optimizer-api-offer-list-example.json)
- [Journey Optimizer Api Placement](examples/journey-optimizer-api-placement-example.json)
- [Journey Optimizer Api Placement Input](examples/journey-optimizer-api-placement-input-example.json)
- [Journey Optimizer Api Placement List](examples/journey-optimizer-api-placement-list-example.json)
- [Target Api Activity](examples/target-api-activity-example.json)
- [Target Api Activity Input](examples/target-api-activity-input-example.json)
- [Target Api Activity List](examples/target-api-activity-list-example.json)
- [Target Api Audience](examples/target-api-audience-example.json)
- [Target Api Audience Input](examples/target-api-audience-input-example.json)
- [Target Api Audience List](examples/target-api-audience-list-example.json)
- [Target Api Delivery Request](examples/target-api-delivery-request-example.json)
- [Target Api Delivery Response](examples/target-api-delivery-response-example.json)
- [Target Api Environment List](examples/target-api-environment-list-example.json)
- [Target Api Offer](examples/target-api-offer-example.json)
- [Target Api Offer Input](examples/target-api-offer-input-example.json)
- [Target Api Offer List](examples/target-api-offer-list-example.json)
- [Target Api Property List](examples/target-api-property-list-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Analytics Api](capabilities/shared/analytics-api.yaml)
- [Experience Platform Api](capabilities/shared/experience-platform-api.yaml)
- [Journey Optimizer Api](capabilities/shared/journey-optimizer-api.yaml)
- [Target Api](capabilities/shared/target-api.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Customer Data Platform](capabilities/customer-data-platform.yaml) | Experience Platform | 4 | Data Engineer |
| [Digital Marketing](capabilities/digital-marketing.yaml) | Analytics, Target, Journey Optimizer | 10 | Digital Marketer |

## Vocabulary

- [Adobe Experience Cloud Vocabulary](vocabulary/adobe-experience-cloud-vocabulary.yaml) — Unified taxonomy mapping 12 resources, 8 actions, 2 workflows, and 4 personas across Adobe Experience Cloud APIs

## Rules

- [Adobe Experience Cloud Spectral Rules](rules/adobe-experience-cloud-spectral-rules.yml) — 30 rules across 13 categories enforcing Adobe Experience Cloud API conventions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
