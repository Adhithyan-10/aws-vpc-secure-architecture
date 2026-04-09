# 🏗️ Architecture

This folder contains the architecture diagram of the project.

The architecture represents a secure AWS VPC design with:

* Public Subnet (Bastion Host)
* Private Subnet (Backend EC2)
* Internet Gateway (IGW)
* NAT Gateway

The diagram clearly shows:

* Controlled inbound access via Bastion Host
* No direct internet access to private EC2
* Outbound-only internet via NAT Gateway
