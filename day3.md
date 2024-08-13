### Objective
AWS offers a broad set of global cloud-based products including compute,storage,databases,analytics,networking,etc. These services helps build elastic, agile architectures.

### Monolithic Architecture
A monolithic application is built as a single unified unit while a microservices architecture is a collection of smaller, independently deployable services. A monolithic architecture is a traditional model of a software program, which is built as a unified unit that is self-contained and independent from other applications. A monolithic architecture is a singular, large computing network with one code base that couples all of the business concerns together.  To make a change to this sort of application requires updating the entire stack by accessing the code base and building and deploying an updated version of the service-side interface. This makes updates restrictive and time-consuming.
These components might includes :
1. Servers
2. Databases
3. User interface
4. Business logic
If a single component fails then other components likely fail.

### Microservices
A microservices architecture, also simply known as microservices, is an architectural method that relies on a series of independently deployable services. These services have their own business logic and database with a specific goal. Updating, testing, deployment, and scaling occur within each service. Microservices decouple major business, domain-specific concerns into separate, independent code bases. Microservices don’t reduce complexity, but they make any complexity visible and more manageable by separating tasks into smaller processes that function independently of each other and contribute to the overall whole. In Microservices architecture might includes:
1. Servers
2. Databases
3. User interface
4. Business logic
In this logic if a single component fails the other components continue to work because they are connected with each other.

### Types of services:
1. Managed services- A managed services is a way to describe the services that requires you to manage infrastructure management tasks like patching,backup,and repair. These services grant you virtual access to the underlying operating system and servers. With managed services,you are respponsible for scaling and building for high availability.

2. Fully managed services-A fully managed services is a way to describe the services that automate infrastructure management tasks that AWS handles , like patching,backup, and repair. These services do not grant you any virtual access to the underlying operating system or servers. With a fully managed service, you are still responsible for scaling and building for high availability.

3. Serverless services-Serverless is a way to describe the services,pratices, and stratigies that you can use to build more agile application. In this way,you can innovate and respond to change faster.With serverless services,AWS handles infracture management tasks like capacity provisioning and patching so that you can focus on building applications that serve your customers.

### Core services
1. Amazon Virtual Private Cloud (VPC) is a service that lets you create and manage a private network in the AWS cloud. It essentially allows you to set up a virtual network environment that mirrors a traditional network you might operate on-premises, but with the added benefits of cloud computing. 

2. Amazon Elastic Compute Cloud (Amazon EC2) is a core service within AWS that provides scalable computing capacity in the cloud. Essentially, EC2 allows you to run virtual servers, known as instances, on demand.

3.Amazon Relational Database Service (Amazon RDS) is a managed service provided by AWS that simplifies the setup, operation, and scaling of relational databases in the cloud.

4.Amazon CloudWatch is a monitoring and observability service provided by AWS that offers comprehensive visibility into your cloud resources and applications.

5.Amazon Simple Notification Service (Amazon SNS) is a fully managed messaging service provided by AWS that facilitates the sending of notifications and messages to a large number of recipients.

6.Amazon Identity and Access Management (IAM) is a service provided by AWS that allows you to control access to AWS resources securely.

7.Amazon Simple Storage Service (Amazon S3) is a scalable object storage service provided by AWS for storing and retrieving any amount of data at any time from anywhere on the web. 

8.AWS Lambda is a serverless computing service provided by AWS that allows you to run code without provisioning or managing servers. It automatically scales and manages the infrastructure required to execute your code, allowing you to focus solely on writing and deploying your functions.

9.Amazon DynamoDB is a fully managed NoSQL database service provided by AWS that offers fast and predictable performance with seamless scalability. It is designed for applications that require consistent, single-digit millisecond latency and can handle a wide range of workloads. 