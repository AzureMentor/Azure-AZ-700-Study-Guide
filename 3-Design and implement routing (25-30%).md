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
- [Choose an Azure Front Door SKU](https://docs.microsoft.com/en-us/azure/frontdoor/standard-premium/tier-comparison)
- [Configure Health Probes, including customization of HTTP response codes](https://docs.microsoft.com/en-us/azure/////frontdoor/front-door-health-probes)
- [Configure SSL termination and end-to-end SSL encryption](https://docs.microsoft.com/en-us/azure/frontdoor/standard-premium/how-to-configure-https-custom-domain)
- [Configure multi-site listeners](https://docs.microsoft.com/en-us/azure/application-gateway/multiple-site-overview#wildcard-host-names-in-listener)
- [Configure back-end targets in Azure Front Door](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-backend-pool)
- [Configure routing rules, including redirection rules](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-how-to-redirect-https)

## Implement an Azure Traffic Manager profile
- [Configure an Azure Traffic Manager routing method (mode)](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods) | [Tutorial: Configure priority traffic routing method in Traffic Manager](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-configure-priority-routing-method)
    - [Priority](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods#priority-traffic-routing-method) - to have a primary service endpoint for all traffic. You can provide multiple backup endpoints in case the primary or one of the backup endpoints is unavailable
    - [Weighted](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods#weighted) - to distribute traffic across a set of endpoints based on their weight. Set the weight the same to distribute evenly across all endpoints
    - [Performance](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods#performance) - to have endpoints in different geographic locations and you want end users to use the "closest" endpoint for the lowest network latency
    - [Geographic](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods#geographic) - to direct users to specific endpoints (Azure, External, or Nested) based on where their DNS queries originate from geographically. With this routing method, it enables you to be in compliance with scenarios such as data sovereignty mandates, localization of content & user experience and measuring traffic from different regions
    - [Multivalue](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods#multivalue) - Select MultiValue for Traffic Manager profiles that can only have IPv4/IPv6 addresses as endpoints. When a query is received for this profile, all healthy endpoints are returned
    - [Subnet](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods#subnet) - to map sets of end-user IP address ranges to a specific endpoint. When a request is received, the endpoint returned will be the one mapped for that request’s source IP address
- [Configure Azure Traffic Manager Endpoints](https://docs.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile#add-traffic-manager-endpoints)
- Create HTTP settings
    - [Azure Traffic Manager endpoint monitoring](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-monitoring)

## Design and implement an Azure Virtual Network NAT
- [Choose when to use a Virtual Network Address Translation (NAT)](https://docs.microsoft.com/en-us/azure/virtual-network/nat-gateway/nat-overview)
- Allocate public IP or public IP prefixes for a NAT gateway
    - [Design virtual networks with NAT gateway](https://docs.microsoft.com/en-us/azure/virtual-network/nat-gateway/nat-gateway-resource)
    - [Tutorial: Create a NAT gateway using Azure portal](https://docs.microsoft.com/en-us/azure/virtual-network/nat-gateway/tutorial-create-nat-gateway-portal#nat-gateway)
- Associate a Virtual Network NAT with a subnet
    - [Tutorial: Create a NAT gateway using Azure portal](https://docs.microsoft.com/en-us/azure/virtual-network/nat-gateway/tutorial-create-nat-gateway-portal)
    - [Tutorial: Create a NAT gateway using Azure PowerShell](https://docs.microsoft.com/en-us/azure/virtual-network/nat-gateway/tutorial-create-nat-gateway-powershell)
    - [Tutorial: Create a NAT gateway using Azure CLI](https://docs.microsoft.com/en-us/azure/virtual-network/nat-gateway/tutorial-create-nat-gateway-cli)

[Return to Table of Contents](README.md)