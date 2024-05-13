# Digital Leader

## Questions

1. You are migrating workloads to the cloud. The goal of the migration is to serve customers worldwide as quickly as possible According to local regulations, certain data is required to be stored in a specific geographic area, and it can be served worldwide. You need to design the architecture and deployment for your workloads. What should you do?

    - [ ] Select a public cloud provider that is only active in the required geographic area
    - [ ] Select a private cloud provider that globally replicates data storage for fast data access
    - [x] Select a public cloud provider that guarantees data location in the required geographic area
    - [ ] Select a private cloud provider that is only active in the required geographic area

2. Your organization needs a large amount of extra computing power within the next two weeks. After those two weeks, the need for the additional resources will end. Which is the most cost-effective approach?

    - [ ] Use a committed use discount to reserve a very powerful virtual machine
    - [ ] Purch ase one very powerful physical computer
    - [x] Start a very powerful virtual machine without using a committed use discount
    - [ ] Purchase multiple physical computers and scale workload across them

3. Your organization needs to plan its cloud infrastructure expenditures. Which should your organization do?

    - [x] Review cloud resource costs frequently, because costs change often based on use 
    - [ ] Review cloud resource costs annually as part of planning your organization's overall budget
    - [ ] If your organization uses only cloud resources, infrastructure costs are no longer part of your overall budget 
    - [ ] Involve fewer people in cloud resource planning than your organization did for on-premises resource planning

4. The operating systems of some of your organization's virtual machines may have a security vulnerability. How can your organization most effectively identify all virtual machines that do not have the latest security update?

    - [x] View the Security Command Center to identify virtual machines running vulnerable disk images 
    - [ ] View the Compliance Reports Manager to identify and download a recent PCI audit
    - [ ] View the Security Command Center to identify virtual machines started more than 2 weeks ago
    - [ ] View the Compliance Reports Manager to identify and download a recent SOC 1 audit

5. You are currently managing workloads running on Windows Server for which your company owns the licenses. Your workloads are only needed during working hours, which allows you to shut down the instances during the weekend. Your Windows Server licenses are up for renewal in a month, and you want to optimize your license cost. What should you do?

    - [ ] Renew your licenses for an additional period of 3 years. Renew your licenses for an additional period of 3 years. Negotiate a cost reduction with your current hosting provider wherein infrastructure cost is reduced when workloads are not in use
    - [ ] Renew your licenses for an additional period of 2 years. Negotiate a cost reduction by committing to an automatic renewal of the licenses at the end of the 2 year period
    - [x] Migrate the workloads to Compute Engine with a bring-your-own-license (BYOL) model
    - [ ] Migrate the workloads to Compute Engine with a pay-as-you-go (PAYG) model

6. Your organization runs a distributed application in the Compute Engine virtual machines. Your organization needs redundancy, but it also needs extremely fast communication (less than 10 milliseconds) between the parts of the application in different virtual machines. Where should your organization locate this virtual machines?

    - [ ] In a single zone within a single region
    - [ ] In different zones within a single region 
    - [ ] In multiple regions, using one zone per region
    - [x] In multiple regions, using multiple zones per region

7. An organization decides to migrate their on-premises environment to the cloud. They need to determine which resource components still need to be assigned ownership. Which two functions does a public cloud provider own? (Choose two.)

    - [x] Hardware maintenance 
    - [ ] Infrastructure architecture
    - [ ] Infrastructure deployment automation
    - [x] Hardware capacity management 
    - [ ] Fixing application security issues

8. You are a program manager within a Software as a Service (SaaS) company that offers rendering software for animation studios. Your team needs the ability to allow scenes to be scheduled at will and to be interrupted at any time to restart later. Any individual scene rendering takes less than 12 hours to complete, and there is no service-level agreement (SLA) for the completion time for all scenes. Results will be stored in a global Cloud Storage bucket. The compute resources are not bound to any single geographical location. This software needs to run on Google Cloud in a cost-optimized way. What should you do?

    - [x] Deploy the application on Compute Engine using preemptible instances 
    - [ ] Develop the application so it can run in an unmanaged instance group
    - [ ] Create a reservation for the minimum number of Compute Engine instances you will use
    - [ ] Start more instances with fewer virtual centralized processing units (vCPUs) instead of fewer instances with more vCPUs

9. Your manager wants to restrict communication of all virtual machines with internet access; with resources in another network; or with a resource outside Compute Engine. It is expected that different teams will create new folders and projects in the near future. How would you restrict all virtual machines from having an external IP address?

    - [x] Define an organization policy at the root organization node to restrict virtual machine instances from having an external IP address 
    - [ ] Define an organization policy on all existing folders to define a constraint to restrict virtual machine instances from having an external IP address
    - [ ] Define an organization policy on all existing projects to restrict virtual machine instances from having an external IP address
    - [ ] Communicate with the different teams and agree that each time a virtual machine is created, it must be configured without an external IP address

10. Your multinational organization has servers running mission-critical workloads on its premises around the world. You want to be able to manage these workloads consistently and centrally, and you want to stop managing infrastructure. What should your organization do?

    - [x] Migrate the workloads to a public cloud 
    - [ ] Migrate the workloads to a central office building
    - [ ] Migrate the workloads to multiple local co-location facilities
    - [ ] Migrate the workloads to multiple local private clouds

