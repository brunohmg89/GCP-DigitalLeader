# Digital Leader

Reference: <https://www.examtopics.com/exams/google/>

## Questions

1. Which Google Cloud service or feature lets you build machine learning models using Standard SQL and data in a data warehouse?
    
    **Tradução:** _Qual serviço ou recurso do Google Cloud permite criar modelos de machine learning usando SQL padrão e dados em um data warehouse?_

    :white_check_mark: BigQuery ML 
    :black_large_square: TensorFlow 
    :black_large_square: C. AutoML Tables 
    :black_large_square: D. Cloud Bigtable ML 

<br>

    **Explanation:** BigQuery ML lets you create and execute machine learning models in BigQuery using standard SQL queries.

---

2. What are the key features of Google Cloud Identity. 

    - [ ] Multi-factor authentication (MFA) 
    - [ ] Single sign-on (SSO) 
    - [ ] Works with your favorite apps and Endpoint management 
    - [x] All of the Above 
    
    **Explanation:** Cloud Identity: A unified identity, access, app, and endpoint management (IAM/EMM) platform. - Give users easy access to apps with single sign-on. - Multi-factor authentication protects user and company data. - Endpoint management enforces policies for personal and corporate devices KEY FEATURES : Modernize IT and strengthen security Multi-factor authentication (MFA) Help protect your user accounts and company data with a wide variety of MFA verification methods such as push notifications, Google Authenticator, phishing-resistant Titan Security Keys, and using your Android or iOS device as a security key. Endpoint management Improve your company’s device security posture on Android, iOS, and Windows devices using a unified console. Set up devices in minutes and keep your company data more secure with endpoint management. Enforce security policies, wipe company data, deploy apps, view reports, and export details. Single sign-on (SSO) Enable employees to work from virtually anywhere, on any device, with single sign-on to thousands of pre-integrated apps, both in the cloud and on-premises. Works with your favorite apps Cloud Identity integrates with hundreds of cloud applications out of the box—and we’re constantly adding more to the list so you can count on us to be your single identity platform today and in the future.

3. Your organization needs to process large amounts of data from an online application that operates continuously. You do not want to be required to provision infrastructure or create server clusters. What should your organization choose? 

    - [ ] Compute Engine with BigQuery 
    - [ ] Dataproc 
    - [ ] Google Kubernetes Engine with Cloud Bigtable 
    - [x] Dataflow 

    **Explanation:** You do not want to be required to provision infrastructure or create server clusters. Because Unified stream and batch data processing that's serverless, fast, and cost-effective.

4. The Border Security Agency has hired your software services firm to build an application for them that will collect information about visas stamped on passports. You are given stamped images. You have to find out which country issued the visa and the period of validity. Pull out this data and put it into a database. Which of these applications would be suitable for that? 

    - [x] Use Cloud Vision API - write code to identify the text blocks, copy the data, and store it 
    - [ ] Use TensorFlow - write code that will identify the type of visa and the bounding text blocks. Copy the data and then store it. 
    - [ ] Use AutoML - upload other images of visas and run the model creation process which will automatically identify the visas 
    - [ ] Use Data Labeling service - outsource the work of marking and extracting the in-formation to others. 

    **Explanation:** Cloud Vision API allows you to programmatically identify images, text, etc. in the document. This would be the best

5. The customer has applications that do data processing on-premise. They have been built using Ha-doop and Spark. What product should I use on Google Cloud? 

    - [x] Dataproc 
    - [ ] Dataflow 
    - [ ] Dataprep 
    - [ ] Dataplex 

    **Explanation:** Because Dataproc is used to run Hadoop/Spark workloads 

6. Your organization is running all its workloads in a private cloud on top of a hypervisor. Your organization has decided it wants to move to Google Cloud as quickly as possible. Your organization wants minimal changes to the current environment, while using the maximim amount of managed services Google offers. What should your organization do? 

    - [ ] Migrate the workloads to Google Cloud VMware Engine 
    - [x] Migrate the workloads to Compute Engine 
    - [ ] C. Migrate the workloads to Bare Metal Solution 
    - [ ] Migrate the workloads to Google Kubernetes Engine 
    
    **Explanation:** Migrate for Compute Engine enables you to lift and shift workloads at scale to Google Cloud Compute Engine with minimal changes and risk.

7. What characteristics should an organization adopt to be a DevOps organization? 

    - [ ] Teamwork over individual work 
    - [ ] Obsession with Automation over preoccupation with manual work 
    - [ ] Product based teams over component teams. 
    - [x] All of the Above 

8. When you update the function in firebase by deploying updated code, instances for older versions are cleaned up along with build artifacts in __________________ and replaced by new instances.

    - [ ] Google Cloud console. 
    - [x] Storage and Container Registry. 
    - [ ] Container Registry repository. 
    - [ ] None of the Above 

    **Explanation:** Container Registry is a single place for your team to manage Docker images, perform vulnerability analysis, and decide who can access what with fine-grained access control

