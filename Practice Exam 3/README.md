# Questions and Anwers 

CREDITS
> https://certyiq.com/papers?provider=google&exam=cloud-digital-leader


### 01 - You are migrating workloads to the cloud. The goal of the migration is to serve customers worldwide as quickly as possible According to local regulations, certain data is required to be stored in a specific geographic area, and it can be served worldwide. You need to design the architecture and deployment for your workloads. What should you do?

`Select a public cloud provider that guarantees data location in the required geographic area.`

Explanation:
Select a public cloud provider that guarantees data location in the required geographic area


### 02 - Your organization needs a large amount of extra computing power within the next two weeks. After those two weeks, the need for the additional resources will end. Which is the most cost-effective approach?

`Start a very powerful virtual machine without using a committed use discount.`

Explanation:
C is correct because we don’t know the compute use for 2 weeks and discount is available on 1-3 years not for 2 weeks.
https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts

### 03 - Your organization needs to plan its cloud infrastructure expenditures. Which should your organization do?

`Review cloud resource costs frequently, because costs change often based on use.`

Explanation:
A. Review cloud resource costs frequently, because costs change often based on use.

### 04 - The operating systems of some of your organization's virtual machines may have a security vulnerability. How can your organization most effectively identify all virtual machines that do not have the latest security update?

`View the Security Command Center to identify virtual machines running vulnerable disk images.`

Explanation:
You can filter findings by detector name and finding type using the Security Command Center Vulnerabilities tab in the Google Cloud console


### 05 - You are currently managing workloads running on Windows Server for which your company owns the licenses. Your workloads are only needed during working hours, which allows you to shut down the instances during the weekend. Your Windows Server licenses are up for renewal in a month, and you want to optimize your license cost. What should you do?

 `Migrate the workloads to Compute Engine with a pay-as-you-go (PAYG) model.`

Explanation:
License cost will be reduced / eliminated if you go with "D" option. You don't need BYOL as the license is going to expire soon anyway. If license were for another year or so, then BYOL would have been the choice.

### 06 - Your organization runs a distributed application in the Compute Engine virtual machines. Your organization needs redundancy, but it also needs extremely fast communication (less than 10 milliseconds) between the parts of the application in different virtual machines. Where should your organization locate this virtual machines?

`In different zones within a single region.`

Explanation:
Since it guarantees a latency of ~10 milliseconds is maintained, well also giving the redundancy of multi-zone. If it was D, we could not guarantee 10 milliseconds between the different regions.


### 07 - An organization decides to migrate their on-premises environment to the cloud. They need to determine which resource components still need to be assigned ownership. Which two functions does a public cloud provider own? (Choose two.)

`Hardware maintenance.`
`Hardware capacity management.`

Explanation:
A & D. CSP is generally responsible for the maintenance of all its hardware. Whereas customer is responsible for how the application-side is run in those hardware.

### 08 - You are a program manager within a Software as a Service (SaaS) company that offers rendering software for animation studios. Your team needs the ability to allow scenes to be scheduled at will and to be interrupted at any time to restart later. Any individual scene rendering takes less than 12 hours to complete, and there is no service-level agreement (SLA) for the completion time for all scenes. Results will be stored in a global Cloud Storage bucket. The compute resources are not bound to any single geographical location. This software needs to run on Google Cloud in a cost-optimized way.
What should you do?

`Deploy the application on Compute Engine using preemptible instances.`

Explanation:
Can be interrupted at any time to restart later, software needs to run on Google Cloud in a cost-optimized way

### 09 - Your manager wants to restrict communication of all virtual machines with internet access; with resources in another network; or with a resource outside Compute Engine. It is expected that different teams will create new folders and projects in the near future. How would you restrict all virtual machines from having an external IP address?

`Define an organization policy at the root organization node to restrict virtual machine instances from having an external IP address.`

Explanation:

Reference:
https://cloud.google.com/resource-manager/docs/organization-policy/overview"target="_blank"style="word-break:break-all;">

### 10 - Your multinational organization has servers running mission-critical workloads on its premises around the world. You want to be able to manage these workloads consistently and centrally, and you want to stop managing infrastructure. What should your organization do?

`Migrate the workloads to a public cloud.`

