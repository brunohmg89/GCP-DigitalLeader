# Digital Leader

Reference: <https://www.examtopics.com/exams/google/>

## Questions

1. Your organization is developing and deploying an application on Google Cloud. Tracking your Google Cloud spending needs to stay as simple as possible. What should you do to ensure that workloads in the development environment are fully isolated from production workloads?

    - [ ] Apply a unique tag to development resources
    - [ ] Associate the development resources with their own network
    - [ ] Associate the development resources with their own billing account
    - [x] Put the development resources in their own project

2. Your company is running the majority of its workloads in a co-located data center. The workloads are running on virtual machines (VMs) on top of a hypervisor and use either Linux or Windows server editions. As part of your company's transformation strategy, you need to modernize workloads as much as possible by adopting cloud-native technologies. You need to migrate the workloads into Google Cloud. What should you do?

    - [ ] Export the VMs into VMDK format, and import them into Compute Engine
    - [ ] Export the VMs into VMDK format, and import them into Google Cloud VMware Engine
    - [ ] Migrate the workloads using Migrate for Compute Engine
    - [x] Migrate the workloads using Migrate for Anthos

    **Explanation:** Migrate to Containers makes it fast and easy to modernize traditional applications away from virtual machines and into native containers. Our unique automated approach extracts the critical application elements from the VM so you can easily insert those elements into containers in Google Kubernetes Engine, Cloud Run, or Anthos clusters without the VM layers (like Guest OS) that become unnecessary with containers.

3. Your organization is running all its workloads in a private cloud on top of a hypervisor. Your organization has decided it wants to move to Google Cloud as quickly as possible. Your organization wants minimal changes to the current environment, while using the maximum amount of managed services Google offers. What should your organization do?

    - [ ] Migrate the workloads to Google Cloud VMware Engine
    - [x] Migrate the workloads to Compute Engine
    - [ ] Migrate the workloads to Bare Metal Solution
    - [ ] Migrate the workloads to Google Kubernetes Engine

    **Explanation:** Migrate for Compute Engine enables you to lift and shift workloads at scale to Google Cloud Compute Engine with minimal changes and risk.

4. Your organization is releasing its first publicly available application in Google Cloud. The application is critical to your business and customers and requires a 2- hour SLA. How should your organization set up support to minimize costs?
    
    - [ ] Enroll in Premium Support
    - [x] Enroll in Enhanced Support
    - [ ] Enroll in Standard Support
    - [ ] Enroll in Basic Support

    **Explanation:** Enhanced Support: Designed to provide fast response times, a robust set of services, and the technical support necessary for workloads in production. Ideal for workloads in production, with 1-hour response time.

5. Your organization offers public mobile apps and websites. You want to migrate to a Google Cloud-based solution for checking and maintaining your users' usernames and passwords and controlling their access to different resources based on their identity. Which should your organization choose?
    
    - [ ] VPN tunnels
    - [x] Identity Platform
    - [ ] Compute Engine firewall rules
    - [ ] Private Google Access

    **Explanation:** An identity platform is a modern solution for managing the identities of users and devices in a centralized fashion.

6. Which Google Cloud service or feature lets you build machine learning models using Standard SQL and data in a data warehouse?

    - [x] BigQuery ML
    - [ ] TensorFlow
    - [ ] AutoML Tables
    - [ ] Cloud Bigtable ML

    **Explanation:** BigQuery ML lets you create and execute machine learning models in BigQuery using standard SQL queries.

7. Your organization runs an application on virtual machines in Google Cloud. This application processes incoming images. This activity takes hours to create a result  for each image. The workload for this application normally stays at a certain baseline level, but at regular intervals it spikes to a much greater workload. Your organization needs to control the cost to run this application. What should your organization do?
    
    - [ ] Purchase committed use discounts for the baseline load
    - [ ] Purchase committed use discounts for the expected spike load
    - [x] Leverage sustained use discounts for your virtual machines
    - [ ] Run the workload on preemptible VM instances

    **Explanation:** The idea of the Sustained Use discount is that the longer you run a VM instance in any given month, the bigger discount you will get from the list price.

