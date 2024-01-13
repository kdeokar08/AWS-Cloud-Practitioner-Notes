A VPC, or Virtual Private Cloud, is essentially your own private network in AWS.
VPC allows to define private IP ranges for your AWS resources, like EC2 instances and ELBs. 

Resources are placed into subnets.
Subnets - chunk of IP addresses in your VPC that allow you to group resources together.
Subnets + Rule = Access

Public Gateway
  > For public traffic to enter into your vpc - internet gateway must be attached.

Private Gateway
   > For a VPC containing all internal private resources - no gateway.
     a private gateway, only allowing ones coming from an approved network. (Such as dedicated VPN)
     This is called a virtual private gateway.
     To establish, encrypted VPN connection to your private resources we would need a virtual private gateway.

AWS Direct Connect
> But even connecting to this private resources using VPN, this would be slow as the bandwidth would be shared with people using internet. Using AWS Direct Connect, it allows you to establish a completely private, dedicated fiber connection from your data center to AWS.

Subnet and Network Access Control Lists.
Network ACL - virtual firewall. Allows all inbound and outbount traffic.
> Every packet that crosses the subnet boundaries gets checked against something called a network access control list or network ACL. This check is to see if the packet has permissions to either leave or enter the subnet based on who it was sent from and how it's trying to communicate.
> Stateless, has no memory of the packets entering the subnet. Hence a check is done on the way outward too.
> Allow all incoming packets by default.

> But sometimes, different EC2 instances in the same subnet have different rules. (Who can send messages, port settings etc).
For such instance level access issues, security group is introduced.
> Stateful - keep tracks of packets entering, hence allows packet to leave without a check.
> Deny all packets by default.


Amazon Route 53 - DNS
Once customer receives the IP address from DNS service, the customer's request is sent to the nearest edge location through Amazon CloudFront.
Amazon Cloud Front connects to Application Load Balancer.
