# Digital Leader

Reference (1): <https://www.whizlabs.com/blog/google-cloud-certified-digital-leader-exam-free-questions/>

## Questions

1. You are working with a Financial giant looking to adopt a public Cloud. The IT advisory group of the company has indicated the intent that they want cloud infrastructure to be solely operated for them and hosted internally. Which of the below options is the right choice for the organisation?

    - [ ] Public Cloud
        - Option A is incorrect because the Public Cloud deployment model generally offers services to multiple customers unless opted explicitly for. Public Cloud is also not a correct choice because Public Cloud will not be hosted internally.
    - [x] Private Cloud
        - Option B is correct because the Private Cloud deployment model caters to the below requirements:
            - Solely operated for one customer
            - Hosted internally for the customer
    - [ ] Hybrid Cloud
        - Option C is incorrect as this option comprises the combination of both the Private and Public Cloud.
    - [ ] Any of the above
        - Option D is incorrect as Public Cloud and Hybrid one are not a suitable choice.

2. You are a Senior Project Manager working on a Request for Proposal (RFP). Architects have completed the high-level architecture of the proposed solution. In addition, this proposed solution includes a section that details how the implementation will ensure that the client application and data will be available in case of unavailability of a particular data center. How will you put this section in your RFP?

    - [x] Highlight this as a “Business Continuity Plan.”
        - Option A is correct. As this part of the solution details how the application and data will be available in case of unavailability of a particular data center, we will need to highlight this as a Business Continuity Plan.
    - [ ] Highlight this as “Proactive Monitoring.”
        - Option B is incorrect. Proactive monitoring is the continuous monitoring of various alerts and monitoring application behavior to identify any potential problem. In the given scenario, the solution discusses ensuring business continuity in case of a particular data center unavailability.
    - [ ] Highlight this as a “Continuous Improvement Plan.”
        - Option C is incorrect. The Continuous Improvement Plan details efforts to improve ongoing services that are being provided.
    - [ ] Highlight this as an “Automation” section.
        - Option D is incorrect. Automation plan details the plans of automation to be implemented and not on Business continuity.

3. Which of the below is a Google Cloud PaaS product offering?

    - [ ] Google Workspace
        - Option A is incorrect. Google Workspace is a SaaS offering.
    - [x] Google App Engine
        - Option B is correct. Google App Engine is a PaaS offering.
    - [ ] Google Compute Engine
        - Option C is incorrect. Google Compute Engine is an IaaS offering.
    - [ ] Persistent Disk
        - Option D is incorrect. Persistent Disk is an IaaS offering.

4. Which Cloud Computing models require customers to own Operating System patching?

    - [x] IaaS (Infrastructure as a Service)
        - Option A is correct. The IaaS model requires customers to own the patching of the servers.
    - [ ] PaaS (Platform as a Service)
        - Option B is incorrect. Cloud provider is responsible for patching the Operating System for their PaaS offerings.
    - [ ] SaaS (Software as a Service)
        - Option C is incorrect. Cloud provider is responsible for patching the Operating System for their SaaS offerings.
    - [ ] FSaaS (FileSystem as a Service)
        - Option D is incorrect. FSaaS is not a valid Cloud Computing model.

5. A startup working on self-driving vehicles applications requires to collect data from vehicles on-road. Which offering from Cloud providers will help the organization transmit the data from vehicles currently on-road for data collection?

    - [ ] Machine Learning product offering
        - Option A is incorrect. Machine learning product offerings from Cloud providers enable organizations to build, deploy and scale the AI models.
    - [x] IoT product offering
        - Option B is correct. IoT offerings from Cloud providers help in data collection from the field, like collecting data from sensors including self-driving vehicles, farmlands, satellites etc.
    - [ ] Data Analytics product offering
        - Option C is incorrect. Data Analytics offerings from Cloud providers help unlock big data potential by improving data analysis capabilities and eventually improving businesses’ decision-making.
    - [ ] Storage product offering
        - Option D is incorrect. Storage product offerings from Cloud providers help facilitate storing of the data of various data types.

6. Which of the Google cloud offerings for Virtual Machine offers block storage that is reliable and high performance ?

    - [ ] Preemptible VMs
        - Option A is Incorrect. Preemptible VMs are compute instances that are short-lived and are appropriate to be used for batch jobs.
    - [ ] Cloud storage for Firebase
        - Option B is Incorrect. Cloud storage for Firebase stores and serves content that is user generated on block storage.
    - [ ] Local SSD
        - Option C is Incorrect. Local SSD also offers high performance block storage but is attached locally.
    - [x] Persistent Disk
        - Option D is Correct. Persistent disk from Google Cloud offers block storage that is reliable and high performance for Virtual Machines.

