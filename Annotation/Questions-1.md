# Digital Leader

**Reference:** <https://www.examtopics.com/exams/google/>

## Questions

1. Which Google Cloud service or feature lets you build machine learning models using Standard SQL and data in a data warehouse?<br>
    _Qual serviço ou recurso do Google Cloud permite criar modelos de machine learning usando SQL padrão e dados em um data warehouse?_

    :white_check_mark: BigQuery ML

    :black_large_square: TensorFlow

    :black_large_square: C. AutoML Tables

    :black_large_square: D. Cloud Bigtable ML

    > BigQuery ML lets you create and execute machine learning models in BigQuery using standard SQL queries.<br>
    
    > _O BigQuery ML permite criar e executar modelos de machine learning no BigQuery usando consultas SQL padrão._

---

2. What are the key features of Google Cloud Identity?<br>
    _Quais são os principais recursos do Google Cloud Identity?_

    :black_large_square: Multi-factor authentication (MFA)

    :black_large_square: Single sign-on (SSO)

    :black_large_square: Works with your favorite apps and Endpoint management

    :white_check_mark: All of the Above 
    
    >- Cloud Identity: A unified identity, access, app, and endpoint management (IAM/EMM) platform.
    >  - Give users easy access to apps with single sign-on.
    >  - Multi-factor authentication protects user and company data.
    >  - Endpoint management enforces policies for personal and corporate devices KEY FEATURES : Modernize IT and strengthen security Multi-factor authentication (MFA) Help protect your user accounts and company data with a wide variety of MFA verification methods such as push notifications, Google Authenticator, phishing-resistant Titan Security Keys, and using your Android or iOS device as a security key. Endpoint management Improve your company’s device security posture on Android, iOS, and Windows devices using a unified console. Set up devices in minutes and keep your company data more secure with endpoint management. Enforce security policies, wipe company data, deploy apps, view reports, and export details. Single sign-on (SSO) Enable employees to work from virtually anywhere, on any device, with single sign-on to thousands of pre-integrated apps, both in the cloud and on-premises. Works with your favorite apps Cloud Identity integrates with hundreds of cloud applications out of the box—and we’re constantly adding more to the list so you can count on us to be your single identity platform today and in the future.
    
    >- _Uma plataforma unificada de gerenciamento de identidade, acesso, aplicativos e endpoints (IAM/EMM)._
    >  - _Dê aos usuários acesso fácil a aplicativos com logon único._<br>
    >  - _A autenticação multifator protege os dados do usuário e da empresa._<br>
    >  - _O gerenciamento de endpoint aplica políticas para dispositivos pessoais e corporativos RECURSOS PRINCIPAIS: Modernize a TI e fortaleça a segurança Autenticação multifatorial (MFA) Ajude a proteger suas contas de usuário e dados da empresa com uma ampla variedade de métodos de verificação de MFA, como notificações push, Google Authenticator, phishing chaves de segurança Titan resistentes e usando seu dispositivo Android ou iOS como chave de segurança. Gerenciamento de endpoints Melhore a postura de segurança de dispositivos da sua empresa em dispositivos Android, iOS e Windows usando um console unificado. Configure dispositivos em minutos e mantenha os dados da sua empresa mais seguros com o gerenciamento de endpoints. Aplique políticas de segurança, limpe dados da empresa, implante aplicativos, visualize relatórios e exporte detalhes. Logon único (SSO) Permita que os funcionários trabalhem de praticamente qualquer lugar, em qualquer dispositivo, com logon único em milhares de aplicativos pré-integrados, tanto na nuvem quanto no local. Funciona com seus aplicativos favoritos O Cloud Identity integra-se com centenas de aplicativos em nuvem prontos para uso, e estamos constantemente adicionando mais à lista para que você possa contar conosco para ser sua plataforma de identidade única hoje e no futuro._

---

