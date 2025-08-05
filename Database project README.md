# 📂 Project 1: Build Your DB Server and Interact With Your DB Using an App
Overview
This project focuses on establishing a robust and highly available database infrastructure on AWS, and then demonstrating seamless interaction with it via a web application. The core objective was to simulate a common three-tier application setup, where a web server communicates with a backend database. This hands-on exercise provided crucial experience in deploying managed database services, configuring secure network access, and validating application-to-database connectivity.

## Project Objectives
### The key objectives for this lab project were:

Launch an Amazon RDS DB instance with high availability: To ensure the database's resilience and continuous operation, even in the event of an Availability Zone outage.

Configure the DB instance to permit connections from your web server: To establish secure and controlled network access between the application layer and the database layer using AWS networking and security features.

Open a web application and interact with your database: To validate the end-to-end connectivity and demonstrate that the application can successfully read from and write to the deployed database.

## Architecture Diagram

### We will start off with this infrastructure

![image alt](https://github.com/Nndoza/AWS-re-start-Program/blob/43636a2b38a3eb54fd1cc84e98a7f11e17dd5ffa/Project%201%3A%20Database/Screenshot%202025-07-07%20205400.png)

### And end up with this infrastructure

![image alt](https://github.com/Nndoza/AWS-re-start-Program/blob/3cb67096aa158e1b85497f97d7d98958c8c6ac22/Project%201%3A%20Database/Screenshot%202025-07-07%20205416.png)

## Screenshots of Steps Taken

### Task1: Create a Security Group for the RDS DB Instance

In this task, I created a security group to allow the webserver to access the RDS DB instance. The security group will be used when I launch the database instance.

![image alt](https://github.com/Nndoza/AWS-re-start-Program/blob/42844ffd0204d9d7b81c0e01c620103fc79ddf24/Project%201%3A%20Database/Task%201.png)

### Task2: Create a DB subnet Group

In this task, I created a DB subnet group that is used to tell RDS which subnets can be used for the database. Each DB subnet group requires subnets in at least two Availability Zones.

![image alt](https://github.com/Nndoza/AWS-re-start-Program/blob/7fe945aa6ac045fc7a7a746a43dd947be04c2eb6/images/task%202.png)

### Task 3: Create an Amazon RDS DB instance

In this task, I configured and launched a Multi-AZ Amazon RDS for MySQL database instance.



### Task 4: Interact with Your Database

In this task, I opened a web application running on your web server and configured it to use the database. 





