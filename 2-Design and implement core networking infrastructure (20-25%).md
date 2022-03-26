# AZ-700: Design and implement core networking infrastructure (20-25%)

## Design and implement private IP addressing for VNets
- [Create a VNet](https://docs.microsoft.com/en-us/azure/virtual-network/quick-create-portal)
- Plan and configure subnetting for services, including:
    - [VNet gateways](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)
    - [Private Endpoints](https://docs.microsoft.com/en-us/azure/private-link/private-endpoint-overview)
    - Firewalls
    - Application Gateways
    - VNet-integrated platform services
        - [Integrate your app with an Azure virtual network](https://docs.microsoft.com/en-us/azure/app-service/overview-vnet-integration)
- [Plan and configure subnet delegation](https://docs.microsoft.com/en-us/azure/virtual-network/manage-subnet-delegation)
- Plan and configure subnetting for Azure Route Server
    - [Create and configure Route Server using the Azure portal](https://docs.microsoft.com/en-us/azure/route-server/quickstart-configure-route-server-portal)
    - [Azure Route Server overview](https://docs.microsoft.com/en-us/azure/route-server/overview)
    - [Route Server FAQ](https://docs.microsoft.com/en-us/azure/route-server/route-server-faq)
    - [Troubleshooting Azure Route Server issues](https://docs.microsoft.com/en-us/azure/route-server/troubleshoot-route-server)
    - [Configure peering between Azure Route Server and Quagga network virtual appliance](https://docs.microsoft.com/en-us/azure/route-server/tutorial-configure-route-server-with-quagga)

## Design and implement name resolution
- [Design public DNS zones](https://docs.microsoft.com/en-us/azure/dns/dns-getstarted-portal)
- [Design private DNS zones](https://docs.microsoft.com/en-us/azure/dns/private-dns-getstarted-portal)
- [Design name resolution inside a VNet](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-name-resolution-for-vms-and-role-instances)
- [Configure a public DNS zone](https://docs.microsoft.com/en-us/azure/dns/dns-getstarted-portal)
- [Configure a private DNS zone](https://docs.microsoft.com/en-us/azure/dns/private-dns-getstarted-portal)
- Link a private DNS zone to a VNet
    - [Virtual network link](https://docs.microsoft.com/en-us/azure/dns/private-dns-virtual-network-links)

## Design and implement cross-VNet connectivity
- [Design service chaining, including gateway transit](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-peering-gateway-transit)
- [Design VPN connectivity between VNets](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-vnet-vnet-resource-manager-portal)
- [Implement VNet peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview)
    - [Create, change, or delete a virtual network peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering)

## Design and implement an Azure Virtual WAN architecture
- [Design an Azure Virtual WAN architecture, including selecting types and services](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-about)
- [Connect a VNet gateway to Azure Virtual WAN](https://docs.microsoft.com/en-us/azure/virtual-wan/connect-virtual-network-gateway-vwan)
- [Create a Hub in Virtual WAN](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-site-to-site-portal)
- [Create a Network Virtual Appliance (NVA) in a virtual hub](https://docs.microsoft.com/en-us/azure/virtual-wan/how-to-nva-hub)
- [Configure virtual hub routing](https://docs.microsoft.com/en-us/azure/virtual-wan/how-to-virtual-hub-routing)
- [Create a connection unit](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-faq)

[Return to Table of Contents](README.md)