3. Your organization needs to process large amounts of data from an online application that operates continuously. You do not want to be required to provision infrastructure or create server clusters. What should your organization choose?<br>
    _Sua organização precisa processar grandes quantidades de dados de um aplicativo online que opera continuamente. Você não quer ser obrigado a provisionar infraestrutura ou criar clusters de servidores. O que sua organização deve escolher?_

    :black_large_square: Compute Engine with BigQuery

    :black_large_square: Dataproc

    :black_large_square: Google Kubernetes Engine with Cloud Bigtable

    :white_check_mark: Dataflow

    >- You do not want to be required to provision infrastructure or create server clusters. Because Unified stream and batch data processing that's serverless, fast, and cost-effective.<br>
    >  - Dataflow is a fully-managed service for strongly consistent, parallel data-processing pipelines. It provides an SDK for Java with composable primitives for building data-processing pipelines for batch or continuous processing. This service manages the life cycle of Compute Engine resources of the processing pipeline(s). It also provides a monitoring user interface for understanding pipeline health.<br>
    
    >- _Você não quer ser obrigado a provisionar infraestrutura ou criar clusters de servidores. Porque fluxo unificado e processamento de dados em lote, sem servidor, rápido e econômico._<br>
    >  - _O Dataflow é um serviço totalmente gerenciado para pipelines de processamento de dados paralelos e altamente consistentes. Ele fornece um SDK para Java com primitivos combináveis ​​para construir pipelines de processamento de dados para processamento em lote ou contínuo. Este serviço gerencia o ciclo de vida dos recursos do Compute Engine dos pipelines de processamento. Ele também fornece uma interface de usuário de monitoramento para compreender a integridade do pipeline._

---

4. The Border Security Agency has hired your software services firm to build an application for them that will collect information about visas stamped on passports. You are given stamped images. You have to find out which country issued the visa and the period of validity. Pull out this data and put it into a database. Which of these applications would be suitable for that?<br>
    _A Agência de Segurança de Fronteiras contratou sua empresa de serviços de software para criar um aplicativo que coletará informações sobre vistos carimbados em passaportes. Você recebe imagens carimbadas. Você deve descobrir qual país emitiu o visto e o período de validade. Retire esses dados e coloque-os em um banco de dados. Qual dessas aplicações seria adequada para isso?_

    :white_check_mark: Use Cloud Vision API - write code to identify the text blocks, copy the data, and store it

    :black_large_square: Use TensorFlow - write code that will identify the type of visa and the bounding text blocks. Copy the data and then store it.

    :black_large_square: Use AutoML - upload other images of visas and run the model creation process which will automatically identify the visas

    :black_large_square: Use Data Labeling service - outsource the work of marking and extracting the in-formation to others.

    > Cloud Vision API allows you to programmatically identify images, text, etc. in the document. This would be the best.<br>
    
    > _A API Cloud Vision permite identificar programaticamente imagens, texto etc. Este seria o melhor._

---

5. The customer has applications that do data processing on-premise. They have been built using Ha-doop and Spark. What product should I use on Google Cloud?<br>
    _O cliente possui aplicativos que fazem o processamento de dados localmente. Eles foram construídos usando Ha-doop e Spark. Qual produto devo usar no Google Cloud?_

    :white_check_mark: Dataproc

    :black_large_square: Dataflow

    :black_large_square: Dataprep

    :black_large_square: Dataplex

    > Because Dataproc is used to run Hadoop/Spark workloads<br>
    
    > _Porque o Dataproc é usado para executar cargas de trabalho do Hadoop/Spark_

---

6. Your organization is running all its workloads in a private cloud on top of a hypervisor. Your organization has decided it wants to move to Google Cloud as quickly as possible. Your organization wants minimal changes to the current environment, while using the maximim amount of managed services Google offers. What should your organization do?<br>
    _Sua organização está executando todas as suas cargas de trabalho em uma nuvem privada sobre um hipervisor. Sua organização decidiu que quer migrar para o Google Cloud o mais rápido possível. Sua organização deseja mudanças mínimas no ambiente atual, ao mesmo tempo em que utiliza a quantidade máxima de serviços gerenciados que o Google oferece. O que sua organização deve fazer?_

    :black_large_square: Migrate the workloads to Google Cloud VMware Engine

    :white_check_mark: Migrate the workloads to Compute Engine

    :black_large_square: Migrate the workloads to Bare Metal Solution

    :black_large_square: Migrate the workloads to Google Kubernetes Engine
    
    > Migrate for Compute Engine enables you to lift and shift workloads at scale to Google Cloud Compute Engine with minimal changes and risk.<br>
    
    > _O Migrate for Compute Engine permite transferir cargas de trabalho em escala para o Google Cloud Compute Engine com alterações e riscos mínimos._

---

