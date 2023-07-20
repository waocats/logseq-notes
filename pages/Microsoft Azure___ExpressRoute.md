tags:: Microsoft Azure, Microsoft Azure/AZ-900
alias:: Azure ExpressRoute

-
- **Allows for *extending on-premises networks into the Microsoft Cloud over a private connection* with the help of a connectivity provider**
	- This connection is called an *ExpressRoute circuit*
		- Offices, datacenters, or other facilities can be connected to the Microsoft cloud through its own ExpressRoute circuit
-
- **Using ExpressRoute comes with multiple benefits:**
	- Connectivity to Microsoft cloud services across all regions in the geopolitical region
		- ExpressRoute enables direct access to the following services in all regions:
			- Microsoft Office 365
			- Microsoft Dynamics 365
			- Azure computer services (such as [Azure Virtual Machines]([[Microsoft Azure/Virtual Machines]]))
			- Azure cloud services (such as [Azure Cosmos DB]([[Microsoft Azure/Cosmos DB]]) and [Azure Storage]([[Microsoft Azure/Storage]]))
	- Global connectivity to Microsoft services across all regions with *ExpressRoute Global Reach*
		- Allows you to exchange data across your on-premises sites by connecting your ExpressRoute circuits, allowing them to communicate without transferring data over the public internet
	- Dynamic routing between your network and Microsoft via Border Gateway Protocol (BGP)
	- Built-in redundancy in every peering location
-
- **ExpressRoute supports *four functionally identical models* to connect an on-premises network to the Microsoft cloud:**
	- ***Co-location at a cloud exchange***
		- If your facility is co-located at a cloud exchange, such as an ISP, you can request a virtual cross-connect to the Microsoft cloud
	- ***Point-to-point Ethernet connection***
	- ***Any-to-any (IPVPN) networks***
		- You can integrate your wide area network (WAN) with Azure by providing connections to your offices and datacenters
	- ***Directly from ExpressRoute sites***
		- *ExpressRoute Direct* provides dual 100-Gbps or 10-Gbps connectivity
-
- While data sent over ExpressRoute doesn't travel over the public internet, DNS queries, certificate revocation list checking, and Azure CDN requests are still sent over the public internet