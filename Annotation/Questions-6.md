# Digital Leader

Reference (1): <https://www.whizlabs.com/blog/google-cloud-certified-digital-leader-exam-free-questions/>

## Questions

1. A crowdsourcing platform is looking forward to hosting its applications and services on Google Cloud. Before onboarding the applications and services on Google Cloud, they have expressed an intention to estimate the total cost that they will incur for running their workload on Google Cloud. What would you suggest to them for getting this estimation immediately?<br>
    _Uma plataforma de crowdsourcing espera hospedar seus aplicativos e serviços no Google Cloud. Antes de integrar os aplicativos e serviços no Google Cloud, eles expressaram a intenção de estimar o custo total em que incorrerão para executar a carga de trabalho no Google Cloud. O que você sugeriria a eles para obter essa estimativa imediatamente?_

    :black_large_square: Browse Pricing list for Individual service

    :white_check_mark: Use Pricing Calculator

    :black_large_square: Contact Google Support

    :black_large_square: Contact Your Google Account Manager

    > Option A is incorrect. This option requires manual effort. Hence, this is not a good choice provided that Google provides a “Pricing Calculator”.<br>
    _A opção A está incorreta. Esta opção requer esforço manual. Portanto, esta não é uma boa escolha, desde que o Google forneça uma “Calculadora de preços”.

    > Option B is correct. This is the best way to get the estimation. Google pricing calculator is free of cost and can be accessed by anyone.<br>
    _A opção B está correta. Esta é a melhor maneira de obter a estimativa. A calculadora de preços do Google é gratuita e pode ser acessada por qualquer pessoa._

    > Option C is incorrect. Yes, this is an option provided by Google. However, a pricing calculator will be a good choice as it will give the estimate immediately. Hence, it is a better option to choose.<br>
    _A opção C está incorreta. Sim, esta é uma opção fornecida pelo Google. No entanto, uma calculadora de preços será uma boa escolha, pois fornecerá a estimativa imediatamente. Portanto, é a melhor opção de escolha._

    > Option D is incorrect. Google Account Manager contact is available only with certain Google Support plans. Since the scenario does not mention if the customer has a Google Support plan, this option is not correct.<br>
    _A opção D está incorreta. O contato do gerente de contas do Google está disponível apenas em determinados planos de suporte do Google. Como o cenário não menciona se o cliente possui um plano de Suporte do Google, esta opção não está correta._

---

2. You are working on designing a solution that requires you to build an application that has disaster recovery capability and can withstand the loss of an entire region. Identify the strategy that is not suitable for implementing this solution.<br>
    _Você está trabalhando no projeto de uma solução que exige a criação de um aplicativo que tenha capacidade de recuperação de desastres e possa suportar a perda de uma região inteira. Identifique a estratégia que não é adequada para implementar esta solução._

    :black_large_square: Use multiregional storage services.

    :black_large_square: Use a zonal resource, but snapshot data to a multiregional resource.

    :black_large_square: Use a zonal resource but manage own data replication to other regions as required.

    :white_check_mark: Use a managed zonal resource.

    > Option A is incorrect. Since you are using multiregional storage services, the application can withstand the loss of an entire region.<br>
    _A opção A está incorreta. Como você está usando serviços de armazenamento multirregional, o aplicativo pode suportar a perda de uma região inteira._

    > Option B is incorrect. Since you are taking a snapshot of data to a multiregional resource, the application can withstand the loss of an entire region.<br>
    _A opção B está incorreta. Como você está tirando um instantâneo dos dados para um recurso multirregional, o aplicativo pode suportar a perda de uma região inteira._

    > Option C is incorrect. Although zonal resources are being used, data replication is being done to other regions. The application can withstand the loss of an entire region.<br>
    _A opção C está incorreta. Embora estejam a ser utilizados recursos zonais, a replicação de dados está a ser feita para outras regiões. A aplicação pode suportar a perda de uma região inteira._

    > Option D is correct. Using “zonal resources only” will not be ideal as the application, in this case, will not be able to sustain regional failure.<br>
    _A opção D está correta. Utilizar “apenas recursos zonais” não será o ideal, pois a aplicação, neste caso, não será capaz de sustentar o fracasso regional._

---

