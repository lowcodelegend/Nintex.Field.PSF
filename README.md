# Nintex.Field.PSF
Nintex K2 PreSalesFramework

Nintex K2 PreSalesFramework is a framwork for our customers and partners to rapidly prototype Case Management sytle applications while demonstrating the best Nintex K2 has to offer in terms of prebuilt components, integration of multiple community projects, as well as providing a number of its own innovation such as Progressive Web Applicaton support, Workflow, SmartObject, and SmartForm generation, Azure B2C Integration, Nintex Promapp integration and much more.

It's not designed for production application delivery, but that resulting apps could be made so.

It's designed to be very quick to start using

Latest K2 packages can be downloaded here until a build pipeline is in place: https://tinyurl.com/nintexpsflatest

Deployment instructions:

	• Ensure Latest K2 (At least K2 5.6)
	• Copy DLLs to K2 Service Broker folder.
		○ Default: C:\Program Files\K2\ServiceBroker
	• Make sure Service Types are registered.
		○ You should know how to do this from Partner On-boarding training
		○ Documentation is at: Registering Custom Service Brokers (nintex.com)
	• Register an instance of each deployed service broker.
		○ You should know how to do this from your partner On-boarding training
		○ K2 Management Site -> Integration -> Service Instances -> Add
		○ Do this for each of the Service Types registered above.
	• Make sure an instance of the Exchange Online service broker is also registered.
		○ You can register this even if you don't have Exchange Online, just provide dummy credentials
	• Deploy KSPX
		○ Nintex K2 Five
	• Watch PSF Intro Video 
		○ Nintex Partner Program
	• Go to PSF Admin form in K2 Designer 
	• Add an “App”
	• Add some stages (promapp import or manual).
	• Add some Action is desired.
	• Add some “custom fields” (button at top).
	• Click the Generate App button.
