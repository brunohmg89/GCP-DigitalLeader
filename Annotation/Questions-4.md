# Digital Leader

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