3. Which of the below defines a Region appropriately?<br>
    _Qual das opções abaixo define uma região adequadamente?_

    :black_large_square: Collection of Data Centers is Region.

    :black_large_square: There is One Zone per Region.

    :white_check_mark: Collection of Zones is Region.

    :black_large_square: There is One Data Center per Region.
    
    > Option A is incorrect. Regions consist of Zones, and Zones consist of Data Centers.<br>
    _A opção A está incorreta. As regiões consistem em zonas e as zonas consistem em data centers._

    > Option B is incorrect. A Region can have multiple Zones.<br>
    _A opção B está incorreta. Uma região pode ter várias zonas._

    > Option C is correct. This statement correctly defines a Region.<br>
    _A opção C está correta. Esta declaração define corretamente uma região._

    > Option D is incorrect. A Region comprises one or more Zones. Regions consist of Zones, and Zones consist of Data Centers.<br>
    _A opção D está incorreta. Uma região compreende uma ou mais zonas. As regiões consistem em zonas e as zonas consistem em data centers._

---

4. Which of the below statements about Google Cloud resources is CORRECT?<br>
    _Qual das afirmações abaixo sobre os recursos do Google Cloud está CORRETA?_

    :black_large_square: Static external IP addresses are Zone specific resources.

    :black_large_square: Disk snapshots are Region-specific resources.

    :white_check_mark: Any Google Cloud resource that is being used, must necessarily belong to a project.

    :black_large_square: VM instances are Global.

    > Option A is incorrect. Static external IP addresses are Regional, not Zone-specific.<br>
    _A opção A está incorreta. Os endereços IP externos estáticos são regionais e não específicos da zona._

    > Option B is incorrect. Disk snapshots are Global, not Region-specific.<br>
    _A opção B está incorreta. Os instantâneos de disco são globais e não específicos da região._

    > Option C is correct. This is a correct statement. All the Google Cloud resources that are being used must necessarily belong to a project.<br>
    _A opção C está correta. Esta é uma afirmação correta. Todos os recursos do Google Cloud que estão sendo utilizados devem necessariamente pertencer a um projeto._

    > Option D is incorrect. VM instances are Zonal, not Global resources.<br>
    _A opção D está incorreta. As instâncias de VM são zonais e não globais._

---

5. A new team member has joined your project. You need to grant him permission to access a few Google Cloud resources through IAM. How can you grant permission to your new team member so that he can access the required Google Cloud resources?<br>
    _Um novo membro da equipe se juntou ao seu projeto. Você precisa conceder permissão a ele para acessar alguns recursos do Google Cloud por meio do IAM. Como você pode conceder permissão ao novo membro da equipe para que ele possa acessar os recursos necessários do Google Cloud?_

    :black_large_square: Directly grant the permissions to access the resources as required.

    :white_check_mark: Grant role to the team member to access the resources as required.

    :black_large_square: Grant IAM policy to the team member to access the resources as required.

    :black_large_square: Give pre-authenticated URLs so that the new team member can access the required resources.

    > Option A is incorrect. In IAM, permissions are not granted directly to the team member to access resources.<br>
    _A opção A está incorreta. No IAM, as permissões não são concedidas diretamente ao membro da equipe para acessar recursos._

    > Option B is correct. The permissions are grouped into roles, and roles can be granted to the team member to access the resources.<br>
    _A opção B está correta. As permissões são agrupadas em funções e as funções podem ser concedidas ao membro da equipe para acessar os recursos._

    > Option C is incorrect. This is an incorrect statement. IAM policy is attached to resources, defines and enforces what roles are granted to which members and the policy.<br>
    _A opção C está incorreta. Esta é uma afirmação incorreta. A política do IAM é anexada aos recursos, define e impõe quais funções são concedidas a quais membros e à política._

    > Option D is incorrect. Pre-authenticated URLs are not a valid option to provide access to the resources.<br>
    _A opção D está incorreta. URLs pré-autenticados não são uma opção válida para fornecer acesso aos recursos._

---

