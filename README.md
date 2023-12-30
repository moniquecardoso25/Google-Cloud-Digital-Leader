# GOOGLE CLOUD DIGITAL LEADER ANNOTATIONS

Summary for the Google Cloud Digital Leader Certification. 

## Table Of Contents
01. [Introduction](#introduction-to-cloud-computing)


## References and Resources
Google Cloud Digital Leader Certification Course - Pass the Exam - FreeCodeCamp

> https://www.youtube.com/watch?v=UGRDM86MBIQ&t=1117s&ab_channel=freeCodeCamp.org

Summary sketches to visualize core services
> https://thecloudgirl.dev/

Google Cloud Skills Boost - Digital Leader Learning Path
> https://www.cloudskillsboost.google/paths/9

Google Cloud Learn
> https://cloud.google.com/learn/

# Introduction to Cloud Computing

## What's Cloud Computing
* "Cloud computing is the on-demand availability of computing resources (such as storage and infrastructure), as services over the internet. It eliminates the need for individuals and businesses to self-manage physical resources themselves, and only pay for what they use."(Google Cloud)

### On-Premise
* Company owns the servers
* Company hires the IT people
* Compny takes all the risk
* Company pays or rent the real-estate

### Cloud Providers
* Providers own the servers
* Providers hire the IT people
* Providers pay or rents the real-estate
* Company is responsible for its configuration cloud services and code, providers take care of the rest

## Evolution Cloud Hosting

### Dedicated Server
* 1 physical machine dedicated to a single a business. It runs a single web-app/site.
* **Very expensive, high security, high maintenance.**

### Virtual Private Server

* 1 physical machine dedicated to a single business. This machine is virtualized into sub-machines, which runs multiple web-app/sites.

### Shared Hosting
* 1 physical machine, shared by other businesses. It relies on most tentans under-utilizing their resoucers. **Very cheap and limited.**

### Cloud Hosting
* Multiple physical machines, which act as one system, it is abstracted in multiple cloud services. **Scalable, Flexible, Cost-Effective, Secure, High Configurability.**

## Benefits of Cloud Comptuting

### Cost-Effective
* You pay for what you consume, no up-front cost. On-demand pricing/Pay-as-you-go(PAYG) which many customers sharing the cost of resources.
### Global
* Launch workload anywhere in the world, choose a region.
### Secure
* Cloud provider takes care of physical security, which can be secure by default or you can configure access down to a granular level.
### Reliable(reability)
* Disaster recovery, data backup, data replication and fault torelance.
### Scalable(scalability)
* Decrease or increase resources and services based on demand.
### Elastic(Elasticity)
* Automate scaling during spikes and drop in demand.

## Common Cloud Services
A cloud provider have hundreds of cloud services which are joined into diverses types of services. GCP has more than 60 cloud services. The word "Cloud Computing" are used to refer to all categories. The four most common types of these services for Iaas(Infrastructure as a Service) are:

### Compute
* Virtual computer that runs applications, programs and Code. Ex: Compute Engine -> VM instances

### Networking
* Virtual network able to define internet connections or network isolations. Ex: Virtual Private Cloud(VPC) -> Connect, provisiton or isolate Google Cloud resources using the Google global network. 

### Storage
* Virtual hard-drive that stores files. Ex: Google Cloud Storage -> Store unstructured data.

### Databases
* Virtual database, store the reporting data or a database for general purpose web-application. Ex: Cloud SQL -> Fully managed PostgreSQL, MySQL, and SQL Server.

## Types of Cloud Computing 

### Iaas (Infrastructre as a Service)
* IaaS offers on-demand access to IT infrastructure services. Providers access compute, storage, networking, and virtualization. It provides the highest level of control over your IT resources and similar to traditional on-premises IT resources. Companies don't need to worry about staff, IT, data centers and hardware.
* Examples: Compute Engine, Cloud Storage. Google Cloud, Azure, AWS.

### Paas (Plarform as a Service) - For developers
* PaaS offers all the hardware and software resources needed for cloud application development. With PaaS, companies don't worry to provision, configure and understand the hardware or OS.
* Examples: Cloud Run, App Engine, BigQuery, Google Kubernetes Engine(GKE)

### Saas (Service as a Service) - For Customers
* SaaS is a full stack of applications as a service, usually an end-user application, where both the infrastructure and the service are managed and maintained by the provided cloud service. Companies don't care about how this service is maintained, it just remains available and works.
* Examples: Gmail, Office 365, Google Workspace.

### FaaS (Function as a Service)
* FaaS provides the platform for developers to run small, single-purpose code(functions) which run in response to particular events. It's used for particular things, like creating a function that runs when data is loaded into Cloud Storage and can be sorted.
* Example: Cloud Functions 

## Shared Responsability Model

Shared Responsability Model is a simple visualization to determine what customers are responsable for and what Google is responsabile for related to GCP.

![image](https://github.com/moniquecardoso25/Google-Cloud-Digital-Leader/assets/140358716/9217695b-3dd4-4a79-ae2c-ef21603816a1)

Source: FreeCodeCamp 

* Customers are responsible for data and configuration of access controls within the GCP platform.
* Google is responsible for the underlying infrastructure.

![image](https://github.com/moniquecardoso25/Google-Cloud-Digital-Leader/assets/140358716/137b7e10-e1ee-4403-aa18-0e4afe9d31bb)

Source: FreeCodeCamp 


![image](https://github.com/moniquecardoso25/Google-Cloud-Digital-Leader/assets/140358716/83e653ba-f4c1-4b07-9180-e6185c626ed8)

Source: FreeCodeCamp 


![image](https://github.com/moniquecardoso25/Google-Cloud-Digital-Leader/assets/140358716/c2465e90-7202-4826-ae60-2b544859f1b9)

Source: FreeCodeCamp 


## Cloud Computing Deployment Models

### Public Cloud
* Everything built on Cloud Provider. Cloud-native.
* Private and Public subnet.

### Private Cloud
* Everything build on company's datacenters. Knwon as On-premise. It could be OpenStack.
* Private and Public subnet.

### Hybrid Cloud
* Use both On-premise and Cloud service provider.
* Private and Public subnet (VPN conection) betwen on-premise datacenter and Google Cloud.


### Cross-Cloud
* Use multiple cloud providers.
* Anthos in GCP offers a control plane for compute across multiple CSPs and On-premise environments.
* Example: Connection - Amazon EKS <-> Azure Arc <-> GCP Kubernetes Engine


![image](https://github.com/moniquecardoso25/Google-Cloud-Digital-Leader/assets/140358716/18c29863-1f8f-4c2d-b291-51dfbb71df67)

Source: FreeCodeCamp 

## Total Cost of Owenership(TCO)

### On-Premise(CAPEX)
* Software licence fees
  
* Implementation
* Configuration
* Training

* Physical Security
* Hardware
* IT Personal
* Maintenance


### GCP(OPEX) 
* Subscription fees
* 75% savings. Physical secutiry until maintenance below are GCPs responsability
Just
* Implementation
* Configuration
* Training


## Capital x Operational Expenditure

## Capital Expenditure(CAPEX)

Spend money upfront on physical infrastructure. 
Capital expenses - guess upfront what a person plan to spend.

CUSTOMER COSTS
* Server(computers)
* Network(routers, switches, cables)
* Storage(hard drives)
* Disaster recovery
* Backup and archieve costs
* Datacenter(rent, physical security, cooling)
* Technical personal

## Operational Expenditure(OPEX)

Customers only have non-physical costs because they are associated with local data centers that have transferred the cost to the service provider.
Operation Expenses - try a service or product without investing in equipment.

CUSTOMER COSTS
* Train employees on Cloud services
* Lease software and customizing features
* Pay for Cloud support
* Bill based on cloud metrics -> Compute and storage usage.


## Cloud Architecture Terminologies

### Availability 

* Ability to ensure a service remains available by ensuring there is no single point of failure and/or ensure a certain level of performance. (Highly Available -HA)

* Cloud Load Balancing - A load balancer allows you to evenly distribute traffic to multiple servers in one or more datacenter. If a datacenter or server becomes unabailable(unhealthy) the load balancer will route the traffic to only available datacenters with servers.

* Running a workload across multiple Zones ensures that if 1 or 2 Zones become unavailable, service/applications remain available.

### Elasticity 
* High Elasticity is ability to automatically increase or decrease capacity based on the current demand of traffic, memory and computing power.

Horizontal Scaling
* Scaling Out - Add more servers of the same size
* Scaling In - Removing more servers of the same size.

Vertical Scaling is normally hard for tradicional achitecture, it`s usually see horiozntal scaling described with Elasticity.


### Fault Tolerance 
* Ability to prevent a failure

### Scalability 
* Ability to grow rapidly or unimpeded

### Disaster Recovery 
* Ability to recover from a failure(Highly Durable - DR)



### Regions and Zones
* Each Region has three or more zones
* Each Zone has one or more discrete clusters


# GCE (Google Compute Engine)
### Image
* **Hardening an Image** means to create an image out of a GCE instance that adheres to the corporate standards of the organization
* You need to stop an instance before creating an image out of it. However there is still an option to take an image while the instance is running but it is not recommended

### Instance Template
* You cannot edit an instance template once you created it. You can only create a copy of it and modify the copy


