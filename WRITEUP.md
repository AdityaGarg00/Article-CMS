# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
## Justification for my choice of chossing App service as the approproiate solution for app deployment


We can deploy our application with either means whether its an app or an virtual machine. Here,App service is a part of Platform as a Service or (PaaS) which means I am provided with the whole building and now I have to develop the app only and it is also specialized for HTTP-based service for hosting web application whereas in Virtual Machine I have access to the  Infrastructure as a Service which means (IaaS), which means here I will be responsible for the Operating system, the server Ill use to deploy the app into here I will also be responcible for the ram required, computation power required and many other factors. Both the platforms are good for deploying the application but here I have chossen the app service as for this app I do not require to control much of the computation power or the storage or anything else as this is a small scale application. Whereas If I was to develop a large scale application which might grow over a period of time I must have chossen the Virtual Machine. In chossing the App service we will only have to pay for the recourses as we use them so it is more cost benifitial as compared to the virtual machine. Also Deploying Virtual Machine is a time consuming process whereas deploying an app service is not that time consuming so it is a better option. 

#### Cost Analysis
Virtual Machines cost three times the price of the app service and in app service i will be paying for recourses as i use them but in virtual machine ill be paying for some recourse even while i am not using them

### Scalability
we will have to integrate the load balancer and auto scaling functions in the Virtual machoines but in app service these functions such as load balancer and auto scaling are pre integrated

### availability aand workflow 
In availability and workflow options virtuial machines would be better as they are available for aprox 99.95 persent of time and have better workflow as mentioned in the first para but as it is a small scale application so we can ignore these factors.

### Assess app changes that would change your decision.
If this would have been a large scale application then i would have prefered virtual machine as it provides better availability and workflow in this case we can surely ignore the cost and time factors as good thing take time to develop




