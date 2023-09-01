# azure_intro_assessment
This is assignment 1.

## Storage 

### Identify and List Services 
Two categories are Azure Blob Storage and Azure confidential ledger. 

### Service Description 
Azure Blob Storage is a storage solution that Microsoft created for the cloud. Unstructured data can be stored in large amount in this type of storage and it can hold things such as images and documents from browser, store files and data and much more. This is interesting because it is not limited to just words or binary data.

Azure confidential ledgers refers to a service that allows for the secure management of sensitive data records as mentioned by Azure. This is interesting because it is so secure and private not even Microsoft can override it. It is a heavily monitored and guarded service and can be installed in python

### Python Interaction

Interacting with this service using Python for Azure Blob Service can be done using client libaries which can also be done in other languages such as  Java and Go. Clients can access objects from this type of storage via HTTP/HTTPS from any location. 

In order for Azure confidential Ledgers  to be installed in Python. Ine way  to succesfully undertake this process would be to open up a Python virtual network and install the different pip code that the Azure website directs. For example these inclydes the Active directory identity client library, the confidential ledger control plane client library and the ledger data plan client library. 





## Compute

### Identify & List services
Two categories are App Service and Azure Functions. 

### Service Description
App service, as described on the Microsoft website, lets you make  and launch your own web applications, as well as restful APIs and mobile back ends. An interesting feature of this this service is that it allows you the flexibility to choose any programming language and it can be deployed on Github, Azure DevOps and any repostiory on Github. It will automatically scale your applications and is a fully managed platform. Additionally, features include security, serverless code, and more. 

Azure Functions is a cloud infrastructure that allows a person who is writing code to connect to specific functions and keep their applications going. It can save time as well as money and Azure Functions can help to build web APIs and much more. 

### Python Interaction
For Azure App Service, any language you want can be used to to create and build your web apps, mobile back ends, and restfulAPIs. Python would be the language of interest here when building things in this sitation;
In the quickstart portion  on the Microsoft website, Flask or Django were examples are how Python can be used. Those are both python web applications, and App Service uses a Linux server envirornment that hosts the Python applications. 

For Azure functions the way that this relates to python is that the the code of choice is dependent on the user which allows for flexibility and ease of use. The code is up to the user and you would create code for your functions using Python which will then be deployed to the cloud in Azure. Visual Studion Code can be used to leverage this service and once the python extension is installed it can then be used to create Python functions. 

## Database Services

### Identify & List services
The two categories are Azure Cache for Redis documentation and Azure SQL documentation. 

### Service Description 
Azure SQL database is a platform as a service and and include functions that set out to manage the database. This includes upgrading, backing up information and monitoring things without prompt. 

Azure Cache for Redis documentation refers to a data cache that is safe and secure on Redis software. It is an in memory data storage that processes many requests by the application and for application that have large back end data storage it can help with that bettering performance and with scaling. 

### Python Interaction
Azure Cache for Redis can be integrated into a Python application. This is important because it allows access to a cache in Azure from numerous applications. A python interface known as Redis-py would need to be installed which will allow you to test the cache. 

In the instance of the Azure SQL database, it is possibe to use Python to connect to the database. Python can be used to connect and query from applications. There are things called python SQL drivers such as pyodbc or pymssql to configure envirornments for development. 



