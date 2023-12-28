# GOOGLE CLOUD DIGITAL LEADER ANNOTATIONS

Summary for the Google Cloud Digital Leader Certification. 

## Table Of Contents
01. [Introduction](#introduction-to-cloud-computing)
02. [Google Compute Engine](#gce-google-compute-engine)
03. [Iaas, Paas, Saas](#iaas-paas-saas)
04. [GCP Compute Services](#gcp-compute-services)
05. [Databases](#databases)
06. [Identity Access Management](#iam)
07. [Resource Organization](#resource-organization-in-gcp)
08. [More on Virtual Machines](#vms-contd)
09. [DevOps](#devops)
10. [Decoupling with pub-sub](#decoupling-w-pub-sub)
11. [Other Services](#other-services)
12. [Architectures in the Cloud](#arcitectures-in-the-cloud)
13. [Cost Management in GCP](#cost-management-in-gcp)
14. [Summary](#final-review)
15. [Practice Test Notes](#notes)

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

### What's Cloud Computing
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

### Evolution Cloud Hosting

#### Dedicated Server
* 1 physical machine dedicated to a single a business. It runs a single web-app/site.
* **Very expensive, high security, high maintenance.**

#### Virtual Private Server

* 1 physical machine dedicated to a single business. This machine is virtualized into sub-machines, which runs multiple web-app/sites.

#### Shared Hosting
* 1 physical machine, shared by other businesses. It relies on most tentans under-utilizing their resoucers. **Very cheap and limited.**

#### Cloud Hosting
* Multiple physical machines, which act as one system, it is abstracted in multiple cloud services. **Scalable, Flexible, Cost-Effective, Secure, High Configurability.**

### Benefits of Cloud Comptuting

#### Cost-Effective
* You pay for what you consume, no up-front cost. On-demand pricing/Pay-as-you-go(PAYG) which many customers sharing the cost of resources.
#### Global
* Launch workload anywhere in the world, choose a region.
#### Secure
* Cloud provider takes care of physical security, which can be secure by default or you can configure access down to a granular level.
#### Reliable(reability)
* Disaster recovery, data backup, data replication and fault torelance.
#### Scalable(scalability)
* Decrease or increase resources and services based on demand.
#### Elastic(Elasticity)
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

  

## Regions and Zones
* Each Region has three or more zones
* Each Zone has one or more discrete clusters

# GCE (Google Compute Engine)
### Image
* **Hardening an Image** means to create an image out of a GCE instance that adheres to the corporate standards of the organization
* You need to stop an instance before creating an image out of it. However there is still an option to take an image while the instance is running but it is not recommended

### Instance Template
* You cannot edit an instance template once you created it. You can only create a copy of it and modify the copy

## Discounts
### Sustained Discounts
![](img/sustainedDiscounts.png)
* They are automatically applied for GCE and GKE

### Committed use discounts
![](img/committedUse.png)

## VMs
