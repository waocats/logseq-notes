tags:: Microsoft Azure, Microsoft Azure/AZ-900
alias:: Azure Virtual Networks

-
- **Azure virtual networks (and virtual subnets) enable Azure resources to communicate with:**
	- ***Each other***
		- Virtual networks can connect resources such as the App Service Environment for Power Apps, Azure Kubernetes Service, and Azure virtual machine scale sets
		- Service endpoints can connect to other Azure resource types, such as Azure SQL databases and storage accounts
			- This allows for improved security and optimal routing between resources
	- ***Users on the internet***
	- ***On-premises resources***
		- *Point-to-site* virtual private network connections are from a computer outside of your organization back into your corporate network
		  id:: 64ad84f7-8b80-4ba7-bbd2-5438a132a52a
			- The client computer initiates an encrypted VPN connection to connect to the virtual network
			  id:: 64ad8681-90a0-487f-b524-dc2492a0d1bd
		- *Site-to-site* virtual private networks link an on-premises VPN device or gateway to the Azure VPN gateway
		  id:: 64ad8529-0b04-482c-9190-620a92ea1bce
			- In effect, the devices can appear as being on the local network
			  id:: 64ad8540-c681-4e07-8320-320ae45ecfb6
			- The connection works over the internet and is encrypted
			  id:: 64ad854c-df7b-4285-a21d-7a756c832978
		- [Azure ExpressRoute]([[Microsoft Azure/ExpressRoute]]) provides a dedicated private connectivity that doesn't travel over the internet
		  id:: 64ad86b2-419e-4cd6-9a5f-b6d9c7c1dfc2
			- Useful for environments where you need greater bandwidth and even higher levels of security
			  id:: 64ad86d2-1ed1-4b9b-813c-0cac110e3dd7
-
- **Additionally, they provide the following *key networking capabilities:* **
	- **Isolation and segmentation**
		- When you set up a virtual network, you can define a private IP address space (which only exists within the virtual network and isn't internet routable) using either public or private IP address ranges
	- **Route and filter network traffic**
		- *Network security groups* can contain multiple inbound and outbound security rules
			- For example, you can allow/block based on source/destination IP address, port, and protocol
		- *Network virtual appliances* are specialized VMs that are comparable to a hardened network appliance
			- These carry out a particular function, such as running a firewall or performing WAN optimization
	- **Connect virtual networks**
-
- **Virtual networks support both *public* and *private* endpoints**
	- Public endpoints have a public IP address and can be accessed from anywhere
	- Private endpoints exist within a virtual network and have a private IP address from within the address space of that virtual network