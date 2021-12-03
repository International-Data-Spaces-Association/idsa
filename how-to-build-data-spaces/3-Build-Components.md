# 3. Build Components
You can either build IDS components from scratch by using existing resources as a template, or you can reuse existing open source components available on the IDS Github repository. Already at this stage, you must ensure that the necessary requirements for a later, successful certification are met. Below you can check the existing projects that are available on IDS OS Landscape.

### Connectors

* [Dataspace Connector](../../../../DataspaceConnector/) is an implementation of an IDS connector component following the IDS Reference Architecture Model.
* [Eclipse Dataspace Connector](https://projects.eclipse.org/projects/technology.dataspaceconnector)
Existing open-source projects address the technical challenges of cataloguing and transferring data for a wide range of use cases. However, there is no open-source effort aimed at providing an interoperable, cross-organization framework for data sharing that is built on a common identity model and uniform policy enforcement. This project will integrate with existing data exchange technologies and provide these missing pieces to create a system for data sharing where each organization is able to exert control over how its shared data is used.
* [TRUE Connector](../../../../true-connector/) (TRUsted Engineering) Connector for the IDS (International Data Space) ecosystem.
* [Trusted Connector](../../../../trusted-connector/) is an Apache Karaf-based platform for the Industrial Internet of Things (IIoT).

### Metadata Broker

* [Metadata Broker Open Core](../../../../metadata-broker-open-core/) is an implementation of an International Data Spaces (IDS) Metadata Broker, which is a registry for IDS Connector self-description documents. It is currently under development and intends to act as a reference for members of the International Data Spaces Association (IDSA) to help with the implementation of custom Broker solutions.

### Identity Management

* [DAPS](../../../../omejdn-daps/) (Dynamic Attribute Provisioning Service) is the component to provide certain attributes to organizations and connectors. 
* [ParIS Open Core](../../../../ParIS-open-core/) is an implementation of an International Data Spaces (IDS) Participant Information Service (ParIS), which is a registry for IDS Participant self-description documents. It is currently under development and intends to act as a reference for members of the International Data Spaces Association (IDSA) to help with the implementation of custom ParIS solutions.

### App Store

* [AppStore Open Core](../../../../IDS-AppStore/) is an implementation of the App Store by Fraunhofer FIT.

### Clearing House

* [Clearing House](../../../../ids-clearing-house-core/) is an implementation of the IDS Clearing House. It consists of two microservices that support the Clearing House Service, which is a prototype implementation of the Clearing House component of the Industrial Data Space.

### Frameworks & Other Resources
* [Certification Criteria Catalogue](../../../../ids3c-co/) International Data Spaces Certification Criteria Catalog for Components.
* [DataspaceConnector UI](../../../../DataspaceConnectorUI/) is a user interface for the Dataspace Connector, facilitating the operation and configuration of the connector.
* [Deployment Examples](../../../../IDS-Deployment-Examples/) is used to provide working deployments across the various IDSA repositories.
* [IDS Enterprise Integration Connector](../../../../IDS-Enterprise-Integration-Connector/) is an implementation of an International Data Spaces (IDS) Connector that serves static content (files) using the standard message types defined in the IDS Information Model.
* [IDS Clearing House Service](../../../../ids-clearing-house-service/) is a prototype implementation of the Clearing House component of the Industrial Data Space. It consists of app and processors and its API is defined by the IDS-G and represents the top level service.
* [IDSCP2Rust](../../../../idscp2-rust/) is the Rust implementation of the IDSCP2 transport layer.
* [IDS Information Model](../../../../InformationModel/) is an RDFS/OWL-ontology covering the fundamental concepts of the International Data Spaces (IDS), i.e. the types of digital contents that are exchanged by participants by means of the IDS infrastructure components.
* [IDS Messaging Services](../../../../IDS-Messaging-Services/) provides a lightweight implementation for IDS-Message-Handling. The IDS-Messaging-Services offer open-source functionality for sending IDS-Messages as well as interfaces for processing received IDS-Messages.
* [IDS Testbed](../../../../IDS-testbed/) can be used for component behaviour testing and to verify interoperability testing against IDS components (Connector, DAPS, CA, Metadata Broker). It also functions as a preparation tool for IDS certification as well as a starting point for creation of data spaces. 