9. Virtual Machine vCPU and memory usage for each of these categories can receive one of the following discounts? (Select Three Answer) 

    - [ ] Military Discounts 
    - [ ] Spot Instances 
    - [x] Committed-Use    
    - [x] Sustained-Use 
    - [x] Preemptible VMs 
    
    **Explanation:** Sustained, Committed and Preemptible vCPU and memory usage for each of these categories can receive discounts VM vCPU and memory usage for each of these categories can receive discounts Sustained-use discounts—Google offers up to 30% off for workloads that run for most of the billing month on GCP services. Committed-use discounts—users can save up to 57% by committing to use an instance for a certain time period, with no upfront payment and with the flexibility to change instances during the commitment period. Preemptible VMs—similar to the concept of AWS spot instances, Google offers up to 79% off for Virtual Machines that may be shut down at any time and replaced by others.

10. A startup is planning to create their entire suite of applications on Google Cloud. They are looking at various open source technologies to build applications. One of the considera-tion is about having a well integrated monitoring tool. They have to be able to constantly review load capacity and performance of their applications and virtual machines. What would you advise them to do? 

    - [ ] It is best to build a custom solution so that they know it integrates well with all their custom applications. 
    - [ ] Since they are using open source for applications, find another open source monitoring tool and integrate it, which could turn out to be very cheap. 
    - [x] Use the Google Cloud Operations Suite which contains monitoring among other operations tools. 
    - [ ] Update the application code to regularly write to output logs. Export the logs to BigQuery to analyze them frequently. 

    **Explanation:** Explanation Operations Suite is well integrated into Google and it s the recommended option.

11. A Customer has their current SAP systems using Microsoft SQL Server as the Database. They are migrating to Google Cloud and also preparing to later migrate to the latest version of SAP. The entire IT team is being directed to focus on the migration to the new version of SAP. The new version of SAP does not use Microsoft SQL Server as the Database, Any but the most critical IT management tasks are being deprioritized, How should they migrate their current database to Google Cloud? 

    - [ ] Spanner 
    - [ ] Bare Metal 
    - [ ] BigQuery 
    - [x] Cloud SQL 
    
    **Explanation:** Cloud SQL supports SQL Server, Since the IT team's attention is being focused on other activities, they will have less time for existing admin tasks, It would be best to take a managed/hosted version.

12. You are consulting for a client who is migrating to Google Cloud. They presently have a matrix or-ganization. Their IT environments were managed around projects. Each team had multiple projects. All the projects had a flat structure under the company. What would you advise them when plan-ning for the move?

    - [x] On Google Cloud, create a folder corresponding to each team. Under that, there could be projects or further sub folders as the team decides. 
    - [ ] In terms of not disturbing the project developers and testers, advise them that the strategic decision is to retain the structure on Google Cloud also. 
    - [ ] Since a Project could spawn other sub-Projects, on Google Cloud it is better to as-sign a folder for each Project.
    - [ ] The flat structure is what is currently used in IT organizations, and this can be used as-is which will provide the best results. 
    
    **Explanation:** Folders for a related group of projects are the recommended approach. -> A flat structure under the organization node is possible on Google Cloud, but it is not recommended. It becomes tougher to manage. -> Projects cannot have sub-projects; there can only be resources within Projects.

13. Your company has signed up with a cloud provider and you will be using storage and virtual machines with the provider. The provider has provided your organization some expectations for what the service should perform at. What type of agreement provides a guarantee of a certain level of service such as “Uptime”? 

    - [ ] Performance Agreement 
    - [ ] Interconnection Agreement 
    - [ ] Warranty 
    - [x] Service Level Agreement 
    
    **Explanation:** Service Level Agreement (SLA) A service level agreement (SLA) is a contract between a service provider (either internal or external) and the end user that defines the level of service expected from the service provider. Some common SLA’s are uptime, Response Time, etc.

14. Which of the following statements is / are correct about Machine Learning? 

    - [x] Machine learning examples include chatbots and automated virtual assistants to automate routine customer service tasks and speed up issue resolution. 
    - [ ] Machine learning automates the job of building statistical models with Human In-tervention. 
    - [ ] Robotic process automation (RPA) can not be attached with ML. 
    - [ ] None of the Above. 
    
    **Explanation:** Customer service Machine learning examples include chatbots and automated virtual assistants to automate routine customer service tasks and speed up issue resolution. 

15. Your application is onboarding a number of users. The details of the users very widely. What kind of database would be most suitable for this use case? 

    - [x] NoSQL database like Firestore 
    - [ ] OLAP database like BigQuery which support SQL 
    - [ ] SQL database like MySQL or PostgreSQL 
    - [ ] OLTP database like Cloud Spanner 

    **Explanation:** Explanation 1.NoSQL databases are best suited for this use case. Firestore is an appropriate one to use here 2.Cloud Firestore is a NoSQL document database that lets you easily store, sync, and query data for your mobile and web apps - at global scale. 

