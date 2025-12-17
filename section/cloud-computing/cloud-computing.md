# Cloud Computing

- [Cloud Computing](#cloud-computing)
  - [What is Cloud Computing?](#what-is-cloud-computing)
    - [The Deployment Models of the Cloud](#the-deployment-models-of-the-cloud)
    - [The Five Characteristics of Cloud Computing](#the-five-characteristics-of-cloud-computing)
    - [Six Advantages of Cloud Computing](#six-advantages-of-cloud-computing)
    - [Problems Solved by the Cloud](#problems-solved-by-the-cloud)
    - [Types of Cloud Computing](#types-of-cloud-computing)
    - [Example of Cloud Computing Types](#example-of-cloud-computing-types)
    - [Pricing of the Cloud – Quick Overview](#pricing-of-the-cloud--quick-overview)
    - [How Cloud Pricing Solves Traditional IT Cost Issues](#how-cloud-pricing-solves-traditional-it-cost-issues)
    - [AWS Cloud Use Cases](#aws-cloud-use-cases)

## What is Cloud Computing?

Cloud computing is the on-demand delivery of compute power, database storage, applications, and other IT resources through a cloud services platform with pay-as-you-go pricing. It provides:

- Provisioning of exactly the right type and size of computing resources.
- Access to as many resources as needed, almost instantly.
- A simple way to access servers, storage, databases, and a set of application services.
- Amazon Web Services (AWS) owns and maintains the network-connected hardware, while you provision and use what you need via a web application.

### The Deployment Models of the Cloud

| **Private Cloud**                                                        | **Public Cloud**                                                                                         | **Hybrid Cloud**                                                             |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| Cloud services used by a single organization, not exposed to the public. | Cloud resources owned and operated by a third-party cloud service provider, delivered over the Internet. | Keep some servers on-premises and extend some capabilities to the cloud.     |
| Complete control over data, security, and compliance.                    | Cost-effective as infrastructure is shared among multiple users.                                         | Allows data and applications to be shared between private and public clouds. |
| Security for sensitive applications, ideal for critical workloads.       | Suitable for less sensitive workloads that require high scalability and availability.                    | Offers flexibility, security, and scalability for different use cases.       |
| Meet specific business needs and compliance requirements.                | No maintenance required as the cloud provider manages the infrastructure.                                | Provides business continuity, disaster recovery, and data backup solutions.  |

### The Five Characteristics of Cloud Computing

1. **On-demand self-service**: Provision computing resources as needed automatically.
2. **Broad network access**: Access cloud resources over the network using standard mechanisms.
3. **Resource pooling**: Providers serve multiple customers using a multi-tenant model.
4. **Rapid elasticity**: Resources can be scaled up or down rapidly.
5. **Measured service**: Resource usage is monitored and billed accordingly.

### Six Advantages of Cloud Computing

1. **Cost Savings**: Pay only for the computing power, storage, and other resources you use.
2. **Speed and Agility**: Quickly deploy services and resources.
3. **Scalability**: Easily scale resources up or down as needed.
4. **High Availability**: Highly available architecture for business continuity.
5. **Global Reach**: Access services from any geographical region.
6. **Security**: AWS provides robust security capabilities to protect your data.

### Problems Solved by the Cloud

- **High upfront costs**: Replaced by a pay-as-you-go model.
- **Scalability limitations**: Dynamic scaling to meet business demands.
- **Limited infrastructure availability**: Global infrastructure to support workloads.

### Types of Cloud Computing

| **Infrastructure as a Service (IaaS)**                                      | **Platform as a Service (PaaS)**                                                                               | **Software as a Service (SaaS)**                                                            |
| --------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| Provides virtualized computing resources over the internet (e.g., AWS EC2). | Provides a platform allowing customers to develop, run, and manage applications (e.g., AWS Elastic Beanstalk). | Provides software applications over the internet on a subscription basis (e.g., AWS Chime). |
| Offers maximum control over the infrastructure.                             | Focus on deploying applications without managing underlying infrastructure.                                    | Accessible over the internet, usually via a web browser.                                    |
| Suitable for developers needing control over OS, middleware, and runtime.   | Ideal for developers who want to focus on application development.                                             | Suitable for users needing access to software without infrastructure management.            |

### Example of Cloud Computing Types

- **IaaS**: AWS EC2 (Elastic Compute Cloud)
  - GCP, Azure, Rackspace, Digital Ocean, Linode
- **PaaS**: AWS Elastic Beanstalk
  - Heroku, Google App Engine (GCP), Windows Azure (Microsoft)
- **SaaS**: AWS Chime
  - Google Apps (Gmail), Dropbox, Zoom

### Pricing of the Cloud – Quick Overview

AWS follows three fundamental pricing principles based on the pay-as-you-go pricing model:

| **Fundamental**       | **Description**                                                                                                                                                      |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Compute**           | Pay for the compute time you consume. Examples include EC2 instance hours or Lambda invocation duration.                                                             |
| **Storage**           | Pay for the amount of data stored in the cloud. Examples include S3 storage space and EBS volume usage.                                                              |
| **Data Transfer OUT** | Pay for data transfer out of the cloud. Data transfer IN is free. This pricing structure solves the issue of expensive data transfer fees in traditional IT systems. |

### How Cloud Pricing Solves Traditional IT Cost Issues

- Traditional IT requires expensive upfront investments for hardware, maintenance, and upgrades.
- With AWS's pay-as-you-go model, you only pay for what you use, reducing overall costs.
- You can scale up or down based on demand, minimizing under-utilized resources.

### AWS Cloud Use Cases

1. **Web Hosting**: Host websites with elastic scaling and high availability.
2. **Big Data Analytics**: Run analytics on large datasets.
3. **Application Hosting**: Host applications with global accessibility and automated scaling.
4. **Disaster Recovery**: Implement disaster recovery strategies with minimized infrastructure.
5. **Backup and Storage**: Store backups in a highly durable and secure manner.
