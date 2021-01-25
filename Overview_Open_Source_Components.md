# Motivation

we need an overview on OSS Components

# Requirements to OSS components

# List of known components


IDS Functionalities  | Trusted Connector |	Dataspace Connector	| IDS Enterprise Integration Connector |	TNO Trusted Connector |	GEC  Connector| DIH Connector	| Orbiter Connector	| Open Data Connector	| OPC UA Factory Connector | Metadata-broker-open-core 
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
**Based on another Connector** | -	| - |	- |	- |	- |	Trusted Connector |	-	| - |	Trusted Connector | -
**Planned CertificationLevel**	|	Trust |	Base |	Base |	Trust |	Trust '(Base eval.)' |	Trust	| Trust+ |	Base |	Trust | Base
**Planned CertificationLevel**	|	Trust |	Base |	Base |	Trust |	Trust '(Base eval.)' |	Trust	| Trust+ |	Base |	Trust | Base
**Using Identity Provider**	|	yes |	yes |	yes	| yes |	yes |	own IdP |	own IdP(idento.one) |	yes |	yes | yes
**Using Infomodel Version 4.0.0** |	yes |	yes |	yes	| yes |	3.1.0 |	3.1.0 |	3.1.0 |	3.1.0 |	2.0.0 | yes
**Validate Infomodel** | - |	yes |	yes |	yes	| not IDS conform	| - |	yes | yes |	yes | yes
**Broker registration** | yes |	yes |	yes |	yes |	- |	yes |	- |	yes |	yes | n/a
Provide Data in IDS via	**HTTPS** |	- | yes | yes |	yes |	yes |	yes	| not IDS conform	| yes |	not IDS conform | yes
Provide Data in IDS via **IDSCP** |	yes	| - |	- |	yes |	- |	yes |	- |	-	| - | -
Consume Data in IDS via	**HTTPS**	| yes | yes | yes | yes | not IDS conform	| yes |	not IDS conform	| -	| not IDS conform | n/a
Consume Data in IDS via **IDSCP**	|	yes |	- |	- |	yes |	- | yes | - | - | - | n/a
**Usage Policy Negotiation**	|	- |	- |	yes |	-	| - |	- |	not IDS conform	| - |	- | in Preparation
**Usage Control realization**	| LUCON	| Dataspace	| - |	not IDS conform	| -	| LUCON/MYDATA	| - |	-	| MYDATA | -
**Support AppStore / IDS Data Apps**	|	yes | - |	-	| not IDS conform |	- |	- |	- |	- |	- | in Preparation
**Support Clearing House** | yes | - |	in Preparation	| not IDS conform	| -	| yes |	- |	- | in Preparation
**Support ParIS**	|	- |	- |	- |	- |	- | - | - | - | - | in Preparation
**Support Vocabulary Provider**	|	- |	- |	- |	- |	- | - | - | - | - | in Preparation


Further Functionalities/Features | Trusted Connector |	Dataspace Connector	| IDS Enterprise Integration Connector |	TNO Trusted Connector |	GEC  Connector| DIH Connector	| Orbiter Connector	| Open Data Connector	| OPC UA Factory Connector | Metadata-broker-open-core 
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
**Developer** | Fraunhofer | Fraunhofer | Fraunhofer | TNO | German Edge Cloud	| T-Systems	| Orbiter	| Fraunhofer	| Fraunhofer | Fraunhofer
**GUI**	| yes |	- |	yes |	yes |	yes |	yes |	- |	yes |	yes | -
Open Source: **Open Source**	| yes |	yes |	in Preparation |	- |	- |	yes |	- |	yes |	- | yes
Open Source: **Community**	|	- |	- |	in Preparation | - |	- | - | - | - | - | -
Open Source: **Link / contact**	| [GitHub](https://github.com/industrial-data-space)	| [Github](https://github.com/FraunhoferISST/DataspaceConnector)	| [GitHub](https://github.com/International-Data-Spaces-Association/IDS-Enterprise-Integration-Connector)	| [TNO](maarten.kollenstart@tno.nl)	| GEC	| n.n 	| Truzzt	| [GitHub](https://github.com/public-data-space/ids-open-data-connector)	| [Fraunhofer-Gitlab](friedrich.volz@iosb.fraunhofer.de) | [GitHub](https://github.com/International-Data-Spaces-Association/metadata-broker-open-core)
**Deployment**|  Server	| Docker	| Docker	| Server/Docker/K8s	| Helm/Docker	| Server/Docker	| Docker	| Docker	| Server/Docker | Docker
**Backend Interaction**	| via Apache Camel	| HTTP	| HTTP	| via Apache Camel (HTTP & Kafka) |	HTTP	| via Apache Camel	| HTTP |	HTTP	| via Apache Camel | HTTP
**TRL** (20/12/08)	| 6-7	| 6	| 7	| 6-7	| n.n.	| 5, (6 Q4/2020) |	n.n.	| 3-4	| 6-7 | 7


----
