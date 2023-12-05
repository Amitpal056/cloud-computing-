# What Is Cloud Computing
Cloud computing is the delivery of computing of  services - including server, storage , database ,networking , software , analytics , and intelligence over the internet.
### Benfits Of Cloud 
- Cost saving
- Better Collaboration
- Scalibility And Flexibility
- Advance Security
### Disadvantage Of Cloud 
- Risk of vendor lock in
- Less control over under lying cloud infrastructure
- Concern about data security and online threats
#### Public Cloud And Private Cloud
Public cloud available for everyone but private cloud is available for only selected users 
#### Hybrid Cloud 
It is combination of public and hybrid cloud 
### Cloud Service Model
- IaaS(Infrastructure as a service )
- PaaS (Platform as a service )
- SaaS(software as a service )
# Amazon Web Service 
AWS is the world most comprehensive and broadly adopted cloud platform offering over 200 fully featured services from data centers  globally.
## Compute Services 
- Elastic compute compute - EC2(most offering and provide rented VM.)
             Types of EC2
                 - t2.micro
                 - t2.xlarge
                 - c5d.4xlarge
                 - r5.16xlarge
                 - m5.8xlarge
- ECS/EKS - Containerized services
- Lambda - Serverless
## Storage Services 
###### Simple Storage Service-S3
             it is a object storage with durability of 99.99999999% which can keep the files in buckets.This is a infinitely scaling storage.It has user based security.
###### Elastic Block Storage-EBS
              Amazon EBS allows you to create storage volumes and attach them to Amazon EC2 instances. Once attached, you can create a file system on top of these volumes, run a database, or use them in any other way you would use block storage
###### Elastic File System-EFS
              Encrypting File System provides an added layer of protection by encrypting files or folders on various versions of the Microsoft Windows OS. EFS is a functionality of New Technology File System (NTFS) and is built into a device via the OS.
###### Archival Service - Glacier
                The Amazon S3 Glacier storage classes are purpose-built for data archiving, providing you with the highest performance, most retrieval flexibility, and the lowest cost archive storage in the cloud. You can now choose from three archive storage classes optimized for different access patterns and storage duration.
## Network Services
- virtual private cloud - VPC(vPC role defines which of the two vPC peer devices processes Bridge Protocol Data Units (BPDUs) and responds to Address Resolution Protocol (ARP) requests)
- domain name service - Route 53(You can use Route 53 to perform three main functions in any combination: domain registration, DNS routing, and health checking)
- direct connect (a networking service that provides an alternative to using the internet to connect to AWS)

#### Some Important Points 
- security groups (A security group controls the traffic that is allowed to reach and leave the resources that it is associated with. For example, after you associate a security group with an EC2 instance, it controls the inbound and outbound traffic for the instance. When you create a VPC, it comes with a default security group.)
- vpc
- subnet (A subnet is a range of IP addresses in your VPC. You launch AWS resources, such as Amazon EC2 instances, into your subnets. You can connect a subnet to the internet, other VPCs, and your own data centers, and route traffic to and from your subnets using route tables.)
- target group (Target groups route requests to individual registered targets, such as EC2 instances, using the protocol and port number that you specify. You can register a target with multiple target groups. You can configure health checks on a per target group basis)
- load balancer (The load balancer distributes incoming application traffic across multiple targets, such as EC2 instances, in multiple Availability Zones. This increases the availability of your application)
- key pair (a combination of a public key that is used to encrypt data and a private key that is used to decrypt data.)
- putty ( a free SSH client that allows you to do this from a local computer running Windows.)
- nginx (it turns your AWS clusters into production-grade application delivery powerhouses.)
- ip address( the unique identifying number assigned to every device connected to the internet.)

##### SUMMARY 
   First you have to create a instance and after that you have to create a  key that will used to encrypt data and a private key that is used to decrypt data. For more information about key pairs, ensure you are signed into the AWS console and then review Amazon EC2 Key Pairs in the Amazon EC2 User Guide for Linux Instances. After successfull creating the instance you have to deploy application on the nginx server . For that you have to connect your instance to your SSH client like putty .
   Then you have to create load balancer and make another paired instance and divide the load equally with the help of load balancer.
  
