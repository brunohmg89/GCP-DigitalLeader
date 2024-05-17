# Digital Leader

## Questions

1. Your organization needs to build streaming data pipelines. You don't want to manage the individual servers that do the data processing in the pipelines. Instead, you want a managed service that will automatically scale with the amount of data to be processed. Which Google Cloud product or feature should your organization choose?

    - [ ] Pub/Sub
    - [x] Dataflow
    - [ ] Data Catalog
    - [ ] Dataprep by Trifacta

    **Explanation:** Dataflow is a fully-managed service for strongly consistent, parallel data-processing pipelines. It provides an SDK for Java with composable primitives for building data-processing pipelines for batch or continuous processing. This service manages the life cycle of Compute Engine resources of the processing pipeline(s). It also provides a monitoring user interface for understanding pipeline health.

2. Your organization is building an application running in Google Cloud. Currently, software builds, tests, and regular deployments are done manually, but you want to reduce work for the team. Your organization wants to use Google Cloud managed solutions to automate your build, testing, and deployment process. Which Google Cloud product or feature should your organization use?

    - [ ] Cloud Scheduler
    - [ ] Cloud Code
    - [x] Cloud Build
    - [ ] Cloud Deployment Manager

    **Explanation:** Deploy your application to App Engine using the gcloud app deploy command. This command automatically builds a container image by using the Cloud Build service and then deploys that image to the App Engine flexible environment.

3. Which Google Cloud product can report on and maintain compliance on your entire Google Cloud organization to cover multiple projects?

    - [ ] Cloud Logging
    - [x] Identity and Access Management
    - [ ] Google Cloud Armor
    - [ ] Security Command Center

    **Explanation:** IAM provides administrators the ability to manage cloud resources centrally by controlling who can take what action on specific resources.

4. Your organization needs to establish private network connectivity between its on-premises network and its workloads running in Google Cloud. You need to be able to set up the connection as soon as possible. Which Google Cloud product or feature should you use?

    - [ ] Cloud Interconnect
    - [ ] Direct Peering
    - [x] Cloud VPN
    - [ ] Cloud CDN

    **Explanation:** Cloud VPN allows you to connect to your Virtual Private Cloud (VPC) network from your existing network, such as your on-premises network, another VPC network, or another cloud provider's network, through an IPsec connection using (i) Classic VPN, which supports dynamic (BGP) routing or static routing (route-based or policy-based), or (ii) HA (high-availability) VPN, which supports dynamic routing with a simplified redundancy setup, separate failure domains for the gateway interfaces, and a higher service level objective.

5. Your organization is developing a mobile app and wants to select a fully featured cloud-based compute platform for it. Which Google Cloud product or feature should your organization use?

    - [ ] Google Kubernetes Engine
    - [x] Firebase
    - [ ] Cloud Functions
    - [ ] App Engine

    **Explanation:** Firebase is an app development platform that helps you build and grow apps and games users love. Backed by Google and trusted by millions of businesses around the world.

6. Your company has been using a shared facility for data storage and will be migrating to Google Cloud. One of the internal applications uses Linux custom images that need to be migrated. Which Google Cloud product should you use to maintain the custom images?

    - [ ] App Engine flexible environment
    - [x] Compute Engine
    - [ ] App Engine standard environment
    - [ ] Google Kubernetes Engine

    **Explanation:** Compute Engine offers scalable and flexible virtual machine computing capabilities in the cloud, with options to utilize certain CPUs, GPUs, or Cloud TPUs. You can use Compute Engine to solve large-scale processing and analytic problems on Google's computing, storage, and networking infrastructure.

7. Your organization wants to migrate its data management solutions to Google Cloud because it needs to dynamically scale up or down and to run transactional SQL queries against historical data at scale. Which Google Cloud product or service should your organization use?

    - [ ] BigQuery
    - [ ] Cloud Bigtable
    - [ ] Pub/Sub
    - [x] Cloud Spanner

    **Explanation:** Cloud Spanner is a fully-managed, mission-critical relational database service. It is designed to provide a scalable online transaction processing (OLTP) database with high availability and strong consistency at global scale.

