# Title: Deploy Three Tier Architecture
This template could be useful in quickly deploy the resources for below scenerios:-

Cloud born Three tier application architecture with web and application layer

This template can be customised to meet the requirement of deploying three tier architecture for the Hybrid scenerios

Rehosting of apllications from onprem to cloud

Quickly deploy POCs set up for application workload testing



# Solution overview and deployed resources. 



## Target audience
Infrastructure Architect

Application Developer

IT Professional

Cloud Solution Architect


# Architecture

N-tier architecture on virtual machines
![alt image](https://github.com/nikhil7891/Deploy-Three-Tier-Architecture/blob/master/Reference_Architecture.JPG)

The Template.json Azure Resource Manager template will help you automatically deploy the diagram below, which includes:
![alt image](https://github.com/nikhil7891/Deploy-Three-Tier-Architecture/blob/master/Architecture.png)




[Template.json](https://github.com/nikhil7891/Deploy-Three-Tier-Architecture/blob/master/template.json) can be modified to match your current infrastructure needs.

## One Click Deploying Template
<!-- Powershell command for Translating Git URL for template.json
    $url = "https://raw.githubusercontent.com/nikhil7891/Deploy-Three-Tier-Architecture/master/template.json"
    [uri]::EscapeDataString($url)
    >> uri = https%3A%2F%2Fraw.githubusercontent.com%2Fnikhil7891%2FDeploy-Three-Tier-Architecture%2Fmaster%2Ftemplate.json

Base URL: https://portal.azure.com/#create/Microsoft.Template/uri
Final URL: <Base URL>/<uri>
-->
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnikhil7891%2FDeploy-Three-Tier-Architecture%2Fmaster%2Ftemplate.json)


## Deploying an ARM Template using the Azure portal
Visit https://portal.azure.com

Allow 5-10 minutes for the deployment to complete

## Azure services and related products
Resource Group

Azure virtual Network (with Subnets)

Azure Storage Account

Azure Virtual Machine

Network Security Group

## Deployment steps



## Related references
https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/n-tier

https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/n-tier/n-tier-sql-server

https://docs.microsoft.com/en-us/azure/architecture/high-availability/ref-arch-iaas-web-and-db

## License & Contribute

You are responsible for the performance, the necessary testing, and if needed any regulatory clearance for any of the models produced by this toolbox.
Please refer [LICENSE](LICENSE) &  [Contribute](https://github.com/nikhil7891/Deploy-Three-Tier-Architecture/blob/master/Contribute.md) for more details


