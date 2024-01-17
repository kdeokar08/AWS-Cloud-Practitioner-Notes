Regions, AZs, DataCentres.

  AWS builds Regions to be closest to where the business traffic demands. 
  Inside each Region, we have multiple data centers that have all the compute, storage, and other services you need to run your applications. 
  Each Region can be connected to each other Region through a high speed fiber network, controlled by AWS, a truly global operation from corner to corner if you need it to be.

  To choose a region, consider following 4 topics:
    1. Compliance - where should the data live ?
    2. Proximity. (latency issues)
    3. Feature availability.
    4. Pricing

  Each Region is made of multiple data centres.
  A single datacenter or group makes up an availability zone.
  Each region consists of multiple availability zones. Availability zones have multiple datacenters.

Edge locations - 
  AWS Edge locations run Amazon CloudFront to help get content closer to your customers, no matter where they are in the world.
  Make data available to places where datacentre is not present by caching there. Using CDN's.
  Edge locations run CDN's , DNS (Amazon Route 53)

AWS Outposts - Customer's datacentre itself hosts AWS services.
What is your business wants to use, AWS services inside their own building ? 
AWS will install an operational mini region. inside customer's data centre.

To interact with AWS Services
  1. AWS Management Console.
  2. AWS Command Line Interface
  3. Software Development Kits.

Elastic Bean Stalk - provision your cloud deployments for EC2 only.
  you can instead provide your application code and desired configurations to the AWS Elastic Beanstalk service,
  which then takes that information and builds out your environment for you.

AWS Cloud Formation - infra as code.
   help create automated and repeatable deployments.
   declarative way using JSON or YAML text-based documents called CloudFormation templates
   It also isn't just limited to EC2-based solutions. 
   CloudFormation supports many different AWS resources from storage, databases, analytics, machine learning, and more.
   