6. How many parent(s) can one resource have?<br>
    _Quantos pais um recurso pode ter?_

    :white_check_mark: 1

    :black_large_square: 2

    :black_large_square: 3

    :black_large_square: Depends on the resource type

    > Option A is correct. Each resource has exactly one parent.<br>
    _A opção A está correta. Cada recurso tem exatamente um pai._

    > Option D is incorrect. Each resource has exactly one parent and does not depend on the resource type.<br>
    _A opção D está incorreta. Cada recurso possui exatamente um pai e não depende do tipo de recurso._

---

7. Your organization has opted for an Enhanced support offering. You have created a support case. The current status of the support case is “In progress Google engineering”. What does support case status of “In progress Google engineering” mean?<br>
    _Sua organização optou por uma oferta de suporte aprimorado. Você criou um caso de suporte. O status atual do caso de suporte é “Engenharia do Google em andamento”. O que significa o status do caso de suporte "Engenharia do Google em andamento"?_

    :black_large_square: The case is assigned to one of Google’s cloud engineers.

    :black_large_square: The support case is being worked upon by Google Cloud Customer care engineers.

    :white_check_mark: The support case is being investigated by Google product engineers.

    :black_large_square: The support case is being investigated by another Google engineer team.

    > Option A is incorrect. When the case is assigned to one of Google cloud engineers, the status of the support case is “Assigned”.<br>
    _A opção A está incorreta. Quando o caso é atribuído a um dos engenheiros de nuvem do Google, o status do caso de suporte é “Atribuído”._

    > Option B is incorrect. When the support case is being worked upon by Google Cloud Customer care engineers, the status of the support case is “In progress Cloud Customer Care”.<br>
    _A opção B está incorreta. Quando o caso de suporte está sendo trabalhado pelos engenheiros de atendimento ao cliente do Google Cloud, o status do caso de suporte é “Em andamento Cloud Customer Care”._

    > Option C is correct. When the support case is being investigated by Google product engineers, the status of the support case is “In progress Google engineering”.<br>
    _A opção C está correta. Quando o caso de suporte está sendo investigado pelos engenheiros de produto do Google, o status do caso de suporte é “Engenharia do Google em andamento”._

    > Option D is incorrect. When the support case is being investigated by another Google engineer team, the status of the support case is “In progress Google other.”<br>
    _A opção D está incorreta. Quando o caso de suporte estiver sendo investigado por outra equipe de engenheiros do Google, o status do caso de suporte será “Em andamento, outro Google”._

---

8. While creating a Support Case and describing the issue, which of the below problem types would you select for ‘momentary problems’?<br>
    _Ao criar um caso de suporte e descrever o problema, quais dos tipos de problemas abaixo você selecionaria para “problemas momentâneos”?_

    :black_large_square: Intermittent

    :white_check_mark: Transient

    :black_large_square: Consistent

    :black_large_square: Recurring
        - 

    > Option A is incorrect. Intermittent problems occur randomly without a regular failure pattern.<br>
    _A opção A está incorreta. Problemas intermitentes ocorrem aleatoriamente sem um padrão de falha regular._

    > Option B is correct. For momentary problems, the appropriate problem type is Transient.<br>
    _A opção B está correta. Para problemas momentâneos, o tipo de problema apropriado é Transiente._

    > Option C is incorrect. Consistent problems are problems that fail completely.<br>
    _A opção C está incorreta. Problemas consistentes são problemas que falham completamente._

    > Option D is incorrect. Recurring is an invalid problem type.<br>
    _A opção D está incorreta. Recorrente é um tipo de problema inválido._

---

9. You are implementing security for and plan to store API keys and certificates used across your Google cloud. Which of the below will you plan to use?<br>
    _Você está implementando segurança e planeja armazenar chaves de API e certificados usados ​​em sua nuvem do Google. Qual das opções abaixo você planeja usar?_

    :white_check_mark: Secret Manager

    :black_large_square: Cloud Key Management

    :black_large_square: Security command center

    :black_large_square: A & B

    > Option A is Correct. A secret manager can be used to store API keys, passwords, and certificates.<br>
    _A opção A está correta. Um gerenciador de segredos pode ser usado para armazenar chaves de API, senhas e certificados._

    > Option B is Incorrect. Cloud Key Management helps manage encryption keys and cannot be used for storing API keys and certificates.<br>
    _A opção B está incorreta. O Cloud Key Management ajuda a gerenciar chaves de criptografia e não pode ser usado para armazenar chaves de API e certificados._

    > Option C is Incorrect. The security command center cannot be used for storing API keys and certificates, but it is appropriate to be used to defend Google cloud assets against threats.<br>
    _A opção C está incorreta. O centro de comando de segurança não pode ser usado para armazenar chaves de API e certificados, mas é apropriado para defender os ativos em nuvem do Google contra ameaças._

