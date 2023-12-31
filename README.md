---
description: This template deploys an Active Directory lab environment consisting of 3 Azure VMs, with one domain controller and two domain-joined member servers
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: active-directory-new-domain
languages:
- arm
- json
---
# Create an Azure VM with a new AD Forest

![Azure Public Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/PublicDeployment.svg)

![Azure US Gov Last Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/FairfaxLastTestDate.svg)
![Azure US Gov Last Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/FairfaxDeployment.svg)

![Best Practice Check](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/BestPracticeResult.svg)
![Cred Scan Check](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/CredScanResult.svg)

![Bicep Version](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/BicepVersion.svg)

This template will provision an Azure VM (along with a new virtual network) hosting an Active Directory domain controller in a new single-domain forest, followed by provisioning of two domain member servers into another subnet in the same virtual network.

Click the button below to deploy

[![Deploy To Azure](https://raw.githubusercontent.com/mpolicht/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmpolicht%2Fsms-lab%2Fmain%2Fazuredeploy.json)  [![Deploy To Azure US Gov](https://raw.githubusercontent.com/mpolicht/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmpolicht%2Fsms-lab%2Fmain%2Fazuredeploy.json)  [![Visualize](https://raw.githubusercontent.com/mpolicht/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmpolicht%2Fsms-lab%2Fmain%2Fazuredeploy.json)

`Tags: Microsoft.Network/publicIPAddresses, Microsoft.Compute/availabilitySets, Microsoft.Resources/deployments, Microsoft.Network/loadBalancers, Microsoft.Network/networkInterfaces, Microsoft.Compute/virtualMachines, extensions, DSC, Microsoft.Network/virtualNetworks`
