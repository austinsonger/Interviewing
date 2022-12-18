# Networking

### What is a VPC?

A logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network that you define

* a subnet must reside entirely in one AZ.

\


### What is a Internet Gateway?

Component that allows communication between instances in your VPC and the internet

* Only one internet gateway can be attached to a single VPC.

\


### What are Security Groups and Network ACLs?

* NACL - security layer on the subnet level.
  * NACL allow or deny traffic on the subnet level
* Security Group - security layer on the instance level.



### What is AWS Direct Connect?

Allows you to connect your corporate network to AWS network.

### What is an Elastic IP address?

An Elastic IP address is a static IPv4 address designed for dynamic cloud computing. An Elastic IP address is allocated to your AWS account, and is yours until you release it. By using an Elastic IP address, you can mask the failure of an instance or software by rapidly remapping the address to another instance in your account.



### Why would you use an Elastic IP address?

Let's say you have an instance that you need to shutdown or perform some maintenance on. In that case, what you would want to do is to move the Elastic IP address to another instance that is operational, until you finish to perform the maintenance and then you can move it back to the original instance (or keep it assigned to the second one).

### What are the best practices around Elastic IP?

The best practice is actually not using them in the first place. It's more common to use a load balancer without a public IP or use a random public IP and register a DNS record to it

###

### What would you use if you need a fixed public IP for your EC2 instance?

Elastic IP

###

### What is VPC peering?

A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them using private IPv4 addresses or IPv6 addresses."