---

10. Your client, a newly set up startup company, wants to opt for the cheapest customer care support plan that provides phone support for billing issues. Which support plan would you suggest to your client ensuring that the proposed plan is the most cost-efficient?<br>
    _Seu cliente, uma empresa iniciante recém-criada, deseja optar pelo plano de suporte de atendimento ao cliente mais barato que forneça suporte por telefone para questões de faturamento. Qual plano de suporte você sugeriria ao seu cliente, garantindo que o plano proposto seja o mais econômico?_

    :white_check_mark: Basic Support

    :black_large_square: Standard Support

    :black_large_square: Enhanced Support

    :black_large_square: Premium Support

    > Option A is correct. Basic support from Google Cloud provides phone support for billing issues only along with case and chat support. Basic support is included with Google Cloud subscription, and there are no additional charges. Hence, this is the correct choice.<br>
    _A opção A está correta. O suporte básico do Google Cloud oferece suporte por telefone apenas para problemas de faturamento, juntamente com suporte por caso e chat. O suporte básico está incluído na assinatura do Google Cloud e não há cobranças adicionais. Portanto, esta é a escolha correta._

    > Option B is incorrect. Although Standard support provides phone support for billing issues, it’s an incorrect choice since it is a paid plan. The scenario wants us to identify the most cost-efficient support plan.<br>
    _A opção B está incorreta. Embora o suporte padrão forneça suporte telefônico para questões de cobrança, é uma escolha incorreta, pois é um plano pago. O cenário quer que identifiquemos o plano de suporte com melhor relação custo-benefício._

    > Option C is incorrect. Although Enhanced support provides phone support for billing issues, it’s an incorrect choice since it is a paid plan. The scenario wants us to identify the most cost-efficient support plan.<br>
    _A opção C está incorreta. Embora o suporte avançado forneça suporte telefônico para problemas de cobrança, é uma escolha incorreta, pois é um plano pago. O cenário quer que identifiquemos o plano de suporte com melhor relação custo-benefício._

    > Option D is incorrect. Although Premium support provides phone support for billing issues, it’s an incorrect choice since it is a paid plan. The scenario wants us to identify the most cost-efficient support plan.<br>
    _A opção D está incorreta. Embora o suporte Premium forneça suporte telefônico para questões de cobrança, é uma escolha incorreta, pois é um plano pago. O cenário quer que identifiquemos o plano de suporte com melhor relação custo-benefício._

--- 

11. Which of the below disk types is not backed by Solid State Drives (SSD)?<br>
    _Qual dos tipos de disco abaixo não é compatível com unidades de estado sólido (SSD)?_

    :white_check_mark: Standard persistent disks (pd-standard)

    :black_large_square: Balanced persistent disks (pd-balanced)

    :black_large_square: SSD persistent disks (pd-ssd)

    :black_large_square: Extreme persistent disks (pd-extreme)

    > Option A is correct. Standard persistent disks (pd-standard) are backed by HDD (standard Hard Disk Drive). Hence, this option is Correct.<br>
    _A opção A está correta. Discos persistentes padrão (padrão pd) são suportados por HDD (unidade de disco rígido padrão). Portanto, esta opção está correta._

    > Option B is incorrect. Balanced persistent disks (pd-balanced) are backed by solid-state drives (SSD).<br>
    _A opção B está incorreta. Discos permanentes balanceados (balanceados por pd) são apoiados por unidades de estado sólido (SSD)._

    > Option C is incorrect. SSD persistent disks (pd-ssd) are backed by solid-state drives (SSD).<br>
    _A opção C está incorreta. Os discos permanentes SSD (pd-ssd) são apoiados por unidades de estado sólido (SSD)._

    > Option D is incorrect. Extreme persistent disks (pd-extreme) are backed by solid-state drives (SSD).<br>
    _A opção D está incorreta. Os discos persistentes extremos (pd-extreme) são apoiados por unidades de estado sólido (SSD)._