8. Your organization is developing a plan for migrating to Google Cloud. What is a best practice when initially configuring your Google Cloud environment?

    - [ ] Create a project via Google Cloud Console per department in your company
    - [x] Define your resource hierarchy with an organization node on top
    - [ ] Create projects based on team members' requests
    - [ ] Make every member of your company the project owner

9. Your organization runs many workloads in different Google Cloud projects, each linked to the same billing account. Each project's workload costs can vary from month to month, but the overall combined cost of all projects is relatively stable. Your organization needs to optimize its cost. What should your organization do?

    - [ ] Purchase a commitment per project for each project's usual minimum
    - [ ] Create a billing account per project, and link each project to a different billing account
    - [x] Turn on committed use discount sharing, and create a commitment for the combined usage
    - [ ] Move all workloads from all different projects into one single consolidated project

    **Explanation:** Compute Engine provides resource-based committed use discounts (CUDs) for your predictable workloads to help you cut costs on resources that you need. You can purchase and renew resource-based committed use contracts or commitments in return for heavily discounted prices for VM usage.

10. How should a multinational organization that is migrating to Google Cloud consider security and privacy regulations to ensure that it is in compliance with global standards?

    - [x] Comply with data security and privacy regulations in each geographical region
    - [ ] Comply with regional standards for data security and privacy, because they supersede all international regulations
    - [ ] Comply with international standards for data security and privacy, because they supersede all regional regulations
    - [ ] Comply with regional data security regulations, because they're more complex than privacy standards

11. Your organization wants to optimize its use of Google Cloud's discounts on virtual machine-based workloads. You plan to use 200 CPUs constantly for the next 3 years, and you forecast that spikes of up to 300 CPUs will occur approximately 30% of the time. What should you choose?

    - [ ] 1-year committed use discount for 200 CPUs
    - [ ] 3-year committed use discount for 300 CPUs
    - [x] 3-year committed use discount for 200 CPUs
    - [ ] Regular pay-as-you-go pricing

12. Your organization needs to minimize how much it pays for data traffic from the Google network to the internet. What should your organization do?

    - [x] Choose the Standard network service tier.
    - [ ] Choose the Premium network service tier.
    - [ ] Deploy Cloud VPN.
    - [ ] Deploy Cloud NAT.

    **Explanation:** There are some limitations when leveraging the Standard tier for its pricing benefits. At a high level, these include compliance needs around traffic traversing the public internet, as well as HTTP(S), SSL Proxy, TCP Proxy load-balancing, or usage of Cloud CDN. You can read about these in more detail here. After reviewing some of the recommendations, you’ll be empowered to review your services with your team and determine whether you can benefit from lower Standard Tier pricing without impacting the performance of your external-facing services.

13. our organization wants to migrate your on-premises environment to Google Cloud. The on-premises environment consists of containers and virtual machine instances. Which Google Cloud products can help to migrate the container images and the virtual machine disks?

    - [ ] Compute Engine and Filestore
    - [x] Artifact Registry and Cloud Storage
    - [ ] Dataflow and BigQuery
    - [ ] Pub/Sub and Cloud Storage

14. Your company security team manages access control to production systems using an LDAP directory group. How is this access control managed in the Google Cloud production project?

    - [ ] Assign the proper role to the Service Account in the project's IAM Policy
    - [ ] Grant each user the roles/iam.serviceAccountUser role on a service account that exists in the Google Group.
    - [x] Assign the proper role to the Google Group in the project's IAM Policy.
    - [ ] Create the project in a folder with the same name as the LDAP directory group.

    **Explanation:** Let’s start at the very beginning. Google Cloud offers several ways to onboard users. Cloud Identity is a centralized hub for Google Cloud and G Suite to define, setup, and manage users and groups—think of Cloud Identity as a provisioning and authentication solution, whereas Cloud IAM is principally an authorization solution. Once they’re onboarded, you’ll be able to assign permissions to these users and groups in Google Cloud IAM to allow them access to resources.

