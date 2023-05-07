## Project X
Project to provision an infrastructure on AWS for a multi-tier application (Service X) using Terraform.

### Divisions
* <strong>Network:</strong> 
    * Route Table
    * Internet Gateway
    * Subnet:
        * Public
        * Private
    * VPC
* <strong>FrontEnd:</strong> 
    * Auto Scalling
    * Load Ballancer
    * Security Group
* <strong>BackEnd:</strong> 
    * API
    * IAM Role
    * Lambda Function
    * Security Group
* <strong>Database:</strong> (MySQL and Postgre) 
    * DB - Instance
    * DB - Parameters Group
    * DB - Subnet Group
