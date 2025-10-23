AWS Networking
It refers to the suite services and tools that enables users to build secure and scalable networks in the cloud.

Amazon VPC
A virtual private cloud (VPC) is a private network in the cloud

Amazon VPC components
1. A subnet
  A Subnet (sub-network) is a smaller section of your VPC and it also allows you to group and isolate your resources.
2. A Route Table 
   is a set of rules (routes) that determine where network traffic should go from a subnet.
3. An internet gateway
 It allows resources in your public subnets (such as EC2 instances) to connect to the internet if the resource has a public IPv4  address or an IPv6 address.
4. NAT Gateways (AWS- managed) & NAT Instances (self-managed) 
   allow your instances in your Private Subnets to access the internet while remaining private.
5.  Security Group
    A security group acts as a virtual firewall for your EC2 instances to control incoming and outgoing traffic.
    They have inbound and outbound rules that control incoming and outgoing traffic from your instance.
6. Network ACL (Access Control List)
   A firewall that controls traffic from and to subnet, can have Alow and Deny rules and are attached to the subnet level.

Summary
I learned about AWS Networking, Amazon VPC and its components


