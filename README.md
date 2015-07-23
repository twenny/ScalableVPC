#Scalable VPC Template
AWS CloudFormation template for creating a VPC of a specified size.

Provides:
* Scaling from one public subnet (1x1) to three layers of subnets across three AZs (3x3)
* Immutable NAT instances - no SSH keys, logs sent to CloudWatch Logs
* Dynamic public IPs to conserve EIPs

![Architecture & Parameters](https://raw.githubusercontent.com/twenny/ScalablVPC/master/images/parameters.png "Architectures & Parameters")

![Resource Creation Logic](https://raw.githubusercontent.com/twenny/ScalableVPC/master/images/creation_logic.png "Resource Creation Logic")

![Condition Dependencies & Inheritance](https://raw.githubusercontent.com/twenny/ScalableVPC/master/images/conditions.png "Condition Dependencies & Inheritance")