7. What characteristics should an organization adopt to be a DevOps organization?<br>
    _Quais características uma organização deve adotar para ser uma organização DevOps?_

    :black_large_square: Teamwork over individual work

    :black_large_square: Obsession with Automation over preoccupation with manual work

    :black_large_square: Product based teams over component teams.

    :white_check_mark: All of the Above

---

8. When you update the function in firebase by deploying updated code, instances for older versions are cleaned up along with build artifacts in __________________ and replaced by new instances.<br>
    _Quando você atualiza a função no Firebase implantando código atualizado, as instâncias de versões mais antigas são limpas junto com os artefatos de compilação em __________________ e substituídas por novas instâncias._

    :black_large_square: Google Cloud console.

    :white_check_mark: Storage and Container Registry.

    :black_large_square: Container Registry repository.
    
    :black_large_square: None of the Above

    > Container Registry is a single place for your team to manage Docker images, perform vulnerability analysis, and decide who can access what with fine-grained access control<br>
    
    > _O Container Registry é um local único para sua equipe gerenciar imagens do Docker, realizar análises de vulnerabilidades e decidir quem pode acessar o quê com controle de acesso refinado_

---

9. Virtual Machine vCPU and memory usage for each of these categories can receive one of the following discounts? (Select Three Answer)<br>
    _O uso de vCPU e memória da máquina virtual para cada uma dessas categorias pode receber um dos seguintes descontos? (Selecione três respostas)_

    :black_large_square: Military Discounts
    
    :black_large_square: Spot Instances

    :white_check_mark: Committed-Use

    :white_check_mark: Sustained-Use

    :white_check_mark: Preemptible VMs
    
    > - Sustained, Committed and Preemptible vCPU and memory usage for each of these categories can receive discounts.
    >   - Sustained-use discounts—Google offers up to 30% off for workloads that run for most of the billing month on GCP services.
    >   - Committed-use discounts—users can save up to 57% by committing to use an instance for a certain time period, with no upfront payment and with the flexibility to change instances during the commitment period. 
    >   - Preemptible VMs—similar to the concept of AWS spot instances, Google offers up to 79% off for Virtual Machines that may be shut down at any time and replaced by others.<br>
    
    > - _O uso de vCPU e memória sustentado, comprometido e preemptivo para cada uma dessas categorias pode receber descontos._
    >   - _Descontos por uso prolongado: o Google oferece até 30% de desconto para cargas de trabalho executadas durante a maior parte do mês de faturamento nos serviços do GCP._
    >   - _Descontos por uso contínuo — os usuários podem economizar até 57% ao se comprometerem a usar uma instância por um determinado período, sem pagamento adiantado e com flexibilidade para alterar as instâncias durante o período de compromisso._
    >   - _VMs preemptivas – semelhante ao conceito de instâncias spot da AWS, o Google oferece até 79% de desconto para máquinas virtuais que podem ser desligadas a qualquer momento e substituídas por outras._

---

10. A startup is planning to create their entire suite of applications on Google Cloud. They are looking at various open source technologies to build applications. One of the consideration is about having a well integrated monitoring tool. They have to be able to constantly review load capacity and performance of their applications and virtual machines. What would you advise them to do?<br>
    _Uma startup está planejando criar todo o seu conjunto de aplicativos no Google Cloud. Eles estão buscando diversas tecnologias de código aberto para criar aplicativos. Uma das considerações é ter uma ferramenta de monitoramento bem integrada. Eles precisam ser capazes de revisar constantemente a capacidade de carga e o desempenho de seus aplicativos e máquinas virtuais. O que você os aconselharia a fazer?_

    :black_large_square: It is best to build a custom solution so that they know it integrates well with all their custom applications.

    :black_large_square: Since they are using open source for applications, find another open source monitoring tool and integrate it, which could turn out to be very cheap.

    :white_check_mark: Use the Google Cloud Operations Suite which contains monitoring among other operations tools.

    :black_large_square: Update the application code to regularly write to output logs. Export the logs to BigQuery to analyze them frequently.

    > Operations Suite is well integrated into Google and it s the recommended option.<br>
    
    > _O Operations Suite está bem integrado ao Google e é a opção recomendada._

---

