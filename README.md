# Ex.4 Deployment and configuration of a Private Cloud  in AWS
## NAME: GOKUL SHARAN R
## REG NO: 212223040052

## Aim:
To set up of a Private Cloud  in AWS.

## Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.

## Procedure:
## 1. Plan Your VPC:
## ● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
## ● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
## ● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
## ● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
## ● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.

## 3. Create Your VPC:
Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
 Choose "Create VPC": Initiate the VPC creation process.
Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
other necessary settings.
Create subnets: Define subnets within your VPC to isolate different parts of your
network.
Create route tables: Specify how traffic is routed within and outside the VPC.
 Create security groups: Define access control rules for your resources.

## 4. Deploying Resources:
Launch EC2 instances: Create and launch virtual machines within your VPC.
 Set up RDS instances: Deploy databases for your applications.
Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

## 5.Managing and Monitoring:
Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
Implement security best practices: Regularly review and update your security
configuration.
Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

##  Output:

## Create VPC:

![image](https://github.com/user-attachments/assets/a688ced3-32ec-42f2-afdf-d3d6ed46a923)


## Configure subnets:

![image](https://github.com/user-attachments/assets/e83ff395-389e-4046-bdc8-5355177b5e44)


![image](https://github.com/user-attachments/assets/1eb4d4cf-bf54-4b6b-b238-a135b7d65c3e)


## Setting Internet Gateway:

![image](https://github.com/user-attachments/assets/f1d06462-4013-4d11-a2fb-ae8a90575357)


![image](https://github.com/user-attachments/assets/571bf150-0042-4c72-b304-e5487f5be5d2)


![image](https://github.com/user-attachments/assets/a2cd9a0a-d06a-4064-9e3c-2d2e4925ae33)


## Creating Route Table:

![Screenshot 2025-05-13 132731](https://github.com/user-attachments/assets/ed8136ca-ff43-4627-9582-bb9a2c470a54)

## Configuring Route Table:

![image](https://github.com/user-attachments/assets/50754fea-3a18-4e8d-bc28-a0675abcd739)

## Editing Routes:

![image](https://github.com/user-attachments/assets/cb5b8235-f2ad-459a-90f5-cfb8f6d7fbc5)


## Creating Route Table:

![image](https://github.com/user-attachments/assets/c87b1ce8-36bf-4f41-ad48-383427e80d07)

## Result:

Thus, a private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.


