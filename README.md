# Cloud Resource Descriptions and Comparison Table

This document compares common cloud services across AWS, Microsoft Azure, and Google Cloud Platform.

| # | Description | AWS (Service Name) | Azure (Service Name) | Google Cloud (Service Name) |
|---|-------------|---------------------|-----------------------|------------------------------|
| 1 | A compute service that provides scalable virtual machines for running applications. | Amazon EC2 | Azure Virtual Machines | Compute Engine |
| 2 | An object storage service used to store and retrieve data, commonly used for backups and static website content. | Amazon S3 | Azure Blob Storage | Cloud Storage |
| 3 | A managed relational database service that supports multiple database engines like MySQL, PostgreSQL, and SQL Server. | Amazon RDS | Azure SQL Database | Cloud SQL |
| 4 | A serverless compute service that allows you to run code in response to events without provisioning or managing servers. | AWS Lambda | Azure Functions | Cloud Functions |
| 5 | A virtual private network service that allows you to create isolated networks within the cloud provider’s infrastructure. | Amazon VPC | Azure Virtual Network (VNet) | Virtual Private Cloud (VPC) |
| 6 | A content delivery network (CDN) service that delivers data, videos, applications, and APIs with low latency. | Amazon CloudFront | Azure CDN | Cloud CDN |
| 7 | A managed NoSQL database service designed for low-latency, high-scale applications. | Amazon DynamoDB | Azure Cosmos DB | Firestore |
| 8 | A block storage service for use with virtual machines, offering persistent storage for data. | Amazon EBS | Azure Managed Disks | Persistent Disk |
| 9 | A managed container orchestration service based on Kubernetes. | Amazon EKS | Azure Kubernetes Service (AKS) | Google Kubernetes Engine (GKE) |
| 10 | A service for managing user access and encryption keys to secure cloud resources. | AWS IAM | Microsoft Entra ID (Azure AD) | Cloud IAM |
| 11 | A platform that automates application deployment and scaling without needing to manage infrastructure. | AWS Elastic Beanstalk | Azure App Service | App Engine |
| 12 | A service that provides monitoring and logging of applications and infrastructure. | Amazon CloudWatch | Azure Monitor | Cloud Monitoring |
| 13 | A domain name system (DNS) service that routes traffic globally and translates domain names to IP addresses. | Amazon Route 53 | Azure DNS | Cloud DNS |
| 14 | A load balancing service that distributes incoming network traffic across multiple targets. | Elastic Load Balancing (ELB) | Azure Load Balancer | Cloud Load Balancing |
| 15 | A service that automatically scales cloud infrastructure based on demand. | AWS Auto Scaling | Virtual Machine Scale Sets | Managed Instance Groups |
| 16 | A message queuing service that enables applications to send and receive messages between components. | Amazon SQS | Azure Service Bus | Pub/Sub |
| 17 | A managed real-time data streaming service for large volumes of data. | Amazon Kinesis | Azure Event Hubs | Dataflow |
| 18 | A fully managed, highly scalable data warehouse for analytics. | Amazon Redshift | Azure Synapse Analytics | BigQuery |
| 19 | A workflow orchestration service that integrates multiple cloud services. | AWS Step Functions | Azure Logic Apps | Workflows |
| 20 | A data integration (ETL) service for moving and transforming data. | AWS Glue | Azure Data Factory | Data Fusion |
| 21 | A data catalog and governance service for metadata management. | AWS Glue Data Catalog | Microsoft Purview | Data Catalog |
| 22 | A set of machine learning and AI services. | Amazon SageMaker | Azure AI Services | Vertex AI |
| 23 | Infrastructure as Code (IaC) for defining and deploying cloud resources. | AWS CloudFormation | Azure Bicep | Deployment Manager |
| 24 | A CI/CD service for building and deploying applications. | AWS CodePipeline | Azure DevOps | Cloud Build |
| 25 | Desktop as a Service (DaaS) for cloud-based virtual desktops. | Amazon WorkSpaces | Azure Virtual Desktop | Workstations |
| 26 | Backup and disaster recovery service. | AWS Backup | Azure Backup | Backup and DR |
| 27 | Big data analytics and processing service. | Amazon EMR | Azure Databricks | Dataproc |
| 28 | File storage service for shared file systems. | Amazon EFS | Azure Files | Filestore |
| 29 | Media processing and streaming service. | AWS Elemental Media Services | Azure Media Services | Transcoder API |
| 30 | Real-time communication and notification service (email, SMS, push). | Amazon SNS | Azure Notification Hubs | Firebase Cloud Messaging (FCM) |

## Reflection

This comparison highlights that major cloud providers offer similar core services with different naming conventions. While AWS, Azure, and Google Cloud provide comparable compute, storage, networking, and data services, each platform has unique strengths and integrations. Understanding these mappings helps cloud architects design portable and scalable cloud architectures.
