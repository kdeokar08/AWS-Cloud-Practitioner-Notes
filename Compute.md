```
Compute
  EC2 - Amazon Elastic Compute Cloud.
    The service you use to gain access to virtual servers is called EC2.
    Pay for what you use. Because with EC2, you only pay for running instances, not stopped or terminated instances. 
    EC2 runs on top of physical host machines managed by AWS using virtualization technology. 
    When you spin up an EC2 instance, you aren't necessarily taking an entire host to yourself. 
    Instead, you are sharing the host with multiple other instances, otherwise known as virtual machines. 
    And a hypervisor running on the host machine is responsible for sharing the underlying physical resources between the virtual machines. 
    This idea of sharing underlying hardware is called multitenancy. 

  To create an EC2 instance - define the following
    Hardware specifications: CPU, memory, network, and storage bullet
    Logical configurations: Networking location, firewall rules, authentication, and the operating system of your choice

  Before creating an EC2 first setting that is choosing the operating system by choosing the AMI.
  AMIs can be choosen from AWS itself, marketplace, custom one created by user, Community.

  Amazon EC2 instance types - decoding names
    c5n.xlarge
    c - instance type (compute)
    5 - generation
    n - attribute
    xlarge - size.
    
  

  EC2 - Instance Types
    General purpose, Compute optimized, Memory optimized, Accelerated computing, and Storage optimized.
    General - good balance of compute, memory, network, storage. Usage - web services / code repositories.
    Compute - compute intensive tasks, gaming, scientific modelling, high performance computing(HPC)
    Memory - memory optimized instances are good for memory-intensive tasks. 
    Accelerated computing - for floating point number calculations, graphics processing, or data pattern matching, as they use hardware accelerators
    Storage optimized - high performance for locally stored data.
    
```