Explanation:
A is correct. Key is manage centrally. Manage these workloads consistently and centrally, and you want to stop managing infrastructure.

### 11 - Your organization stores highly sensitive data on-premises that cannot be sent over the public internet. The data must be processed both on-premises and in the cloud. What should your organization do?

`Enable Private Google Access in your Google Cloud VPC network`

Explanation:
After the service provider provisions your connection, you can start passing traffic between your networks by using the service provider's network.

Reference: 
https://cloud.google.com/network-connectivity/docs/interconnect/concepts/partner-overview

### 12 - Your company's development team is building an application that will be deployed on Cloud Run. You are designing a CI/CD pipeline so that any new version of the application can be deployed in the fewest number of steps possible using the CI/CD pipeline you are designing. You need to select a storage location for the images of the application after the CI part of your pipeline has built them.
What should you do?

`Store the images in Container Registry.`

Explanation:

Reference:
https://cloud.google.com/container-registry/docs/pushing-and-pulling"target="_blank" style="word-break:break-all;">

### 13 - Each of the three cloud service models - infrastructure as a service (IaaS), platform as a service (PaaS), and software as a service (SaaS) - offers benefits between flexibility and levels of management by the cloud provider and the customer.
Why would SaaS be the right choice of service model?

`You want to minimize the level of management by the customer.`

Explanation:
Benefits of SaaS - The main benefit of SaaS is that it offloads all infrastructure and application management to the SaaS vendor

### 14 - As your organization increases its release velocity, the VM-based application upgrades take a long time to perform rolling updates due to OS boot times. You need to make the application deployments faster.
What should your organization do?

`Convert your applications into containers.`

Explanation:
The last sentence is key. "You need to make the application deployments faster." By converting apps into containers, you speed up the deployment by removing the OS boot component in the previous statement. Answer is B

### 15 - Your organization uses Active Directory to authenticate users. Users' Google account access must be removed when their Active Directory account is terminated.

`Configure single sign-on in the Google domain.`

Explanation:
Your organization uses Active Directory to authenticate users. Then you need to use Single sign-on (SSO) is an authentication scheme that allows a user to log in with a single ID and password to different systems and software. SSO allows IT departments to administrator a single identity that can access many machines and cloud services.


### 16 - Your company has recently acquired three growing startups in three different countries. You want to reduce overhead in infrastructure management and keep your costs low without sacrificing security and quality of service to your customers.
How should you meet these requirements?

`Host all your subsidiaries' services together with your existing services on the public cloud.`

Explanation:
Both maintenance cost becomes cheaper and management becomes easier when subsidiaries workloads along with parent organisation's workloads are deployed on the public cloud.

### 17 - What is the difference between Standard and Coldline storage?

`Coldline storage is for infrequently accessed data.`

Explanation:
> https://www.msp360.com/resources/blog/google-cloud-nearline-storage-vs-coldline-vs-standard/"target="_blank"style="word-break:break-all;">

### 18 - What would provide near-unlimited availability of computing resources without requiring your organization to procure and provision new equipment?

`Public cloud.`

> https://cloud.google.com/docs/overview

### 19 - You are a program manager for a team of developers who are building an event-driven application to allow users to follow one another's activities in the app. Each time a user adds himself as a follower of another user, a write occurs in the real-time database. The developers will develop a lightweight piece of code that can respond to database writes and generate a notification to let the appropriate users know that they have gained new followers. The code should integrate with other cloud services such as Pub/Sub, Firebase, and Cloud APIs to streamline the orchestration process. The application requires a platform that automatically manages underlying infrastructure and scales to zero when there is no activity. Which primary compute resource should your developers select, given these requirements?

`Cloud Functions.`

Explanation:
https://firebase.google.com/docs/functions/use-cases"target="_blank"style="word-break: break-all;">

### 20 - Your organization is developing an application that will capture a large amount of data from millions of different sensor devices spread all around the world. Your organization needs a database that is suitable for worldwide, high-speed data storage of a large amount of unstructured data. Which Google Cloud product should your organization choose?

`Cloud Bigtable.`

Explanation:
A fully managed, scalable NoSQL database service for large analytical and operational workloads with up to 99,999% availability.
Consistent sub-10ms latency-hangle millions of requests per second. Ideal for use cases such as personalization, ad tech, fintech, digital media and IoT.
