@{
    ViewData["Title"] = "Connected Health / iDaaS Use Cases";
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Connected Health / iDaaS (Intelligent Data As A Service) - Platform Components</title>
</head>
<body>

    <br />
<div class="text-center">
    <h4 class="display-6">Connected Health / iDaaS (Intelligent Data as A Service) Use Cases</h4>
    <br />
    <p>
        Connected Health / iDaaS is all about transforming the way the healthcare industry can interact with data and information.
        As part of that we understand the importance of ensuring we convey specific use cases/scenarios .
    </p>
</div>
<br/>
<div class="text-center">
    <h4 class="display-8">HL7 v2 Messaging</h4>
    <br />
    <p>
        The following specific use cases involve how iDaaS works with HL7 v2.x messaging. It is important to know that we DO NOT limit the version or shape of data from ANY vendor.
        Please look <a href="/Home/SupportedTransactions" target="_blank"> here </a> to see the natively supported transactions 
    </p>
</div>

<br />
<div align="left">
    <table class="table table-striped">
        <thead class="thead-dark">
        <tr>
            <th scope="col">Use Case Name</th>
            <th scope="col">Code Repositories To Leverage</th>
            <th scope="col">Use Case Desc.</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>Receiving </td>
            <td><a href="https://github.com/RedHat-Healthcare/iDaaS-Connect-Clinical-IndustryStandards" target="_blank"> iDaaS Connect Clinical - Industry Standards</a></td>
            <td>
                This connects specifically to clinical integration standards and specific protocols that might be required.
                For this component it is designed to connect to HL7v2 and FHIR based transactions. For this specific use case are ONLY From an integration connectivity and standards
                perspective it can demonstrates the processing HL7v2 messages of the following types from any vendor and any specific message
                version from 2.1 to 2.8: ADT (Admissions), ORM (Orders), ORU (Results), SCH (Schedules), PHA (Pharmacy), MFN (Master File Notifications),
                MDM (Medical Document Management) and VXU (Vaccinations). 
            </td>
        </tr>
        </tbody>
    </table>
</div>

    <p>
        We also wanted to ensure simple means to test and implement the platform so we have several components to leverage in this space
    </p>
    <br />
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
                    <td>Testing </td>
                    <td><a href="https://github.com/RedHat-Healthcare/iDaaSTestingComponent" target="_blank">iDaaS Testing Component</a></td>
                    <td>
                        This component is specifically designed to test the platform component with a small subset of components for HL7 and FHIR data processing
                        including the Healthcare data distribution enterprise integration pattern (HCDD-EIP).
                    </td>
                </tr>
            </tbody>
        </table>
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
                    <td>Testing  - Message Simulation</td>
                    <td>Message Simulation</td>
                    <td>
                        This component is specifically designed to enable implementors to quickly connect and test with clinical and financial healthcare information with the platform component with a small subset of components for HL7 and FHIR data processing
                        including the Healthcare data distribution enterprise integration pattern (HCDD-EIP).
                    </td>
                </tr>
            </tbody>
        </table>
    </div>

</body>
</html>