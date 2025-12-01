# Private EC2 Instance Access Project

## Description
This project demonstrates how to deploy and access a *private EC2 instance* inside a private subnet.  
The instance does not have a public IP address, so it cannot be reached directly from the internet.  
To access it securely, I created a *bastion host* in a public subnet and connected to the private instance through it.  
Additionally, I configured a *NAT Gateway* to allow the private instance to access the internet for updates and outbound traffic while keeping it fully isolated from external inbound connections.

The setup shows a standard and secure way to build private infrastructure inside AWS using:
- A private EC2 instance
- A bastion host for remote SSH access
- A NAT Gateway for outbound connectivity
- Proper routing and subnet isolation

This project highlights best practices for accessing private resources inside AWS while maintaining a secure and controlled network architecture.
