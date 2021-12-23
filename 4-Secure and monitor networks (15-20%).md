# AZ-700: Secure and Monitor Networks (15–20%)

## Design, implement, and manage an Azure Firewall deployment
- [Design an Azure Firewall deployment](https://docs.microsoft.com/en-us/azure/firewall/tutorial-firewall-deploy-portal)
    - [What is Azure Firewall?](https://docs.microsoft.com/en-us/azure/firewall/overview)
    - [Azure Firewall Standard features](https://docs.microsoft.com/en-us/azure/firewall/features)
    - [Azure Firewall Premium features](https://docs.microsoft.com/en-us/azure/firewall/premium-features)
- [Create and implement an Azure Firewall deployment](https://docs.microsoft.com/en-us/azure/firewall/deploy-ps)
    -[Tutorial: Deploy and configure Azure Firewall and policy using the Azure portal](https://docs.microsoft.com/en-us/azure/firewall/tutorial-firewall-deploy-portal-policy)
- [Configure Azure Firewall rules](https://docs.microsoft.com/en-us/azure/firewall/rule-processing)
    - [Use fully qualified domain name (FQDN) filtering in network rules](https://docs.microsoft.com/en-us/azure/firewall/fqdn-filtering-network-rules)
    - [Configure Azure Firewall application rules with SQL FQDNs](https://docs.microsoft.com/en-us/azure/firewall/sql-fqdn-filtering)
- [Create and implement Azure Firewall Manager policies](https://docs.microsoft.com/en-us/azure/firewall-manager/policy-overview)
- [Create a secure hub by deploying Azure Firewall inside an Azure Virtual WAN hub](https://docs.microsoft.com/en-us/azure/virtual-wan/howto-firewall)
    - [Tutorial: Secure your virtual hub using Azure Firewall Manager](https://docs.microsoft.com/en-us/azure/firewall-manager/secure-cloud-network)
- [Integrate an Azure Virtual WAN hub with a 3rd-party Network Virtual Appliance (NVA)](https://docs.microsoft.com/en-us/azure/virtual-wan/about-nva-hub)
    - [Scenario: Route traffic through a Network Virtual Appliance (NVA)](https://docs.microsoft.com/en-us/azure/virtual-wan/scenario-route-through-nva)

## Implement and manage Network Security Groups (NSGs)
- [Create an NSG](https://docs.microsoft.com/en-us/azure/virtual-network/manage-network-security-group#create-a-network-security-group)
- [Associate an NSG to a resource](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-network-interface#associate-or-dissociate-a-network-security-group)
    - [Associate an NSG to a subnet](https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-filter-network-traffic#associate-network-security-group-to-subnet)
- [Create an Application Security Group (ASG)](https://docs.microsoft.com/en-us/azure/virtual-network/application-security-groups)
    - [Create Application Security Groups](https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-filter-network-traffic#create-application-security-groups)
- [Associate an ASG to a NIC](https://docs.microsoft.com/en-us/azure/virtual-network/application-security-groups)
    - [Associate or dissociate a Network Security Group](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-network-interface#associate-or-dissociate-a-network-security-group)
- [Create and configure NSG rules](https://docs.microsoft.com/en-us/azure/virtual-network/manage-network-security-group#create-a-security-rule)
- [Read NSG flow logs](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-read-nsg-flow-logs)
    - [Tutorial: Log network traffic to and from a virtual machine using the Azure portal](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-nsg-flow-logging-portal)
- Validate NSG flow rules
    - [Introduction to flow logging for network security groups](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-nsg-flow-logging-overview)
- [Verify IP flow](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-ip-flow-verify-overview)

## Implement a Web Application Firewall (WAF) deployment
- [Configure detection or prevention mode](https://docs.microsoft.com/en-us/azure/web-application-firewall/ag/ag-overview#waf-modes)
    - Detection mode
        - Monitors and logs all threat alerts.
        - You turn on logging diagnostics for Application Gateway in the Diagnostics section.
        - You must also make sure that the WAF log is selected and turned on.
        - Web application firewall does not block incoming requests when it is operating in Detection mode.
    - Prevention mode
        - Blocks intrusions and attacks that the rules detect.
        - The attacker receives a "403 unauthorized access" exception, and the connection is closed.
        - Prevention mode records such attacks in the WAF logs.
    - [Configure Web Application Firewall rules](https://docs.microsoft.com/en-us/azure/web-application-firewall/afds/waf-front-door-create-portal#change-mode)
- [Configure rule sets for Azure Front Door, including Microsoft managed and user defined](https://docs.microsoft.com/en-us/azure/web-application-firewall/afds/waf-front-door-custom-rules)
    - [Web Application Firewall DRS rule groups and rules](https://docs.microsoft.com/en-us/azure/web-application-firewall/afds/waf-front-door-drs?tabs=drs20)
    - [Default Rule Set (DRS)](https://docs.microsoft.com/en-us/azure/web-application-firewall/afds/waf-front-door-create-portal#default-rule-set-drs)
- Configure rule sets for Application Gateway, including Microsoft managed and user defined
    - [Custom rules for Web Application Firewall v2 on Azure Application Gateway](https://docs.microsoft.com/en-us/azure/web-application-firewall/ag/custom-waf-rules-overview)
    - [Web Application Firewall CRS rule groups and rules](https://docs.microsoft.com/en-us/azure/web-application-firewall/ag/application-gateway-crs-rulegroups-rules?tabs=owasp31)
- [Implement a WAF policy](https://docs.microsoft.com/en-us/azure/web-application-firewall/ag/create-waf-policy-ag)
- [Associate a WAF policy](https://docs.microsoft.com/en-us/azure/web-application-firewall/ag/associate-waf-policy-existing-gateway)

## Monitor networks 
- [Configure Network Health Alerts and Logging by using Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/network-insights-overview#networkhealth)
- [Create and configure a Connection Monitor instance](https://docs.microsoft.com/en-us/azure/network-watcher/connection-monitor-create-using-portal)
- [Configure and use Traffic Analytics](https://docs.microsoft.com/en-us/azure/network-watcher/traffic-analytics)
- Configure NSG flow logs
    - [Configuring Network Security Group Flow logs with Azure PowerShell](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-nsg-flow-logging-powershell)
    - [Configuring Network Security Group Flow logs with Azure CLI](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-nsg-flow-logging-powershell)
    - [Configure NSG Flow Logs from an ARM template](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-nsg-flow-logging-azure-resource-manager)
- [Enable and configure diagnostic logging](https://docs.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings)
    - [Resource logging for a Network Security Group](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-nsg-manage-log)
- [Configure Azure Network Watcher](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-create)
    - [What is Azure Network Watcher?](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-monitoring-overview)

[Return to Table of Contents](README.md)