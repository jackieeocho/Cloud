## What is Cloud Computing?
Cloud computing is the delivery of various services over the internet, including storage, computing power, networking, and databases. It enables organizations and individuals to access and use IT resources without the need for physical hardware and infrastructure.

Key features of cloud computing include on-demand availability, scalability, and pay-as-you-go pricing.

## How Do We Know if Something is in the Cloud?
A service or application is considered to be **"in the cloud"** if it meets the following criteria:

**Remote Access**: Accessible via the internet from anywhere with an internet connection.
Managed by a Third Party: Hosted and maintained by an external cloud service provider.

**Scalability**: Can scale up or down based on demand without manual intervention.
On-Demand Service: Resources can be provisioned and released automatically as needed.

**Pay-As-You-Go**: Users are charged based on their actual usage of the service, rather than a fixed cost.

## On-Premises vs. Cloud

|           | **On-Premises**                                                                                            | **Cloud**                                                                                           |
|-----------|------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Infrastructure** | Hardware and software are on the company's own servers and maintained by internal IT staff.                | Resources are on the provider's infrastructure and accessed over the internet.                      |
| **Cost**     | Requires large upfront investment in hardware and software + ongoing maintenance costs.                    | Operates on a subscription or pay-as-you-go model, reducing upfront costs for operational expenses. |
| **Scalability** | Scaling up requires purchasing and installing additional hardware, which can be time-consuming and costly. | Easily scalable with a few clicks or automatically, based on real-time demand.                      |
| **Maintenance** | Requires IT staff to manage and maintain hardware and software.                                            | The service provider handles maintenance, updates, and security.                                    |
| **Flexibility** | Limited by the capacity of the existing infrastructure.                                                    | Offers high flexibility and agility to quickly deploy new services or resources.                    |


## The Four Deployment Models of Cloud

### 1. Private Cloud


| PRIVATE CLOUD | Cloud infrastructure dedicated to a single organization. Managed either internally or by a third-party provider. |
|---------------|------------------------------------------------------------------------------------------------------------------|
| **(+)**      | Greater control over resources, improved security and privacy, customisable infrastructure.                      |
| **(-)**      | Higher cost due to dedicated resources, requires in-house expertise or managed services.                         |

### 2. Public Cloud


| PUBLIC CLOUD | Cloud infrastructure shared among multiple organizations (tenants) and managed by a third-party provider. |
|--------------|----------------------------------------------------------------------------------|
| **(+)**      | Cost-effective due to shared resources, highly scalable, minimal management overhead. |
| **(-)**      | Less control over security and compliance, potential privacy concerns.           |

### 3. Hybrid Cloud


| HYBRID CLOUD | A combination of private and public cloud infrastructures, allowing data and applications to be shared between them. |
|--------------|-----------------------------------------------------------------------------------------|
| **(+)**     | Balances cost and control, flexibility to choose optimal environment for each workload. |
| **(-)**     | Complex management, potential security challenges with data transfer between environments. |

### 4. Multi-Cloud


| MULTI CLOUD | Use of multiple cloud services from different providers, without necessarily integrating them. |
|-------------|------------------------------------------------|
| **(+)**    | ncreased resilience and redundancy.            |
| **(-)**    | Complex management and integration, potential for higher costs due to multiple vendors, varied security protocols.|


## Types of Cloud Services: IaaS, PaaS, SaaS

### 1. Infrastructure as a Service (IaaS)

| Aspect         | Details                                                                                       |
|----------------|-----------------------------------------------------------------------------------------------|
| **Definition** | Provides virtualized computing resources over the internet. Users rent infrastructure components such as servers, storage, and networking. |
| **(+)**       | Flexible and scalable, pay-as-you-go pricing, no need for physical hardware, high control over the infrastructure.               |
| **(-)**       | Requires IT expertise to manage and maintain infrastructure, users are responsible for managing applications, data, runtime, middleware, and OS. |

### 2. Platform as a Service (PaaS)

| Aspect         | Details                                                                                       |
|----------------|-----------------------------------------------------------------------------------------------|
| **Definition** | Provides a platform allowing customers to develop, run, and manage applications without dealing with the underlying infrastructure. Includes OS, middleware, and runtime environment. |
| **(+)**       | Simplifies development process, allows for faster deployment, reduces management overhead, scalable, developers can focus on coding without worrying about infrastructure. |
| **(-)**       | Less control over the underlying infrastructure, potential for vendor lock-in, may not be suitable for all types of applications. |

