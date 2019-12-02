azure arm templates for UDR with NVA, after deploying this template we can have

    one VNet and 3 Subnets
    A Windows 2016 DC VM in each subnet
    An NSG with allowing RDP 3389 for VMs
    A routing table that will allow traffic through NVM and will be associated to subnet 1.
    A network interface fo each VM and a Public IP will be assoiated to each interface
    At the end, enable IP routing within NVM using registry otherwise traffic will not pass through this VM. HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters and set the value 1 to IPEnableRouter