11. A Customer has their current SAP systems using Microsoft SQL Server as the Database. They are migrating to Google Cloud and also preparing to later migrate to the latest version of SAP. The entire IT team is being directed to focus on the migration to the new version of SAP. The new version of SAP does not use Microsoft SQL Server as the Database, Any but the most critical IT management tasks are being deprioritized, How should they migrate their current database to Google Cloud?<br>
    _Um cliente tem seus sistemas SAP atuais usando o Microsoft SQL Server como banco de dados. Eles estão migrando para o Google Cloud e também se preparando para migrar posteriormente para a versão mais recente do SAP. Toda a equipe de TI está sendo direcionada para focar na migração para a nova versão do SAP. A nova versão do SAP não usa o Microsoft SQL Server como banco de dados. Todas as tarefas mais críticas de gerenciamento de TI estão sendo despriorizadas. Como eles deveriam migrar seu banco de dados atual para o Google Cloud?_

    :black_large_square: Spanner

    :black_large_square: Bare Metal

    :black_large_square: BigQuery

    :white_check_mark: Cloud SQL
    
    > Cloud SQL supports SQL Server, Since the IT team's attention is being focused on other activities, they will have less time for existing admin tasks, It would be best to take a managed/hosted version.<br>
    
    > _O Cloud SQL oferece suporte ao SQL Server. Como a atenção da equipe de TI está focada em outras atividades, eles terão menos tempo para as tarefas administrativas existentes. Seria melhor escolher uma versão gerenciada/hospedada._

---

12. You are consulting for a client who is migrating to Google Cloud. They presently have a matrix organization. Their IT environments were managed around projects. Each team had multiple projects. All the projects had a flat structure under the company. What would you advise them when planning for the move?<br>
    _Você está prestando consultoria para um cliente que está migrando para o Google Cloud. Atualmente possuem uma organização matricial. Seus ambientes de TI eram gerenciados em torno de projetos. Cada equipe tinha vários projetos. Todos os projetos tiveram uma estrutura plana sob a empresa. O que você os aconselharia ao planejar a mudança?_

    :white_check_mark: On Google Cloud, create a folder corresponding to each team. Under that, there could be projects or further sub folders as the team decides.

    :black_large_square: In terms of not disturbing the project developers and testers, advise them that the strategic decision is to retain the structure on Google Cloud also.

    :black_large_square: Since a Project could spawn other sub-Projects, on Google Cloud it is better to as-sign a folder for each Project.

    :black_large_square: The flat structure is what is currently used in IT organizations, and this can be used as-is which will provide the best results. 
    
    > Folders for a related group of projects are the recommended approach. A flat structure under the organization node is possible on Google Cloud, but it is not recommended. It becomes tougher to manage. Projects cannot have sub-projects, there can only be resources within Projects.<br>
    
    > _Pastas para um grupo relacionado de projetos são a abordagem recomendada. Uma estrutura plana no nó da organização é possível no Google Cloud, mas não é recomendada. Torna-se mais difícil de gerenciar. Projetos não podem ter subprojetos, só podem existir recursos dentro de Projetos._

---

13. Your company has signed up with a cloud provider and you will be using storage and virtual machines with the provider. The provider has provided your organization some expectations for what the service should perform at. What type of agreement provides a guarantee of a certain level of service such as “Uptime”?<br>
    _Sua empresa se inscreveu em um provedor de nuvem e você usará armazenamento e máquinas virtuais com o provedor. O provedor forneceu à sua organização algumas expectativas sobre o desempenho do serviço. Que tipo de contrato oferece garantia de um determinado nível de serviço como “Uptime”?_

    :black_large_square: Performance Agreement

    :black_large_square: Interconnection Agreement

    :black_large_square: Warranty

    :white_check_mark: Service Level Agreement
    
    > A service level agreement (SLA) is a contract between a service provider (either internal or external) and the end user that defines the level of service expected from the service provider. Some common SLA’s are uptime, Response Time, etc.<br>
    
    > _Um acordo de nível de serviço (SLA) é um contrato entre um provedor de serviços (interno ou externo) e o usuário final que define o nível de serviço esperado do provedor de serviços. Alguns SLAs comuns são tempo de atividade, tempo de resposta, etc._

---

