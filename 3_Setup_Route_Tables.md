# Setup Route Tables

September 28, 2023

By:  Annie V Lam - Kura Labs

## Route table contains a set of rules that is used to determine where data packets travelin over the internet will be directed.

### Create Route Tables

1.  Navigate to https://us-east-1.console.aws.amazon.com/vpc/home?region=us-east-1#Home:
2.  Route tables
3.  Click "Create route table"
4.  Click the "Name - optional" field and name your route table with "private" in the name (e.g. "private-kura-rt")
5.  Click "Select a VPC" and select your VPC
6.  Click "Create route table"

### To verify your route table 
7. Click "Route tables"
8. You should see your route table

### Link your private subnet to the privaate route table
9.   Click "Edit subnet associations"
10.  Click this checkbox of your private subnet B
11.  Click this checkbox of your private subnet A
12.  Click "Save associations"

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