### 3. Software as a Service (SaaS)

| Aspect         | Details                                                                                       |
|----------------|-----------------------------------------------------------------------------------------------|
| **Definition** | Delivers software applications over the internet, on a subscription basis. Applications are hosted and managed by the service provider. |
| **(+)**       | No need for installation or maintenance, accessible from anywhere with an internet connection, scalable, lower upfront costs, provider manages all aspects of the application. |
| **(-)**       | Limited customization, reliance on the provider for security and uptime, potential for data privacy issues, less control over the software environment. |

### Differences Between IaaS, PaaS, and SaaS

| Features         | IaaS                                      | PaaS                                      | SaaS                                      |
|------------------|-------------------------------------------|-------------------------------------------|-------------------------------------------|
| **Management**   | Users manage applications, data, runtime, middleware, OS | Users manage applications and data; provider manages runtime, middleware, OS, infrastructure | Provider manages all aspects of the application |
| **Control**      | High control over infrastructure          | Moderate control over application environment | Low control; focus on using the software  |
| **Scalability**  | High scalability, pay-as-you-go           | High scalability, tailored for development needs | High scalability, pay-per-use or subscription-based |
| **Target Users** | IT administrators, developers needing infrastructure | Developers looking to build and deploy applications | End-users needing functional software    |
| **Examples**     | Amazon EC2, Google Compute Engine, Microsoft Azure VMs | Google App Engine, Microsoft Azure App Services, Heroku | Google Workspace, Microsoft Office 365, Salesforce |

---

### What are the advantages/disadvantages of the cloud? (Particularly for a business)

Advantages include cost savings on hardware and maintenance, scalability to meet demand, and easy access to the latest technologies. Disadvantages can include concerns over data security and privacy, dependency on internet connectivity, and potential long-term costs.

### Difference between OpEx vs CapEx and how it relates the cloud

Operating Expenses (OpEx) are ongoing costs for running a business, like rent and utilities, while Capital Expenditures (CapEx) are one-time costs for purchasing assets, like hardware. Cloud computing shifts IT spending from CapEx to OpEx, as you pay for cloud services as you use them rather than making large upfront investments in infrastructure.

### Is migrating to the cloud always cheaper?

Migrating to the cloud can be cheaper, especially for businesses that need to scale quickly or have variable workloads. However, it depends on the specific needs and usage patterns of the business. There can be hidden costs, such as data transfer fees and the need for ongoing management.

### Marketshare - What is the breakdown? Add a diagram to help understand marketshare trends

As of recent data, the cloud market is dominated by Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). AWS leads with around 32% market share, followed by Azure with 20%, and GCP with 9%. Other providers make up the rest of the market.

### What are the 3 largest Cloud providers known for (What makes them popular? Any USPs?)

AWS is known for its extensive range of services and global infrastructure. Microsoft Azure is popular for its strong integration with Microsoft products and enterprise solutions. Google Cloud Platform is recognized for its data analytics and machine learning capabilities.

### Which cloud provider do you think might be the best? Why?

The best cloud provider depends on specific needs. AWS is great for diverse services and mature infrastructure, Azure is ideal for businesses already using Microsoft products, and GCP excels in data analytics and machine learning.

### What sorts of things do you usually need to pay for when using the cloud?

In the cloud, you typically pay for computing power, storage, data transfer, network usage, and specific services like databases or machine learning tools. Pricing is usually based on usage, which can include per-hour or per-minute billing for compute resources and per-gigabyte fees for storage and data transfer.

### How is data used/managed in the cloud? What do data professionals need to know to leverage cloud technologies effectively?

Data in the cloud is managed through various services that handle storage, databases, analytics, and machine learning. Data professionals need to understand how to use these services, manage data security, and optimize performance and cost. Skills in cloud-specific tools and platforms, as well as knowledge of data governance and compliance, are essential.

### Case Studies

Netflix migrated to AWS to scale its streaming service globally, benefiting from AWS's scalable infrastructure and wide range of services.
Capital One used AWS to enhance security and innovation, leveraging cloud-based machine learning and big data analytics to improve customer experience.
Spotify moved to Google Cloud Platform to boost its data processing capabilities, using GCP's data analytics and machine learning services to improve its recommendation algorithms.