14. Which of the following statements is/are correct about Machine Learning?<br>
    _Qual das seguintes afirmações está correta sobre o aprendizado de máquina?_

    :white_check_mark: Machine learning examples include chatbots and automated virtual assistants to automate routine customer service tasks and speed up issue resolution.

    :black_large_square: Machine learning automates the job of building statistical models with Human Intervention.

    :black_large_square: Robotic process automation (RPA) can not be attached with ML.

    :black_large_square: None of the Above.
    
    > Machine learning examples include chatbots and automated virtual assistants to automate routine customer service tasks and speed up issue resolution.<br>
    
    > _Exemplos de aprendizado de máquina incluem chatbots e assistentes virtuais automatizados para automatizar tarefas rotineiras de atendimento ao cliente e acelerar a resolução de problemas._

---

15. Your application is onboarding a number of users. The details of the users very widely. What kind of database would be most suitable for this use case?<br>
    _Seu aplicativo está integrando vários usuários. Os detalhes dos usuários são muito amplos. Que tipo de banco de dados seria mais adequado para este caso de uso?_

    :white_check_mark: NoSQL database like Firestore

    :black_large_square: OLAP database like BigQuery which support SQL

    :black_large_square: SQL database like MySQL or PostgreSQL

    :black_large_square: OLTP database like Cloud Spanner

    > - NoSQL databases are best suited for this use case. Firestore is an appropriate one to use here.<br>
    >   - Cloud Firestore is a NoSQL document database that lets you easily store, sync, and query data for your mobile and web apps at global scale.<br>
    
    > - _Os bancos de dados NoSQL são mais adequados para este caso de uso. Firestore é apropriado para usar aqui._
    >   - _Cloud Firestore é um banco de dados de documentos NoSQL que permite armazenar, sincronizar e consultar facilmente dados para seus aplicativos móveis e da web em escala global._

---

16. Your organization needs to plan its cloud infrastructure expenditures. Which should your organization do?<br>
    _Sua organização precisa planejar seus gastos com infraestrutura em nuvem. O que sua organização deve fazer?_

    :white_check_mark: Review cloud resource costs frequently, because costs change often based on use.

    :black_large_square: Review cloud resource costs annually as part of planning your organization’s overall budget.

    :black_large_square: If your organization uses only cloud resources, infrastructure costs are no longer part of your overall budget.

    :black_large_square: Involve fewer people in cloud resource planning than your organization did for onpremises resource planning.

    > Review cloud resource costs frequently, because costs change often based on use because one need to know current usage/trend for planning, While public cloud eliminates capex, and gets into pay as you go model, the usage pattern determines the cloud cost and hence needs to be measured frequently to enable better forecast.<br>
    
    > _Revise os custos dos recursos da nuvem com frequência, porque os custos mudam frequentemente com base no uso, porque é necessário conhecer o uso/tendência atual para o planejamento. Embora a nuvem pública elimine o investimento e entre no modelo de pagamento conforme o uso, o padrão de uso determina o custo da nuvem e, portanto, as necessidades ser medido frequentemente para permitir uma melhor previsão._

---

