---
layout: default
title: General Capabilities
parent: Design Principles
nav_order: 5
description: "General Capabilities"
---

# General Capabilities
As you saw on our <a href="~/home/Index" target="_blank">main page</a> in the Design Principals section we wanted to ensure we could deliver and maintain critical practices within any asset we delivered. With these design principals as our guide we also wanted to focus on how to ensure iDaaS platform was nimble, lightweight, and focused on capabilities to ensure healthcare market(s) needs could be addressed in a consistent manner.
    <br/><br/>
         <div align="center">
             <img src="~/img/platform/iDAASPlatform-Visuals-iDAASDataTier-4Rs.png" width="850" height="650" />
    <br/><br/>
| Default | Left align | Center align | Right align |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |



    As we express the capabilities we often refer to them as the four R’s:
    | Capability | Capability Area | Capability Description |
    | :------------- |:-------------:| :-----|
    | Receive      | Integration |  Receive data from various formats. We have branded this capability iDaaS Connect. iDaaS Connect has seevral specific projects to ensure focus on delivering specific capabilities. These capabilities extend from receiving data we focus on industry standards to third party connectivity. Industry standards support include HL7 v2, FHIR, and EDI Claims. There are potential future plans for NCPDP and HL7 v3 message support being discussed. From a third party connectivity perspective we focus on building an on-ramp for data to be leveraged within iDaaS for over 75 common protocols like: JDBC data sources, File, FTP, SFTP, FTPS, APIs, WSDL, AS400, Mongo, Kafka, numerous cloud platforms and many more. |
    |Route|Data Queuing|  Enable data to be routed to many sources. For this capability we have focused on building out several specific components such as healthcare event builder (both code and integration) to form the intelligent healthcare data router. In order to demonstrate this, our focus was on building a reusable repeatable enterprise application integration message pattern along with the ability for organizations to build and deliver healthcare even streaming.|
    |Run|Ability to Process/Parsing/Tracform| This is one of the most exciting capabilities we are enabling. This is done through our DREAM component(s). DREAM, Data Realtime Management, is all about driving change in the healthcare community and building out a value exchange that can be used by anyone implementing iDaaS to add new capabilities in a low latency and very low risk. You would build a component that has the capability of acting on streaming information and being invoked in a real-time manner. These activities could include areas like event population and building, business rules enablement, third party application integration, AI, ML, dynamic mapping of data sources, cross mapping codes and many other potential examples.|
    |Resolve/Research| Data Insight|Enable error handling and insight to resolve potential processing issues. Also, the need to replay messages for new needs.|
    