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

## Design and implement service endpoints
- [Create service endpoints]()
- [Configure service endpoint policies]()
- [Configure service tags]()
- [Configure access to service endpoints]()

## Configure VNet integration for dedicated platform as a service (PaaS) services
- [Configure App Service for regional VNet integration]()
- [Configure Azure Kubernetes Service (AKS) for regional VNet integration]()
- [Configure clients to access App Service Environmen]()

[Return to Table of Contents](README.md)