A VPC, or Virtual Private Cloud, is essentially your own private network in AWS.
VPC allows to define private IP ranges for your AWS resources, like EC2 instances and ELBs. 

Resources are placed into subnets.
Subnets - chunk of IP addresses in your VPC that allow you to group resources together.
Subnets + Rule = Access

Public Gateway
  For public traffic to enter into your vpc - internet gateway must be attached.

Private Gateway
  For a VPC containing all internal private resources - no gateway.
    a private gateway, only allowing ones coming from an approved network. (Such as dedicated VPN)
    This is called a virtual private gateway.
    To establish, encrypted VPN connection to your private resources we would need a virtual private gateway.

    But even connecting to this private resources using VPN, this would be slow as the bandwidth would be shared with people using internet.
    With AWS, you can achieve that using what is called AWS Direct Connect. 
    Direct Connect allows you to establish a completely private, dedicated fiber connection from your data center to AWS.

Subnet and Network Access Control Lists.
    Every packet that crosses the subnet boundaries gets checked against something called a network access control list or
    network ACL. This check is to see if the packet has permissions to either leave or enter the subnet based on who it was sent from and how it's trying to communicate.
      
