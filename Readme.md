# AWS Certified Solutions Architect (SAA-C03)

Analytics:
==========

## Amazon Athena
---------------
#### Q: What is Amazon Athena?
Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to setup or manage, and you can start analyzing data immediately. You don’t even need to load your data into Athena, it works directly with data stored in S3. To get started, just log into the Athena Management Console, define your schema, and start querying. Amazon Athena uses Presto with full standard SQL support and works with a variety of standard data formats, including CSV, JSON, ORC, Apache Parquet and Avro. While Amazon Athena is ideal for interactive analytics and integrates with Amazon QuickSight for easy visualization, it can also handle complex analysis, including large joins, window functions, and arrays.
 
#### Q: What can I do with Amazon Athena?
Amazon Athena helps you analyze data stored in Amazon S3. You can use Athena to run interactive analytics using ANSI SQL, without the need to aggregate or load the data into Athena. Amazon Athena can process unstructured, semi-structured, and structured data sets. Examples include CSV, JSON, Avro or columnar data formats such as Apache Parquet and Apache ORC. Amazon Athena integrates with Amazon QuickSight for easy visualization. You can also use Amazon Athena to generate reports or to explore data with business intelligence tools or SQL clients, connected via an ODBC or JDBC driver.

### Benefits

#### Start querying instantly

Serverless, no ETL

Athena is serverless. You can quickly query your data without having to setup and manage any servers or data warehouses. Just point to your data in Amazon S3, define the schema, and start querying using the built-in query editor. Amazon Athena allows you to tap into all your data in S3 without the need to set up complex processes to extract, transform, and load the data (ETL).

#### Pay per query

Only pay for data scanned

With Amazon Athena, you pay only for the queries that you run. You are charged $5 per terabyte scanned by your queries. You can save from 30% to 90% on your per-query costs and get better performance by compressing, partitioning, and converting your data into columnar formats. Athena queries data directly in Amazon S3. There are no additional storage charges beyond S3.

#### Open, powerful, standard

Built on Presto, runs standard SQL

Amazon Athena uses Presto with ANSI SQL support and works with a variety of standard data formats, including CSV, JSON, ORC, Avro, and Parquet. Athena is ideal for interactive querying and can also handle complex analysis, including large joins, window functions, and arrays. Amazon Athena is highly available; and executes queries using compute resources across multiple facilities and multiple devices in each facility. Amazon Athena uses Amazon S3 as its underlying data store, making your data highly available and durable.

#### Fast, really fast

Interactive performance even for large datasets

With Amazon Athena, you don't have to worry about having enough compute resources to get fast, interactive query performance. Amazon Athena automatically executes queries in parallel, so most results come back within seconds.

