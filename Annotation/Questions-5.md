# Digital Leader

Reference (1): <https://certsqa.com/questions/?exam=Cloud-Digital-Leader/>
Reference (2): <https://www.itexams.com/exam/Cloud-Digital-Leader>

## Questions

4. The operating systems of some of your organization’s virtual machines may have a security vulnerability. How can your organization most effectively identify all virtual machines that do not have the latest security update?

    - [x] View the Security Command Center to identify virtual machines running vulnerable disk images
    - [ ] View the Compliance Reports Manager to identify and download a recent PCI audit
    - [ ] View the Security Command Center to identify virtual machines started more than 2 weeks ago
    - [ ] View the Compliance Reports Manager to identify and download a recent SOC 1 audit

    **Explanation:** Security Health Analytics and Web Security Scanner detectors generate vulnerabilities findings that are available in Security Command Center. Your ability to view and edit findings is determined by the Identity and Access Management (IAM) roles and permissions you are assigned. For more information about IAM roles in Security Command Center.

5. You are currently managing workloads running on Windows Server for which your company owns the licenses. Your workloads are only needed during working hours, which allows you to shut down the instances during the weekend. Your Windows Server licenses are up for renewal in a month, and you want to optimize your license cost. What should you do?

    - [ ] Renew your licenses for an additional period of 3 years. Renew your licenses for an additional period of 3 years. Negotiate a cost reduction with your current hosting provider wherein infrastructure cost is reduced when workloads are not in use
    - [ ] Renew your licenses for an additional period of 2 years. Negotiate a cost reduction by committing to an automatic renewal of the licenses at the end of the 2 year period
    - [ ] Migrate the workloads to Compute Engine with a bring-your-own-license (BYOL) model
    - [x] Migrate the workloads to Compute Engine with a pay-as-you-go (PAYG) model

    **Explanation:** The PAYG model is more convenient because you only pay for usage. And the case describes that the workloads are only run on certain days.

6. Your team is publishing research results and needs to make large amounts of data available to other researchers within the professional community and the public at minimum cost. How should you host the data?

    - [x] Use a Cloud Storage bucket and enable Requester Pays.
    - [ ] Use a Cloud Storage bucket and provide Signed URLs for the data files.
    - [ ] Use a Cloud Storage bucket and set up a Cloud Interconnect connection to allow access to the data.
    - [ ] Host the data on-premises, and set up a Cloud Interconnect connection to allow access to the data.

    **Explanation:** Whenever a user accesses a Cloud Storage resource such as a bucket or object, there are charges associated with making and executing the request. Normally, the project owner of the resource is billed for these charges; however, if the requester provides a billing project with their request, the requester's project is billed instead. With Requester Pays enabled on your bucket, you can require requesters to include a billing project in their requests, thus billing the requester's project. Enabling Requester Pays is useful, for example, if you have a lot of data you want to make available to users, but you don't want to be charged for their access to that data.

7. Your company needs to segment Google Cloud resources used by each team from the others. The teams' efforts are changing frequently, and you need to reduce operational risk and maintain cost visibility. Which approach does Google recommend?

    - [x] One project per team.
    - [ ] One organization per team.
    - [ ] One project that contains all of each team's resources.
    - [ ] One top-level folder per team.

8. How do Migrate for Compute Engine and Migrate for Anthos differ?

    - [ ] Unlike Migrate for Anthos, Migrate for Compute Engine assumes that the migration source is VMware vSphere.
    - [ ] Migrate for Compute Engine charges for ingress, but Migrate for Anthos does not.
    - [ ] Migrate for Compute Engine is closed source, and Migrate for Anthos is open source.
    - [x] Migrate for Anthos migrates to containers, and Migrate for Compute Engine migrates to virtual machines.

    **Explanation:** Use Migrate to Containers to modernize traditional applications away from virtual machine (VM) instances and into native containers that run on Google Kubernetes Engine (GKE) or Cloud Run platform.

9. Your large and frequently changing organization's user information is stored in an on-premises LDAP database. The database includes user passwords and group and organization membership. How should your organization provision Google accounts and groups to access Google Cloud resources?

    - [ ] Replicate the LDAP infrastructure on Compute Engine
    - [ ] Use the Firebase Authentication REST API to create users
    - [x] Use Google Cloud Directory Sync to create users
    - [ ] Use the Identity Platform REST API to create users

    **Explanation:** You can run a single instance of Google Cloud Directory Sync to synchronize user accounts and groups to Google Cloud.

