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


# Introduction

### Cloud Advantages
* Trade CAPEX for Variable expense. Meaning they don't own infrastructure now, but they rent

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
