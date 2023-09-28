# Create Internet Gateways

September 28, 2023

By:  Annie V Lam - Kura Labs

## Internet Gateways connects two different networks that uses different rules for communicating

### Internet Gateways

1.  Navigate to https://us-east-1.console.aws.amazon.com/vpc/home?region=us-east-1#Home:
2.  Click "Internet gateways"
3.  Click "Internet gateways"
4.  Click the "Name tag" field and enter an name (e.g."kura-gateway")
5.  Click "Create internet gateway"

### Attach the VPC to the Internet gateway
6.  Click "Internet gateways"
7.  Click "Actions"
8.  Click "Attach to VPC"
9.  Under Available VPC, select your VPC
10. Click "Attach internet gateway"

### Link your public subnet to a public route table
13.  Click "Route tables"
14.  Expand this column to see your VPC name
15.  Select your the route table that is not private
16.  Click "Routes"
17.  Click "Edit routes"
18.  Click "Add route"
19.  Click on the Destination search field
20.  Select 0.0.0.0/0
21.  Click on the Target search field
22.  Click "Internet Gateway"
23.  Select your internet gateway
24.  Click "Save changes"

### Verify your VPC
1.  Click "Your VPCs"
2.  Select your vpc
3.  Click "Resource map"

### To reroute subnets to different route tables
1.  Click "Routing Tables"
2.  Select the route table
3.  Select "Subnet associations"
4.  Select "Edit subnet assocation"
5.  Select the subnets that should be linked to this route table
6.  

