- VPC endpoint is crucial for private connectivity from your VPC to other AWS services. For example, you can create a VPC endpoint and access S3 from EC2 without going to the internet.
- Each VPC can contain one or more subnet. 
  - Some subnets are connected to the internet via an internet gateway. These are called public subnets. 
  - Private subnets do not have a route to an internet gateway.  