---

12. As part of your workload, a VM instance runs a SQL server, and another VM is being used as a license manager. Given the criticality of SQL Server and license manager, you need to ensure that these instances run indefinitely and do not get deleted. How can these VMs be protected from deletion?<br>
    _Como parte da sua carga de trabalho, uma instância de VM executa um servidor SQL e outra VM está sendo usada como gerenciador de licenças. Dada a criticidade do SQL Server e do gerenciador de licenças, você precisa garantir que essas instâncias sejam executadas indefinidamente e não sejam excluídas. Como essas VMs podem ser protegidas contra exclusão?_

    :white_check_mark: Enable “delete protection” feature.

    :black_large_square: Enable “no delete” feature.

    :black_large_square: Enable “restrict delete” feature.

    :black_large_square: Enable “run continuous” feature.

    > Option A is correct. To protect the VMs from being deleted, the “delete protection” feature needs to be enabled.<br>
    _A opção A está correta. Para proteger as VMs contra exclusão, o recurso “proteção contra exclusão” precisa ser habilitado._

    > Option B, C and D is incorrect. The “no delete” feature is an invalid option.<br>
    _As opções B, C e D estão incorretas. O recurso “não excluir” é uma opção inválida._

---

13. Which of the resources listed below is an ideal choice for a Persistent Disk snapshot? (Choose 2)<br>
    _Qual dos recursos listados abaixo é a escolha ideal para um snapshot de disco permanente?_

    :white_check_mark: Single disk backup

    :white_check_mark: Differential backup

    :black_large_square: Multiple disk backup

    :black_large_square: VM Instance configuration

    :black_large_square: Instance cloning and replication

---

14. Which Google Cloud product would be best suited to serve as a metadata inventory service, enabling customers to have a view of all the GCP and Anthos assets across projects and services?<br>
    _Qual produto do Google Cloud seria mais adequado para servir como serviço de inventário de metadados, permitindo que os clientes tenham uma visão de todos os ativos do GCP e do Anthos em projetos e serviços?_

    :black_large_square: Access Transparency & Access Approval

    :black_large_square: Binary Authorization

    :white_check_mark: Cloud Asset Inventory

    :black_large_square: Confidential Computing

    > Option A is incorrect. Access Transparency & Access Approval help provide visibility and control by facilitating admin access logs and approval controls.<br>
    _A opção A está incorreta. A transparência e a aprovação de acesso ajudam a fornecer visibilidade e controle, facilitando registros de acesso de administrador e controles de aprovação._

    > Option B is incorrect. Binary Authorization helps ensure deployment of trusted container images on Google Kubernetes Engine (GKE) or Cloud Run.<br>
    _A opção B está incorreta. A autorização binária ajuda a garantir a implantação de imagens de contêiner confiáveis ​​no Google Kubernetes Engine (GKE) ou Cloud Run._

    > Option C is correct. Cloud Asset Inventory is a metadata inventory service that facilitates customers to have a view of all the GCP and Anthos assets across projects and services, along with enabling them to monitor and analyze all the GCP and Anthos assets across projects and services.<br>
    _A opção C está correta. Cloud Asset Inventory é um serviço de inventário de metadados que permite aos clientes ter uma visão de todos os ativos do GCP e do Anthos em projetos e serviços, além de permitir que eles monitorem e analisem todos os ativos do GCP e do Anthos em projetos e serviços._

    > Option D is incorrect. Confidential Computing helps customers encrypt sensitive data while the data is in-use.<br>
    _A opção D está incorreta. A Computação Confidencial ajuda os clientes a criptografar dados confidenciais enquanto os dados estão em uso._

---