7. Which of the below could be implemented for fine-grained management and cost allocation using organizations in Google cloud? 

    - [ ] Billing access control 
        - Option A is Incorrect. Billing access control helps to enforce organizational policies at various levels in the resource hierarchy.
    - [ ] Quotas
        - Option B is Incorrect. Quotas help to control the spending and unforeseen usage spikes proactively.
    - [x] Resource hierarchy
        - Option C is Correct. Resource hierarchy should be implemented for fine-grained management and cost allocation using organizations in Google cloud.
    - [ ] Budgets
        - Option D is Incorrect. Budgets are most useful in performing the monitoring of the costs being incurred on google cloud.

8. A crowdsourcing platform is looking forward to hosting its applications and services on Google Cloud. Before onboarding the applications and services on Google Cloud, they have expressed an intention to estimate the total cost that they will incur for running their workload on Google Cloud. What would you suggest to them for getting this estimation immediately?

    - [ ] Browse Pricing list for Individual service
        - Option A is incorrect. This option requires manual effort. Hence, this is not a good choice provided that Google provides a “Pricing Calculator”.
    - [x] Use Pricing Calculator
        - Option B is correct. This is the best way to get the estimation. Google pricing calculator is free of cost and can be accessed by anyone.
    - [ ] Contact Google Support
        - Option C is incorrect. Yes, this is an option provided by Google. However, a pricing calculator will be a good choice as it will give the estimate immediately. Hence, it is a better option to choose.
    - [ ] Contact Your Google Account Manager
        - Option D is incorrect. Google Account Manager contact is available only with certain Google Support plans. Since the scenario does not mention if the customer has a Google Support plan, this option is not correct.

9. You are working on designing a solution that requires you to build an application that has disaster recovery capability and can withstand the loss of an entire region. Identify the strategy that is not suitable for implementing this solution.

    - [ ] Use multiregional storage services.
        - Option A is incorrect. Since you are using multiregional storage services, the application can withstand the loss of an entire r egion.
    - [ ] Use a zonal resource, but snapshot data to a multiregional resource.
        - Option B is incorrect. Since you are taking a snapshot of data to a multiregional resource, the application can withstand the loss of an entire region.
    - [ ] Use a zonal resource but manage own data replication to other regions as required.
        - Option C is incorrect. Although zonal resources are being used, data replication is being done to other regions. The application can withstand the loss of an entire region.
    - [x] Use a managed zonal resource.
        - Option D is correct. Using “zonal resources only” will not be ideal as the application, in this case, will not be able to sustain regional failure.

10. Which of the below defines a Region appropriately?

    - [ ] Collection of Data Centers is Region.
        - Option A is incorrect. Regions consist of Zones, and Zones consist of Data Centers.
    - [ ] There is One Zone per Region.
        - Option B is incorrect. A Region can have multiple Zones.
    - [x] Collection of Zones is Region.
        - Option C is correct. This statement correctly defines a Region.
    - [ ] There is One Data Center per Region.
        - Option D is incorrect. A Region comprises one or more Zones. Regions consist of Zones, and Zones consist of Data Centers.    
    
11. Which of the below statements about Google Cloud resources is CORRECT?

    - [ ] Static external IP addresses are Zone specific resources.
        - Option A is incorrect. Static external IP addresses are Regional, not Zone-specific.
    - [ ] Disk snapshots are Region-specific resources.
        - Option B is incorrect. Disk snapshots are Global, not Region-specific.
    - [x] Any Google Cloud resource that is being used, must necessarily belong to a project.
        - Option C is correct. This is a correct statement. All the Google Cloud resources that are being used must necessarily belong to a project.
    - [ ] VM instances are Global.
        - Option D is incorrect. VM instances are Zonal, not Global resources.

12. A new team member has joined your project. You need to grant him permission to access a few Google Cloud resources through IAM. How can you grant permission to your new team member so that he can access the required Google Cloud resources?

    - [ ] Directly grant the permissions to access the resources as required.
        - Option A is incorrect. In IAM, permissions are not granted directly to the team member to access resources.
    - [x] Grant role to the team member to access the resources as required.
        - Option B is correct. The permissions are grouped into roles, and roles can be granted to the team member to access the resources.
    - [ ] Grant IAM policy to the team member to access the resources as required.
        - Option C is incorrect. This is an incorrect statement. IAM policy is attached to resources, defines and enforces what roles are granted to which members and the policy.
    - [ ] Give pre-authenticated URLs so that the new team member can access the required resources.
        - Option D is incorrect. Pre-authenticated URLs are not a valid option to provide access to the resources.

13. How many parent(s) can one resource have?

    - [x] 1
        - Option A is correct. Each resource has exactly one parent.
    - [ ] 2
    - [ ] 3
    - [ ] Depends on the resource type
        - Option D is incorrect. Each resource has exactly one parent and does not depend on the resource type.

