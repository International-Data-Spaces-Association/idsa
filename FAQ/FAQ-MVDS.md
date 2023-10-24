# Frequently Asked Questions

Below we've addressed some of the common questions about Minimum Viable Data Space (MVDS). If your question isn't listed here, feel free to raise an issue in the [Issues](https://github.com/International-Data-Spaces-Association/idsa/issues) section.

---

# Table of Contents
1. [What is a Minimum Viable Data Space (MVDS)?](#what-is-a-minimum-viable-data-space-mvds)
2. [Why is MVDS important?](#why-is-mvds-important)
3. [What are the components required for a MVDS?](#what-are-the-components-required-for-a-mvds)
4. [Can I reuse open-source components for MVDS implementation?](#can-i-reuse-open-source-components-for-mvds-implementation)
5. [How can I start implementing a MVDS?](#how-can-i-start-implementing-a-mvds)
6. [Can I add additional components to MVDS?](#can-i-add-additional-components-to-mvds)
7. [What is the purpose of the MVDS in the context of IDSA?](#what-is-the-purpose-of-the-mvds-in-the-context-of-idsa)
8. [Can MVDS be customized and expanded to meet specific requirements?](#can-mvds-be-customized-and-expanded-to-meet-specific-requirements)
9. [What is the benefit of starting with a MVDS for experimenters?](#what-is-the-benefit-of-starting-with-a-mvds-for-experimenters)
10. [Are there examples of MVDS implementation and experiments?](#are-there-examples-of-mvds-implementation-and-experiments)
11. [Can MVDS be used for different types of data spaces?](#can-mvds-be-used-for-different-types-of-data-spaces)
12. [Is MVDS only applicable for specific industries or sectors?](#is-mvds-only-applicable-for-specific-industries-or-sectors)
13. [Can MVDS be used for both small-scale and large-scale data exchange?](#can-mvds-be-used-for-both-small-scale-and-large-scale-data-exchange)
14. [Can I add additional components to MVDS based on my specific requirements?](#can-i-add-additional-components-to-mvds-based-on-my-specific-requirements)
15. [How are MVDS implementations related to IDS Deployment Scenarios?](#how-are-mvds-implementations-related-to-ids-deployment-scenarios)
16. [Are IDS Testbed and MVDS the same thing? What are the differences between them?](#are-ids-testbed-and-mvds-the-same-thing-what-are-the-differences-between-them)
17. [What should I do if I have technical questions about my implementation or encounter problems while working with MVDS? Who can help me with this?](#what-should-i-do-if-i-have-technical-questions-about-my-implementation-or-encounter-problems-while-working-with-mvds-who-can-help-me-with-this)
18. [Why is IDS Certification important for MVDS?](#why-is-ids-certification-important-for-mvds)
19. [How can I contribute to MVDS?](#how-can-i-contribute-to-mvds)

---

# What is a Minimum Viable Data Space (MVDS)?
A MVDS is a combination of components that enable the creation of a data space with just enough features to be usable for secure and sovereign data exchange, as specified by IDSA.

---

# Why is MVDS important?
MVDS streamlines the implementation process, making it easier and faster for experimenters to create a working data space with secure and sovereign data exchange. 
It provides a starting point for customization and expansion to meet specific requirements.

---

# What are the components required for a MVDS?
A MVDS consists of two connectors (one acting as a data provider and one as a data consumer), an identity provider (Dynamic Attribute Provisioning Service, Certificate Authority), 
and optional additional components for extended functionality.

---

# Can I reuse open-source components for MVDS implementation?
Yes, you can (re)use and customize open-source components listed on IDSA Github or check the ones part of [IDS Graduation Scheme](https://github.com/International-Data-Spaces-Association/idsa/blob/main/graduation_scheme/Projects.md) for higher maturity level solutions.

---

# How can I start implementing a MVDS?
You can implement MVDS by either (re)using and customizing open-source components or developing components from scratch, following the specifications listed on [IDS-G](https://github.com/International-Data-Spaces-Association/IDS-G). 
[IDS-testbed](https://github.com/International-Data-Spaces-Association/IDS-testbed) is recommended for compatibility and interoperability testing.

---

# Can I add additional components to MVDS?
Yes, you can add optional and additional components such as a metadata broker, app store, clearing house, or vocabulary provider to extend the functionality of MVDS as needed.

---

# What is the purpose of the MVDS in the context of IDSA?
MVDS is a solution provided by IDSA Head Office as a best practice to facilitate the implementation of secure and sovereign data exchange in a data space.

---

# Can MVDS be customized and expanded to meet specific requirements?
Yes, MVDS serves as a starting point that can be customized and expanded as needed to meet specific requirements of the data space being implemented.

---

# What is the benefit of starting with a MVDS for experimenters?
Starting with a MVDS allows experimenters to have a first working version of a data space with secure and sovereign data exchange, 
enabling iterative development and quick response to requirements.

---

# Are there examples of MVDS implementation and experiments?
Yes, [IDS Deployment Scenarios](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios/tree/main) provide examples of implementation and experiments run with MVDS, 
serving as best practices and sources of inspiration for building data spaces. 

---

# Can MVDS be used for different types of data spaces?
Yes, MVDS can be used as a starting point for implementing different types of data spaces, tailored to specific use cases and requirements.

---

# Is MVDS only applicable for specific industries or sectors?
No, MVDS can be implemented in various industries or sectors that require secure and sovereign data exchange, such as healthcare, finance, manufacturing, logistics, and more.

---

# Can MVDS be used for both small-scale and large-scale data exchange?
Yes, MVDS can be used for both small-scale and large-scale data exchange. It provides a starting point that can be customized and expanded as needed to meet the requirements of different data exchange scenarios.

---

# Can I add additional components to MVDS based on my specific requirements?
Yes, MVDS allows for the addition of optional and additional components based on specific requirements. These can include metadata brokers, app stores, clearing houses, vocabulary hubs, or other components that extend the functionality of the MVDS.

---

# How are MVDS implementations related to IDS Deployment Scenarios?
MVDS implementations are potential candidates to become [IDS Deployment Scenarios](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios/).
MVDS serves as a starting point for experimenters to create functional data spaces with secure and sovereign data exchange. 
MVDS implementations can be considered as examples of IDS Deployment Scenarios. MVDS implementations that have been successfully tested, validated, 
and certified by IDSA can serve as valuable references for other organizations or industries looking to implement similar data spaces, providing 
practical guidance for building data spaces based on the IDS architecture.

---

# Are IDS Testbed and MVDS the same thing? What are the differences between them?
No, IDS Testbed and MVDS are not the same thing, although they are related. IDS Testbed is a testing environment, while MVDS is a concept that 
defines a set of components for building a functional data space with just enough features. MVDS implementations can be tested and validated using 
IDS Testbed to ensure interoperability and compatibility with the IDS architecture.

---

# What should I do if I have technical questions about my implementation or encounter problems while working with MVDS? Who can help me with this? 
If you have questions or encounter problems while using MVDS, you can create an issue in the IDS Testbed repository. Please note that the IDSA Head Office does not provide support for MVDS directly, 
but there are technical implementation partners listed on the [IDSA website](https://internationaldataspaces.org/adopt/implementation-partners/) who can provide assistance with any technical questions or issues related to MVDS. 
Creating an issue in the [IDS Testbed repository](https://github.com/International-Data-Spaces-Association/IDS-testbed) would be the appropriate way to seek support.

---

# Why is IDS Certification important for MVDS? 
IDS Certification ensures the trustworthiness of the implemented MVDS components and operational environments, providing an additional trust layer within clearly specified boundaries.

------

# How can I contribute to MVDS?
If you would like to contribute to MVDS, you can create an issue on the [IDS Testbed repository](https://github.com/International-Data-Spaces-Association/IDS-testbed), which is the place where MVDS is hosted. 
By creating an issue, you can provide feedback, suggest improvements, or contribute to the MVDS.

