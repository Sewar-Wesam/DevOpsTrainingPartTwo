# DevOpsTrainingPartTwo 

## Cloud Computing
Today is the first day in my second part in DevOps Training at quiz plus , and I will start with the basics of cloud computing, let we walk through the following :   

### Types of Clouds:   
Understanding the cloud types will help you to understand the types of cloud services types. Here are the types of cloudes:   
1. Public Cloud: In the public clouds anyone can rent space of resources. it is is a great choice for flexibility and cost efficiency. AWS, Microsoft Asure and Google cloud are examples on the public cloud.
2. Private Cloud: In the private clouds, only your team can access this cloud computing enviroment. Companies set up their own resources. For example, Banks and goverments use this type of computing for full control and security.
3. Hybrid Cloud: This type is a mix between the two previous parts, so you can access the resources publicaly and privately. It likes that you are renting a private room in a public large company.

### Types of cloud services:   
There are three main cloud services that differ in the level of control, management and flexibility they provide. These are the types:  
1. IaaS: Infrastructure as a Service
2. PaaS: Platform as a Service
3. SaaS: Software as a Service 

#### ==> Let we walk through each type and disscuss some points:       
* IaaS: Infrastructure as a Service: Here, you are renting the resources, but the control of the software and run the application still for you. The most important property in this type of services, that you dont have to suffer with the hassles of maintaining the hardware resources.
IaaS enables you to add or remove resources depending on your needs, so it provides a high scalability.
* PaaS: Platform as a Service: Here, you focus on your code, or your application. and the provider automatically maintain, setup and manage the infrastructure, OS and the network resources. An Example on PaaS: AWS Elastic Beanstalk sets up and maintain the server configurations, all you need to do is to run your application and focus on your own code.   
* SaaS: Software as a Service: SaaS is a fully managed software applications hosted by the provider and accessible via internet. Examples on this type of cloud services are the Gmail, Dropbox, and the microsoft 365. You simply log in and start using the service immediatly without installation, updates, or maintinance. Since the provider manage the updates, then you always have the latest features.

### AWS 
AWS is an example on a cloud providers. it provides a very wide types of resources. you can use them as you need, without need to buy or maintain these resources physically.   

#### AWS Cloud Architecture:   

##### Key Components of AWS Architecture:  
1. Compute services: this is the processing power of the cloud-based applications. to process the data, run the code and handle the users requests.
   when we are talking about Compute services in AWS, then we had to disscuss the following :
   
a. EC2 (Elastic Compute Cloud) : it is the main engine that run your application. EC2 instances are virtual servers. You can specify and customize your own EC2 instance to suit your application need. when you customize the EC2 instance, then you are determine the amount of memory, CPUs, and the storage space.   

b. AWS Lambda: it is a computing service provided by AWS. It is a serverless service, so you dont have to configure the server because the provider does this for you. it is called the star of the serverless services because it is very powerfull and popular.


==> Usually, when you run your code, then you need a server, but with lambda you dont have to set up or maintain a server, because AWS does this for you.  lambda is the perfect choice for the event-driven tasks. Event-Drive  tasks are : (If something happens then the lambda runs).    
For example, you have a website that allows you to upload photos, when you upload that photo, then you need to resize it. here, it is very clear that we will use lambda to resize these photos at the uploading time then stop.     

2. Storage Services: we need a place to store the data, user profiles, ... etc, so, when we are talking about storage service in AWS, we should talk about the following:
   
   a. Amazon S3 (Simple Storage Service) : it is just like an online, unlimited online filling cabinet.
   
   b. Amazon EBS (Ellastic Block Store)  : it likes a hard drive attached to the EC2 instances. so the Amazon EBS it is the best choice for the applications that need high storage space.
    




  