14. our organization has opted for an Enhanced support offering. You have created a support case. The current status of the support case is “In progress Google engineering”. What does support case status of “In progress Google engineering” mean?

    - [ ] The case is assigned to one of Google’s cloud engineers.
        - Option A is incorrect. When the case is assigned to one of Google cloud engineers, the status of the support case is “Assigned”.
    - [ ] The support case is being worked upon by Google Cloud Customer care engineers.
        - Option B is incorrect. When the support case is being worked upon by Google Cloud Customer care engineers, the status of the support case is “In progress Cloud Customer Care”.
    - [x] The support case is being investigated by Google product engineers.
        - Option C is correct. When the support case is being investigated by Google product engineers, the status of the support case is “In progress Google engineering”.
    - [ ] The support case is being investigated by another Google engineer team.
        - Option D is incorrect. When the support case is being investigated by another Google engineer team, the status of the support case is “In progress Google other.”

15. While creating a Support Case and describing the issue, which of the below problem types would you select for ‘momentary problems’?

    - [ ] Intermittent
        - Option A is incorrect. Intermittent problems occur randomly without a regular failure pattern.
    - [x] Transient
        - Option B is correct. For momentary problems, the appropriate problem type is Transient.
    - [ ] Consistent
        - Option C is incorrect. Consistent problems are problems that fail completely.
    - [ ] Recurring
        - Option D is incorrect. Recurring is an invalid problem type.

16. You are implementing security for and plan to store API keys and certificates used across your Google cloud. Which of the below will you plan to use?

    - [x] Secret Manager
        - Option A is Correct. A secret manager can be used to store API keys, passwords, and certificates.
    - [ ] Cloud Key Management
        - Option B is Incorrect. Cloud Key Management helps manage encryption keys and cannot be used for storing API keys and certificates.
    - [ ] Security command center
        - Option C is Incorrect. The security command center cannot be used for storing API keys and certificates, but it is appropriate to be used to defend Google cloud assets against threats.
    - [ ] A & B

17. Your client, a newly set up startup company, wants to opt for the cheapest customer care support plan that provides phone support for billing issues. Which support plan would you suggest to your client ensuring that the proposed plan is the most cost-efficient?

    - [x] Basic Support
        - Option A is correct. Basic support from Google Cloud provides phone support for billing issues only along with case and chat support. Basic support is included with Google Cloud subscription, and there are no additional charges. Hence, this is the correct choice.
    - [ ] Standard Support
        - Option B is incorrect. Although Standard support provides phone support for billing issues, it’s an incorrect choice since it is a paid plan. The scenario wants us to identify the most cost-efficient support plan.
    - [ ] Enhanced Support
        - Option C is incorrect. Although Enhanced support provides phone support for billing issues, it’s an incorrect choice since it is a paid plan. The scenario wants us to identify the most cost-efficient support plan.
    - [ ] Premium Support
        - Option D is incorrect. Although Premium support provides phone support for billing issues, it’s an incorrect choice since it is a paid plan. The scenario wants us to identify the most cost-efficient support plan.

18. Which of the below disk types is not backed by Solid State Drives (SSD)?

    - [x] Standard persistent disks (pd-standard)
        - Option A is correct. Standard persistent disks (pd-standard) are backed by HDD (standard Hard Disk Drive). Hence, this option is Correct.
    - [ ] Balanced persistent disks (pd-balanced)
        - Option B is incorrect. Balanced persistent disks (pd-balanced) are backed by solid-state drives (SSD).
    - [ ] SSD persistent disks (pd-ssd)
        - Option C is incorrect. SSD persistent disks (pd-ssd) are backed by solid-state drives (SSD).
    - [ ] Extreme persistent disks (pd-extreme)
        - Option D is incorrect. Extreme persistent disks (pd-extreme) are backed by solid-state drives (SSD).

19. As part of your workload, a VM instance runs a SQL server, and another VM is being used as a license manager. Given the criticality of SQL Server and license manager, you need to ensure that these instances run indefinitely and do not get deleted. How can these VMs be protected from deletion?

    - [x] Enable “delete protection” feature.
        - Option A is correct. To protect the VMs from being deleted, the “delete protection” feature needs to be enabled.
    - [ ] Enable “no delete” feature.
    - [ ] Enable “restrict delete” feature.
    - [ ] Enable “run continuous” feature.
        - Option B, C and D is incorrect. The “no delete” feature is an invalid option.

20. Which of the resources listed below is an ideal choice for a Persistent Disk snapshot? (Choose 2)

    - [x] Single disk backup
    - [x] Differential backup 
        - Option A is correct. Please refer to the picture below for details.
    - [ ] Multiple disk backup
    - [ ] VM Instance configuration
    - [ ] Instance cloning and replication