8. Your organization needs to categorize objects in a large group of static images using machine learning. Which Google Cloud product or service should your organization use?

    - [ ] BigQuery ML
    - [ ] AutoML Video Intelligence
    - [x] Cloud Vision API
    - [ ] AutoML Tables

    **Explanation:** Cloud Vision classifies images into categories, detects individual objects and faces, and finds and reads printed words.

9. Your organization runs all its workloads on Compute Engine virtual machine instances. Your organization has a security requirement: the virtual machines are not allowed to access the public internet. The workloads running on those virtual machines need to access BigQuery and Cloud Storage, using their publicly accessible interfaces, without violating the security requirement. Which Google Cloud product or feature should your organization use?

    - [ ] Identity-Aware Proxy
    - [x] Cloud NAT (network address translation)
    - [ ] VPC internal load balancers
    - [ ] Private Google Access

    **Explanation:** Cloud NAT (Network Address Translation): Cloud NAT enables instances in a private network to communicate with the internet.

10. Which Google Cloud product is designed to reduce the risks of handling personally identifiable information (PII)?

    - [ ] Cloud Storage
    - [ ] Google Cloud Armor
    - [x] Cloud Data Loss Prevention
    - [ ] Secret Manager

    **Explanation:** Sensitive Data Protection (including Cloud Data Loss Prevention or DLP): Sensitive Data Protection is a fully-managed service enabling customers to discover, classify, de-identify, and protect sensitive data, such as personally identifiable information.

11. Your organization is migrating to Google Cloud. As part of that effort, it needs to move terabytes of data from on-premises file servers to Cloud Storage. Your organization wants the migration process to be automated and to be managed by Google. Your organization has an existing Dedicated Interconnect connection that it wants to use. Which Google Cloud product or feature should your organization use?

    - [x] Storage Transfer Service
    - [ ] Migrate for Anthos
    - [ ] BigQuery Data Transfer Service
    - [ ] Transfer Appliance

    **Explanation:** Storage Transfer Service: Storage Transfer Service enables you to import large amounts of online data into Cloud Storage, quickly and cost-effectively. With Storage Transfer Service, you can transfer data from locations reachable by the general internet (e.g., HTTP/HTTPS), including Amazon Simple Storage Service (Amazon S3), as well as transfer data between Google Cloud products (e.g., between two Cloud Storage buckets). You can also use Storage Transfer Service to move data between private data center storage (e.g., NFS) and Google Cloud products (e.g., transfer from NFS to Cloud Storage).

12. Your organization needs to analyze data in order to gather insights into its daily operations. You only want to pay for the data you store and the queries you perform. Which Google Cloud product should your organization choose for its data analytics warehouse?

    - [ ] Cloud SQL
    - [ ] Dataproc
    - [ ] Cloud Spanner
    - [x] BigQuery

    **Explanation:** BigQuery is a fully-managed data analysis service that enables businesses to analyze Big Data. It features highly scalable data storage that accommodates up to hundreds of terabytes, the ability to perform ad hoc queries on multi-terabyte datasets, and the ability to share data insights via the web.

13. Your organization wants to run a container-based application on Google Cloud. This application is expected to increase in complexity. You have a security need for fine-grained control of traffic between the containers. You also have an operational need to exercise fine-grained control over the application's scaling policies. What Google Cloud product or feature should your organization use?

    - [x] Google Kubernetes Engine cluster
    - [ ] App Engine
    - [ ] Cloud Run
    - [ ] Compute Engine virtual machines

    **Explanation:** Google Kubernetes Engine, powered by the open source container scheduler Kubernetes, enables you to run containers on Google Cloud Platform. Kubernetes Engine takes care of provisioning and maintaining the underlying virtual machine cluster, scaling your application, and operational logistics such as logging, monitoring, and cluster health management.

