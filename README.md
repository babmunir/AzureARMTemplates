# AzureARMTemplates
azure arm templates for UDR, after deploying this template we can have
1) one VNet and 3 Subnets
2) A Windows 2016 DC VM in each subnet
3) An NSG with allowing RDP 3389 for VMs
4) A routing table that will allow traffic through NVM and will be associated to subnet 1.
5) A network interface fo each VM and a Public IP will be assoiated to each interface