17. In terms of Cloud SQL for MySQL Features offered by Google Cloud Platform which of the statements is/are correct?<br>
    _Em termos de recursos do Cloud SQL para MySQL oferecidos pelo Google Cloud Platform, quais das afirmações estão corretas?_

    :black_large_square: Do not support Private IP (private service access).

    :white_check_mark: Customer data is encrypted on Google's internal networks and in database tables, temporary files, and backups.

    :black_large_square: Do not Provide automated and on-demand backups and point-in-time recovery.

    :black_large_square: None of the above

    > - Cloud SQL for MySQL - Features
    >   - Fully managed MySQL Community Edition databases in the cloud.<br>
    >   - Cloud SQL instances support MySQL 8.0, 5.7 (default), and 5.6, and provide up to 624 GB of RAM and 64 TB of data storage, with the option to automatically increase the storage size, as needed.<br>
    >   - Create and manage instances in the Google Cloud Console.<br>
    >   - Instances are available in the Americas, EU, Asia, and Australia.<br>
    >   - Customer data is encrypted on Google's internal networks and in database tables, temporary files, and backups.<br>
    >   - Support for secure external connections with the Cloud SQL Auth proxy or with the SSL/TLS protocol.<br>
    >   - Support for private IP (private services access).<br>
    >   - Data replication between multiple zones with automatic failover.<br>
    >   - Import and export databases using mysqldump, or import and export CSV files.<br>
    >   - Support for MySQL wire protocol and standard MySQL connectors.<br>
    >   - Automated and on-demand backups and point-in-time recovery.<br>
    >   - Instance cloning.<br>
    >   - Integration with Google Cloud's operations suite logging and monitoring.<br>
    
    > - Cloud SQL for MySQL - Features
    >   - _Bancos de dados MySQL Community Edition totalmente gerenciados na nuvem._
    >   - _As instâncias do Cloud SQL são compatíveis com MySQL 8.0, 5.7 (padrão) e 5.6 e fornecem até 624 GB de RAM e 64 TB de armazenamento de dados, com a opção de aumentar automaticamente o tamanho do armazenamento, conforme necessário._
    >   - _Crie e gerencie instâncias no Console do Google Cloud._
    >   - _As instâncias estão disponíveis nas Américas, EU, Ásia e Austrália._
    >   - _Os dados dos clientes são criptografados nas redes internas do Google e em tabelas de bancos de dados, arquivos temporários e backups._
    >   - _Suporte para conexões externas seguras com o proxy Cloud SQL Auth ou com o protocolo SSL/TLS._
    >   - _Suporte para IP privado (acesso a serviços privados)._
    >   - _Replicação de dados entre múltiplas zonas com failover automático._
    >   - _Importe e exporte bancos de dados usando mysqldump ou importe e exporte arquivos CSV._
    >   - _Suporte para protocolo MySQL e conectores MySQL padrão._
    >   - _Backups automatizados e sob demanda e recuperação pontual._
    >   - _Clonagem de instância._
    >   - _Integração com registro e monitoramento do conjunto de operações do Google Cloud._

---

18. A prospect wants to be able to store and analyze data. Their analysts already know SQL, but are not familiar with other technologies. Which of these databases can the analysts use without additional training?<br>
    _Um cliente potencial deseja ser capaz de armazenar e analisar dados. Seus analistas já conhecem SQL, mas não estão familiarizados com outras tecnologias. Quais desses bancos de dados os analistas podem usar sem treinamento adicional?_

    :black_large_square: Cloud SQL, BigQuery, Datastore

    :white_check_mark: Spanner, Cloud SQL, BigQuery

    :black_large_square: Cloud SQL, Firestore, Datastore

    :black_large_square: Cloud SQL, Bigtable, BigQuery

    > - Spanner, Cloud SQL, BigQuery
    >   - Cloud Spanner is a fully managed, mission-critical, relational database service that offers transactional consistency at global scale, automatic, synchronous replication for high availability, and support for two SQL Google Standard SQL and PostgreSQL.<br>
    >   - Cloud SQL is a fully-managed database service that helps you set up, maintain, manage, and administer your relational databases on Google Cloud Platform.<br>
    >   - Google BigQuery is a cloud-based Architecture and provides exceptional performance as it can auto-scale up and down based on the data load and performs data analysis efficiently. On the other hand, SQL Server is based on client-server architecture and has fixed performance throughout unless the user scales it manually.<br>
    > - Spanner, Cloud SQL, BigQuery
    
    >   - _O Cloud Spanner é um serviço de banco de dados relacional de missão crítica totalmente gerenciado que oferece consistência transacional em escala global, replicação automática e síncrona para alta disponibilidade e suporte para dois SQL, SQL padrão do Google e PostgreSQL._
    >   - _O Cloud SQL é um serviço de banco de dados totalmente gerenciado que ajuda você a configurar, manter, gerenciar e administrar bancos de dados relacionais no Google Cloud Platform._
    >   - _O Google BigQuery é uma arquitetura baseada em nuvem e oferece desempenho excepcional, pois pode aumentar e diminuir automaticamente com base na carga de dados e realizar análises de dados com eficiência. Por outro lado, o SQL Server é baseado na arquitetura cliente-servidor e tem desempenho fixo, a menos que o usuário o dimensione manualmente._

---

