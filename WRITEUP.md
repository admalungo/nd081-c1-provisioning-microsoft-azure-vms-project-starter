# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

After a careful consideration for an environment to deploy the FlaskWebProject to Azure, I chose to use the azure App Service instead of a VM. Mainly because I do not require full control to host it on a VM. So for that reason app service makes more sense.

Although a virtual machine would give me full control of the resource, App service solution satisfies the need and a fraction of the cost. 

However, cost is not the only advantage. By using App Service, I do not have to worry about maintaining the underlying operating system and all the stack, as an App Service handles all that seemlesly for me. This is a great time saver and a great advantage of App Service over VM.

cost
surprisingly, there is not much difference on cost to host the cms app on either vm or app service; using the azure pricing calculator, the lowest estimated monthly cost for a vm, east us, linux, basic tier, pay as you go subscription, is $13.19, and $12.41 per month for an App service.

Cost-wise, it is advantageous to host the CMS app using App Service instead of a VM.

scalability

availability

workflow

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 