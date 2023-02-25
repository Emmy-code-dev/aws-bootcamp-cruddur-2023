# Week 0 — Billing and Architecture 
# Architecture
Considering the cruddur app we are about to build, then host in AWS, a napkin diagram was introduced which essentially abstractly describing the architectural design of the proposed app and which are the essential elements to host various infrastructure as in the youtube video. This architecture diagram includes:
# 1. Napkin Diagram

![Napkin Diagram](https://user-images.githubusercontent.com/63400363/221359633-565bc421-9caa-4cc7-a187-a0f500ea1a5f.png)

# 2. Cruddur Conceptual Diagram

![Cruddur Logical Diagram](https://user-images.githubusercontent.com/63400363/221359638-5e942413-eebe-4e5c-866f-af09c10da993.png)

# Billing
In this youtube video instructions decribes the services used to set a budget to set a specific threshold of which usage should not exceed, set a billing alarm to alert us when resource usage exceed a particlar amount earlier set. The aspect of cost explorer for forcasting cost of resource over time was discussed and also AWS cloud trail was briefly introduced. All this are services to keep the user abreast of spike in cost accumulation, to prevent exceeding budget for a particular resource and also to calculate cost implication upfront for AWS service about to me used.

# AWS CLI
This is a secured shell CLI (command line interface) used to provision resource without to use of GUI (graphical user interface) which support across various platforms for ease of implementation. To access the CLI shell your have to creat an IAM (identity and access management user) which generates a user Id and key to access the CLI securely. The gitpod was choosen as a virtual environment to connect to github where AWS CLI is installed to help provision resources. 

# Security 
This involves the creation of AWS Organization to regulate how sub accounts own rights to access various resources which can be further separated into several billing budgets, in organization the root user can assigned administartor policies and privilegies to a user to perfomr certian operation. This in AWS is regarded as a security best practice. 




