# The International Data Spaces Association on GitHub
"The International Data Spaces Association is a coalition of over 150+ members who share a vision of a world where all companies and organizations can self-determine the usage rules of their data in secure, trusted, and equal partnerships. Their goal is to establish a global standard for international data spaces (IDS) while fostering related technologies and business models for open, federated data ecosystems and marketplaces that ensure data sovereignty for all participants.

As shown in the infographic below, IDS enables trusted data exchange between data providers and consumers. All IDS participants can trust each other because they adhere to a common trust framework. This framework specifies that everyone must use a specific data endpoint: the IDS Connector.  To ensure that each IDS Connector behaves as intended, it is certified against security criteria along with any participant in data sharing. Based on this foundation of trust, IDS improves cooperation, lowers entry barriers, and enhances innovation for the future of the data economy."

![Data Sharing in a Data Space](images/IDSA-Infographic-Data-Sharing-in-a-Data-Space.jpg)

## What is Available Here?
This is an umbrella repository designed to guide you through the International Data Spaces Association (IDSA) on GitHub by directing you to the right sources of information. We provide a brief overview of the resources available in this repository and beyond to help you build data spaces and share data in a secure and sovereign way. You can also find an overview of the repositories [here](./overview_repositories.md). If you are interested in terms commonly used in the IDS ecosystem, check out the [IDS Glossary in IDS-G](https://github.com/International-Data-Spaces-Association/IDS-G/tree/main/Glossary).


**If you are not yet a user of IDS GitHub**, please join us by clicking on the button below and submitting a request to participate. *Requests are typically processed within two business days, and in most cases, invitations are sent within several hours.*

[![Join](/images/button_click-to-join-ids-githubv2.png.png)](https://forms.office.com/r/LMFt6pbji4)


# Table of contents

-   What is Available Here?
    -   [IDS Reference Architecture Model (IDS RAM)](#IDS-RAM)
    -   [IDSA Rulebook](#IDS-RULEBOOK)
    -   [IDS-G](#IDS-G)
    -   [IDS Reference Testbed](#IDS-Reference-Testbed)
    -   [Minimum Viable Data Space](#Minimum-Viable-Data-Space)
    -   [IDS Deployment Scenarios](#IDS-Deployment-Scenarios)
    -   [IDS Graduation Scheme](#IDS-Graduation-Scheme)
-   [IDSA at a Glance](#IDSA-at-a-Glance)
-   [How to Contribute?](#How-to-Contribute?)
-   [Management of Releases & License](#Management-of-Releases-&-License)


## :blue_book: IDS Reference Architecture Model (IDS RAM) <a name="IDS-RAM"></a>
The [IDS RAM](https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0) is the beating heart of the IDS. It includes the standards for secure and sovereign data exchange, certification, and governance. The RAM serves as the blueprint for trusted ecosystems for data exchange and processing.

Since the release of v4.0, the IDS RAM is available on [Github](https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0) and -as always- open for contributions. You are warmly invited to start contributing by checking the [contribution rules here](https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0/blob/main/CONTRIBUTING.md) and/or [the list of existing issues](https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0/issues).

You may also find the [previous version (v3.0) here](IDS-Reference-Architecture-Model-3.0-2019.pdf) in PDF format.


## :green_book: IDS Rulebook <a name="IDS-RULEBOOK"></a>
In an era dominated by data-driven ecosystems and businesses, the development and operation of data spaces have become crucial for organizations seeking success and competitiveness. The IDSA Rulebook plays a pivotal role in this landscape, serving multiple purposes that are instrumental in shaping the data space framework. At its core, the IDSA Rulebook aims to provide a clear delineation between mandatory rules and optional guidelines, encompassing functional, technical, operational, and legal dimensions. This governance framework lays down guidelines for common service functionalities, defining processes, and outlining specific roles and services within data spaces. In short, the IDSA Rulebook stands as a comprehensive guide for navigating the complexities of data spaces, offering essential guidelines for data functionality, technical implementation, collaboration, and legal compliance. Join us in contributing to the development and enhancement of the IDS Rulebook. Your expertise and insights can make a significant impact on creating guidelines that foster innovation, collaboration, and compliance in data spaces.

You can access the [IDSA Rulebook repository here](https://github.com/International-Data-Spaces-Association/IDSA-Rulebook).

You may also find the [rendered version here](https://docs.internationaldataspaces.org/ids-knowledgebase/v/idsa-rulebook/front-matter/readme) in PDF format.


## :globe_with_meridians: IDS-G <a name="IDS-G"></a>
The [IDS-G](https://github.com/International-Data-Spaces-Association/IDS-G) is the point of truth for specifications of IDS components. It is publicly available to everyone and provides approved specifications that were confirmed by the IDS Technical Steering Committee (IDS-TSC) and the IDSA working groups. IDS-G publishes quarterly releases with new approvals by the working groups and the TSC.

An overview of the IDS resources and the status of specifications in IDS-G can be found [here on GitHub](https://github.com/International-Data-Spaces-Association/IDS-G).

As part of this repository, you can also find the [IDS Glossary of Terms](https://github.com/International-Data-Spaces-Association/IDS-G/tree/main/Glossary) 

You are invited to [create issues on IDS-G](https://github.com/International-Data-Spaces-Association/IDS-G/issues). 


## ✔️IDS Reference Testbed <a name="IDS-Reference-Testbed"></a>
[IDS Testbed](https://github.com/International-Data-Spaces-Association/IDS-testbed) is a setup with open-source IDS components. It can be used to verify if a component implements the IDS specifications for establishing connections and communication, and thus, can work interoperable with all IDS components in the testbed setup. 

The IDS Testbed is the starting point for the creation of data spaces. It can be used for:
-	component behavior testing
-	interoperability testing against IDS components (Connector, DAPS, CA, Metadata Broker)
-	preparation for IDS Certification 

You can check the [IDS Reference Testbed repository](https://github.com/International-Data-Spaces-Association/IDS-testbed) for more information.

## 💊 Minimum Viable Data Space <a name="Minimum-Viable-Data-Space"></a>
The Minimum Viable Data Space (MVDS) is a combination of IDS components to create a data space with just enough features to be used for secure and sovereign data exchange as specified by IDSA. It aims to facilitate the work of experimenters by shortening the implementation time (by avoiding lengthy details that would slow down the first release). MVDS allows them to start with a first working version (where secure and sovereign data exchange is guaranteed), where the development team can iterate, identify and respond to the assumptions about the requirements of the data space.

To start experimenting with a MVDS, you can start with the setup explained [on this page](https://github.com/International-Data-Spaces-Association/IDS-testbed/blob/master/minimum-viable-data-space/MVDS.md) of IDS Reference Testbed repository.

## ✍️ IDS Deployment Scenarios <a name="IDS-Deployment-Scenarios"></a>
The [IDS Deployment Scenarios](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios) repository is a collection of deployment examples from various domains and use cases. It is a library of information for IDS projects and can be used as a great source of inspiration prior to your implementation process.

If your IDS implementation is either on Pilot or Live stage, you are warmly invited to apply with your IDS Deployment Scenario via the [Data Space Radar form](https://forms.office.com/Pages/ResponsePage.aspx?id=NNZGs_usx0K9RPFVfuibG3WVHeFvj2hHgjU7ZCgshUhUMExMOTdCWDNMSERJTjlIUlRKMVc0QTUxMCQlQCN0PWcu). 


## 🥚 IDS Graduation Scheme <a name="IDS-Graduation-Scheme"></a>
The IDS Graduation Scheme is the set of rules, processes and criteria to evaluate the maturity level of a IDS component.

You can find the latest version of [IDS Graduation Scheme here](https://github.com/International-Data-Spaces-Association/idsa/tree/main/graduation_scheme). Check out this [one pager](https://github.com/International-Data-Spaces-Association/idsa/blob/main/graduation_scheme/IDSA-Sandbox-Application.pdf) as a starting point to understand how you can apply with your project. If you already have an IDS-related project, you can quickly initiate your application via [this form](https://internationaldataspaces.org/sandbox-application/).

## :book: Knowledge Base <a name="Knowledge-Base"></a>
The IDS Knowledge Base is a step-by-step guide on [How to Build Data Spaces](./how-to-build-data-spaces/README.md) on the foundation of IDS. This community-driven knowledge base is a place to gather and share information. New contributions are always very welcome. If you are interested in sharing your experiences with the community, please start with the [contribution guidelines](/CONTRIBUTING.md).

:triangular_flag_on_post: Part of the IDS Knowledge Base is also available on the IDSA website [docs.internationaldataspaces.org](https://docs.internationaldataspaces.org/knowledge-base/) where you will find lean and brief information on the most popular topics about IDS technologies.

:triangular_flag_on_post: In IDSA Github, you may also check [this repository](https://github.com/International-Data-Spaces-Association/OPENDEI-Building-Blocks) that lists the building blocks developed in OPEN DEI project as result of Task Force 1 Iteration 2.


#
## IDSA AT A GLANCE <a name="IDSA-at-a-Glance"></a>
You may read the Executive Summary of the IDSA [here](https://www.internationaldataspaces.org/publications/sharing-data-while-keeping-data-ownership-the-potential-of-ids-for-the-data-economy/) and check the [goals](GOALS.md) of the association.

[IDSA Website](https://internationaldataspaces.org/) | [LinkedIn](https://www.linkedin.com/company/international-data-spaces-association/) | [Twitter](https://twitter.com/ids_association) | [YouTube](https://www.youtube.com/channel/UC9PsQnKgreCmj-F6Kea5QRg) 

[Most Important Documents from IDSA](https://internationaldataspaces.org/publications/most-important-documents/)

[Benefits and Advantages of Becoming a Member of IDSA](https://internationaldataspaces.org/we/become-a-member/)
#

## How to Contribute to IDS Assets on Github? <a name="How-to-Contribute?"></a>
You are warmly invited to contribute to the IDSA work here. While some aspects of the IDSA work are limited to IDSA members, most of the work here on GitHub is open for everybody to use and to contribute. You can always create change requests as issues on the repositories below: 

| You Can Contribute to | By | Rules are Available in
| ----------- | ----------- | ----------- |
| [IDSA Main Repository (this repo)](https://github.com/International-Data-Spaces-Association/idsa), [IDS Knowledge Base](https://github.com/International-Data-Spaces-Association/idsa/tree/main/how-to-build-data-spaces), [IDS Graduation Scheme](https://github.com/International-Data-Spaces-Association/idsa/tree/main/graduation_scheme) | [Creating an Issue](https://github.com/International-Data-Spaces-Association/idsa/issues/new/choose) | [Contribution Guidelines](https://github.com/International-Data-Spaces-Association/idsa/blob/main/CONTRIBUTING.md)
| [IDS Reference Architecture Model](https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0) | [Creating an Issue](https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0/issues/new)| [Contribution Guidelines](https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0/blob/main/CONTRIBUTING.md)
| [IDS-G](https://github.com/International-Data-Spaces-Association/IDS-G) | [Creating an Issue](https://github.com/International-Data-Spaces-Association/IDS-G/issues/new)| [Contribution Guidelines](https://github.com/International-Data-Spaces-Association/IDS-G/blob/main/CONTRIBUTING.md)
| [IDS Reference Testbed](https://github.com/International-Data-Spaces-Association/IDS-testbed) | [Creating an Issue](https://github.com/International-Data-Spaces-Association/IDS-testbed/issues/new)| [Contribution Guidelines](https://github.com/International-Data-Spaces-Association/IDS-testbed/blob/master/CONTRIBUTING.md)
| [IDS Deployment Scenarios](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios) | [Applying with a Deployment Scenario](https://forms.office.com/Pages/ResponsePage.aspx?id=NNZGs_usx0K9RPFVfuibG3WVHeFvj2hHgjU7ZCgshUhUMExMOTdCWDNMSERJTjlIUlRKMVc0QTUxMCQlQCN0PWcu) or [Creating an Issue](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios/issues/new)| [Contribution Guidelines](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios/blob/main/CONTRIBUTING.md)

## Management of IDSA Releases <a name="Management-of-Releases-&-License"></a>
The [IDS-RAM](https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0) and specifications on [IDS-G](https://github.com/International-Data-Spaces-Association/IDS-G) are governed and managed by the IDSA and its members, through the bodies of the association. The main bodies are the IDSA Working Groups. Details on the management of IDSA releases are described in the [IDS-G Handbook](https://github.com/International-Data-Spaces-Association/IDS-G/blob/main/Handbook/README.md).

Please be also aware of our [Code of Conduct](/CODE_OF_CONDUCT.md).

## License
[CC-BY 4.0](/LICENSE.md) © International Data Spaces Association e.V.







