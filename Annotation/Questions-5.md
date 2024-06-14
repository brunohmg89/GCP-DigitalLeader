# Digital Leader

Reference (1): <https://certsqa.com/questions/?exam=Cloud-Digital-Leader/><br>
Reference (2): <https://www.itexams.com/exam/Cloud-Digital-Leader>

## Questions

1. How do Migrate for Compute Engine and Migrate for Anthos differ?<br>
    _Qual a diferença entre o Migrate for Compute Engine e o Migrate for Anthos?_

    :black_large_square: Unlike Migrate for Anthos, Migrate for Compute Engine assumes that the migration source is VMware vSphere.<br>
    _Ao contrário do Migrate for Anthos, o Migrate for Compute Engine pressupõe que a origem da migração seja o VMware vSphere._

    :black_large_square: Migrate for Compute Engine charges for ingress, but Migrate for Anthos does not.<br>
    _O Migrate for Compute Engine cobra pela entrada, mas o Migrate for Anthos não._

    :black_large_square: Migrate for Compute Engine is closed source, and Migrate for Anthos is open source.<br>
    _O Migrate for Compute Engine é de código fechado e o Migrate for Anthos é de código aberto._

    :white_check_mark: Migrate for Anthos migrates to containers, and Migrate for Compute Engine migrates to virtual machines.<br>
    _O Migrate for Anthos migra para contêineres e o Migrate for Compute Engine migra para máquinas virtuais._

    > Use Migrate to Containers to modernize traditional applications away from virtual machine (VM) instances and into native containers that run on Google Kubernetes Engine (GKE) or Cloud Run platform.<br>
    _Use o Migrate to Containers para modernizar aplicativos tradicionais de instâncias de máquinas virtuais (VM) e para contêineres nativos executados no Google Kubernetes Engine (GKE) ou na plataforma Cloud Run.

---

2. Your large and frequently changing organization's user information is stored in an on-premises LDAP database. The database includes user passwords and group and organization membership. How should your organization provision Google accounts and groups to access Google Cloud resources?<br>
    _As informações de usuário da sua organização grande e que muda frequentemente são armazenadas em um banco de dados LDAP local. O banco de dados inclui senhas de usuários e membros de grupos e organizações. Como sua organização deve provisionar contas e grupos do Google para acessar os recursos do Google Cloud?_

    :black_large_square: Replicate the LDAP infrastructure on Compute Engine

    :black_large_square: Use the Firebase Authentication REST API to create users

    :white_check_mark: Use Google Cloud Directory Sync to create users

    :black_large_square: Use the Identity Platform REST API to create users

    > You can run a single instance of Google Cloud Directory Sync to synchronize user accounts and groups to Google Cloud.<br>
    _Você pode executar uma única instância do Google Cloud Directory Sync para sincronizar contas de usuários e grupos com o Google Cloud._

---

3. Your organization recently migrated its compute workloads to Google Cloud. You want these workloads in Google Cloud to privately and securely access your large volume of on-premises data, and you also want to minimize latency. What should your organization do?<br>
    _Sua organização migrou recentemente as cargas de trabalho de computação para o Google Cloud. Você deseja que essas cargas de trabalho no Google Cloud acessem de maneira privada e segura seu grande volume de dados locais e também deseja minimizar a latência. O que sua organização deve fazer?_

    :black_large_square: Use Storage Transfer Service to securely make your data available to Google Cloud

    :white_check_mark: Create a VPC between your on-premises data center and your Google resources

    :black_large_square: Peer your on-premises data center to Google's Edge Network

    :black_large_square: Use Transfer Appliance to securely make your data available to Google Cloud

---

4. Your organization consists of many teams. Each team has many Google Cloud projects. Your organization wants to simplify the management of identity and access policies for these projects. How can you group these projects to meet this goal?<br>
    _Sua organização consiste em muitas equipes. Cada equipe tem muitos projetos do Google Cloud. Sua organização deseja simplificar o gerenciamento de políticas de identidade e acesso para esses projetos. Como você pode agrupar esses projetos para atingir esse objetivo?_

    :black_large_square: Group each team's projects into a separate domain<br>
    _Agrupe os projetos de cada equipe em um domínio separado_

    :white_check_mark: Assign labels based on the virtual machines that are part of each team's projects<br>
    _Atribua rótulos com base nas máquinas virtuais que fazem parte dos projetos de cada equipe_

    :black_large_square: Use folders to group each team's projects<br>
    _Use pastas para agrupar os projetos de cada equipe_

    :black_large_square: Group each team's projects into a separate organization node<br>
    _Agrupe os projetos de cada equipe em um nó de organização separado_

