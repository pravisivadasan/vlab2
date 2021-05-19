# Challenge 1
The Terraform script is used to create a 3-tier Architecture on AWS. The infrastructure contains the following components 
````
* Web Tier
* App Tier
* DataBase Tier
````
Terraform scripts palced in different folder for ease of development and managment of configuration files. almost all configuration paramaters are variablized. it contain the follwoing resource
VPC, Subnets,NAT, IGW, Security groups, Auto scaling group, ALB, RDS, S3.

We using AWS secrect manager to store credentils to avoid any security flaws in terraform configuration files.

We using AWS S3 as remote backed to store state file. DynamoDB for state locking.
