# BridgeSync Hub Database Optimization and Deployment

## Introduction

The **"BridgeSync Hub Database Optimization and Deployment"** project addresses performance and scalability issues faced by BridgeSync Hub. The project involved deploying an Amazon RDS Aurora MySQL instance and configuring an EC2 instance to enhance the database infrastructure for the address book application.

## Prerequisites

1. **AWS EC2 Instance**: A running EC2 instance with appropriate SSH key and security group settings.
2. **RDS Aurora MySQL Instance**: An RDS Aurora MySQL instance set up within your VPC.
3. **MySQL Client**: Installed on the EC2 instance for database management.

## Steps to Implement

### 1. Create a VPC and Security Group

- **Create a VPC**: Set up a Virtual Private Cloud (VPC) with appropriate subnets.
- **Configure Security Group**: Define inbound and outbound rules to allow necessary traffic.

### 2. Create an RDS Aurora MySQL Instance

- **Choose Database Engine**: Select Amazon Aurora MySQL.
- **Configure Instance**: Set instance size, storage, and other parameters.
- **Enable Multi-AZ Deployment**: Ensure high availability and failover support.
- **Monitor with CloudWatch**: Set up CloudWatch for monitoring performance and resource utilization.

### 3. Configure EC2 Instance

- **Set Up EC2 Instance**: Deploy an EC2 instance and configure it with necessary software (e.g., LAMP stack).
- **Connect to RDS Aurora**: Configure the EC2 instance to connect to the RDS Aurora MySQL instance.

## Database Operations

To perform common database operations, use the following commands:

1. **Show Databases:**
   ```sql
   SHOW DATABASES;

2. **Use a Database:**
   ```sql
   USE <database-name>;

3. **Show Tables:**
   ```sql
   SHOW TABLES;

4. **Query Data:**
   ```sql
   SELECT * FROM <table-name>;

## Conclusion
The **"BridgeSync Hub Database Optimization and Deployment"** project successfully established a robust database setup, improving performance and reliability for the BridgeSync Hub address book application. This setup ensures a scalable and stable database environment, supporting the application's growth and stability.