---

5. An organization needs to categorize text-based customer reviews on their website using a pre-trained machine learning model. Which Google Cloud product or service should the organization use?<br>
    _Uma organização precisa categorizar avaliações de clientes baseadas em texto em seu site usando um modelo de aprendizado de máquina pré-treinado. Qual produto ou serviço do Google Cloud a organização deve usar?_

    :black_large_square: Cloud Natural Language API

    :black_large_square: Dialogflow

    :white_check_mark: Recommendations AI

    :black_large_square: TensorFlow

    > Take advantage of Google's expertise in recommendations, powered by state-of-the-art machine learning models. Provide effective and real-time personalization with the recommendations capability (formerly Recommendations AI) of Vertex AI Search. Earn your customers’ trust and loyalty by proving how well you understand them. Google delivers content to billions across consumer facing platforms including Google Ads, Google Search, and YouTube.<br>
    _Aproveite a experiência do Google em recomendações, com base em modelos de aprendizado de máquina de última geração. Forneça personalização eficaz e em tempo real com o recurso de recomendações (anteriormente Recommendations AI) do Vertex AI Search. Conquiste a confiança e a lealdade de seus clientes, provando o quão bem você os entende. O Google fornece conteúdo para bilhões de pessoas em plataformas voltadas para o consumidor, incluindo Google Ads, Pesquisa Google e YouTube._

---

6. An organization is planning its cloud expenditure. What should the organization do to control costs?<br>
    _Uma organização está planejando seus gastos com nuvem. O que a organização deve fazer para controlar os custos?_

    :black_large_square: Consider cloud resource costs as capital expenditure in annual planning.

    :black_large_square: Use only cloud resources; they have no cloud infrastructure costs.

    :white_check_mark: Review cloud resource costs frequently because costs depend on usage.

    :black_large_square: Assess cloud resources costs only when SLO is not met by their cloud provider.

---

7. An organization is searching for an open-source machine learning platform to build and deploy their own custom machine learning applications using TPUs. Which Google Cloud product or service should the organization use?<br>
    _Uma organização está procurando uma plataforma de aprendizado de máquina de código aberto para criar e implantar seus próprios aplicativos personalizados de aprendizado de máquina usando TPUs. Qual produto ou serviço do Google Cloud a organização deve usar?_

    :black_large_square: TensorFlow

    :black_large_square: BigQuery ML

    :black_large_square: Vision API

    :white_check_mark: AutoML Vision

---

8. What is an example of unstructured data that organizations can capture from social media?<br>
    _Qual é um exemplo de dados não estruturados que as organizações podem capturar nas redes sociais?_

    :black_large_square: Post comments

    :black_large_square: Tagging

    :white_check_mark: Profile picture

    :black_large_square: Location

---

9. An organization relies on online seasonal sales for the majority of their annual revenue. Why should the organization use App Engine for their customer app?<br>
    _Uma organização depende de vendas sazonais online para a maior parte de sua receita anual. Por que a organização deve usar o App Engine no aplicativo do cliente?_

    :black_large_square: Automatically adjusts physical inventory in real time<br>
    _Ajusta automaticamente o inventário físico em tempo real_

    :black_large_square: Autoscales during peaks in demand<br>
    _Escalonamento automático durante picos de demanda_

    :white_check_mark: Runs maintenance during seasonal sales<br>
    _Executa manutenção durante vendas sazonais_

    :black_large_square: Recommends the right products to customers<br>
    _Recomenda os produtos certos aos clientes_

---

10. An organization is using machine learning to make predictions. One of their datasets mistakenly includes mislabeled data. How will the prediction be impacted?<br>
    _Uma organização está usando aprendizado de máquina para fazer previsões. Um de seus conjuntos de dados inclui erroneamente dados rotulados incorretamente. Como a previsão será impactada?_

    :black_large_square: Increased risk of privacy leaks

    :white_check_mark: Increased risk of inaccuracy

    :black_large_square: Decreased model compatibility

    :black_large_square: Decreased model training time

---

