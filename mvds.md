# Minimum Viable Data Space (MVDS)

## What is a Minimum Viable Data Space?

A minimum viable data space (MVDS) is a combination of components to initiate a data space with just enough features to be usable for secure and sovereign data exchange, as specified by IDSA. It aims to facilitate the work of experimenters by shortening the implementation time (by avoiding lengthy details that would slow down the first release). This allows them to start with a first working version (where secure and sovereign data exchange is granted), where the development team can iterate, identify and respond to the assumptions about the requirements of the data space.

A Minimum Viable Data Space consists of the items that are available in Portfolio of IDS-compliant Building Blocks that are currently available on the [Build Components page](https://github.com/International-Data-Spaces-Association/idsa/blob/main/how-to-build-data-spaces/3-Build-Components.md) of the [How to Build Data Spaces?](https://github.com/International-Data-Spaces-Association/idsa/tree/main/how-to-build-data-spaces) section.

The MVDS is the unique solution provided by IDSA Head Office, as current best practice.

(_The IDS Deployment Scenarios is currently under development and will be available by Q2, 2022_). The deployment scenarios will act as best practices and sources of inspiration on building data spaces.

## What are the components that make a MVDS?

A minimum viable data space consists of:

1. Two or more IDS connectors
2. The [Certificate Authority (CA)](https://github.com/International-Data-Spaces-Association/IDS-testbed/blob/master/InstallationGuide.md#certificate-authority) granting X.509 certificates (not to be confused with certification)
3. The [Dynamic Attributes Provisioning Service (DAPS)](https://github.com/International-Data-Spaces-Association/IDS-testbed/blob/master/InstallationGuide.md#daps) to handle dynamic attributes and manage dynamic access tokens

![Minimum Viable Data Space](.gitbook/assets/MVDS-Testbed\_1.0.png)

[Certification](https://internationaldataspaces.org/use/certification/) of all components and the operational environments is an additional trust layer, since it ensures the functionality of components work in clearly specified boundaries.

## What are the practical things MVDS setup allows you to do?

Every data provider can define the rules and conditions (usage policies) under which Data is shared with a data consumer. These rules include scenarios like, e. g., restriction of data usage for a specific group of participants, restriction of usage to specific purposes, usage of data not more then N times, etc.

After a data consumer requests a data set from the provider a contract negotiation process is started during which the usage policies are negotiated.

The picture below depicts a data flow example from two technical and legal enforcement perspectives. ![Minimum Viable Data Space](.gitbook/assets/IDSA\_MVDS-Scenarios.png)

### Example :one: (legal enforcement)

The connector of the data consumer (Company 2) is connected with an ERP system that is not deployed in the connector. Therefore the data provider (company 1) has to agree that data will be processed outside of the connector. Here a digital contract between the two parties is establishes that is legally binding for both parties, even though, technical control is lost for the data provider.

### Example :two: (technical enforcement)

The app that is deployed in the connector of the data consumer (company 3). Applications which are deployed in the runtime environment of a connector can enforce usage policies in a technical manner, e. g., deleting data after 5 days. This adds a further trust layer to the digital contracts as established with company 2.

## How can I start experimenting with a MVDS?

To start with implementing a MVDS, you can check the list of IDS-compliant components that are listed [on this page](https://github.com/International-Data-Spaces-Association/idsa/blob/main/how-to-build-data-spaces/3-Build-Components.md), which is part of the [How to Build Data Spaces?](https://github.com/International-Data-Spaces-Association/idsa/tree/main/how-to-build-data-spaces) section, that explains the process of building data spaces in five steps.

:arrow\_forward: And we recommend to use [IDS-testbed](https://github.com/International-Data-Spaces-Association/IDS-testbed) to ensure the compatibility and interoperability of the components you will be using in your MVDS.
