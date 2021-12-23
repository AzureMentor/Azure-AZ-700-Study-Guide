# AZ-700: Design and implement Private access to Azure Services (10-15%)

## Design and implement Azure Private Link service and Azure Private Endpoint
- Plan a Private Link service
    - [What is Azure Private Link service?](https://docs.microsoft.com/en-us/azure/private-link/private-link-service-overview)
        - Azure Private Link service is the reference to your own service that is powered by Azure Private Link.
        - Your service that is running behind Azure Standard Load Balancer can be enabled for Private Link access so that consumers to your service can access it privately from their own VNets.
        - Your customers can create a Private Endpoint inside their VNet and map it to this service.
- Create a Private Link service
    - [Quickstart: Create a Private Link service using Azure portal](https://docs.microsoft.com/en-us/azure/private-link/create-private-link-service-portal)
    - [Quickstart: Create a Private Link service using Azure PowerShell](https://docs.microsoft.com/en-us/azure/private-link/create-private-link-service-powershell)
    - [Quickstart: Create a Private Link service using Azure CLI](https://docs.microsoft.com/en-us/azure/private-link/create-private-link-service-cli)
    - [Quickstart: Create a Private Link service using an ARM template](https://docs.microsoft.com/en-us/azure/private-link/create-private-link-service-template)
- Plan Azure Private Endpoints
    - [What is Azure Private Endpoint?](https://docs.microsoft.com/en-us/azure/private-link/private-endpoint-overview)
        - A Private Endpoint is a network interface that uses a Private IP address from your virtual network.
        - This network interface connects you privately and securely to a service powered by Azure Private Link.
        - By enabling a Private Endpoint, you are bringing the service into your virtual network.
- Create Private Endpoints
    - [Quickstart: Create an Azure Private Endpoint using Azure portal](https://docs.microsoft.com/en-us/azure/private-link/create-private-endpoint-portal)
    - [Quickstart: Create an Azure Private Endpoint using Azure PowerShell](https://docs.microsoft.com/en-us/azure/private-link/create-private-endpoint-powershell)
    - [Quickstart: Create an Azure Private Endpoint using Azure CLI](https://docs.microsoft.com/en-us/azure/private-link/create-private-endpoint-cli)
    - [Quickstart: Create an Azure Private Endpoint using an ARM template](https://docs.microsoft.com/en-us/azure/private-link/create-private-endpoint-template)
    - [Manage a Private Endpoint connection](https://docs.microsoft.com/en-us/azure/private-link/manage-private-endpoint)
- Configure access to Private Endpoints
    - [Using Private Endpoints for Azure App Configuration](https://docs.microsoft.com/en-us/azure/azure-app-configuration/concept-private-endpoint)
    - [Use Private Endpoints for Azure Storage](https://docs.microsoft.com/en-us/azure/storage/common/storage-private-endpoints)
- [Integrate Private Link with DNS](https://docs.microsoft.com/en-us/azure/private-link/private-endpoint-dns)
    - [Private Link and DNS integration at scale](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/private-link-and-dns-integration-at-scale)
- Integrate a Private Link service with on-premises clients
    - [Tutorial: Connect to an Azure SQL server using an Azure Private Endpoint - Azure portal](https://docs.microsoft.com/en-us/azure/private-link/tutorial-private-endpoint-sql-portal)

## Design and implement Service Endpoints
- Create Service Endpoints
    - [Tutorial: Restrict network access to PaaS resources with virtual network Service Endpoints using the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-restrict-network-access-to-resources)
- Configure Service Endpoint policies
    - [Create, change, or delete Service Endpoint policy using the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoint-policies-portal)
    - [Manage data exfiltration to Azure Storage accounts with Virtual network Service Endpoint policies using Azure PowerShell](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoint-policies-powershell)
    - [Manage data exfiltration to Azure Storage accounts with virtual network Service Endpoint policies using the Azure CLI](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoint-policies-cli)
- [Configure Virtual Network Service Tags](https://docs.microsoft.com/en-us/azure/virtual-network/service-tags-overview)
- [Configure access to Service Endpoints](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoints-overview)
    - [Allow access to Azure Service Bus namespace from specific virtual networks](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-service-endpoints)

## Configure VNet integration for dedicated platform as a service (PaaS) services
- Configure App Service for regional VNet integration
    - [Integrate your app with an Azure virtual network](https://docs.microsoft.com/en-us/azure/app-service/overview-vnet-integration)
    - [Enable virtual network integration in Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/configure-vnet-integration-enable)
- Configure Azure Kubernetes Service (AKS) for regional VNet integration
    - [Create a private Azure Kubernetes Service cluster](https://docs.microsoft.com/en-us/azure/aks/private-clusters)
- [Configure clients to access App Service Environment (ASE) v3](https://docs.microsoft.com/en-us/azure/app-service/environment/creation)
    - [ASE v1](https://docs.microsoft.com/en-us/Azure/app-service/environment/app-service-web-configure-an-app-service-environment)
    - [ASE v2](https://docs.microsoft.com/en-us/azure/app-service/environment/using-an-ase#app-access)

[Return to Table of Contents](README.md)