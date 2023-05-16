# 3. Build Components
When building components for a dataspace, the three main paths to follow are:

:one: You can initiate a custom implementation by using the available open-source components on [IDS Github](https://github.com/International-Data-Spaces-Association/idsa/blob/main/overview_repositories.md). This option allows for greater flexibility and customization based on the purpose of the implementation.

:two: Alternatively, you can use [IDS Reference Testbed as a Minimum Viable Data Space](https://github.com/International-Data-Spaces-Association/IDS-testbed/blob/master/minimum-viable-data-space/MVDS.md) which consists of just enough features to create a working dataspace with secure and sovereign data exchange. 

:three: [IDS-Basecamp](https://github.com/International-Data-Spaces-Association/IDS-BaseCamp) can be used as a more mature industry-grade solution. IDS Basecamp is an open-source solution that aims to help organizations agilely initiate an industry-ready dataspace for secure and sovereign data sharing, as defined by IDSA. Compared to other alternatives to quickly initiate a dataspace, IDS Basecamp has a higher level of maturity.

In all three options, [IDS Graduation Scheme](https://github.com/International-Data-Spaces-Association/idsa/blob/main/graduation_scheme/Projects.md) and [Data Connector Report](https://internationaldataspaces.org/data-connector-report/) can be helpful resources to support the implementation process of dataspaces. 

The [Data Connector Report](https://internationaldataspaces.org/data-connector-report/) provides an overview of available connectors in the market, including open-source options, while the [IDS Graduation Scheme](https://github.com/International-Data-Spaces-Association/idsa/blob/main/graduation_scheme/Projects.md) showcases projects that are aligned with a clear path towards IDS-compliancy and are at a more mature stage of development. These resources can help organizations choose the right components and ensure that their implementation is secure and trustworthy.

Also to be compliant with IDS standard, one should always check and try to comply with the specifications listed on [IDS-G repository](https://github.com/International-Data-Spaces-Association/IDS-G) and in the [specifications/criteria catalogues of IDS components](https://internationaldataspaces.org/publications/white-papers/) that are available via IDSA website.

You can see the entire development journey (and the roles of the IDS assets) in the picture below: 


![](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios/blob/a87492b2b420658b336bc2f36e8fab6109de4f1c/images/development-journey-and-IDS-Assets.png)



4️⃣ A fourth path to implementing a dataspace is to partner with a technical implementation partner who can provide guidance and support throughout the process. With the help of an experienced IDS technical implementation partner, organizations can ensure that their dataspace implementation meets their unique needs and is aligned with industry standards and best practices. You can see a list of available [IDS Technical Implementation Partners](https://internationaldataspaces.org/adopt/implementation-partners/) on the IDSA website.


### Additional content that can support your journey
[IDS Information Model](https://github.com/International-Data-Spaces-Association/InformationModel)
The Information Model helps people find and use data products and software in the IDS. These important resources are labeled with specific descriptions and IDS Information Model makes it easier to find what you need and allows you to use it automatically. However, the Information Model doesn't provide a way to create custom structured data types or deal with real-time machine control scenarios. It's mainly focused on modeling digital assets and their interchange. 

The [Dataspace Protocol](https://github.com/International-Data-Spaces-Association/ids-specification) is a comprehensive set of specifications designed to facilitate secure, trustworthy, and interoperable data sharing between entities using web technologies and governed by usage control. These specifications define the required schemas, protocols, and interfaces that allow entities to publish data, negotiate usage agreements, and access data within a federation of technical systems known as a dataspace. By leveraging the Dataspace Protocol, organizations can ensure that their data sharing practices comply with industry standards and best practices, while also enabling new data-driven business models and opportunities.

[IDS Deployment Scenarios](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios) is the repository where you can find various examples of IDS implementations along with the description of the steps and processes involved in delivering a component or a set of components to end-users. It outlines the various stages of deployment, from development and testing to release and optionally maintenance. An IDS Deployment Scenario typically includes information on the prerequisites (such as hardware and software requirements), configuration settings, and any necessary third-party integrations. It also includes details on the deployment environment, such as whether it will be installed on-premises or in the cloud, and how the system will be monitored and supported once it is live. A deployment scenario helps ensure that the deployment process is consistent, easily repeatable, reusable and efficient, and that the system is deployed in a way that meets the needs of end-users. Based on your purpose, you may want to check the existing IDS Deployment Scenarios, get inspired from them and reuse them for your own use case.
