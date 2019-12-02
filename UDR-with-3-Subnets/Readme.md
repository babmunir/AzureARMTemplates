azure arm templates for UDR, after deploying this template we can have

    one VNet and 3 Subnets
    A Windows 2016 DC VM in each subnet
    An NSG with allowing RDP 3389 for VMs
    A routing table that will allow traffic through NVM and will be associated to subnet 1.
    A network interface fo each VM and a Public IP will be assoiated to each interface
