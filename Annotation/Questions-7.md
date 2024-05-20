# Digital Leader

Reference (1): <https://www.whizlabs.com/blog/google-cloud-certified-digital-leader-exam-free-questions/>

## Questions

1. Which Google Cloud product would be best suited to serve as a metadata inventory service, enabling customers to have a view of all the GCP and Anthos assets across projects and services? 

    - [ ] Access Transparency & Access Approval
        - Option A is incorrect. Access Transparency & Access Approval help provide visibility and control by facilitating admin access logs and approval controls.
    - [ ] Binary Authorization
        - Option B is incorrect. Binary Authorization helps ensure deployment of trusted container images on Google Kubernetes Engine (GKE) or Cloud Run.
    - [x] Cloud Asset Inventory
        - Option C is correct. Cloud Asset Inventory is a metadata inventory service that facilitates customers to have a view of all the GCP and Anthos assets across projects and services, along with enabling them to monitor and analyze all the GCP and Anthos assets across projects and services.
    - [ ] Confidential Computing
        - Option D is incorrect. Confidential Computing helps customers encrypt sensitive data while the data is in-use.

2. Which Google Cloud AI product helps classify unstructured text and sentiment analysis?

    - [ ] Vertex AI
        - Option A is incorrect. Vertex AI helps build, deploy and scale ML models faster within a unified AI platform.
    - [ ] Cloud Translation
        - Option B is incorrect. Cloud Translation helps build multilingual applications with the help of machine translation.
    - [x] Natural Language AI
        - Option C is correct. Natural Language AI is a Google Cloud AI product that helps classify unstructured text and performs sentiment analysis.
    - [ ] Dialogflow
        - Option D is incorrect. Dialog flow helps build conversational applications.

3. To ensure the developers’ code functionality in “Event-Driven Serverless Functions”, which Google Cloud product should a customer opt for?

    - [x] Cloud Functions
        - Option A is correct. Cloud Functions help develop Event-Based serverless Functions.
    - [ ] Cloud Serverless
        - Option B is incorrect. Cloud Serverless is an invalid option.
    - [ ] Anthos Cluster
        - Option C is incorrect. Anthos Cluster helps utilize Kubernetes across Multi-Cloud and Hybrid cloud environments.
    - [ ] Cloud Foundation toolkit
        - Option D is incorrect. Cloud foundation toolkit helps provide Infrastructure as a code template

4. Which Google Cloud product helps customers.
    - Search and analyze log files through query statements?
    - Use Public Write APIs to write custom logs from on-premise?
    - Set alerts for notifying when a specific message appears in logs?

    - [x] Cloud Logging
        - Option A is correct. Cloud Logging helps in the real-time analysis and management of logs.
    - [ ] Cloud Debugger
        - Option B is incorrect. Cloud Debugger helps in the investigation of code’s behavior in production.
    - [ ] Cloud Trace
        - Option C is incorrect. Cloud Trace helps identify bottlenecks in production.
    - [ ] Cloud Monitoring
        - Option D is incorrect. Cloud Monitoring facilitates the collection of metrics, creating visualizations for metrics pertaining to applications and Infrastructure’s availability, performance, and health.

5. Which of the below features of Pub/Sub allows offline examination and debugging of messages to ensure no-delay processing of other messages?

    - [ ] Exactly once processing
        - Option A is Incorrect. Exactly once processing ensures that the Pub/Sub stream is processed exactly once.
    - [ ] Seek and replay
        - Option B is Incorrect. The seek and replay feature of Pub/Sub can reprocess messages by facilitating point-in-time rewind of backlog.
    - [x] Dead Letter topics
        - Option C is Correct. It allows offline examination and debugging of messages to ensure no-delay processing of other messages.
    - [ ] Filtering
        - Option D is Incorrect. Filtering enables message filtering based on message attributes.

6. Which of the below-listed use cases should Local SSD be used for?

    - [ ] Genome sequencing
        - Option A is Incorrect. Since Genome sequencing requires performing analysis and needs speed, scalabiity and security, filestore is most apt.
    - [x] Media rendering
        - Option B is Correct. Local SSD is appropriate to be used for Media rendering.
    - [ ] Data archiving
        - Option C is Incorrect. Cold storage is most optimal for data archiving.
    - [x] Use as cache
        - Option D is Correct. Local SSD is the most optimal choice for being used as a cache as it provides high IOPS and very low latency.
    - [ ] Batch Jobs
        - Option E is Incorrect. Preemptible VMs are appropriate for batch jobs.

7. An issue is reported in the code deployed in the production environment. To diagnose the issue, your developer requires injecting a new logging statement and taking a snapshot of the state of running the application. How can this be done?

    - [ ] Cloud Logging
        - Option A is Incorrect. Cloud logging helps in real-time management and analysis of logs.
    - [ ] Cloud Monitoring
        - Option B is Incorrect. Cloud Monitoring helps to monitor the health, availability and performance of infrastructure and the configured application by producing metrics of help.
    - [ ] Cloud Trace
        - Option C is Incorrect. Cloud Trace is an offering from Google cloud that helps find production performance bottlenecks by collecting application’s latency data.
    - [x] Cloud Debugger
        - Option D is Correct. Cloud Debugger helps to investigate the behavior of code in production.

8. Which of the below-listed ways cannot be used to connect to the services and resources hosted in the Google Cloud platform?

    - [ ] Cloud SDK
        - Option A is incorrect as Cloud SDK is an excellent way to interact and connect with the services and resources hosted in the Google Cloud Platform.
    - [ ] Cloud Shell
        - Option B is incorrect as Cloud Shell is an excellent way to interact and connect with the services and resources hosted in the Google Cloud Platform.
    - [ ] Google Cloud Console
        - Option C is incorrect as Google Cloud Console is an excellent way to interact and connect with the services and resources hosted in the Google Cloud Platform.
    - [x] Google Management Console
        - Option D is correct as “Google Management Console” is an invalid option.

    **Explanation:** There are three basic ways to interact and connect with the services and resources hosted in Google Cloud Platform.
    - Google Cloud Console
    - Command Line Interface (includes Cloud SDK and Cloud Shell)
    - Client Libraries

9. You are asked to deploy applications so that they are fault-tolerant and highly available. Since the customers are based only in India, you plan to use only one region. Which deployment area within a region would you use to deploy the applications?

    - [x] Zone
        - Option A is correct. Zones are a deployment area within a region, and Zones can be utilized for deploying applications in a way that they are fault-tolerant and highly available.
    - [ ] Datacenter
        - Option B is incorrect. If an application is deployed in a particular data center, and the data center is impacted by, say power failure or some calamity, the application would also go down. Hence, opting for a data center would not be the right choice.
    - [ ] Sub-Region
        - Option C is incorrect. Sub-Region is an invalid option.
    - [ ] Datazone
        - Option D is incorrect. Datazone is an invalid option.

10. You are working on implementing a solution that requires you to use a scalable, no-maintenance and serverless document database. Which of the below Google Cloud products would you use?

    - [x] Firestore
        - Option A is correct. Firestore is a Google product that is scalable, requires no maintenance, and it is a serverless document database.
    - [ ] Cloud Spanner
        - Option B is incorrect. Cloud Spanner is incorrect because it is a relational database service, not a document database.
    - [ ] Memorystore
        - Option C is incorrect. Memorystore, also known as Memorystore for Redis, is a fully managed Google’s in-memory data store service.
    - [ ] Cloud Bigtable
        - Option D is incorrect. Cloud Bigtable is a big data database service, not a document database.