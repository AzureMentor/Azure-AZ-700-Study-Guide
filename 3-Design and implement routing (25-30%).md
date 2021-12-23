# AZ-700: Design and Implement Routing (25–30%)

## Design, implement, and manage VNet routing
- [Design and implement User-Defined Routes (UDRs)](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-udr-overview#user-defined) | [Tutorial: Route network traffic with a route table using the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-create-route-table-portal)
- [Associate a Route Table with a subnet](https://docs.microsoft.com/en-us/azure/virtual-network/manage-route-table#associate-a-route-table-to-a-subnet)
- [Configure forced tunneling](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-forced-tunneling-rm)
- [Diagnose and resolve routing issues](https://docs.microsoft.com/en-us/azure/virtual-network/diagnose-network-routing-problem)
    - [Diagnose a virtual machine network routing problem - Azure PowerShell](https://docs.microsoft.com/en-us/azure/network-watcher/diagnose-vm-network-routing-problem-powershell)
    - [Diagnose a virtual machine network routing problem - Azure CLI](https://docs.microsoft.com/en-us/azure/network-watcher/diagnose-vm-network-routing-problem-cli)

## Design and implement an Azure Load Balancer
- [Choose an Azure Load Balancer SKU (Basic versus Standard)](https://docs.microsoft.com/en-us/azure/load-balancer/skus)
- [Choose between Public and Internal Azure Load Balancer](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)
    - [Quickstart: Create a public load balancer to load balance VMs using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/quickstart-load-balancer-standard-public-portal)
    - [Quickstart: Create an internal load balancer to load balance VMs using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/quickstart-load-balancer-standard-internal-portal)
- [Create and configure an Azure Load Balancer (including Cross-Region)](https://docs.microsoft.com/en-us/azure/load-balancer/tutorial-cross-region-portal)
- [Implement a load balancing rule](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-load-balancer#create-a-load-balancer-rule)
- [Create and configure inbound NAT rules](https://docs.microsoft.com/en-us/azure/load-balancer/tutorial-load-balancer-port-forwarding-portal#create-an-inbound-nat-port-forwarding-rule)
- [Create explicit outbound rules for a load balancer](https://docs.microsoft.com/en-us/azure/load-balancer/outbound-rules)

## Design and implement Azure Application Gateway
- Recommend Azure Application Gateway deployment options
    - [Quickstart: Direct web traffic with Azure Application Gateway - Azure portal](https://docs.microsoft.com/en-us/azure/application-gateway/quick-create-portal)
    - [Quickstart: Direct web traffic with Azure Application Gateway - Azure PowerShell](https://docs.microsoft.com/en-us/azure/application-gateway/quick-create-powershell)
    - [Quickstart: Direct web traffic with Azure Application Gateway - Azure CLI](https://docs.microsoft.com/en-us/azure/application-gateway/quick-create-cli)
    - [Quickstart: Direct web traffic with Azure Application Gateway - ARM template](https://docs.microsoft.com/en-us/azure/application-gateway/quick-create-template)
- [Choose between Manual and Autoscale](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-autoscaling-zone-redundant#scaling-application-gateway-and-waf-v2)
- [Create a back-end pool](https://docs.microsoft.com/en-us/azure/application-gateway/quick-create-portal#backends-tab)
- [Configure Health Probes](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-create-probe-portal#create-probe-for-application-gateway-v2-sku)
- [Configure Application Gateway Listeners](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-listeners)
- [Configure Application Gateway Routing Rules](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-request-routing-rules)
- [Configure Application Gateway HTTP settings](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-http-settings)
- Configure Transport Layer Security (TLS)
    - [Configure end-to-end TLS by using Application Gateway with Azure portal](https://docs.microsoft.com/en-us/azure/application-gateway/end-to-end-ssl-portal)
    - [Configure end to end TLS by using Application Gateway with PowerShell](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-end-to-end-ssl-powershell)
- [Configure URL Rewrite policies](https://docs.microsoft.com/en-us/azure/application-gateway/rewrite-url-portal)

## Implement Azure Front Door
- [Choose an Azure Front Door SKU]()
- [Configure health probes, including customization of HTTP response codes]()
- [Configure SSL termination and end-to-end SSL encryption]()
- [Configure multisite listeners]()
- [Configure back-end targets]()
- [Configure routing rules, including redirection rules]()

## Implement an Azure Traffic Manager profile
- [Configure a routing method (mode)]()
- [Configure endpoints]()
- [Create HTTP settings]()

## Design and implement an Azure Virtual Network NAT
- [Choose when to use a Virtual Network NAT]()
- [Allocate public IP or public IP prefixes for a NAT gateway]()
- [Associate a Virtual Network NAT with a subnet]()

[Return to Table of Contents](README.md)