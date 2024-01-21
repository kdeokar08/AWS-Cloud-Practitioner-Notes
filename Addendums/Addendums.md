

AWS Application Integration Services - Technical.

    Amazon Event Bridge - Event Driven Applications.
        > No custom code required or server management. 
        > Connect AWS, SaaS and custom apps for event workflows.
        > Manage millions of events with Eventbridge scheduler.
        Developers face trouble in integrating two different applications. Event bridge manages that side for you. 

    Visual Workflows with AWS Step Functions.
        > Intutive drag and drop interface with workflow studio.	
        > Automation across 220 aws services.
        > On-demand data processing using parallel workflows.
        > Develop and visualize robus workflows for event-driven setups.	

Topic B: Addendum - Networking Services.
    VPN Services:
        Client VPN: 
            enables remote workforce to access resources securely.
            connects both aws and on-prem networks.
        Site to Site:
            link data centres and remote offices to aws resources.

    Global Accelerator:
        Enhanced networking for public application
            performance boost for apps
            two ips are given as entry point.
            connect up to 10 regions within aws network.

    API Gateway: API Management 
        api creation publishing maintainence and security.
        enables applications to access data,logic,backend.
        supports both rest and websocket.
        integrates with containerized, serverless workloads, and web applications.

    

Topic C: Addendums - AWS Storage and Database Services.
    Amazon FSx: comprehensive Managed File System Solutions.
        > cost-effective, reliable, scalable, feature-rich, high performance. for a wide range of workloads.
        > built on latest latest network of compute.
        > higher performance & lower TCO.
        > fully managed - it will manage all hardware, patching and backups.
        Types:
            netapp ontap 
            open zfs
            windows file server
            lustre


    Amazon Storage Gateway: Bridges on-premises and cloud storage.
    
        > on-prem access to virtually unlimited AWS Storage. 
        > Simplifies storage management and reduces costs for hybrid use cases.
            > Tape gateway: Stores virtual tapes in S3
            > Amazon S3 File Gateway: Backs up on prem data as objects in amazon s3, supports hybrid workflows.
            > Fsx file gateway: integreates with aws services for enhanced storage management and data protection.
            > local backups

    AWS Elastic Disaster Recovery(DRS): Cost effectivity & Rapid Recovery.
        eliminate idle recovery site costs; pay for full disaster recovery only when activated.
    
    AWS Backup: protection for hybrid workloads.
        about data protection & integrity.
        safeguards aws storage, db, compute services.
        streamlined backup scheduling and retention. backups taken of all data - third party can view in a single dashboard.

    In memory database on aws: ultra fast
        elastic cache for redis
            support 15 shared with 6.1tb in-memory capacity.

        elastic cache for memcached:
            for frequently acccessed data in gaming, web, ad-tech.

        memory db for redis:
            ultra-fast performance.
            microsecond read and single-digit write latency.
            durable across azs

Module 11: 
    AWS Compute & Container Services - Technical.
        1. Amazon Lightsail - Web hosting - easy, affordable.
            designed for beginners.
            ideal for blogs, e-commerce, wordpress.
            cost effective for smaller projects.

        2. AWS Elastic Beanstalk - Simplified Web App Deployment.
            tailor made for web based applications.
            specify what language and some infra settings.
            infra management is done by the service.
            only coding is to be focused.
        
        3. AWS Batch: Large Task Volumes
            > Large batch processing tasks & ml computations.
            > The compute resources needed will be handled by aws 
            batch so that we can just focus on the outcomes.
            > Organizes, schedules and executes tasks.
            > Utilizes AWS options: ECS, EKS, Fargate, Spot, On-Demand Instances.
    
    Extension to AWS Global Infra that are related to Compute Topic.
        1. AWS Local Zones: Places Compute, Database, Storage and other selected AWS Services closer to densely populated areas.
            Faster Applications: reduce latency. 
            Simplified hybrid cloud: easy migration.
            data compliance regulations: adhere to local data rules for healthcare, finance.

        2. AWS Wavelength Zones: AWS Services in 5G networks.
           Compute, Storage services in 5g networks. Low latency. VPC (Virtual Private Cloud) can be extended to one or more wavelength zones.
           Wavelength zones are associated with regions.

    Amazon ECR(Elastic Container Registry)
        Efficient container management.
        simplifies processing of storing and sharing container images.

