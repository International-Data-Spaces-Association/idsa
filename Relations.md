# How Do Initiatives Relate in the field of Data Spaces?
The field of Data Spaces and trusted data sharing is rapidly evolving. As industries, research institutions, and governments seek to collaborate across organizational and national boundaries, the need for interoperable approaches to data exchange has become critical. Multiple initiatives and groups are contributing to this ecosystem, each playing a distinct but complementary role. Together, they create the foundation for standardized, reliable, and scalable Data Space solutions.
This section explains how these initiatives relate to one another, highlighting their contributions to specifications, standards, open-source implementations, and testing frameworks.

>This section does not address liaisons or collaborative efforts. Instead, it focuses on IDSA’s standardization and specification projects, which serve as normative references and represent the core outcomes of IDSA’s technical contributions.

## International Data Spaces Association (IDSA)
The International Data Spaces Association (IDSA) brings together global members from both industry and research. Its mission is to develop and promote the concept of data spaces, covering the full spectrum from legal frameworks and business models to technology foundations.

IDSA provides a unique forum for aligning perspectives across its community. By collecting and structuring requirements, the association ensures that the needs of diverse stakeholders are represented in discussions about data space architecture. The value of this end-to-end perspective lies in its ability to integrate legal, organizational, and technical considerations into a coherent vision. At the technical level, IDSA emphasizes the importance of a common core for specification and standardization. This core is designed to foster interoperability between datas pace solutions at the protocol level. To achieve this, IDSA aggregates member requirements and channels them into international specification projects (e.g., within the Eclipse Foundation) and formal standardization activities (such as ISO/IEC JTC 1/SC 38 or CEN/CENELEC Joint Technical Committee (JTC) 25).

In short, IDSA serves as the bridge between conceptual discussions, community requirements, and downstream technical specifications.

## ISO/IEC 20151: A Common Foundation
One of the major milestones in formal standardization is ISO/IEC 20151, Information Technology – Cloud Computing and Distributed Platforms – Data space Concepts and Characteristics.
This standard provides a clear and authoritative definition of Data Space concepts, distinguishing them from related ideas such as data lakes, data fabrics, or data meshes. By describing the essential characteristics and requirements of a Data Space, ISO/IEC 20151 reduces ambiguity and helps ensure consistency in design and implementation.
The standard is not only conceptual; it also lays the baseline for interoperability. By establishing common ground, it enables both intra-data space (within a single ecosystem) and inter-data space (across ecosystems) technical compatibility. In doing so, it creates the foundation on which further specifications and open-source implementations can build.

## Dataspace Protocol (DSP) and Decentralized Claims Protocol (DCP)
The Dataspace Protocol (DSP) and Decentralized Claims Protocol (DCP) are two key specification projects that operationalize the concepts defined by IDSA and ISO/IEC 20151.

- DSP focuses on the communication mechanisms required for trusted data exchange between participants in a Data Space.
- DCP addresses decentralized identity and claims management, which are central to ensuring trustworthiness and accountability.

Both protocols are developed under the governance of the Eclipse Foundation, ensuring transparent processes and adherence to rigorous intellectual property rules. While they are rooted in the requirements articulated by IDSA, their development is open to a broad community beyond the association. This open governance model fosters collaboration and ensures that the specifications can evolve in line with real-world needs.

## Eclipse Dataspace Working Group (EDWG)
To coordinate and endorse data space-related efforts, the Eclipse Foundation has established the Eclipse Dataspace Working Group (EDWG).
The EDWG serves several purposes:

- It associates and endorses specification projects like DSP and DCP.
- It provides a governance structure through its committees, which decide on project alignment and associations.
- It supports submissions towards ISO Publicly Available Specifications (PAS), ensuring that community-driven specifications can influence international standards.

By bringing specifications and open source implementations under one umbrella, the EDWG provides coherence and continuity. It is a key mechanism that through its members ensures data space technologies remain consistent, interoperable, and aligned with global standards.

## Eclipse Dataspace Components (EDC)
Specifications alone are not enough; they must be validated through implementation. This is where the Eclipse Dataspace Components (EDC) project plays a vital role.
EDC is a reference implementation of both DSP and DCP. It provides a framework for developers to build Data Space components with a common core and extensibility mechanism. This design allows rapid integration with existing technologies, such as storage systems, vault services, event processing platforms, or policy engines.
Compliance is a central focus of EDC. Each release version of the framework, together with a defined set of core extensions, is tested against a Technical Compatibility Kit (TCK). Successful test results are published openly, ensuring transparency and building trust in the framework’s conformity to the specifications.

For solution providers, EDC offers two key benefits:

- A ready-to-use, yet extensible foundation for Data Space components.
- Confidence that their solutions can achieve compliance with DSP and DCP at relatively low integration cost.

## Technical Compatibility Kit (TCK)
The Technical Compatibility Kit (TCK) is the backbone of compliance verification. It is a test harness and collection of tools designed to automate the validation of Data Space implementations against DSP and DCP.
By leveraging shared core libraries, the TCK provides comprehensive tests that cover protocol compliance and interoperability scenarios. Solution providers can run their implementations against the TCK to obtain evidence of compliance. Passing results serve as an objective and transparent proof that a solution adheres to the agreed specifications.

The availability of the TCK ensures that the ecosystem does not fragment into incompatible variants. Instead, it promotes trust and interoperability, which are prerequisites for scaling Data Space adoption across industries and borders.