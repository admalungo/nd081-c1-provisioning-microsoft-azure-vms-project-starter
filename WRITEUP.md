# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

After a careful consideration for an environment to deploy the FlaskWebProject to Azure, I chose to use Azure App Service instead of a VM. Mainly because I do not require full control of the resource to host the CMS app. So for that reason app service makes a lot of sense. In addition, by using App Service, I do not have to worry about maintaining the underlying operating system and all the stack. This is a great time saver and a great advantage of App Service over a VM.

Cost
Surprisingly, there is not much difference on cost to host the CMS app on either a VM or app service. Using the Azure Pricing Calculator, the lowest estimated monthly cost for a VM, East US, Linux, basic tier, pay-as-you-go subscription, cost is $13.19 per month for a VM, and $12.41 per month for App service.

Scalability
Scalability is the ability to scale resources up or down. App service has built in capability to dynamically handle changes in volume, bandwidth, storage size. Should the CMS app increase in usage and demand more compute resources, logic can be added for the Azure App Service to increase resources to meet the demand and reduce them when no longer needed. 

Availability
Microsoft Azure offers availiability and redundancy on a global scale with 99.9% uptime.

Workflow
With the ability for continuous integration and continuous deployment (CI/CD) pipeline that pushes changes automatically from GitHub to the App service. A great time saver.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 