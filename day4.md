### Introduction to amazon simple storage services(amazon s3) demo

### What is Amazon S3?
Amazon S3 is a cloud storage service that allows you to store and retrieve any amount of data, anytime, from anywhere on the web. It’s designed to be highly durable, scalable, and secure.

1. Durability: Amazon S3 offers 99.9% durability, ensuring your data is safe across multiple geographically separated data centers.
Scalability: It automatically scales to handle growing amounts of data without the need for you to manage the underlying infrastructure.

2. Availability: It provides high availability with easy access to your data from anywhere in the world.
Security: Amazon S3 includes features like encryption, access control, and logging to secure your data.


## Key Concepts
1. Buckets: A bucket is a container for storing objects in S3. Each bucket is uniquely named and can contain an unlimited number of objects.

2. Objects: An object is the fundamental entity stored in S3, consisting of the data itself, a key (unique identifier), and metadata.

3. Keys: A key is a unique identifier for an object within a bucket. It can be a simple string or a more complex structure to represent file paths.
Regions: Buckets are created in specific AWS regions. Choosing a region close to your users can help reduce latency and costs.

### Basic Operations
1. Creating a Bucket:

Buckets can be created through the AWS Management Console, AWS CLI, or SDKs.
You specify a globally unique name and a region.

2. Uploading Objects:

Objects can be uploaded via the AWS Management Console, AWS CLI, or programmatically using AWS SDKs.
You can upload single files or multiple files in bulk.

3. Managing Permissions:

S3 provides a range of options for setting access permissions, including bucket policies, access control lists (ACLs), and IAM roles.
You can control who can access your data and what actions they can perform.

4. Accessing Data:

You can access your data via the S3 web interface, through REST APIs, or using SDKs.
S3 supports various methods for accessing and managing data, including direct URL access for public objects.

### Demo Walkthrough
 1. Creating a Bucket:

Log in to the AWS Management Console.
Navigate to the S3 service.
Click “Create bucket,” enter a unique name, and choose a region.
Review settings and click “Create bucket.”

2. Uploading a File:

Select the bucket you created.
Click “Upload” and drag and drop a file or choose from your file system.
Configure options as needed and click “Upload.”

## Conclusion
Amazon S3 is a versatile and powerful storage solution that can meet a wide variety of needs with high durability,scalibility,and security factors. In this lesson we learned about S3 amazon storage services and  basic operations needed for demo.