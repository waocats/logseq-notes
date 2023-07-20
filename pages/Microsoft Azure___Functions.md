tags:: Microsoft Azure, Microsoft Azure/AZ-900
alias:: Azure Functions

-
- **An *event-driven*, serverless compute option that *doesn't require maintaining virtual machines or containers* **
-
- **Functions are commonly used when:**
	- You need to *perform work in response to an event*
		- Often via a REST request, timer, or message from another Azure service
	- When that *work can be completed quickly* (within seconds or less)
-
- **Functions can either be *stateless* or *stateful* **
	- When they're ***stateless*** (the default), they behave as if they're restarted every time they respond to an event
	- When they're ***stateful*** (called *Durable Functions*), a context is passed through the function to track prior activity
-
- In this model, **you're only charged for the *CPU time used* while your function runs**