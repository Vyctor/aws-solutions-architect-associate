# Curso a

## AWS Fundamentals

### The Building Blocks of AWS: Availability Zones and Regions

**AWS have 24 regions and 77 availability zones.**

#### Availability Zone

Is has one or multiple data centers that is a building or a group of buildings filled with servers. Every availability zone is isolated from each other, but they are connected through low latency links.

#### Region

Is a geographical area that has **two or more availability zones**.

#### Edge location

Are endpoints for AWS that are used for caching content. Typically this consists of CloudFront, Amazon's Content Delivery Network (CDN).
**There are many more edge locations than regions. Currently there are 215 edge locations.**

#### AWS Service Types

To AWS Solutions Architect Associate exam, you need to know the following service types:

- Analytics
- Management & Governance
- Migration & Transfer
- Compute
- Application Integration
- Security, Identity & Compliance
- Networking & Content Delivery
- Storage
- Containers
- AWS Cost Management
- Databases
- AWS Global Infrastructure

#### Exam Tips

- A **Region** is a physical location in the world which consists of two or more **Availability Zones** (AZ's).
- An **Availability Zone** (AZ) is one or more discrete data centers, each with redundant power, networking and connectivity, housed in separate facilities.
- **Edge Locations** are endpoints for AWS which are used for caching content. Typically this consists of CloudFront, Amazon's Content Delivery Network (CDN).

### Who owns what in the cloud?

#### The Shared Responsibility Model

AWS is responsible for the security of the cloud, while you are responsible for security in the cloud.

#### Can you do this yourself in the AWS Management Console?

- If yes, you're likely responsible for it.
  - Security groups, Iam Users, patching EC2 operating systems, patching databases running on EC2, etc..
- If no, AWS is likely responsible for it.
  - Management of data centers, security cameras, cabling, patching RDS, operating systems, etc..
- Encryption is a shared responsibility.

### Compute, storage, databases and networking

#### Compute

You wouldn't be able to build and application without compute power - you need something crunching the data.

- EC2
- Lambda
- Elastic Beanstalk

#### Storage

Is a giant disk in the cloud, a safe place to save your information

- S3
- EBS
- EFS
- FSx
- Storage Gateway

#### Databases

The easiest way to think of a database is a spreadsheet. It's a way to store and retrieve information.

- RDS
- DynamoDB
- Redshift

#### Networking

We need a way for our compute storage and databases to communicate and even a place them to live. This is where networking comes in.

- VPC
- Direct Connect
- Route 53
- API Gateway
- AWS Global Accelerator

#### Key Services For Know For The Exam

- Compute
  - EC2
  - Lambda
  - Elastic Beanstalk
- Storage
  - S3
  - EBS
  - EFS
  - FSx
  - Storage Gateway
- Databases
  - RDS
  - DynamoDB
  - Redshift
- Networking
  - VPC
  - Direct Connect
  - Route 53
  - API Gateway
  - AWS Global Accelerator

### Well Architected Framework

#### Operation Excellence

Running and monitoring systems to deliver business value and continually improving processes and procedures.

#### Performance Efficiency

Using IT and computing resources efficiently.

#### Security

Protecting information and systems.

#### Reliability

Ensuring a workload performs its intended function correctly and consistently when it's expected to.

#### Cost Optimization

Avoiding un-needed costs.

#### Sustainability

Minimizing the environmental impacts of running cloud workloads

### AWS Fundamentals Exam Tips

- A region is a physical location in the world which consists of two or more availability zones.
- An AZ is one or more discrete data centers, each with redundant power, networking and connectivity, housed in separate facilities.
- Edge Locations are endpoints for AWS that are used for caching content. Typically this consists of CloudFront, Amazon's Content Delivery Network (CDN).
- Can you do this yourself in the AWS Management Console? If yes, you're likely responsible for it. If no, AWS is likely responsible for it.

**Read Well Architected Framework whitepaper.**

## Identity Access Management (IAM)