15. Your organization wants to be sure that is expenditures on cloud services are in line with the budget. Which two Google Cloud cost management features help your organization gain greater visibility into its cloud resource costs? (Choose two.)
    
    - [x] Billing dashboards
    - [x] Resource labels
    - [ ] Sustained use discounts
    - [ ] Financial governance policies
    - [ ] Payments profile

    **Explanation:** Resource hierarchy: Structure and organize your resource hierarchy for fine-grained management and cost allocation using organizations, folders, projects, and labels.
    Billing access control: Enforce organizational policies with granular permissions at different levels in the resource hierarchy to control who can spend and who has administrative and cost-viewing permissions.
    Budgets and alerts: Set budgets to closely monitor your costs and alert stakeholders through email or Pub/Sub when exceeding defined budget thresholds.

16. Your organization needs to process large amounts of data from an online application that operates continuously. You do not want to be required to provision infrastructure or create server clusters. What should your organization choose?

    - [ ] Compute Engine with BigQuery
    - [ ] Dataproc
    - [ ] Google Kubernetes Engine with Cloud Bigtable
    - [x] Dataflow

    **Explanation:** Dataflow is a fully-managed service for strongly consistent, parallel data-processing pipelines. It provides an SDK for Java with composable primitives for building data-processing pipelines for batch or continuous processing. This service manages the life cycle of Compute Engine resources of the processing pipeline(s). It also provides a monitoring user interface for understanding pipeline health.

17. Your organization needs to ensure that the Google Cloud resources of each of your departments are segregated from one another. Each department has several environments of its own: development, testing, and production. Which strategy should your organization choose?

    - [ ] Create a project per department, and create a folder per environment in each project.
    - [x] Create a folder per department, and create a project per environment in each folder.
    - [ ] Create a Cloud Identity domain per department, and create a project per environment in each domain.
    - [ ] Create a Cloud Identity domain per environment, and create a project per department in each domain.

18. Your organization is defining the resource hierarchy for its new application in Google Cloud. You need separate development and production environments. The production environment will be deployed in Compute Engine in two regions. Which structure should your organization choose?

    - [ ] Create a single project for all environments. Use labels to segregate resources by environment.
    - [ ] Create a single project for all environments. Use tags to segregate resources by environment.
    - [x] Create one project for the development environment and one project for the production environment.
    - [ ] Create two projects for the development environment and two projects for the production environment (one for each region).

19. Your organization meant to purchase a 3-year Committed Use Discount, but accidentally purchased a 1-year Committed Use Discount instead. What should your organization do?

    - [ ] Contact your financial institution.
    - [ ] Contact Trust and Safety.
    - [x] Contact Cloud Billing Support.
    - [ ] Contact Technical Support.

    **Explanation:** After you create a commitment, you can't cancel it. You must pay the agreed upon monthly amount for the duration of the commitment. Commitments are not affected by future pricing changes to the standard prices for Compute Engine resources. If you accidentally purchased a commitment or made a mistake configuring your commitment, contact Google Cloud Billing Support for help.

20. Your organization needs to allow a production job to have access to a BigQuery dataset. The production job is running on a Compute Engine instance that is part of an instance group. What should be included in the IAM Policy on the BigQuery dataset?

    - [ ] The Compute Engine instance group
    - [ ] The project that owns the Compute Engine instance
    - [x] The Compute Engine service account
    - [ ] The Compute Engine instance

    **Explanation:** When a principal (a user, group, or service account) calls a Google Cloud API, that principal must have the appropriate IAM permissions to use the resource. To give a principal the required permissions, you grant an IAM role to the principal.