15. Which Google Cloud AI product helps classify unstructured text and sentiment analysis?<br>
    _Qual produto de IA do Google Cloud ajuda a classificar texto não estruturado e análise de sentimento?_

    :black_large_square: Vertex AI

    :black_large_square: Cloud Translation

    :white_check_mark: Natural Language AI

    :black_large_square: Dialogflow

    > Option A is incorrect. Vertex AI helps build, deploy and scale ML models faster within a unified AI platform.<br>
    _A opção A está incorreta. A Vertex AI ajuda a criar, implantar e dimensionar modelos de ML com mais rapidez em uma plataforma de IA unificada._

    > Option B is incorrect. Cloud Translation helps build multilingual applications with the help of machine translation.<br>
    _A opção B está incorreta. O Cloud Translation ajuda a criar aplicativos multilíngues com a ajuda da tradução automática._

    > Option C is correct. Natural Language AI is a Google Cloud AI product that helps classify unstructured text and performs sentiment analysis.<br>
    _A opção C está correta. Natural Language AI é um produto de IA do Google Cloud que ajuda a classificar textos não estruturados e realiza análises de sentimentos._

    > Option D is incorrect. Dialog flow helps build conversational applications.<br>
    _A opção D está incorreta. O fluxo de diálogo ajuda a criar aplicativos de conversação._

---

16. To ensure the developers’ code functionality in “Event-Driven Serverless Functions”, which Google Cloud product should a customer opt for?<br>
    _Para garantir a funcionalidade do código dos desenvolvedores em “Funções sem servidor orientadas a eventos”, qual produto do Google Cloud o cliente deve optar?_

    :white_check_mark: Cloud Functions

    :black_large_square: Cloud Serverless

    :black_large_square: Anthos Cluster

    :black_large_square: Cloud Foundation toolkit

    > Option A is correct. Cloud Functions help develop Event-Based serverless Functions.<br>
    _A opção A está correta. O Cloud Functions ajuda a desenvolver funções sem servidor baseadas em eventos._

    > Option B is incorrect. Cloud Serverless is an invalid option.<br>
    _A opção B está incorreta. Cloud Serverless é uma opção inválida._

    > Option C is incorrect. Anthos Cluster helps utilize Kubernetes across Multi-Cloud and Hybrid cloud environments.<br>
    _A opção C está incorreta. O Anthos Cluster ajuda a utilizar o Kubernetes em ambientes de nuvem híbrida e multinuvem._

    > Option D is incorrect. Cloud foundation toolkit helps provide Infrastructure as a code template<br>
    _A opção D está incorreta. O kit de ferramentas Cloud Foundation ajuda a fornecer infraestrutura como modelo de código_

---

17. Which Google Cloud product helps customers.<bn>
    _Which Google Cloud product helps customers._
    - Search and analyze log files through query statements?<br>
    _Pesquisar e analisar arquivos de log por meio de instruções de consulta?_
    - Use Public Write APIs to write custom logs from on-premise?<br>
    _Usar APIs de gravação pública para gravar logs personalizados localmente?_
    - Set alerts for notifying when a specific message appears in logs?<br>
    _Definir alertas para notificar quando uma mensagem específica aparecer nos logs?_

    :white_check_mark: Cloud Logging

    :black_large_square: Cloud Debugger

    :black_large_square: Cloud Trace

    :black_large_square: Cloud Monitoring

    > Option A is correct. Cloud Logging helps in the real-time analysis and management of logs.<br>
    _A opção A está correta. O Cloud Logging ajuda na análise e gerenciamento de logs em tempo real._

    > Option B is incorrect. Cloud Debugger helps in the investigation of code’s behavior in production.<br>
    _A opção B está incorreta. Cloud Debugger auxilia na investigação do comportamento do código em produção._

    > Option C is incorrect. Cloud Trace helps identify bottlenecks in production.<br>
    _A opção C está incorreta. O Cloud Trace ajuda a identificar gargalos na produção._

    > Option D is incorrect. Cloud Monitoring facilitates the collection of metrics, creating visualizations for metrics pertaining to applications and Infrastructure’s availability, performance, and health.<br>
    _A opção D está incorreta. O Cloud Monitoring facilita a coleta de métricas, criando visualizações de métricas relativas a aplicações e disponibilidade, desempenho e integridade de infraestrutura._

---