11. Global organization is developing an application to manage payments and online bank accounts in multiple regions. Each transaction must be handled consistently in their database, and they anticipate almost unlimited growth in the amount of data stored. Which Google Cloud product should the organization choose?<br>
    _A organização global está desenvolvendo um aplicativo para gerenciar pagamentos e contas bancárias online em diversas regiões. Cada transação deve ser tratada de forma consistente em seu banco de dados e eles prevêem um crescimento quase ilimitado na quantidade de dados armazenados. Qual produto do Google Cloud a organização deve escolher?_

    :black_large_square: Cloud SQL

    :white_check_mark: Cloud Spanner

    :black_large_square: Cloud Storage

    :black_large_square: BigQuery

---

12. An organization has servers running mission-critical workloads on-premises around the world. They want to modernize their infrastructure with a multi-cloud architecture. What benefit could the organization experience?<br>
    _Uma organização possui servidores que executam cargas de trabalho de missão crítica no local em todo o mundo. Eles querem modernizar a sua infraestrutura com uma arquitetura multi-cloud. Que benefícios a organização poderia experimentar?_

    :black_large_square: Ability to disable regional network connectivity during cyber attacks<br>
    _Capacidade de desativar a conectividade de rede regional durante ataques cibernéticos_

    :black_large_square: Ability to keep backups of their data on-premises in case of failure<br>
    _Capacidade de manter backups de seus dados no local em caso de falha_

    :white_check_mark: Full management access to their regional infrastructure<br>
    _Acesso total de gerenciamento à sua infraestrutura regional_

    :black_large_square: Reduced likelihood of system failure during high demand events<br>
    _Probabilidade reduzida de falha do sistema durante eventos de alta demanda_

---

13. An organization needs to run frequent updates for their business app. Why should the organization use Google Kubernetes Engine (GKE)?<br>
    _Uma organização precisa executar atualizações frequentes em seu aplicativo comercial. Por que a organização deveria usar o Google Kubernetes Engine (GKE)?_

    :black_large_square: Customer expectations can be adjusted without using marketing tools<br>
    _As expectativas do cliente podem ser ajustadas sem o uso de ferramentas de marketing_

    :black_large_square: Seamless changes can be made without causing any application downtime.<br>
    _Mudanças perfeitas podem ser feitas sem causar tempo de inatividade do aplicativo._

    :black_large_square: GKE handles version control seamlessly and out of the box<br>
    _O GKE lida com o controle de versão de maneira integrada e pronta para uso_

    :white_check_mark: GKE is well suited for all monolithic applications<br>
    _O GKE é adequado para todos os aplicativos monolíticos_

---

14. You are working with a Financial giant looking to adopt a public Cloud. The IT advisory group of the company has indicated the intent that they want cloud infrastructure to be solely operated for them and hosted internally. Which of the below options is the right choice for the organization?<br>
    _Você está trabalhando com um gigante financeiro que busca adotar uma nuvem pública. O grupo consultivo de TI da empresa indicou a intenção de que a infraestrutura em nuvem seja operada exclusivamente para eles e hospedada internamente. Qual das opções abaixo é a escolha certa para a organização?_

    :black_large_square: Public Cloud
    
    :white_check_mark: Private Cloud
        
    :black_large_square: Hybrid Cloud
        
    :black_large_square: Any of the above

    > Option A is incorrect because the Public Cloud deployment model generally offers services to multiple customers unless opted explicitly for. Public Cloud is also not a correct choice because Public Cloud will not be hosted internally.<br>
    _A opção A está incorreta porque o modelo de implantação de nuvem pública geralmente oferece serviços a vários clientes, a menos que opte explicitamente por isso. A Nuvem Pública também não é uma escolha correta porque a Nuvem Pública não será hospedada internamente._

    > Option B is correct because the Private Cloud deployment model caters to the below requirements:<br>
    > - Solely operated for one customer
    > - Hosted internally for the customer

    > _A opção B está correta porque o modelo de implantação de nuvem privada atende aos requisitos abaixo:_
    > - _Operado exclusivamente para um cliente_
    > - _Hospedado internamente para o cliente_
    
    > Option C is incorrect as this option comprises the combination of both the Private and Public Cloud.<br>
    _A opção C está incorreta, pois esta opção compreende a combinação da Nuvem Privada e Pública._

    > Option D is incorrect as Public Cloud and Hybrid one are not a suitable choice.<br>
    _A opção D está incorreta, pois a nuvem pública e a híbrida não são uma escolha adequada._

---

