# Architecture Designs

## What is Architecture
A system's architecture outlines its main parts, their connections (structures), and how they work together. There are several contributing variables to software architecture and design, including business strategy, quality attributes, human dynamics, design, and IT environment.

A system's architecture acts as a blueprint. It establishes a communication and coordination mechanism among components and offers an abstraction to control the complexity of the system.

Software architecture is the discipline used to create these structures and systems as well as the basic components of a software system. Each structure is made up of software elements, their connections, and the attributes of both the elements and the connections.

## Different Architectural designs templates in solution diagram to choose from
* [A to A integration : On premise to cloud](#a-to-a-integration)
* [B 2 B integration : cloud to cloud](#b-to-b-integration)
* [Data Orchestration: On premise to cloud](#data-orchestration)
* [Embedded Analytics: User to cloud](#embedded-analytics)
* [Mobile Integration: User to On premise](#mobile-integration)
* [Digital Integration Hub](#digital-integration-hub)
* [Event Based Integration](#event-based-integration)

## A to A integration
Integration of on premise applications with cloud applications using a cloud based integration solution to enable business processes across an hybrid application landscape. The communication between the cloud based integration solution and the on premise application landscape and other cloud applications requires special security measures (e.g. via VPN, digital certificate based). The cloud based integration solution is operated by the provider.

## B to B integration
Exchange of business documents from internal on premise applications with external entities such as business partners (customers, suppliers). This integration is implemented with an on premise integration solution (e.g. Middleware, Enterprise Service Bus, B2B Gateway) which supports B2B specific capabilities such as business partner management, acknowledgement handling, different type system (e.g. EDIFACT, ANSI X.12) and B2B protocol standards (e.g. AS2, OFTP). The integration solution is managed by the customer (or service provider).

## Data orchestration
Integration of on premise data sources (e.g. from applications, databases) with cloud based applications (e.g. cloud data warehouse) using a cloud based data integration solution. Focus is on discovering, refining, governing and orchestrating data across heterogenous data sources.

## Embedded Analytics
Provide analytical insights through reports or dashboards for custom built applications that run on the SAP Business Technology Platform or SAP business applications using SAP Analytics Cloud, embedded edition. For custom build applications you can expose business data to SAP Analytics Cloud, embedded edition, using a live data connection to the SAP HANA database of this application.

## Mobile Integration
Consumption of on premise application data within a mobile application which is developed and operated in public cloud. The mobile application can be web based or device specific (iOS, Android). The communication between the cloud based mobile application and the on premise application requires special security measures (e.g. via VPN, digital certificates).

## Digital Integration Hub
The Digital Integration Hub is an emerging architecture for implementing a large-scale, high-throughput access layer to business data by inserting a high performance in-memory data store layer between the frontend API service layer and backend app and data sources.

## Event Based Integration
Loosely coupled integration of business applications (SAP/third party, cloud/on premise) using events. Business applications can publish event notifications on a business object's change in state. Consuming business applications are informed of the event and depending on the application logic defined, can read further details about the event and take appropriate action. 