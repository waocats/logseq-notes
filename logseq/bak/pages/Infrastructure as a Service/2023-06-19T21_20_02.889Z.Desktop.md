filters:: {}
tags:: AZ-900
alias:: IaaS

-
- The **most flexible category of cloud services**, as it provides you **the maximum amount of control** for your cloud resources
	- *When using IaaS, you're essentially* ***renting the hardware*** *in a cloud datacenter*
-
- IaaS in the [shared responsibility model]([[Shared Responsibility Model]]):
  |Service|SaaS|PaaS|**IaaS**|
  |Information and data||||
  |Devices (PCs and mobile)||||
  |Accounts and Identities||||
  |Identity and directory infrastructure|~|~||
  |Applications|✓|~||
  |Network controls|✓|~||
  |Operating system|✓|✓||
  |Physical hosts|✓|✓|**✓**|
  |Physical network|✓|✓|**✓**|
  |Physical datacenter|✓|✓|**✓**|
-
- ***Two* scenarios where IaaS might make sense** could be:
	- **Lift-and-shift migration**
		- You're standing up cloud resources similar to your on-prem datacenter, and *moving what's running on-prem to the IaaS infrastructure*
	- **Testing and development**
		- For development and test environments, you established *configurations that you need to rapidly replicate and keep complete control over*