15. You are a Senior Project Manager working on a Request for Proposal (RFP). Architects have completed the high-level architecture of the proposed solution. In addition, this proposed solution includes a section that details how the implementation will ensure that the client application and data will be available in case of unavailability of a particular data center. How will you put this section in your RFP?<br>
    _Você é um gerente de projeto sênior trabalhando em uma solicitação de proposta (RFP). Os arquitetos concluíram a arquitetura de alto nível da solução proposta. Além disso, esta solução proposta inclui uma seção que detalha como a implementação garantirá que a aplicação cliente e os dados estarão disponíveis em caso de indisponibilidade de um determinado data center. Como você colocará esta seção em sua RFP?_

    :white_check_mark: Highlight this as a “Business Continuity Plan.”
        
    :black_large_square: Highlight this as “Proactive Monitoring.”
        
    :black_large_square: Highlight this as a “Continuous Improvement Plan.”
        
    :black_large_square: Highlight this as an “Automation” section.

    > Option A is correct. As this part of the solution details how the application and data will be available in case of unavailability of a particular data center, we will need to highlight this as a Business Continuity Plan.<br>
    _A opção A está correta. Como esta parte da solução detalha como a aplicação e os dados estarão disponíveis em caso de indisponibilidade de um determinado data center, precisaremos destacá-lo como um Plano de Continuidade de Negócios._

    > Option B is incorrect. Proactive monitoring is the continuous monitoring of various alerts and monitoring application behavior to identify any potential problem. In the given scenario, the solution discusses ensuring business continuity in case of a particular data center unavailability.<br>
    _A opção B está incorreta. O monitoramento proativo é o monitoramento contínuo de vários alertas e o monitoramento do comportamento do aplicativo para identificar qualquer problema potencial. No cenário determinado, a solução discute a garantia da continuidade dos negócios no caso de indisponibilidade de um determinado data center._

    > Option C is incorrect. The Continuous Improvement Plan details efforts to improve ongoing services that are being provided.<br>
    _A opção C está incorreta. O Plano de Melhoria Contínua detalha os esforços para melhorar os serviços contínuos que estão sendo prestados._

    > Option D is incorrect. Automation plan details the plans of automation to be implemented and not on Business continuity.<br>
    _A opção D está incorreta. O plano de automação detalha os planos de automação a serem implementados e não de continuidade do negócio._

---

16. Which of the below is a Google Cloud PaaS product offering?<br>
    _Qual das opções abaixo é uma oferta de produto PaaS do Google Cloud?_

    :black_large_square: Google Workspace

    :white_check_mark: Google App Engine
        
    :black_large_square: Google Compute Engine
        
    :black_large_square: Persistent Disk

    > Option A is incorrect. Google Workspace is a SaaS offering.<br>
    _A opção A está incorreta. O Google Workspace é uma oferta SaaS._

    > Option B is correct. Google App Engine is a PaaS offering.<br>
    _A opção B está correta. O Google App Engine é uma oferta PaaS._

    > Option C is incorrect. Google Compute Engine is an IaaS offering.<br>
    _A opção C está incorreta. O Google Compute Engine é uma oferta IaaS._

    > Option D is incorrect. Persistent Disk is an IaaS offering.<br>
    _A opção D está incorreta. O disco permanente é uma oferta de IaaS._

---

17. Which Cloud Computing models require customers to own Operating System patching?<br>
    _Quais modelos de computação em nuvem exigem que os clientes possuam patches do sistema operacional?_

    :white_check_mark: IaaS (Infrastructure as a Service)

    :black_large_square: PaaS (Platform as a Service)
        
    :black_large_square: SaaS (Software as a Service)
        
    :black_large_square: FSaaS (FileSystem as a Service)

    > Option A is correct. The IaaS model requires customers to own the patching of the servers.<br>
    _A opção A está correta. O modelo IaaS exige que os clientes sejam proprietários dos patches dos servidores._

    > Option B is incorrect. Cloud provider is responsible for patching the Operating System for their PaaS offerings.<br>
    _A opção B está incorreta. O provedor de nuvem é responsável por corrigir o sistema operacional para suas ofertas de PaaS._

    > Option C is incorrect. Cloud provider is responsible for patching the Operating System for their SaaS offerings.<br>
    _A opção C está incorreta. O provedor de nuvem é responsável por corrigir o sistema operacional de suas ofertas de SaaS._

    > Option D is incorrect. FSaaS is not a valid Cloud Computing model.<br>
    _A opção D está incorreta. FSaaS não é um modelo válido de computação em nuvem._

---