18. Which of the below features of Pub/Sub allows offline examination and debugging of messages to ensure no-delay processing of other messages?<br>
    _Qual dos recursos abaixo do Pub/Sub permite o exame e a depuração off-line de mensagens para garantir o processamento sem atraso de outras mensagens?_

    :black_large_square: Exactly once processing

    :black_large_square: Seek and replay

    :white_check_mark: Dead Letter topics

    :black_large_square: Filtering
        - 

    > Option A is Incorrect. Exactly once processing ensures that the Pub/Sub stream is processed exactly once.<br>
    _A opção A está incorreta. O processamento exatamente uma vez garante que o stream do Pub/Sub seja processado exatamente uma vez._

    > A opção B está incorreta. O recurso de busca e reprodução do Pub/Sub pode reprocessar mensagens facilitando o retrocesso pontual do backlog.<br>
    _A opção B está incorreta. O recurso de busca e reprodução do Pub/Sub pode reprocessar mensagens facilitando o retrocesso pontual do backlog._

    > Option C is Correct. It allows offline examination and debugging of messages to ensure no-delay processing of other messages.<br>
    _A opção C está correta. Ele permite o exame offline e a depuração de mensagens para garantir o processamento sem atraso de outras mensagens._

    > Option D is Incorrect. Filtering enables message filtering based on message attributes.<br>
    _A opção D está incorreta. A filtragem permite a filtragem de mensagens com base nos atributos da mensagem._

---

19. Which of the below-listed use cases should Local SSD be used for?<br>
    _Para quais dos casos de uso listados abaixo o SSD local deve ser usado?_

    :black_large_square: Genome sequencing

    :white_check_mark: Media rendering

    :black_large_square: Data archiving

    :white_check_mark: Use as cache

    :black_large_square: Batch Jobs

    > Option A is Incorrect. Since Genome sequencing requires performing analysis and needs speed, scalabiity and security, filestore is most apt.<br>
    _A opção A está incorreta. Como o sequenciamento do genoma requer a realização de análises e precisa de velocidade, escalabilidade e segurança, o filestore é o mais adequado._

    > Option B is Correct. Local SSD is appropriate to be used for Media rendering.<br>
    _A opção B está correta. O SSD local é apropriado para ser usado para renderização de mídia._

    > Option C is Incorrect. Cold storage is most optimal for data archiving.<br>
    _A opção C está incorreta. O armazenamento frio é ideal para arquivamento de dados._

    > Option D is Correct. Local SSD is the most optimal choice for being used as a cache as it provides high IOPS and very low latency.<br>
    _A opção D está correta. O SSD local é a escolha ideal para ser usado como cache, pois fornece IOPS alto e latência muito baixa._

    > Option E is Incorrect. Preemptible VMs are appropriate for batch jobs.<br>
    _A opção E está incorreta. VMs preemptivas são apropriadas para trabalhos em lote._

---

20. An issue is reported in the code deployed in the production environment. To diagnose the issue, your developer requires injecting a new logging statement and taking a snapshot of the state of running the application. How can this be done?<br>
    _Um problema é relatado no código implantado no ambiente de produção. Para diagnosticar o problema, seu desenvolvedor exige a injeção de uma nova instrução de registro e a captura de um instantâneo do estado de execução do aplicativo. Como isso pode ser feito?_

    :black_large_square: Cloud Logging

    :black_large_square: Cloud Monitoring

    :black_large_square: Cloud Trace

    :white_check_mark: Cloud Debugger

    > Option A is Incorrect. Cloud logging helps in real-time management and analysis of logs.<br>
    _A opção A está incorreta. O registro em nuvem ajuda no gerenciamento e análise de logs em tempo real._

    > Option B is Incorrect. Cloud Monitoring helps to monitor the health, availability and performance of infrastructure and the configured application by producing metrics of help.<br>
    _A opção B está incorreta. O Cloud Monitoring ajuda a monitorar a integridade, a disponibilidade e o desempenho da infraestrutura e do aplicativo configurado, produzindo métricas de ajuda._

    > Option C is Incorrect. Cloud Trace is an offering from Google cloud that helps find production performance bottlenecks by collecting application’s latency data.<br>
    _A opção C está incorreta. Cloud Trace é uma oferta da nuvem do Google que ajuda a encontrar gargalos no desempenho da produção coletando dados de latência do aplicativo._

    > Option D is Correct. Cloud Debugger helps to investigate the behavior of code in production.<br>
    _A opção D está correta. O Cloud Debugger ajuda a investigar o comportamento do código em produção._