10. Your organization recently migrated its compute workloads to Google Cloud. You want these workloads in Google Cloud to privately and securely access your large volume of on-premises data, and you also want to minimize latency. What should your organization do?

    - [ ] Use Storage Transfer Service to securely make your data available to Google Cloud
    - [x] Create a VPC between your on-premises data center and your Google resources
    - [ ] Peer your on-premises data center to Google's Edge Network
    - [ ] Use Transfer Appliance to securely make your data available to Google Cloud

11. Your organization consists of many teams. Each team has many Google Cloud projects. Your organization wants to simplify the management of identity and access policies for these projects. How can you group these projects to meet this goal?

    - [ ] Group each team's projects into a separate domain
    - [x] Assign labels based on the virtual machines that are part of each team's projects
    - [ ] Use folders to group each team's projects
    - [ ] Group each team's projects into a separate organization node

12. An organization needs to categorize text-based customer reviews on their website using a pre-trained machine learning model. Which Google Cloud product or service should the organization use?

    - [ ] Cloud Natural Language API
    - [ ] Dialogflow
    - [x] Recommendations AI
    - [ ] TensorFlow

    **Explanation:** Take advantage of Google's expertise in recommendations, powered by state-of-the-art machine learning models. Provide effective and real-time personalization with the recommendations capability (formerly Recommendations AI) of Vertex AI Search. Earn your customers’ trust and loyalty by proving how well you understand them. Google delivers content to billions across consumer facing platforms including Google Ads, Google Search, and YouTube.

13. An organization is planning its cloud expenditure. What should the organization do to control costs?

    - [ ] Consider cloud resource costs as capital expenditure in annual planning.
    - [ ] Use only cloud resources; they have no cloud infrastructure costs.
    - [x] Review cloud resource costs frequently because costs depend on usage.
    - [ ] Assess cloud resources costs only when SLO is not met by their cloud provider.

14. An organization is searching for an open-source machine learning platform to build and deploy their own custom machine learning applications using TPUs. Which Google Cloud product or service should the organization use?

    - [ ] TensorFlow
    - [ ] BigQuery ML
    - [ ] Vision API
    - [x] AutoML Vision

15. What is an example of unstructured data that organizations can capture from social media?

    - [ ] Post comments
    - [ ] Tagging
    - [x] Profile picture
    - [ ] Location

16. An organization relies on online seasonal sales for the majority of their annual revenue. Why should the organization use App Engine for their customer app?

    - [ ] Automatically adjusts physical inventory in real time
    - [ ] Autoscales during peaks in demand
    - [x] Runs maintenance during seasonal sales
    - [ ] Recommends the right products to customers

17. An organization is using machine learning to make predictions. One of their datasets mistakenly includes mislabeled data. How will the prediction be impacted?

    - [ ] Increased risk of privacy leaks
    - [x] Increased risk of inaccuracy
    - [ ] Decreased model compatibility
    - [ ] Decreased model training time

18. lobal organization is developing an application to manage payments and online bank accounts in multiple regions. Each transaction must be handled consistently in their database, and they anticipate almost unlimited growth in the amount of data stored. Which Google Cloud product should the organization choose?

    - [ ] Cloud SQL
    - [x] Cloud Spanner
    - [ ] Cloud Storage
    - [ ] BigQuery

19. An organization has servers running mission-critical workloads on-premises around the world. They want to modernize their infrastructure with a multi-cloud architecture. What benefit could the organization experience?

    - [ ] Ability to disable regional network connectivity during cyber attacks
    - [ ] Ability to keep backups of their data on-premises in case of failure
    - [x] Full management access to their regional infrastructure
    - [ ] Reduced likelihood of system failure during high demand events

20. An organization needs to run frequent updates for their business app. Why should the organization use Google Kubernetes Engine (GKE)?

    - [ ] Customer expectations can be adjusted without using marketing tools
    - [ ] Seamless changes can be made without causing any application downtime.
    - [ ] GKE handles version control seamlessly and out of the box
    - [x] GKE is well suited for all monolithic applications