18. A startup working on self-driving vehicles applications requires to collect data from vehicles on-road. Which offering from Cloud providers will help the organization transmit the data from vehicles currently on-road for data collection?<br>
    _Uma startup que trabalha em aplicações de veículos autônomos precisa coletar dados de veículos na estrada. Qual oferta dos provedores de nuvem ajudará a organização a transmitir os dados dos veículos atualmente em circulação para coleta de dados?_

    :black_large_square: Machine Learning product offering

    :white_check_mark: IoT product offering

    :black_large_square: Data Analytics product offering

    :black_large_square: Storage product offering


    > Option A is incorrect. Machine learning product offerings from Cloud providers enable organizations to build, deploy and scale the AI models.<br>
    _A opção A está incorreta. As ofertas de produtos de aprendizado de máquina de provedores de nuvem permitem que as organizações construam, implantem e dimensionem os modelos de IA._

    > Option B is correct. IoT offerings from Cloud providers help in data collection from the field, like collecting data from sensors including self-driving vehicles, farmlands, satellites etc.<br>
    _A opção B está correta. As ofertas de IoT de provedores de nuvem ajudam na coleta de dados em campo, como coleta de dados de sensores, incluindo veículos autônomos, fazendas, satélites, etc._

    > Option C is incorrect. Data Analytics offerings from Cloud providers help unlock big data potential by improving data analysis capabilities and eventually improving businesses’ decision-making.<br>
    _A opção C está incorreta. As ofertas de análise de dados dos provedores de nuvem ajudam a desbloquear o potencial do big data, melhorando os recursos de análise de dados e, eventualmente, melhorando a tomada de decisões das empresas._

    > Option D is incorrect. Storage product offerings from Cloud providers help facilitate storing of the data of various data types.<br>
    _A opção D está incorreta. As ofertas de produtos de armazenamento de provedores de nuvem ajudam a facilitar o armazenamento de vários tipos de dados._

---

19. Which of the Google cloud offerings for Virtual Machine offers block storage that is reliable and high performance?<br>
    _Qual das ofertas de nuvem do Google para máquinas virtuais oferece armazenamento em bloco confiável e de alto desempenho?_

    :black_large_square: Preemptible VMs

    :black_large_square: Cloud storage for Firebase

    :black_large_square: Local SSD

    :white_check_mark: Persistent Disk

    > Option A is Incorrect. Preemptible VMs are compute instances that are short-lived and are appropriate to be used for batch jobs.<br>
    _A opção A está incorreta. VMs preemptivas são instâncias de computação de curta duração e apropriadas para uso em trabalhos em lote._

    > Option B is Incorrect. Cloud storage for Firebase stores and serves content that is user generated on block storage.<br>
    _A opção B está incorreta. O armazenamento em nuvem para Firebase armazena e veicula conteúdo gerado pelo usuário no armazenamento em bloco._

    > Option C is Incorrect. Local SSD also offers high performance block storage but is attached locally.<br>
    _A opção C está incorreta. O SSD local também oferece armazenamento em bloco de alto desempenho, mas é conectado localmente._

    > Option D is Correct. Persistent disk from Google Cloud offers block storage that is reliable and high performance for Virtual Machines.<br>
    _A opção D está correta. O disco permanente do Google Cloud oferece armazenamento em blocos confiável e de alto desempenho para máquinas virtuais._

---

20. Which of the below could be implemented for fine-grained management and cost allocation using organizations in Google cloud?<br>
    _Qual das opções abaixo poderia ser implementada para gerenciamento refinado e alocação de custos usando organizações na nuvem do Google?_

    :black_large_square: Billing access control

    :black_large_square: Quotas

    :white_check_mark: Resource hierarchy

    :black_large_square: Budgets

    > Option A is Incorrect. Billing access control helps to enforce organizational policies at various levels in the resource hierarchy.<br>
    _A opção A está incorreta. O controle de acesso à cobrança ajuda a impor políticas organizacionais em vários níveis da hierarquia de recursos._

    > Option B is Incorrect. Quotas help to control the spending and unforeseen usage spikes proactively.<br>
    _A opção B está incorreta. As cotas ajudam a controlar proativamente os gastos e picos de uso imprevistos._

    > Option C is Correct. Resource hierarchy should be implemented for fine-grained management and cost allocation using organizations in Google cloud.<br>
    _A opção C está correta. A hierarquia de recursos deve ser implementada para gerenciamento refinado e alocação de custos usando organizações na nuvem do Google._

    > Option D is Incorrect. Budgets are most useful in performing the monitoring of the costs being incurred on google cloud.<br>
    _A opção D está incorreta. Os orçamentos são mais úteis para realizar o monitoramento dos custos incorridos no Google Cloud._