11. Your organization stores highly sensitive data on-premises that cannot be sent over the public internet. The data must be processed both on-premises and in the cloud. What should your organization do?

    - [ ] Configure Identity-Aware Proxy (IAP) in your Google Cloud VPC network
    - [ ] Create a Cloud VPN tunnel between Google Cloud and your data center
    - [x] Order a Partner Interconnect connection with your network provider
    - [ ] Enable Private Google Access in your Google Cloud VPC network

    **Explantion:** After the service provider provisions your connection, you can start passing traffic between your networks by using the service provider's network.

12. Your company's development team is building an application that will be deployed on Cloud Run. You are designing a CI/CD pipeline so that any new version of the application can be deployed in the fewest number of steps possible using the CI/CD pipeline you are designing. You need to select a storage location for the images of the application after the CI part of your pipeline has built them. What should you do?

    - [ ] Create a Compute Engine image containing the application
    - [x] Store the images in Container Registry
    - [ ] Store the images in Cloud Storage
    - [ ] Create a Compute Engine disk containing the application

    **Explantion:** Pushing (uploading) and pulling (downloading) images are two of the most common Container Registry tasks. This document focuses on pushing and pulling images with Docker.

13. Each of the three cloud service models - infrastructure as a service (IaaS), platform as a service (PaaS), and software as a service (SaaS) - offers benefits between flexibility and levels of management by the cloud provider and the customer. Why would SaaS be the right choice of service model? 

    - [ ] You want a balance between flexibility for the customer and the level of management by the cloud provider
    - [x] You want to minimize the level of management by the customer
    - [ ] You want to maximize flexibility for the customer.
    - [ ] You want to be able to shift your emphasis between flexibility and management by the cloud provider as business needs change

    **Explantion:** Benefits of SaaS - The main benefit of SaaS is that it offloads all infrastructure and application management to the SaaS vendor.

14. As your organization increases its release velocity, the VM-based application upgrades take a long time to perform rolling updates due to OS boot times. You need to make the application deployments faster. What should your organization do?

    - [ ] Migrate your VMs to the cloud, and add more resources to them
    - [x] Convert your applications into containers
    - [ ] Increase the resources of your VMs
    - [ ] Automate your upgrade rollouts

15. Your organization uses Active Directory to authenticate users. Users' Google account access must be removed when their Active Directory account is terminated. How should your organization meet this requirement?

    - [ ] Configure two-factor authentication in the Google domain
    - [ ] Remove the Google account from all IAM policies
    - [ ] Configure BeyondCorp and Identity-Aware Proxy in the Google domain
    - [x] Configure single sign-on in the Google domain

16. Your company has recently acquired three growing startups in three different countries. You want to reduce overhead in infrastructure management and keep your costs low without sacrificing security and quality of service to your customers. How should you meet these requirements?

    - [ ] Host all your subsidiaries' services on-premises together with your existing services.
    - [x] Host all your subsidiaries' services together with your existing services on the public cloud. Most Voted
    - [ ] Build a homogenous infrastructure at each subsidiary, and invest in training their engineers.
    - [ ] Build a homogenous infrastructure at each subsidiary, and invest in hiring more engineers.

17. What is the difference between Standard and Coldline storage?

    - [ ] Coldline storage is for data for which a slow transfer rate is acceptable.
    - [ ] Standard and Coldline storage have different durability guarantees.
    - [ ] Standard and Coldline storage use different APIs.
    - [x] Coldline storage is for infrequently accessed data. 

18. What would provide near-unlimited availability of computing resources without requiring your organization to procure and provision new equipment?

    - [x] Public cloud
    - [ ] Containers
    - [ ] Private cloud
    - [ ] Microservices

19. You are a program manager for a team of developers who are building an event-driven application to allow users to follow one another's activities in the app. Each time a user adds himself as a follower of another user, a write occurs in the real-time database. The developers will develop a lightweight piece of code that can respond to database writes and generate a notification to let the appropriate users know that they have gained new followers. The code should integrate with other cloud services such as Pub/Sub, Firebase, and Cloud APIs to streamline the orchestration process. The application requires a platform that automatically manages underlying infrastructure and scales to zero when there is no activity. Which primary compute resource should your developers select, given these requirements?

    - [ ] Google Kubernetes Engine
    - [x] Cloud Functions Most Voted
    - [ ] App Engine flexible environment
    - [ ] Compute Engine

    **Explantion:** Cloud Functions gives developers access to Firebase and Google Cloud events, along with scalable computing power to run code in response to those events. While it's expected that Firebase apps will use Cloud Functions in unique ways to meet their unique requirements

20. Your organization is developing an application that will capture a large amount of data from millions of different sensor devices spread all around the world. Your organization needs a database that is suitable for worldwide, high-speed data storage of a large amount of unstructured data. Which Google Cloud product should your organization choose?

    - [ ] Firestore
    - [ ] Cloud Data Fusion
    - [ ] Cloud SQL
    - [ ] Cloud Bigtable