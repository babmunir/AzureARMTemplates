This template will create two different address space VNets in same location, following will also be deployed once template is executed.
1) Two Vnets and each containing a single subnet
2) one Windows Vm in each Subnet
3) One Nic for each VM
4) one public IP address for each VM
5) one NSG in each VNet and allow RDP 3389 for accessing VM over public IP

once deployment is completed, we can test it by pinging each VM wihtin VMs

