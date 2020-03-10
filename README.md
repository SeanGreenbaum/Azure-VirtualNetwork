# Azure-VirutalNetwork
JSON to build VNets in Azure

These JSON templates take the name of the Resource Group, and name the vNet ResourceGroupName-NET.
It also creates a Subnet named Subnet1.

You must provided the address space for both the vNet and Subnet1.

Deploy a Virtual Network (use Azure for DNS - Default) <a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSeanGreenbaum%2FAzure-VirtualNetwork%2Fmaster%2Fvnet.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/> </a>

Deploy a Virtual Network using custom DNS <a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSeanGreenbaum%2FAzure-VirtualNetwork%2Fmaster%2Fvnet-customDNS.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/> </a>