14. Which Google Cloud product or feature makes specific recommendations based on security risks and compliance violations?

    - [ ] Google Cloud firewalls
    - [x] Security Command Center
    - [ ] Cloud Deployment Manager
    - [ ] Google Cloud Armor

    **Explanation:** Security Command Center is Google Cloud's centralized vulnerability and threat reporting service. Security Command Center provides asset inventory and discovery and allows you to identify misconfigurations, vulnerabilities and threats, helping you to mitigate and remediate risks.

15. Which Google Cloud product provides a consistent platform for multi-cloud application deployments and extends other Google Cloud services to your organization's environment?

    - [ ] Google Kubernetes Engine
    - [ ] Virtual Public Cloud
    - [ ] Compute Engine
    - [x] Anthos

    **Explanation:** The core technology developed by Google empowering enterprise container platforms everywhere. Get access to Anthos capabilities through Google Kubernetes Engine (GKE) and Google Distributed Cloud (GDC).

16. Your organization is developing an application that will manage payments and online bank accounts located around the world. The most critical requirement for your database is that each transaction is handled consistently. Your organization anticipates almost unlimited growth in the amount of data stored. Which Google Cloud product should your organization choose?

    - [ ] Cloud SQL
    - [ ] Cloud Storage
    - [x] Firestore
    - [ ] Cloud Spanner

    **Explanation:** Firestore is a NoSQL document database for storing, syncing, and querying data for mobile and web apps. Its client libraries provide live synchronization and offline support, while its security features and integrations with Firebase and Google Cloud Platform accelerate building serverless apps.

17. Your organization wants an economical solution to store data such as files, graphical images, and videos and to access and share them securely. Which Google Cloud product or service should your organization use?

    - [x] Cloud Storage
    - [ ] Cloud SQL
    - [ ] Cloud Spanner
    - [ ] BigQuery

    **Explanation:** Cloud Storage is a RESTful service for storing and accessing your data on Google's infrastructure. The service combines the performance and scalability of Google's cloud with advanced security and sharing capabilities.

18. Your organization wants to predict the behavior of visitors to its public website. To do that, you have decided to build a machine learning model. Your team has database-related skills but only basic machine learning skills, and would like to use those database skills. Which Google Cloud product or feature should your organization choose?

    - [x] BigQuery ML
    - [ ] LookML
    - [ ] TensorFlow
    - [ ] Cloud SQL

    **Explanation:** 

19. Your organization needs to restrict access to a Cloud Storage bucket. Only employees who are based in Canada should be allowed to view the contents. What is the most effective and efficient way to satisfy this requirement?

    - [ ] Deploy the Cloud Storage bucket to a Google Cloud region in Canada
    - [x] Configure Google Cloud Armor to allow access to the bucket only from IP addresses based in Canada
    - [ ] Give each employee who is based in Canada access to the bucket
    - [ ] Create a group consisting of all Canada-based employees, and give the group access to the bucket

    **Explanation:** Google Cloud Armor offers a policy framework and rules language for customizing access to internet-facing applications and deploying defenses against denial of service attacks as well as targeted application attacks. Components of Google Cloud Armor include: L3/L4 volumetric DDos Protection, preconfigured web-application firewall (WAF) rules, and custom rules language.

20. Your organization is moving an application to Google Cloud. As part of that effort, it needs to migrate the application's working database from another cloud provider to Cloud SQL. The database runs on the MySQL engine. The migration must cause minimal disruption to users. Data must be secured while in transit. Which should your organization use?

    - [ ] BigQuery Data Transfer Service
    - [ ] MySQL batch insert
    - [x] Database Migration Service
    - [ ] Cloud Composer

    **Explanation:** O AWS Database Migration Service (AWS DMS) é um serviço de replicação e migração gerenciado que ajuda a mover workloads analíticos e bancos de dados para a AWS rapidamente, de forma segura e com o mínimo possível de inatividade e zero perda de dados.