![Amazon Athena - How it works](https://d1.awsstatic.com/product-page-diagram_Amazon-Athena-Connectors@2x.746fd3a9135686d6ede41f08a2eecf29b16bea20.png "Amazon Athena - How it works") 



## AWS Data Exchange
-------------------
Easily find, subscribe to, and use third-party data in the cloud.

With AWS Data Exchange, providers publish data products and subscribers subscribe to those products.

#### What is AWS Data Exchange?
AWS Data Exchange is a service that makes it easy for AWS customers to find, subscribe to, and use third-party data in the AWS Cloud.

As a subscriber, you can find and subscribe to thousands of products from qualified data providers. Then, you can use the AWS Data Exchange console or APIs to create, view, manage, and access data sets for use across a variety of AWS analytics and machine learning services. Anyone with an AWS account can be an AWS Data Exchange subscriber.

For providers, AWS Data Exchange eliminates the need to build and maintain any data delivery, entitlement, or billing technology. Providers in AWS Data Exchange have a secure, transparent, and reliable channel to reach AWS customers and grant existing customers their subscriptions more efficiently. 

#### What is an AWS Data Exchange product?
A product is the unit of exchange in AWS Data Exchange that is published by a provider and made available for use to subscribers. When a provider publishes a product, that product is listed on the AWS Data Exchange product catalog as well as AWS Marketplace after being reviewed by AWS. Each product you publish is uniquely identiﬁed by its product ID.

A product has the following parts:

**Product details** – This information includes name, descriptions (both short and long), logo image, and support contact information. 

**Product offers** – Oﬀers deﬁne the terms that subscribers are agreeing to when they subscribe to a product.

**Data sets** – A product can contain one or more data sets. A data set in AWS Data Exchange is a dynamic set of data which is versioned through the use of revisions. Each revision can contain multiple assets. The provider can decide which revisions within a data set are published to a product.

#### Malware prevention:
Security and compliance is a shared responsibility between you and AWS. To promote a safe, secure, and trustworthy service for everyone, AWS Data Exchange scans all S3 object files published by providers before they are made available to subscribers. If AWS detects malware, the affected asset is removed.

#### Supported data sets:
AWS Data Exchange takes a responsible approach to facilitating data transactions by promoting transparency through use of the service. AWS Data Exchange reviews permitted data types, restricting products that are not permitted. Providers are limited to distributing data sets that meet the legal eligibility requirements set forth in the Terms and Conditions for AWS Marketplace Sellers.

#### Accessing AWS Data Exchange:
Subscribers:
- AWS Data Exchange console (Browse catalog)
- AWS Marketplace catalog

Providers:
- Directly through the AWS Data Exchange console (Publish data)

- Programmatically using the following APIs:

  - AWS Data Exchange API – Use the API operations to create, view, update, and delete data sets and revisions. You can also use these API operations to import and export assets to and from those revisions. 

  - AWS Marketplace Catalog API - Use the API operations to view and update products. 

## AWS Data Pipeline
-------------------

## Amazon EMR
------------

## AWS Glue
----------

## Amazon Kinesis
----------------

## AWS Lake Formation
--------------------

## Amazon Managed Streaming for Apache Kafka (Amazon MSK)
--------------------------------------------------------

## Amazon OpenSearch Service (Amazon Elasticsearch Service)
----------------------------------------------------------

## Amazon QuickSight
-------------------

## Amazon Redshift
-----------------

Application Integration:
========================

## Amazon AppFlow
----------------

## AWS AppSync
-------------

## Amazon EventBridge (Amazon CloudWatch Events)
-----------------------------------------------

## Amazon MQ
-----------

## Amazon Simple Notification Service (Amazon SNS)
-------------------------------------------------

## Amazon Simple Queue Service (Amazon SQS)
------------------------------------------

## AWS Step Functions
--------------------

AWS Cost Management:
====================

## AWS Budgets
-------------

## AWS Cost and Usage Report
---------------------------

## AWS Cost Explorer
-------------------

## Savings Plans
---------------

Compute:
========

## AWS Batch
-----------

## Amazon EC2 [(Elastic Compute Cloud)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
---------------------------------------------------------------------------------------------------------

-   Provides scalable computing capacity in the Amazon Web Services (AWS) Cloud
-   Infrastructure as a Service (IaaS)
-   Main capabilities are

-   Renting Virtual Machines (EC2)
-   Storing data on virtual drives (EBS)
-   Distributing load across machines (ELB)
-   Scaling the service using an auto-scaling group (ASG)

-   You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage
-   EC2 enables you to scale up or down to handle changes in requirements or spikes in popularity, reducing your need to forecast traffic

Features

-   Virtual computing environments, known as Instances
-   Preconfigured templates for your instances, known as Amazon Machine Images (AMIs),
-   Secure login information for your instances using Key Pairs
-   Storage volumes for temporary data that's deleted when you stop, hibernate, or terminate your instance, known as Instance store volumes
-   Persistent storage volumes like Elastic Block Store (EBS)
-   A Firewall
-   Static IPv4 addresses for dynamic cloud computing, known as Elastic IP addresses
-   Virtual networks that you can create logically to isolated from the rest of the AWS Cloud

[Instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Instances.html)

-   An instance is a virtual server in the cloud
-   Its configuration at launch is a copy of the AMI that you specified when you launched the instance
-   Select an instance type based on the amount of memory and computing power that you need for the application or software that you plan to run on the instance
-   [Instance types](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)

-   Instance types comprise varying combinations of CPU, memory, storage, and networking capacity and give you the flexibility to choose the appropriate mix of resources for your applications
-   Each instance type includes one or more instance sizes, allowing you to scale your resources to the requirements of your target workload
-   m5.2xlarge

-   m:instance class
-   5: generation
-   2xlarge: size within the instance class
-   Naming:

-   R: applications that needs a lot of RAM (In-memory cache)
-   C: applications that needs good CPU (compute/db)
-   M: applications that are balanced (web-app)
-   I: applications that needs good local I/O (instance storage ## db)
-   G: applications that needs a GPU (video rendering/ machine learning)

-   [Instance Comparison](https://instances.vantage.sh/)
-   [General Purpose Instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/general-purpose-instances.html)

-   Diversity of workloads such as web-servers or code repos
-   Balance between Compute, Memory and Networking
-   M5 and M5a ## balance of compute, memory, and networking resources

-   Small and midsize databases
-   Data processing tasks that require additional memory
-   Caching fleets
-   Backend servers for enterprise applications
-   E.g. m5.large, m5a.16xlarge

-   M5zn ## extremely high single-thread performance, high throughput, and low latency networking

-   Gaming
-   High performance computing
-   E.g. m5zn.large

-   M6g and M6gd ## balanced compute, memory, and networking

-   Application servers
-   Microservices
-   Gaming servers
-   Midsize data stores
-   E.g. m6gd.medium

-   [Burstable performance instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/burstable-performance-instances.html)

-   The T instance family provides a baseline CPU performance with the ability to burst above the baseline at any time for as long as required
-   The EC2 burstable instances consist of T4g, T3a and T3 instance types, and the previous generation T2 instance types
-   T instances are not supported on a Dedicated Host
-   Unlimited mode

-   Can sustain high CPU utilization for any period of time whenever required
-   The hourly instance price automatically covers all CPU usage spikes if the average CPU utilization of the instance is at or below the baseline over a rolling 24-hour period or the instance lifetime, whichever is shorter
-   T4g, T3a and T3 instances launch as unlimited by default

-   Standard mode

-   Suited to workloads with an average CPU utilization that is consistently below the baseline CPU utilization of the instance
-   To burst above the baseline, the instance spends credits that it has accrued in its CPU credit balance
-   If the instance is running low on accrued credits, CPU utilization is gradually lowered to the baseline level, so that the instance does not experience a sharp performance drop-off when its accrued CPU credit balance is depleted

-   Use cases

-   Websites and web applications
-   Code repositories
-   Development, build, test, and staging environments
-   Microservices

-   E.g. t4g.nano, t2.medium, t3.2xlarge

-   [Compute optimized](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/compute-optimized-instances.html)

-   Optimized for compute-intensive tasks that require high performance
-   Use cases

-   Batch processing workloads
-   Media transcoding
-   High-performance web servers
-   High-performance computing (HPC)
-   Scientific modeling
-   Dedicated gaming servers and ad serving engines
-   Machine learning inference and other compute-intensive applications

-   E.g. C5 and C5d instances (c5.large, c5.metal, c5d.24xlarge, c5d.metal)

-   [Memory optimized](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/memory-optimized-instances.html)

-   Optimized for fast performance for workloads with large data set in memory
-   Use cases

-   High-performance, relational (MySQL) and NoSQL (MongoDB, Cassandra) databases
-   Distributed web scale cache stores (Memcached and Redis)
-   In-memory, optimized data storage formats and analytics for business intelligence (for example, SAP HANA)
-   Real-time processing of big unstructured data (financial services, Hadoop/Spark clusters)
-   High-performance computing (HPC) and Electronic Design Automation (EDA) applications.

-   E.g. R5, R5a, R5b, and R5n instances(r5.large, r5a.24xlarge, r5b.2xlarge, r5n.metal)

-   [Storage optimized](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/storage-optimized-instances.html)

-   Optimized for storage-intensive tasks that require high, sequential reads and write access to large data set on local storage
-   Use cases

-   High frequency online transaction processing systems
-   Relational & NoSQL databases
-   Cache for in-memory
-   Data warehouse applications
-   Distributed files systems

-   E.g. D2 instances (d2.xlarge, d2.8xlarge)

-   [Instance purchasing options](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-purchasing-options.html)

-   [On-demand instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-on-demand-instances.html)

-   You pay for compute capacity by the second with no long-term commitments

-   Linux ## billing per second, after first minute
-   All other OS billing per hour

-   You pay for only when its running
-   Recommended for short-term and un-interrupted workloads
-   Highest costs but no upfront payment

-   [Reserved instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html)

-   Minimum 1 or 3 year
-   Up to 72-75% discount compare to on-demand but upfront payment
-   Long workloads
-   Recommended for steady state usage application like sql-server
-   Reserved Instances provide you with significant savings on your Amazon EC2 costs compared to On-Demand Instance pricing
-   Convertible Reserved

-   Enables you to exchange one or more Convertible Reserved Instances for another Convertible Reserved Instance with a different configuration, including instance family, operating system, and tenancy
-   Long workloads with flexible instances i.e. can change instance type
-   Upto 54% discount
-   There are no limits to how many times you perform an exchange
-   Cannot be sold in the Reserved Instance Marketplace

-   Scheduled reserved

-   Launch within time window you reserve
-   When you required a fraction of day/week/month
-   Commitment over 1-3 years
-   E.g. every Thursday between 3 to 6 pm

-   [Spot instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-spot-instances.html)

-   Enable you to request unused EC2 instances at steep discounts
-   90% discount compare to on-demand (most cost efficient)
-   Define max spot price and get instance while current spont price < max
-   Spot Instances are a cost-effective choice if you can be flexible about when your applications run and if your applications can be interrupted
-   Not great for critical jobs or databases
-   Spot Instance request defines Maximum price per hour, desired number of instances, launch specification, request type (one time/persistent), valid from to until
-   Instance that you own can "lose" at any point of time if your max price is less than the current spot price
-   [Spot block](https://aws.amazon.com/blogs/aws/new-ec2-spot-blocks-for-defined-duration-workloads/)

-   Block spot instance during specified frame (1-6 hours) without interruptions (In rare situation instance may get reclaimed)
-   Pricing is based on the requested duration and the available capacity, and is typically 30% to 45% less than On-Demand, with an additional 5% off during non-peak hours for the region.

-   [Spot fleets](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/spot-fleet.html)

-   Spot fleet simplifies bidding by allowing you to select the number of vCPUs you need, and automatically launching the lowest priced Spot instances to request and maintain your desired capacity.
-   A Spot Fleet is set of Spot Instances and optionally On-Demand Instances that is launched based on criteria that you specify
-   Automatically request spot instances with lowest price
-   Can have multiple launch pools so that the fleet can choose
-   Stops launching instances when reaching capacity or max
-   Extra saving

-   Good for workloads which are resilient to failures
-   Use cases

-   Batch jobs
-   Data analysis
-   Image processing
-   Any distributed workloads
-   workloads with flexible times

-   [Dedicated hosts](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/dedicated-hosts-overview.html)

-   Physical dedicated EC2 server
-   Full control of instance placement
-   Visibility into underlying sockets, cores
-   Allocated for 3 years
-   More Expensive
-   Useful for software with complicated licensing model (BYOL ## Bring Your Own Licence) or companies with strong regulatory and compliance needs
-   No other customer will share your hardware
-   Can't be released until the reservation's term is over

-   [Dedicated instances](https://aws.amazon.com/ec2/pricing/dedicated-instances/)

-   Run in a VPC of hardware that's dedicated to a single customer
-   Enable you to use your existing server-bound software licenses like Windows Server and address corporate compliance and regulatory requirement
-   May share hardware with other instances in a same account
-   No control over instance placement
-   Per instance billing

-   Instance lifecycle

-   The following illustration represents the transitions between instance states 


-   Notice that you can't stop and start an instance of store-backed instance
-   [Instance launch](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/LaunchingAndUsingInstances.html)

-   When you launch an instance, it enters the pending state
-   The instance type that you specified at launch determines the hardware of the host computer for your instance
-   As soon as your instance transitions to the running state, you're billed for each second, with a one-minute minimum, that you keep the instance running, even if the instance remains idle and you don't connect to it

-   [Instance stop and start](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Stop_Start.html)

-   For Amazon EBS-backed instances only
-   If your instance fails a status check or is not running your applications as expected, and if the root volume of your instance is an Amazon EBS volume, you can stop and start your instance to try to fix the problem
-   When you stop your instance, it enters the stopping state, and then the stopped state
-   No charge for usage or data transfer fees for your instance after you stop it, but do charge for the storage for any Amazon EBS volumes
-   When you stop and start your instance, you lose any data on the instance store volumes on the previous host computer

-   [Instance hibernate](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Hibernate.html)

-   For Amazon EBS-backed instances only
-   Enable hibernation while instance launch
-   When you stop instance the data on disk (EBS) keep intact in the next start
-   When you terminate EBS volume then root set-up to be destroyed
-   When you start, OS boots up and ec2 used data script is run then application starts and can take time
-   When you hibernate then

-   In-memory (RAM) state is preserved i.e. RAM state is written to a file in the root EBS volume
-   The root EBS volume must be encrypted
-   Useful for long running processing or service that take time to initialize
-   Instance RAM must be less than 150 gb
-   Supported by Amazon linux 2, linux AMI Ubantu and windows
-   Can not be hibernated for more than 60 days

-   [Instance reboot](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-reboot.html)

-   Rebooting an instance is equivalent to rebooting an operating system
-   The instance remains on the same host computer and maintains its public DNS name, private IP address, and any data on its instance store volumes
-   Rebooting an instance doesn't start a new instance billing period; per second billing continues without a further one-minute minimum charge

-   [Instance termination](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/terminating-instances.html)

-   When you've decided that you no longer need an instance, you can terminate it. As soon as the status of an instance changes to shutting-down or terminated, you stop incurring charges for that instance
-   If you enable termination protection, you can't terminate the instance using the console, CLI, or API

## Amazon EC2 Auto Scaling
-------------------------

## AWS Elastic Beanstalk
-----------------------

## AWS Outposts
--------------

## AWS Serverless Application Repository
---------------------------------------

## VMware Cloud on AWS
---------------------

## AWS Wavelength
----------------

Containers:
===========

## Amazon Elastic Container Registry (Amazon ECR)
------------------------------------------------

## Amazon Elastic Container Service (Amazon ECS)
-----------------------------------------------

## Amazon ECS Anywhere
---------------------

## Amazon Elastic Kubernetes Service (Amazon EKS)
------------------------------------------------

## Amazon EKS Anywhere
---------------------

## Amazon EKS Distro
-------------------

Database:
=========

## Amazon Aurora
---------------

## Amazon Aurora Serverless
--------------------------

## Amazon DocumentDB (with MongoDB compatibility)
------------------------------------------------

## Amazon DynamoDB
-----------------

## Amazon ElastiCache
--------------------

## Amazon Keyspaces (for Apache Cassandra)
-----------------------------------------

## Amazon Neptune
----------------

## Amazon Quantum Ledger Database (Amazon QLDB)
----------------------------------------------

## Amazon RDS
------------

## Amazon Redshift
-----------------

## Amazon Timestream
-------------------

Developer Tools:
================

## AWS X-Ray
-----------

Front-End Web and Mobile:
=========================

## AWS Amplify
-------------

## Amazon API Gateway
--------------------

## AWS Device Farm
-----------------

## Amazon Pinpoint
-----------------

Machine Learning:
=================

## Amazon Comprehend
-------------------

## Amazon Forecast
-----------------

## Amazon Fraud Detector
-----------------------

## Amazon Kendra
---------------

## Amazon Lex
------------

## Amazon Polly
--------------

## Amazon Rekognition
--------------------

## Amazon SageMaker
------------------

## Amazon Textract
-----------------

## Amazon Transcribe
-------------------

## Amazon Translate
------------------

Management and Governance:
==========================

## AWS Auto Scaling
------------------

## AWS CloudFormation
--------------------

## AWS CloudTrail
----------------

## Amazon CloudWatch
-------------------

## AWS Command Line Interface (AWS CLI)
--------------------------------------

## AWS Compute Optimizer
-----------------------

## AWS Config
------------

## AWS Control Tower
-------------------

## AWS License Manager
---------------------

## Amazon Managed Grafana
------------------------

## Amazon Managed Service for Prometheus
---------------------------------------

## AWS Management Console
------------------------

## AWS Organizations
-------------------

## AWS Personal Health Dashboard
-------------------------------

## AWS Proton
------------

## AWS Service Catalog
---------------------

## AWS Systems Manager
---------------------

## AWS Trusted Advisor
---------------------

## AWS Well-Architected Tool
---------------------------

Media Services:
===============

## Amazon Elastic Transcoder
---------------------------

## Amazon Kinesis Video Streams
------------------------------

Migration and Transfer:
=======================

## AWS Application Discovery Service
-----------------------------------

## AWS Application Migration Service (CloudEndure Migration)
-----------------------------------------------------------

## AWS Database Migration Service (AWS DMS)
------------------------------------------

## AWS DataSync
--------------

## AWS Migration Hub
-------------------

## AWS Server Migration Service (AWS SMS)
----------------------------------------

## AWS Snow Family
-----------------

## AWS Transfer Family
---------------------

Networking and Content Delivery:
================================

## Amazon CloudFront
-------------------

## AWS Direct Connect
--------------------

## Elastic Load Balancing (ELB)
------------------------------

## AWS Global Accelerator
------------------------

## AWS PrivateLink
-----------------

## Amazon Route 53
-----------------

## AWS Transit Gateway
---------------------

## Amazon VPC
------------

## AWS VPN
---------

Security, Identity, and Compliance:
===================================

## AWS Artifact
--------------

## AWS Audit Manager
-------------------

## AWS Certificate Manager (ACM)
-------------------------------

## AWS CloudHSM
--------------

## Amazon Cognito
----------------

## Amazon Detective
------------------

## AWS Directory Service
-----------------------

## AWS Firewall Manager
----------------------

## Amazon GuardDuty
------------------

## AWS Identity and Access Management (IAM)
------------------------------------------

What is IAM

-   IAM allows you to manage users and their level of access to the AWS Console.
-   It is important to understand IAM and how it works, both for the exam and for administrating a company's AWS account in real life.

Key Features of IAM

-   Centralised control of your AWS account
-   Shared Access to your AWS account
-   Granular Permissions
-   Identity Federation (including Active Directory, Facebook, Linkedin etc)
-   Multifactor Authentication
-   Provide temporary access for users/devices and services where necessary
-   Allows you to set up your own password rotation policy
-   Integrates with many different AWS services
-   Supports PCI DSS Compliance

Key Terminology For IAM

-   Users: End Users such as people, employees of an organization etc.
-   Groups: A collection of users. Each user in the group will inherit the permissions of the group.
-   Policies: Polices are made up of documents, called Policy documents. These documents are in a format called JSON and they give permissions as to what a User/Group/Role is able to do.
-   Roles: You create roles and then assign them to AWS Resources. (For a service to access another service, Eg. EC2 access S3)

Exam Tips

-   IAM is universal. It does not apply to regions at this time.
-   The "root account" is simply the account created when first setup your AWS account. It has complete Admin access.
-   New Users have NO permissions when first created.
-   New Users are assigned Access Key ID & Secret Access Keys when first created.

-   These are not the same as a password. You cannot use the Access key ID & Secret Access Key to Login in to the console. You can use this to access AWS via the APIs and Command Line, however.
-   You only get to view these once. If you lose them, you have to regenerate them. So, save them in a secure location.

-   Always setup Multifactor Authentication on your root account.
-   You can create and customise your own password rotation policies

## Amazon Inspector
------------------

## AWS Key Management Service (AWS KMS)
--------------------------------------

## Amazon Macie
--------------

## AWS Network Firewall
----------------------

## AWS Resource Access Manager (AWS RAM)
---------------------------------------

## AWS Secrets Manager
---------------------

## AWS Security Hub
------------------

## AWS Shield
------------

## AWS Single Sign-On
--------------------

## AWS WAF
---------

Serverless:
===========

## AWS AppSync
-------------

## AWS Fargate
-------------

## AWS Lambda
------------

Storage:
========

## AWS Backup
------------

## Amazon Elastic Block Store (Amazon EBS)
-----------------------------------------

## Amazon Elastic File System (Amazon EFS)
-----------------------------------------

## Amazon FSx (for all types)
----------------------------

## Amazon S3
-----------

## Amazon S3 Glacier
-------------------

## AWS Storage Gateway
---------------------