19. Customer Managed Encryption Keys (CMEK) can be used for encrypting data inside Cloud BigTable, which of the following statements is/are correct. (Select two answer)<br>
    _As chaves de criptografia gerenciadas pelo cliente (CMEK) podem ser usadas para criptografar dados dentro do Cloud BigTable, e quais das afirmações a seguir estão corretas. (Selecione duas respostas)_

    :black_large_square: Administrators can not rotate.

    :white_check_mark: Not supported for instances that have clustered in more than one region.

    :white_check_mark: CMEK can only be configured at the cluster level.

    :black_large_square: You can not use the same CMEK key in multiple projects.
    
    > Customer managed encryption keys for Cloud BigTable. By default, all the data at rest in Cloud Bigtable is encrypted using Google's default encryption. Bigtable handles and manages this encryption for you without any additional action on your part. If you have specific compliance or regulatory requirements related to the keys that protect your data, you can use customer managed encryption keys (CMEK) for BigTable. Instead of Google managing the encryption keys that protect your data, your BigTable instance is protected using a key that you control and manage in Cloud Key Management Service (Cloud KMS). Features Security: CMEK provides the same level of security as Google's default encryption but provides more administrative control. Data access control: Administrators can rotate, manage access to, and disable or destroy the key used to protect data at rest in BigTable. Auditability: All actions on your CMEK keys are logged and viewable in Cloud Logging. Comparable performance: BigTable CMEK protected instances offer comparable performance to BigTable instances that use Google default encryption. Flexibility: You can use the same CMEK key in multiple projects or instances or you can use separate keys, depending on your business needs.<br>
    
    > _Chaves de criptografia gerenciadas pelo cliente para Cloud BigTable. Por padrão, todos os dados em repouso no Cloud Bigtable são criptografados usando a criptografia padrão do Google. O Bigtable cuida e gerencia essa criptografia para você, sem qualquer ação adicional de sua parte. Se você tiver requisitos regulamentares ou de conformidade específicos relacionados às chaves que protegem seus dados, poderá usar chaves de criptografia gerenciadas pelo cliente (CMEK) para o BigTable. Em vez de o Google gerenciar as chaves de criptografia que protegem seus dados, sua instância do BigTable é protegida por meio de uma chave que você controla e gerencia no Cloud Key Management Service (Cloud KMS). Recursos Segurança: CMEK oferece o mesmo nível de segurança que a criptografia padrão do Google, mas oferece mais controle administrativo. Controle de acesso a dados: os administradores podem alternar, gerenciar o acesso e desabilitar ou destruir a chave usada para proteger os dados em repouso no BigTable. Auditabilidade: todas as ações nas suas chaves CMEK são registradas e visíveis no Cloud Logging. Desempenho comparável: as instâncias protegidas do BigTable CMEK oferecem desempenho comparável às instâncias do BigTable que usam a criptografia padrão do Google. Flexibilidade: você pode usar a mesma chave CMEK em vários projetos ou instâncias ou pode usar chaves separadas, dependendo das necessidades do seu negócio._

---

20. A customer deploys an application to App Engine and needs to check for Open Web Application Security Project (OWASP) vulnerabilities. Which service should be used to accomplish this?<br>
    _Um cliente implanta um aplicativo no App Engine e precisa verificar vulnerabilidades do Open Web Application Security Project (OWASP). Qual serviço deve ser usado para fazer isso?_

    :black_large_square: Cloud Armor

    :white_check_mark: Cloud Security Scanner

    :black_large_square: Binary Authorization

    :black_large_square: Forseti Security
    
    > Web Security Scanner identifies security vulnerabilities in your App Engine, Google Kubernetes Engine (GKE), and Compute Engine web applications. It crawls your application, following all links within the scope of your starting URLs, and attempts to exercise as many user inputs and event handlers as possible. Currently, Web Security Scanner only supports public URLs and IPs that aren’t behind a firewall. Web Security Scanner currently supports the App Engine standard environment and App Engine flexible environments, Compute Engine instances, and GKE resources.<br>
    
    > _O Web Security Scanner identifica vulnerabilidades de segurança nos aplicativos da Web do App Engine, do Google Kubernetes Engine (GKE) e do Compute Engine. Ele rastreia seu aplicativo, seguindo todos os links dentro do escopo de seus URLs iniciais, e tenta exercitar o máximo possível de entradas de usuário e manipuladores de eventos. Atualmente, o Web Security Scanner oferece suporte apenas a URLs e IPs públicos que não estão protegidos por firewall. Atualmente, o Web Security Scanner oferece suporte ao ambiente padrão do App Engine e aos ambientes flexíveis do App Engine, às instâncias do Compute Engine e aos recursos do GKE._