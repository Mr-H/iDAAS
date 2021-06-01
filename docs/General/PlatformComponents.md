---
layout: default
title: Platform Components
nav_order: 7
description: "Platform Components"
has_children: true
---

# Platform Components
        <p>
            iDaaS is a series of accelerators, because of this component based design, building with it
            or atop it is straight forward, repeatable and reusable. Within each iDaaS
            component there is an implementation/running specific set of instructions.  <br />
            <i>Each component contains a link to the public Git Hub code repositories!!!</i>
        </p>
    </div>

    <h4 class="display-6">Demo Based Repositories: Platform Components</h4>
    <br />
    <div align="left">
        <p>
            These are very specific repositories meant to showcase the capability with a limited set of features. In January 2021 we
            focused on consolidating almost thirty repositories to less than ten. We did this to ensure we simplified the development and
            implementation experience.
        </p>
    </div>
    <br />
    <div align="left">
        <table class="table table-striped">
            <thead class="thead-dark">
                <tr>
                    <th scope="col">Capability</th>
                    <th scope="col">Component</th>
                    <th scope="col">Component Desc.</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Demo-iDaaS</td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Demos" target="_blank">iDaaS Demos</a></td>
                    <td>
                        This repository is specifically designed to to maintain all the iDaaS platform demos. This repository contains demos for
                        BlueButton, EDI, DREAM, FHIR, HL7, Route Data Distribution, and Third Party. 
                    </td>
                </tr>
                <tr>
                    <td>iDaaS Connect </td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Connect" target="_blank">iDaaS Connect </a></td>
                    <td>
                        This repository is specifically designed to to maintain all the iDaaS Connect components. This repository contains iDaaS
                        Connect components for Audit and Compliance, BlueButton, EDI,  FHIR, HL7,, and Third Party.
                    </td>
                </tr>
                <tr>
                    <td>iDaaS Route</td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Route" target="_blank">iDaaS Route - Data Distribution</a></td>
                    <td>
                        This repository is specifically designed to test a subset of iDaaS Route components and capabilities.
                    </td>
                </tr>
                <tr>
                    <td>iDaaS DREAM</td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDAAS-DREAM" target="_blank">iDaaS DREAM Platform</a></td>
                    <td>
                        This repository is specifically designed for iDaaS DREAM components and capabilities.  Within this repository the 
                        is also the iDaaS Event Builder parsing, builder and generator code base.
                    </td>
                </tr>
            <tr>
                    <td> iDaaS KIC</td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-KIC" target="_blank">iDaaS KIC (Knowledge, Insight and Conformance)</a></td>
                    <td>
                        This repository is specifically designed to specifically support all needed components for iDaaS KIC (Knowledge, Insight and Conformance). 
                        This specific capability is intended to enable auditing and reconciliation of anything the iDaaS platform is engaged in leveraging.
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
    <br />

    <h4 class="display-6">Implementation Based Repositories: Platform Components</h4>
    <p>
        These are the full specific repositories with all features enabled.
    </p>
    <br />
    <div align="left">
        <table class="table table-striped">
            <thead class="thead-dark">
                <tr>
                    <th scope="col">Capability</th>
                    <th scope="col">Component</th>
                    <th scope="col">Component Desc.</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Receiving </td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Connect/tree/master/iDaaS-Connect-HL7" target="_blank"> iDaaS Connect Clinical - HL7</a></td>
                    <td>
                        This iDaaS Connect accelerator specifically and ONLY supports the clinical integration standards of HL7.  From an integration connectivity and standards
                        perspective it has HL7 MLLP Servers that support the following types from any vendor and any specific message
                        version from 2.1 to 2.8: ADT (Admissions), ORM (Orders), ORU (Results), SCH (Schedules), PHA (Pharmacy), MFN (Master File Notifications),
                        MDM (Medical Document Management) and VXU (Vaccinations).  This accelerator apart from handling the needed specific connectivity also does a
                        minimal initial routing of data and has complete auditing integrated.
                    </td>
                </tr>
                <tr>
                    <td>Receiving </td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Connect/tree/master/iDaaS-Connect-FHIR" target="_blank"> iDaaS Connect - FHIR</a></td>
                    <td>
                        This iDaaS Connect accelerator specifically and ONLY  supports ALL FHIR resources.  From an integration perspective it enables processing of
                        over 75+ specific <a href="https://www.hl7.org/fhir/STU3/resourcelist.html" target="_blank">FHIR resources</a> that span base, clinical, financial (all),
                        specialized (all but testing). Another benefit of this platform is that you <b>DO NOT require a FHIR server for this be leveraged</b>. However,  It has been tested to
                        work with several FHIR servers: HAPI JPA Server, Microsoft Azure FHIR Server and IBM FHIR Server. This accelerator apart from handling the needed specific
                        connectivity also does a minimal initial routing of data and has complete auditing integrated.
                    </td>
                </tr>
                <tr>
                    <td>Receiving </td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Connect/tree/master/iDaaS-Connect-BlueButton" target="_blank"> iDaaS Connect Blue Button</a></td>
                    <td>
                        This iDaaS Connect accelerator specifically and ONLY  supports the critical FHIR need of processing data from BlueButton based on a series of data attributes that
                        are passed to it.
                    </td>
                </tr>
                <tr>
                    <td>Receiving </td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Connect/tree/master/iDaaS-Connect-ThirdParty" target="_blank">iDaaS Connect - Third Party</a></td>
                    <td>
                        This iDaaS Connect accelerator is specifically designed to receive data from several dozens connectors. The connectors include JDBC (any jdbc compliant data source with a jar),
                        Kafka, FTP/sFTP and sFTP, AS400, HTTP(s), REST and many more.  Since this accelerator is built atop the upstream of Apache Camel this accelerator can
                        leverage any <a href="https://camel.apache.org/components/latest/index.html" target="_blank">supported components</a>. This accelerator apart from handling the needed specific connectivity also does a
                        minimal initial routing of data and has complete auditing integrated.
                    </td>
                </tr>
                <tr>
                    <td>Routing</td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Route/tree/master/iDaaS-Route-DataDist" target="_blank">iDaaS Connect Data Distribution</a></td>
                    <td>
                        This iDaaS Route component  is specifically implemented to help enable a decoupled enterprise integration pattern. The focus of this component is  solely 
                        on enabling data to be distributed with any implementation needs or requirements. The initial design pattern is termed the HCDD (healthcare
                        data distribution) enterprise integration pattern.
                    </td>
                </tr>
                <tr>
                    <td>Run (Transform and Re-Shape Data)</td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDAAS-DREAM/tree/master/iDaaS-EventBuilder" target="_blank">Event Builder</a></td>
                    <td>
                        This component is what enables Red Hat, partners, SIs and developers to develop, extend or enhance the platform's ability to process data into any type of needed custom
                        format for any type of needed processing. iDaaS Event Builder is designed to call out and invoke needed events and can be customized based on business needs very quickly.
                        The only thing past cloning the source code is setting up the appropriate way to include iDaaS Event Builder jar files so that it can be included. If you do not wish to leverage the
                        existing code, enhance or extend it developers are able to add their own custom code for processing and object building.
                    </td>
                </tr>
                <tr>
                    <td>Run</td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-DREAM/" target="_blank">iDaaS DREAM (Data Runtime Enterprise Automated Mgmt)</a></td>
                    <td>
                        DREAM's design intent is to enable Red Hat, partners, SIs and developers to implement iDaaS and/or other capabilities internal or external to iDaaS in a dynamic manner
                        without the need for stopping the platform and needing to restart it to work with data while adding new features.
                    </td>
                </tr>
                <tr>
                    <td>Research and Resolve</td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaS-KIC" target="_blank">iDaaS KIC (Knowledge, Insight and Compliance)</a></td>
                    <td>
                        iDaaS KIC is where audit and other related data for the platform is stored. Like the rest of iDaaS it is intended to be extensible. iDaaS Data KIC is a platform to enable processing of
                        data into the various components and data models included. The key things Data Hub is meant to ensure resources have data driven insights from ANY activity the iDaaS
                        platform will do. A key thing to note in the data model and events the system focuses on is a way to associate one organization to many healthcare entities and to many
                        applications and within each application any components wished to be defined. This is ALL up to the implementation. Because of this data
                        enablement iDaaS focuses on enabling a detailed eventing model to iDaaS Data Hub for any activities the system does, this specifically is
                        done through a transaction event which has a rich set of data attributes to enable detailed insight.
                        <a href="https://github.com/RedHat-Healthcare/iDaaS-KIC/tree/master/iDaaS-KIC-Integration" target="_blank">iDaas KIC Integration</a> specifically deals with the 
                        processing of all iDaaS Auditing events for scale and performance into both JSON documents and also a RDBMS table set.
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
    <br />

    <div align="left">
        <p>
            We are also continuing to work on new and innovative components to help enable "Data as the asset" building efforts.
        </p>
    </div>
    <br />
    <div align="left">
        <table class="table table-striped">
            <thead class="thead-dark">
                <tr>
                    <th scope="col">Capability</th>
                    <th scope="col">Component</th>
                    <th scope="col">Component Desc.</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Testing - Build Synthetic (Fictitious) Data</td>
                    <td><a href="https://github.com/RedHat-Healthcare/DataSynthesis" target="_blank">Data Synthesis</a></td>
                    <td>
                        This component is specifically designed to enable implementors to quickly build fictitious data for testing. It has over 30B data attributes
                        including names, address, phone numbers, zip codes, company names, drivers licenses, social security numbers, credit cards, bank routing numbers,
                        UPC product codes and much more. All of the data is contained with a MySQL8 database which the dump for it can be easily downloaded and imported.
                        There are also a few other projects as well that are intended (over time) to enable the community to develop and deliver coding capabilities from
                        the extensive data tier. The project that has code artifacts for generating data and APis is located 
                        <a href="https://github.com/RedHat-Healthcare/DataSynthesis/tree/master/Java-APIs" target="_blank">here</a>.  As of February we started working on an 
                        Express Javascript API layer as well with a potential  to add a project based on .Net Core.
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
</div>

</body>
</html>