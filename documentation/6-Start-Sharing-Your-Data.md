## 6. Start Sharing Your Data in a Sovereign Way

Here, you will get hints on how to set for instance usage contrains.

### Data Usage Control
**Data Usage Control in IDS** Data Usage Control is the specification and enforcement of restrictions regulating what must (not) happen to data. It is an extension to traditional Access Control. This document (Data Sovereignty: Updated Position Paper on Data Usage Control in the IDS) provides necessary information about Data Usage Control in IDS. [Link to the document](https://internationaldataspaces.org/data-sovereignty-updated-position-paper-on-data-usage-control-in-the-ids/)

The Usage Control related libraries and applications are listed as follows:
- **Policy-Library** This is the IDS policy model in Java which can read and interpret the IDS Usage Policy Language as JSON-LD. Link to the code: [IDS Policy Library](https://github.com/International-Data-Spaces-Association/Policy-Library)
- **Mydata-Translator** This Java library uses the Policy-Library and translates an IDS usage policy to a MY DATA Control Technologies policy. Link to the code: [MY DATA Control Technologies Translator](https://github.com/International-Data-Spaces-Association/Mydata-Translator)
- **IDS-PAP** This is a web application with Java back end that provides a Material-UI to support the users to specify their IDS policies. Link to the code: [IDS Policy Administration Point (PAP)](https://github.com/International-Data-Spaces-Association/IDS-PAP)
- **Usage-Control-App** This a Usage Control prototype application which uses MY DATA Control Technologies to manage and enforce IDS policies. The app can be called by a [Camel Interceptor](https://camel.apache.org/components/3.4.x/eips/intercept.html)  or can be called directly to integrate Usage Control into the IDS Connectors. Link to the code: [IDS Usage Control Application](https://github.com/International-Data-Spaces-Association/Usage-Control-App)
