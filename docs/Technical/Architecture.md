<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/html">
<head>
    <meta charset="UTF-8">
    <title>Connected Health / iDaaS (Intelligent Data As A Service) Architecture</title>
</head>
<body>
    
<br/>
<div class="text-center">
    <h4 class="display-6">Architecture</h4>
    <br/><br/>
    <div align="left">
        <p>
            As you saw on our <a href="~/home/Index" target="_blank">main page</a> in the Design Principals section we 
            wanted to ensure a very sound set of principles with anything that we helped develop, or deliver to the 
            healthcare market. As it turns out we did not have to develop much at all, it has mostly been about taking the amazing 
            contributions of dozens of organizations, consultants, and architects. We focused on delivering our capabilities 
            whle shaping the assets into what the healthcare industry could leverage. As this effort was going on we world 
            started to struggle with the Covid-19 pandemic and shortly after this started the US healthcare system was needing 
            to address the CMS Interoperability Final Rule.
            <br/>
        </p>
    </div>
    <div align="left">
        <p>
            <b> Conceptual Architecture </b><br/>
            As we looked at the contributions and all the principals we had we quickly took stock of how many Red Hat customers
            were leveraging these capabilities. With such a wide variety of healthcare business leveraging these existing
            capabilities we moved to q high level conceptual architecture of what the iDaaS platform looked like:
            <br/><br/>
            <div align="center">
                <img src="~/img/platform/iDaaSPlatform-iDaaSDataFlow-Detailed.png" width="850" height="650"/>
            </div>
        </p>
    </div>
     <div align="left">
         <p>
             <b> Extensible Architecture </b><br/>
             After validating and vetting the high level conceptual architecture of what the iDaaS platform looked like we 
             started constructing a physical architecture focused on scale, reusability, and extensibility. A key part of
             this extensoble architecture was reusability. As we focused on reusability went back and were able to not only
             validate our <a href="~/home/Capabilities" target="_blank">capabilities</a> but also ensure the capabilities were
             able to address the industry needs.
             <br/><br/>
             <div align="center">
                <img src="~/img/platform/iDaaS Platform - Visuals - iDaaS Data Flow and ModulesFHIR Modules.png" width="650" height="650"/>
             </div>
         </p>
        </div>
</div>
</body>
</html>