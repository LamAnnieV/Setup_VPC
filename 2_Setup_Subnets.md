# Setup Subnets

September 28, 2023

By:  Annie V Lam - Kura Labs

## A subnet is used to segment a network into a smaller network

### Create a public subnet A
1.  Navigate to https://us-east-1.console.aws.amazon.com/vpc/home?region=us-east-1#Home:
2. Click "Subnets"
3.  Click "Create subnet"
4.  Select a VPC
5.  Click the "Subnet name" field and enter "my-private-subnetA"
6.  For Availabiity Zone select "us-east-1a"
7.  Click the "IPv4 CIDR blockInfo" field and enter "172.18.0.0/18"

### Create a private subnet A
8.  Click "Add new subnet"
9.  Click the "Subnet name" field and enter "my-private-subnetA"
10. For Availabiity Zone select "us-east-1a"
11. Click the "IPv4 CIDR blockInfo" field and enter "172.18.64.0/18"

### Create a public subnet B
12.  Click "Add new subnet"
13.  Click the "Subnet name" field and enter "my-public-subnetB"
14. For Availabiity Zone select "us-east-1b"
15. Click the "IPv4 CIDR blockInfo" field and enter "172.18.128.0/18"

### Create a private subnet B
8.  Click "Add new subnet"
9.  Click the "Subnet name" field and enter "my-private-subnetB"
10. For Availabiity Zone select "us-east-1b"
11. Click the "IPv4 CIDR blockInfo" field and enter "172.18.192.0/18"
12. Click "Create subnet"
