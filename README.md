# GOOGLE CLOUD DIGITAL LEADER ANNOTATIONS

Summary for the Google Cloud Digital Leader Certification. 

## Table Of Contents
01. [Introduction](#introduction)
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

# Introduction

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
* Very expensive, high security, high maintenance.

#### Virtual Private Server

* 1 physical machine dedicated to a single business. This machine is virtualized into sub-machines, which runs multiple web-app/sites.

#### Shared Hosting
* 1 physical machine, shared by other businesses. It relies on most tentans under-utilizing their resoucers. Very cheap and limited.
  
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