16. Your organization needs to plan its cloud infrastructure expenditures. Which should your organization do? 

    - [x] Review cloud resource costs frequently, because costs change often based on use 
    - [ ] Review cloud resource costs annually as part of planning your organization’s overall budget 
    - [ ] If your organization uses only cloud resources, infrastructure costs are no longer part of your overall budget 
    - [ ] Involve fewer people in cloud resource planning than your organization did for onpremises resource planning 

    **Explanation:** Review cloud resource costs frequently, because costs change often based on use because One need to know current usage/ trend for planning; While public cloud eliminates capex, and gets into pay as you go model, the usage pattern determines the cloud cost and hence needs to be measured frequently to enable better forecast

17. In terms of Cloud SQL for MySQL Features offered by Google Cloud Platform which of the statements is/are correct? 

    - [ ] Do not support Private IP (private service access). 
    - [x] Customer data is encrypted on Google's internal networks and in database tables, temporary files, and backups. 
    - [ ] Do not Provide automated and on-demand backups and point-in-time recovery. 
    - [ ] None of the above 

    **Explanation:** Cloud SQL for MySQL: Features - Fully managed MySQL Community Edition databases in the cloud. - Cloud SQL instances support MySQL 8.0, 5.7 (default), and 5.6, and provide up to 624 GB of RAM and 64 TB of data storage, with the option to automatically increase the storage size, as needed. - Create and manage instances in the Google Cloud Console. - Instances are available in the Americas, EU, Asia, and Australia. - Customer data is encrypted on Google's internal networks and in database tables, temporary files, and backups. - Support for secure external connections with the Cloud SQL Auth proxy or with the SSL/TLS protocol. - Support for private IP (private services access). - Data replication between multiple zones with automatic failover. - Import and export databases using mysqldump, or import and export CSV files. - Support for MySQL wire protocol and standard MySQL connectors. - Automated and on-demand backups and point-in-time recovery. - Instance cloning. - Integration with Google Cloud's operations suite logging and monitoring. 

18. A prospect wants to be able to store and analyze data. Their analysts already know SQL, but are not familiar with other technologies. Which of these databases can the analysts use without addi-tional training? 

    - [ ] Cloud SQL, BigQuery, Datastore 
    - [x] Spanner, Cloud SQL, BigQuery 
    - [ ] Cloud SQL, Firestore, Datastore
    - [ ] Cloud SQL, Bigtable, BigQuery 

    **Explanation:** Spanner, Cloud SQL, BigQuery Spanner- Cloud Spanner is a fully managed, mission-critical, relational database service that offers transactional consistency at global scale, automatic, synchronous replication for high availability, and support for two SQL Google Standard SQL and PostgreSQL. Cloud SQL- Cloud SQL is a fully-managed database service that helps you set up, maintain, manage, and administer your relational databases on Google Cloud Platform. BigQuery- Google BigQuery is a cloud-based Architecture and provides exceptional performance as it can auto-scale up and down based on the data load and performs data analysis efficiently. On the other hand, SQL Server is based on client-server architecture and has fixed performance throughout unless the user scales it manually. 

19. Customer Managed Encryption Keys (CMEK) can be used for encrypting data inside Cloud BigTable, which of the following statements is/are correct. (Select two answer) 

    - [ ] Administrators can not rotate
    - [x] Not supported for instances that have clustered in more than one region. 
    - [x] CMEK can only be configured at the cluster level. 
    - [ ] You can not use the same CMEK key in multiple projects 
    
    **Explanation:** Customer-managed encryption keys for Cloud BigTable. By default, all the data at rest in Cloud Bigtable is encrypted using Google's default encryption. Bigtable handles and manages this encryption for you without any additional action on your part. If you have specific compliance or regulatory requirements related to the keys that protect your data, you can use customer-managed encryption keys (CMEK) for BigTable. Instead of Google managing the encryption keys that protect your data, your BigTable instance is protected using a key that you control and manage in Cloud Key Management Service (Cloud KMS). Features Security: CMEK provides the same level of security as Google's default encryption but provides more administrative control. Data access control: Administrators can rotate, manage access to, and disable or destroy the key used to protect data at rest in BigTable . Auditability: All actions on your CMEK keys are logged and viewable in Cloud Logging. Comparable performance: BigTable CMEK-protected instances offer comparable performance to BigTable instances that use Google default encryption. Flexibility: You can use the same CMEK key in multiple projects or instances or you can use separate keys, depending on your business needs. 

20. A customer deploys an application to App Engine and needs to check for Open Web Application Security Project (OWASP) vulnerabilities. Which service should be used to accomplish this?

    - [ ] Cloud Armor 
    - [x] Cloud Security Scanner 
    - [ ] Binary Authorization 
    - [ ] Forseti Security 
    
    **Explanation:** Web Security Scanner identifies security vulnerabilities in your App Engine, Google Kubernetes Engine (GKE), and Compute Engine web applications. It crawls your application, following all links within the scope of your starting URLs, and attempts to exercise as many user inputs and event handlers as possible. Currently, Web Security Scanner only supports public URLs and IPs that aren’t behind a firewall. Web Security Scanner currently supports the App Engine standard environment and App Engine flexible environments, Compute Engine instances, and GKE resources.