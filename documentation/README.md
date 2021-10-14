# Documentation
## Introduction
The following content is meant to support everyone who wants to either build IDS components or implement and/or contribute to the existing open source components.
It will link you to relevant sources and will provide guidance on your way. 

Since this documentation relies on the IDS expertise and experience of everyone involved, please feel free **to contribute to it.** 
In case you are unable to locate the information you are looking for, please:
+ Open an issue that points to this topic. 
+ Add a section, link, or whatever that would fill this gap.
+ Have a look at the open issues and try to fix them.

If you are interested in contributing to this document, please check the detailed information on [how to contribute](/documentation/CONTRIBUTING.md) to this documentation.

# Building Data Spaces
On the sections below, you will find the appropriate resources and links that provide technical information/documentation on each step for developing data spaces. As is known, every development journey is an individual one. So your starting point may differ based on your knowledge, as well as the steps you have to take. Please feel free to check the forthcoming chapters to find relevant information and documentation.

In general, a typical data space development journey consists of the following stages:

[1. Gather Knowledge](/documentation/1-Gather-Knowledge.md)

[2. Design Your Architecture](/documentation/2-Design-Your-Architecture.md)

[3. Develop Your Components](/documentation/3-Develop-Your-Components.md)

[4. Integrate Your Components](/documentation/4-Integrate-Your-Components.md)

[5. Get Certified](/documentation/5-Get-Certified.md)

[6. Start Sharing Your Data in a Sovereign Way](/documentation/6-Start-Sharing-Your-Data.md)


---










***Note: Let's move content below into the structure above.

---


### GOALS OF THE INTERNATIONAL DATA SPACES
Data sovereignty is a central aspect of the International Data Spaces. It can be defined as a natural person’s or corporate entity’s capability of being entirely self-determined with regard to its data. The International Data Spaces initiative proposes a Reference Architecture Model for this particular capability and related aspects, including requirements for secure and trusted data exchange in business ecosystems.

+ **TRUST:** Trust is the basis of the International Data Spaces. Each participant is evaluated and certified before being granted access to the trusted business ecosystem.

+ **SECURITY AND DATA SOVEREIGNTY:** All components of the International Data Spaces rely on state-of-the-art security measures. Apart from architectural specifications, security is mainly ensured by the evaluation and certification of each technical component used in the International Data Spaces. In line with the central aspect of ensuring data sovereignty, a data owner in the International Data Spaces attaches usage restriction information to their data before it is transferred to a data consumer. To use the data, the data consumer must fully accept the data owner’s usage policy.

+ **ECOSYSTEM OF DATA:** The architecture of the International Data Spaces does not require central data storage capabilities. Instead, it pursues the idea of decentralization of data storage, which means that data physically remains with the respective data owner until it is transferred to a trusted party. This approach requires a comprehensive description of each data source and the value and usability of data for other companies, combined with the ability to integrate domain-specific data vocabularies. In addition, brokers in the ecosystem provide services for real-time data search.

+ **STANDARDIZED INTEROPERABILITY:** The International Data Spaces Connector, being a central component of the architecture, is implemented in different variants and can be acquired from different vendors. Nevertheless, each Connector is able to communicate with any other Connector (or other technical component) in the ecosystem of the International Data Space.

+ **VALUE ADDING APPS:** The International Data Spaces allows to inject apps into the IDS Connectors in order to provide services on top of data exchange processes. This includes services for data processing, data format alignment, and data exchange protocols, for example. Furthermore, data analytics services can be provided by remote execution of algorithms.

+ **DATA MARKETS:** The International Data Space enables the creation of novel, data-driven services that make use of data apps. It also fosters new business models for these services by providing clearing mechanisms and billing functions, and by creating domain-specific broker solutions and marketplaces. In addition, the International Data Spaces provides templates and other methodological support for participants to use when specifying usage restriction information and requesting legal information.

All research and development activities, as well as all activities with regard to standardization, are driven by the following guidelines:

+ **OPEN DEVELOPMENT PROCESS:** The International Data Spaces Association is a non-profit organization institutionalized under the German law of associations. Every organization is invited to participate, as long as it adheres to the common principles of work.

+ **RE-USE OF EXISTING TECHNOLOGIES:** Inter-organizational information systems, data interoperability, and information security are well-established fields of research and development, with plenty of technologies available in the market. The work of the International Data Spaces initiative is guided by the idea not to “reinvent the wheel”, but to use existing technologies (e.g., from the open-source domain) and standards (e.g., semantic standards of the W3C) to the possible extent.

+ **CONTRIBUTION TO STANDARDIZATION:** Aiming at establishing an international standard itself, the International Data Spaces initiative supports the idea of standardized architecture stacks.
                                       

### International Data Spaces Association
**TODO**: Describe IDSA, Goals, Link to "Become Member"

### How to start
Currently, IDS does not yet have an overarching existing ecosystem. Until now, mainly use cases between individual companies have been addressed
In the following diagram, these are located in evolutionary stage **I**.
In the meantime, use cases of evolution stage **II** are becoming increasingly established. The [Mobility Data Space](https://www.mobility-data-space.de/) and [Catena-X](https://www.handelsblatt.com/27129464.html) are particularly worthy of mention here, as are other [IDS Communities](https://internationaldataspaces.org/make/communities/) and [Projects](https://internationaldataspaces.org/make/projects/).

![IDS ecosystems evolution](./images/IDS_business_ecosystems_evolution.png)
(Boris Otto, 2020)

On the IDSA website some use cases are described, which can be used as a guideline:
[https://internationaldataspaces.org/make/use-cases-overview/](https://internationaldataspaces.org/make/use-cases-overview/)

**TODO**: Describe N:M Ecosystems from figure; Address use case development; Security Level


---
From here on old content

---


## Design your architecture
This stage is meant to support you in designing the architecture of your components. It provides relevant links and explains the context around it. 
## Develop your components
You can either build IDS components from scratch by using existing resources as a template, or you can reuse existing open source components available on the [IDS Git-Hub repository](https://github.com/International-Data-Spaces-Association). Already at this stage, you must ensure that the necessary requirements for a later, successful certification are met.
+ IDS Connector Architecture 
+ Metadata Broker
+ Infomodel
+ Identity Management (DAPS, ParIS, CA)
+ App Store
+ Vocabulary Provider
+ Clearing House

## Integrate your components
+ Integration of IDS into existing systems
## Prepare for certification
+ IDS Plugfest 
+ IDS Testbeds 
+ SQS Integration Test Camp
+ IDS Lab 
+ Sick testbed
+ nicos AG testbed 
+ Fraunhofer workshop IDS_ready
## Get IDS certified
Once you have chosen your preferred evaluation facility, you can start to get your components and operational environemnt certified. Here, you will find relevant information on how to start the process. 
## Register to get on board
You will need to gather all necessary documents and provide them to the on-boarding facility, which will introduce you to the targeted data space. 
## Start sharing your data in a sovereign way
