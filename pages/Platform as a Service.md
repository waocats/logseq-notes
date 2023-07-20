tags:: Microsoft Azure/AZ-900
alias:: PaaS

-
- The **middle ground between renting space in a datacenter** ([[Infrastructure as a Service]]) **and paying for a complete and deployed solution** ([[Software as a Service]])
	- Also, unlike [[Infrastructure as a Service]] , *you don't need to worry about licensing or patching for operating systems and databases*
	- Depending on the configuration, *you or the cloud provider may be responsible for networking, security, and the directory infrastructure*
-
- PaaS in the [shared responsibility model]([[Shared Responsibility Model]]):
  |Service|SaaS|**PaaS**|IaaS|
  |Information and data||||
  |Devices (PCs and mobile)||||
  |Accounts and Identities||||
  |Identity and directory infrastructure|~|**~**||
  |Applications|✓|**~**||
  |Network controls|✓|**~**||
  |Operating system|✓|**✓**||
  |Physical hosts|✓|**✓**|✓|
  |Physical network|✓|**✓**|✓|
  |Physical datacenter|✓|**✓**|✓|
-
- ***Two* scenarios where PaaS might make sense** could be:
	- **Development framework**
		- PaaS provides a framework that developers can build upon to *develop or customize cloud-based applications* using built-in software components
		- Features such as scalability, high-availability, and multi-tenant capability are included, reducing the amount of coding required
	- **Analytics or business intelligence**
		- Tools provided with PaaS allow organizations to *analyze and mine their data*, which can be used for:
			- Finding insights and patterns
			- Predicting outcomes to improve forecasting
			- Product design decisions
			- Investment returns
			- Other business decisions