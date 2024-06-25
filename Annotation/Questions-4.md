# Digital Leader

Reference: <https://www.examtopics.com/exams/google/>

## Questions

1. Your organization is running all its workloads in a private cloud on top of a hypervisor. Your organization has decided it wants to move to Google Cloud as quickly as possible. Your organization wants minimal changes to the current environment, while using the maximum amount of managed services Google offers. What should your organization do?<br>
    _Sua organização está executando todas as suas cargas de trabalho em uma nuvem privada sobre um hipervisor. Sua organização decidiu que quer migrar para o Google Cloud o mais rápido possível. Sua organização deseja mudanças mínimas no ambiente atual e, ao mesmo tempo, usar o máximo de serviços gerenciados que o Google oferece. O que sua organização deve fazer?_

    :black_large_square: Migrate the workloads to Google Cloud VMware Engine

    :white_check_mark: Migrate the workloads to Compute Engine

    :black_large_square: Migrate the workloads to Bare Metal Solution

    :black_large_square: Migrate the workloads to Google Kubernetes Engine

    > Migrate for Compute Engine enables you to lift and shift workloads at scale to Google Cloud Compute Engine with minimal changes and risk.<br>
    _O Migrate for Compute Engine permite transferir cargas de trabalho em escala para o Google Cloud Compute Engine com alterações e riscos mínimos._

---

2. Your organization is releasing its first publicly available application in Google Cloud. The application is critical to your business and customers and requires a 2- hour SLA. How should your organization set up support to minimize costs?<br>
    _Sua organização está lançando o primeiro aplicativo disponível publicamente no Google Cloud. O aplicativo é fundamental para seus negócios e clientes e exige um SLA de 2 horas. Como sua organização deve configurar o suporte para minimizar custos?_
    
    :black_large_square: Enroll in Premium Support

    :white_check_mark: Enroll in Enhanced Support

    :black_large_square: Enroll in Standard Support

    :black_large_square: Enroll in Basic Support

    > Enhanced Support: Designed to provide fast response times, a robust set of services, and the technical support necessary for workloads in production. Ideal for workloads in production, with 1-hour response time.<br>
    _Suporte aprimorado: projetado para fornecer tempos de resposta rápidos, um conjunto robusto de serviços e o suporte técnico necessário para cargas de trabalho em produção. Ideal para cargas de trabalho em produção, com tempo de resposta de 1 hora._

---

3. Your organization offers public mobile apps and websites. You want to migrate to a Google Cloud-based solution for checking and maintaining your users' usernames and passwords and controlling their access to different resources based on their identity. Which should your organization choose?<br>
    _Sua organização oferece aplicativos móveis e sites públicos. Você deseja migrar para uma solução baseada no Google Cloud para verificar e manter os nomes de usuário e senhas dos seus usuários e controlar o acesso deles a diferentes recursos com base na identidade deles. Qual deve sua organização escolher?_
    
    :black_large_square: VPN tunnels

    :white_check_mark: Identity Platform

    :black_large_square: Compute Engine firewall rules

    :black_large_square: Private Google Access

    > An identity platform is a modern solution for managing the identities of users and devices in a centralized fashion.<br>
    _Uma plataforma de identidade é uma solução moderna para gerenciar identidades de usuários e dispositivos de forma centralizada._

---

4. Your organization runs an application on virtual machines in Google Cloud. This application processes incoming images. This activity takes hours to create a result  for each image. The workload for this application normally stays at a certain baseline level, but at regular intervals it spikes to a much greater workload. Your organization needs to control the cost to run this application. What should your organization do?<br>
    _Sua organização executa um aplicativo em máquinas virtuais no Google Cloud. Este aplicativo processa imagens recebidas. Esta atividade leva horas para criar um resultado para cada imagem. A carga de trabalho desse aplicativo normalmente permanece em um determinado nível de linha de base, mas em intervalos regulares aumenta para uma carga de trabalho muito maior. Sua organização precisa controlar o custo para executar este aplicativo. O que sua organização deve fazer?_
    
    :black_large_square: Purchase committed use discounts for the baseline load

    :black_large_square: Purchase committed use discounts for the expected spike load

    :white_check_mark: Leverage sustained use discounts for your virtual machines

    :black_large_square: Run the workload on preemptible VM instances

    > The idea of the Sustained Use discount is that the longer you run a VM instance in any given month, the bigger discount you will get from the list price.<br>
    _A ideia do desconto por uso prolongado é que quanto mais tempo você executar uma instância de VM em um determinado mês, maior será o desconto no preço de tabela._

---

5. Your organization is developing a plan for migrating to Google Cloud. What is a best practice when initially configuring your Google Cloud environment?<br>
    _Sua organização está desenvolvendo um plano de migração para o Google Cloud. Qual é a prática recomendada ao configurar inicialmente seu ambiente do Google Cloud?_

    :black_large_square: Create a project via Google Cloud Console per department in your company<br>
    _Crie um projeto por meio do Google Cloud Console por departamento da sua empresa_

    :white_check_mark: Define your resource hierarchy with an organization node on top<br>
    _Defina sua hierarquia de recursos com um nó de organização no topo_

    :black_large_square: Create projects based on team members' requests<br>
    _Crie projetos com base nas solicitações dos membros da equipe_

    :black_large_square: Make every member of your company the project owner<br>
    _Faça de cada membro da sua empresa o proprietário do projeto_

---

6. Your organization runs many workloads in different Google Cloud projects, each linked to the same billing account. Each project's workload costs can vary from month to month, but the overall combined cost of all projects is relatively stable. Your organization needs to optimize its cost. What should your organization do?<br>
    _Sua organização executa muitas cargas de trabalho em diferentes projetos do Google Cloud, cada um vinculado à mesma conta de faturamento. Os custos da carga de trabalho de cada projeto podem variar de mês para mês, mas o custo geral combinado de todos os projetos é relativamente estável. Sua organização precisa otimizar seus custos. O que sua organização deve fazer?_

    :black_large_square: Purchase a commitment per project for each project's usual minimum<br>
    _Adquira um compromisso por projeto para o mínimo habitual de cada projeto_

    :black_large_square: Create a billing account per project, and link each project to a different billing account<br>
    _Crie uma conta de faturamento por projeto e vincule cada projeto a uma conta de faturamento diferente_

    :white_check_mark: Turn on committed use discount sharing, and create a commitment for the combined usage<br>
    _Ative o compartilhamento de desconto por uso contínuo e crie um compromisso para o uso combinado_

    :black_large_square: Move all workloads from all different projects into one single consolidated project<br>
    _Mova todas as cargas de trabalho de todos os projetos diferentes em um único projeto consolidado_

    > Compute Engine provides resource-based committed use discounts (CUDs) for your predictable workloads to help you cut costs on resources that you need. You can purchase and renew resource-based committed use contracts or commitments in return for heavily discounted prices for VM usage.<br>
    _O Compute Engine oferece descontos por uso contínuo (CUDs, na sigla em inglês) baseados em recursos para suas cargas de trabalho previsíveis para ajudar você a reduzir custos com os recursos necessários. Você pode adquirir e renovar contratos ou compromissos de uso contínuo baseados em recursos em troca de preços com grandes descontos para uso de VM._

---

7. How should a multinational organization that is migrating to Google Cloud consider security and privacy regulations to ensure that it is in compliance with global standards?<br>
    _Como uma organização multinacional que está migrando para o Google Cloud deve considerar as regulamentações de segurança e privacidade para garantir que esteja em conformidade com os padrões globais?_

    :white_check_mark: Comply with data security and privacy regulations in each geographical region<br>
    _Cumpra os regulamentos de segurança e privacidade de dados em cada região geográfica_

    :black_large_square: Comply with regional standards for data security and privacy, because they supersede all international regulations<br>
    _Cumpra os padrões regionais de segurança e privacidade de dados, pois eles substituem todas as regulamentações internacionais_

    :black_large_square: Comply with international standards for data security and privacy, because they supersede all regional regulations<br>
    _Cumpra os padrões internacionais de segurança e privacidade de dados, pois eles substituem todas as regulamentações regionais_

    :black_large_square: Comply with regional data security regulations, because they're more complex than privacy standards<br>
    _Cumpra as regulamentações regionais de segurança de dados, porque elas são mais complexas que os padrões de privacidade_

---

8. Your organization wants to optimize its use of Google Cloud's discounts on virtual machine-based workloads. You plan to use 200 CPUs constantly for the next 3 years, and you forecast that spikes of up to 300 CPUs will occur approximately 30% of the time. What should you choose?<br>
    _Sua organização quer otimizar o uso dos descontos do Google Cloud em cargas de trabalho baseadas em máquinas virtuais. Você planeja usar 200 CPUs constantemente durante os próximos 3 anos e prevê que picos de até 300 CPUs ocorrerão aproximadamente 30% do tempo. O que você deve escolher?_

    :black_large_square: 1-year committed use discount for 200 CPUs

    :black_large_square: 3-year committed use discount for 300 CPUs

    :white_check_mark: 3-year committed use discount for 200 CPUs

    :black_large_square: Regular pay-as-you-go pricing

---

9. Your organization needs to minimize how much it pays for data traffic from the Google network to the internet. What should your organization do?<br>
    _Sua organização precisa minimizar quanto paga pelo tráfego de dados da rede do Google para a Internet. O que sua organização deve fazer?_

    :white_check_mark: Choose the Standard network service tier.

    :black_large_square: Choose the Premium network service tier.

    :black_large_square: Deploy Cloud VPN.

    :black_large_square: Deploy Cloud NAT.

    > There are some limitations when leveraging the Standard tier for its pricing benefits. At a high level, these include compliance needs around traffic traversing the public internet, as well as HTTP(S), SSL Proxy, TCP Proxy load-balancing, or usage of Cloud CDN. You can read about these in more detail here. After reviewing some of the recommendations, you’ll be empowered to review your services with your team and determine whether you can benefit from lower Standard Tier pricing without impacting the performance of your external-facing services.<br>
    _Existem algumas limitações ao aproveitar o nível Standard para obter benefícios de preços. Em alto nível, isso inclui necessidades de conformidade em torno do tráfego que atravessa a Internet pública, bem como HTTP(S), proxy SSL, balanceamento de carga de proxy TCP ou uso de Cloud CDN. Você pode ler sobre isso com mais detalhes aqui. Depois de analisar algumas das recomendações, você poderá revisar seus serviços com sua equipe e determinar se pode se beneficiar de preços mais baixos do nível Standard sem afetar o desempenho de seus serviços externos._

---

10. Your organization wants to migrate your on-premises environment to Google Cloud. The on-premises environment consists of containers and virtual machine instances. Which Google Cloud products can help to migrate the container images and the virtual machine disks?<br>
    _Sua organização quer migrar seu ambiente local para o Google Cloud. O ambiente local consiste em contêineres e instâncias de máquinas virtuais. Quais produtos do Google Cloud podem ajudar a migrar as imagens de contêiner e os discos das máquinas virtuais?_

    :black_large_square: Compute Engine and Filestore

    :white_check_mark: Artifact Registry and Cloud Storage

    :black_large_square: Dataflow and BigQuery

    :black_large_square: Pub/Sub and Cloud Storage

---

11. Your company security team manages access control to production systems using an LDAP directory group. How is this access control managed in the Google Cloud production project?<br>
    _A equipe de segurança da sua empresa gerencia o controle de acesso aos sistemas de produção usando um grupo de diretórios LDAP. Como esse controle de acesso é gerenciado no projeto de produção do Google Cloud?_

    :black_large_square: Assign the proper role to the Service Account in the project's IAM Policy<br>
    _Atribua a função adequada à conta de serviço na política IAM do projeto_

    :black_large_square: Grant each user the roles/iam.serviceAccountUser role on a service account that exists in the Google Group.<br>
    _Conceda a cada usuário o papel role/iam.serviceAccountUser em uma conta de serviço existente no Grupo do Google._

    :white_check_mark: Assign the proper role to the Google Group in the project's IAM Policy.<br>
    _Atribua a função adequada ao Grupo do Google na política IAM do projeto._

    :black_large_square: Create the project in a folder with the same name as the LDAP directory group.<br>
    _Crie o projeto em uma pasta com o mesmo nome do grupo de diretórios LDAP._

    > Let’s start at the very beginning. Google Cloud offers several ways to onboard users. Cloud Identity is a centralized hub for Google Cloud and G Suite to define, setup, and manage users and groups—think of Cloud Identity as a provisioning and authentication solution, whereas Cloud IAM is principally an authorization solution. Once they’re onboarded, you’ll be able to assign permissions to these users and groups in Google Cloud IAM to allow them access to resources.<br>
    _Vamos começar do início. O Google Cloud oferece várias maneiras de integrar usuários. O Cloud Identity é um hub centralizado para o Google Cloud e o G Suite definirem, configurarem e gerenciarem usuários e grupos. Pense no Cloud Identity como uma solução de provisionamento e autenticação, enquanto o Cloud IAM é principalmente uma solução de autorização. Depois que eles estiverem integrados, você poderá atribuir permissões a esses usuários e grupos no Google Cloud IAM para permitir-lhes acesso aos recursos._

---

12. Your organization wants to be sure that is expenditures on cloud services are in line with the budget. Which two Google Cloud cost management features help your organization gain greater visibility into its cloud resource costs? (Choose two.)<br>
    _Sua organização deseja ter certeza de que os gastos com serviços em nuvem estão alinhados com o orçamento. Quais são os dois recursos de gerenciamento de custos do Google Cloud que ajudam sua organização a obter maior visibilidade dos custos de recursos de nuvem? (Escolha dois.)_
    
    :white_check_mark: Billing dashboards

    :white_check_mark: Resource labels

    :black_large_square: Sustained use discounts

    :black_large_square: Financial governance policies

    :black_large_square: Payments profile

    > - Resource hierarchy: Structure and organize your resource hierarchy for fine-grained management and cost allocation using organizations, folders, projects, and labels.<br>
    Billing access control: Enforce organizational policies with granular permissions at different levels in the resource hierarchy to control who can spend and who has administrative and cost-viewing permissions.<br>
    - Budgets and alerts: Set budgets to closely monitor your costs and alert stakeholders through email or Pub/Sub when exceeding defined budget thresholds.<br>
    - Hierarquia de recursos: estruture e organize sua hierarquia de recursos para gerenciamento refinado e alocação de custos usando organizações, pastas, projetos e rótulos.
    - Controle de acesso à cobrança: aplique políticas organizacionais com permissões granulares em diferentes níveis da hierarquia de recursos para controlar quem pode gastar e quem tem permissões administrativas e de visualização de custos.<br>
    - Orçamentos e alertas: defina orçamentos para monitorar de perto seus custos e alertar as partes interessadas por e-mail ou Pub/Sub quando excederem os limites orçamentários definidos.

---

13. Your organization needs to ensure that the Google Cloud resources of each of your departments are segregated from one another. Each department has several environments of its own: development, testing, and production. Which strategy should your organization choose?<br>
    _Sua organização precisa garantir que os recursos do Google Cloud de cada um dos seus departamentos sejam segregados uns dos outros. Cada departamento possui vários ambientes próprios: desenvolvimento, teste e produção. Qual estratégia sua organização deve escolher?_

    :black_large_square: Create a project per department, and create a folder per environment in each project.<br>
    _Crie um projeto por departamento e crie uma pasta por ambiente em cada projeto._

    :white_check_mark: Create a folder per department, and create a project per environment in each folder.<br>
    _Crie uma pasta por departamento e crie um projeto por ambiente em cada pasta._

    :black_large_square: Create a Cloud Identity domain per department, and create a project per environment in each domain.<br>
    _Crie um domínio do Cloud Identity por departamento e um projeto por ambiente em cada domínio._

    :black_large_square: Create a Cloud Identity domain per environment, and create a project per department in each domain.<br>
    _Crie um domínio do Cloud Identity por ambiente e um projeto por departamento em cada domínio._

---

14. Your organization is defining the resource hierarchy for its new application in Google Cloud. You need separate development and production environments. The production environment will be deployed in Compute Engine in two regions. Which structure should your organization choose?<br>
    _Sua organização está definindo a hierarquia de recursos do novo aplicativo no Google Cloud. Você precisa de ambientes de desenvolvimento e produção separados. O ambiente de produção será implantado no Compute Engine em duas regiões. Qual estrutura sua organização deve escolher?_

    :black_large_square: Create a single project for all environments. Use labels to segregate resources by environment.<br>
    _Crie um único projeto para todos os ambientes. Use rótulos para segregar recursos por ambiente._

    :black_large_square: Create a single project for all environments. Use tags to segregate resources by environment.<br>
    _Crie um único projeto para todos os ambientes. Use tags para segregar recursos por ambiente._

    :white_check_mark: Create one project for the development environment and one project for the production environment.<br>
    _Crie um projeto para o ambiente de desenvolvimento e um projeto para o ambiente de produção._

    :black_large_square: Create two projects for the development environment and two projects for the production environment (one for each region).<br>
    _Crie dois projetos para o ambiente de desenvolvimento e dois projetos para o ambiente de produção (um para cada região)._

---

15. Your organization meant to purchase a 3-year Committed Use Discount, but accidentally purchased a 1-year Committed Use Discount instead. What should your organization do?<br>
    _Sua organização pretendia adquirir um desconto por uso contínuo de 3 anos, mas, em vez disso, adquiriu acidentalmente um desconto por uso contínuo de 1 ano. O que sua organização deve fazer?_

    :black_large_square: Contact your financial institution.

    :black_large_square: Contact Trust and Safety.

    :white_check_mark: Contact Cloud Billing Support.

    :black_large_square: Contact Technical Support.

    > After you create a commitment, you can't cancel it. You must pay the agreed upon monthly amount for the duration of the commitment. Commitments are not affected by future pricing changes to the standard prices for Compute Engine resources. If you accidentally purchased a commitment or made a mistake configuring your commitment, contact Google Cloud Billing Support for help.<br>
    _Depois de criar um compromisso, você não poderá cancelá-lo. Você deve pagar o valor mensal acordado durante a vigência do compromisso. Os compromissos não são afetados por alterações futuras nos preços padrão dos recursos do Compute Engine. Se você comprou um compromisso acidentalmente ou cometeu um erro ao configurá-lo, entre em contato com o suporte do Google Cloud Billing para receber ajuda._

---

16. Your organization needs to allow a production job to have access to a BigQuery dataset. The production job is running on a Compute Engine instance that is part of an instance group. What should be included in the IAM Policy on the BigQuery dataset?<br>
    _Sua organização precisa permitir que um job de produção tenha acesso a um conjunto de dados do BigQuery. O job de produção está em execução em uma instância do Compute Engine que faz parte de um grupo de instâncias. O que deve ser incluído na política do IAM no conjunto de dados do BigQuery?_

    :black_large_square: The Compute Engine instance group

    :black_large_square: The project that owns the Compute Engine instance

    :white_check_mark: The Compute Engine service account

    :black_large_square: The Compute Engine instance

    > When a principal (a user, group, or service account) calls a Google Cloud API, that principal must have the appropriate IAM permissions to use the resource. To give a principal the required permissions, you grant an IAM role to the principal.<br>
    _Quando um principal (um usuário, grupo ou conta de serviço) chama uma API do Google Cloud, esse principal precisa ter as permissões apropriadas do IAM para usar o recurso. Para conceder a um principal as permissões necessárias, você concede uma função do IAM ao principal._

---

17. The operating systems of some of your organization’s virtual machines may have a security vulnerability. How can your organization most effectively identify all virtual machines that do not have the latest security update?<br>
    _Os sistemas operacionais de algumas máquinas virtuais da sua organização podem ter uma vulnerabilidade de segurança. Como sua organização pode identificar de forma mais eficaz todas as máquinas virtuais que não possuem a atualização de segurança mais recente?_

    :white_check_mark: View the Security Command Center to identify virtual machines running vulnerable disk images<br>
    _Visualize o Security Command Center para identificar máquinas virtuais que executam imagens de disco vulneráveis_

    :black_large_square: View the Compliance Reports Manager to identify and download a recent PCI audit<br>
    _Visualize o Compliance Reports Manager para identificar e baixar uma auditoria PCI recente_

    :black_large_square: View the Security Command Center to identify virtual machines started more than 2 weeks ago<br>
    _Visualize o Security Command Center para identificar máquinas virtuais iniciadas há mais de duas semanas_

    :black_large_square: View the Compliance Reports Manager to identify and download a recent SOC 1 audit<br>
    _Visualize o Compliance Reports Manager para identificar e baixar uma auditoria SOC 1 recente_

    > Security Health Analytics and Web Security Scanner detectors generate vulnerabilities findings that are available in Security Command Center. Your ability to view and edit findings is determined by the Identity and Access Management (IAM) roles and permissions you are assigned. For more information about IAM roles in Security Command Center.<br>
    _Os detectores Security Health Analytics e Web Security Scanner geram descobertas de vulnerabilidades que estão disponíveis no Security Command Center. Sua capacidade de visualizar e editar descobertas é determinada pelas funções e permissões do Identity and Access Management (IAM) atribuídas a você. Para obter mais informações sobre funções do IAM no Security Command Center._

---

18. You are currently managing workloads running on Windows Server for which your company owns the licenses. Your workloads are only needed during working hours, which allows you to shut down the instances during the weekend. Your Windows Server licenses are up for renewal in a month, and you want to optimize your license cost. What should you do?<br>
    _No momento, você gerencia cargas de trabalho em execução no Windows Server para as quais sua empresa possui as licenças. Suas cargas de trabalho são necessárias apenas durante o horário comercial, o que permite encerrar as instâncias durante o fim de semana. Suas licenças do Windows Server serão renovadas em um mês e você deseja otimizar o custo da licença. O que você deveria fazer?_

    :black_large_square: Renew your licenses for an additional period of 3 years. Renew your licenses for an additional period of 3 years. Negotiate a cost reduction with your current hosting provider wherein infrastructure cost is reduced when workloads are not in use.<br>
    _Renove suas licenças por um período adicional de 3 anos. Renove suas licenças por um período adicional de 3 anos. Negocie uma redução de custos com seu provedor de hospedagem atual, em que o custo da infraestrutura seja reduzido quando as cargas de trabalho não estiverem em uso._

    :black_large_square: Renew your licenses for an additional period of 2 years. Negotiate a cost reduction by committing to an automatic renewal of the licenses at the end of the 2 year period.<br>
    _Renove suas licenças por um período adicional de 2 anos. Negocie uma redução de custos comprometendo-se com a renovação automática das licenças no final do período de 2 anos._

    :black_large_square: Migrate the workloads to Compute Engine with a bring-your-own-license (BYOL) model.<br>
    _Migre as cargas de trabalho para o Compute Engine com um modelo traga sua própria licença (BYOL)._

    :white_check_mark: Migrate the workloads to Compute Engine with a pay-as-you-go (PAYG) model.<br>
    _Migre as cargas de trabalho para o Compute Engine com um modelo de pagamento conforme o uso (PAYG)._

    > Opting for the BYOL (Bring Your Own License) model when migrating workloads to Compute Engine, as indicated in option C, is a sound decision primarily because it allows the utilization of already owned licenses. This approach avoids the typically higher costs associated with PAYG (Pay-As-You-Go) models, which include continuous licensing fees embedded in usage costs. Furthermore, by choosing BYOL, you capitalize on the licenses already acquired, potentially reducing overall expenses significantly, especially since the system needs to operate only during business hours, not around the clock. This strategy aligns perfectly with optimizing license costs while moving to a cloud environment.<br>
    _Optar pelo modelo BYOL (Traga sua própria licença) ao migrar cargas de trabalho para o Compute Engine, conforme indicado na opção C, é uma decisão acertada principalmente porque permite a utilização de licenças já possuídas. Esta abordagem evita os custos normalmente mais elevados associados aos modelos PAYG (Pay-As-You-Go), que incluem taxas de licenciamento contínuas incorporadas nos custos de utilização. Além disso, ao escolher o BYOL, você capitaliza as licenças já adquiridas, potencialmente reduzindo significativamente as despesas gerais, especialmente porque o sistema precisa operar apenas durante o horário comercial, e não 24 horas por dia. Essa estratégia se alinha perfeitamente com a otimização dos custos de licença durante a migração para um ambiente de nuvem._

---

19. Your team is publishing research results and needs to make large amounts of data available to other researchers within the professional community and the public at minimum cost. How should you host the data?<br>
    _A sua equipa está a publicar resultados de investigação e precisa de disponibilizar grandes quantidades de dados a outros investigadores da comunidade profissional e ao público a um custo mínimo. Como você deve hospedar os dados?_

    :white_check_mark: Use a Cloud Storage bucket and enable Requester Pays.

    :black_large_square: Use a Cloud Storage bucket and provide Signed URLs for the data files.

    :black_large_square: Use a Cloud Storage bucket and set up a Cloud Interconnect connection to allow access to the data.

    :black_large_square: Host the data on-premises, and set up a Cloud Interconnect connection to allow access to the data.

    > Whenever a user accesses a Cloud Storage resource such as a bucket or object, there are charges associated with making and executing the request. Normally, the project owner of the resource is billed for these charges; however, if the requester provides a billing project with their request, the requester's project is billed instead. With Requester Pays enabled on your bucket, you can require requesters to include a billing project in their requests, thus billing the requester's project. Enabling Requester Pays is useful, for example, if you have a lot of data you want to make available to users, but you don't want to be charged for their access to that data.<br>
    _Sempre que um usuário acessa um recurso do Cloud Storage, como um bucket ou objeto, há cobranças associadas à criação e execução da solicitação. Normalmente, o proprietário do projeto do recurso é cobrado por esses encargos; entretanto, se o solicitante fornecer um projeto de faturamento com sua solicitação, o projeto do solicitante será cobrado. Com o pagamento do solicitante habilitado em seu bucket, você pode exigir que os solicitantes incluam um projeto de faturamento em suas solicitações, cobrando assim o projeto do solicitante. Ativar o pagamento do solicitante é útil, por exemplo, se você tiver muitos dados que deseja disponibilizar aos usuários, mas não quiser ser cobrado pelo acesso a esses dados._

---

20. Your company needs to segment Google Cloud resources used by each team from the others. The teams' efforts are changing frequently, and you need to reduce operational risk and maintain cost visibility. Which approach does Google recommend?<br>
    _Sua empresa precisa segmentar os recursos do Google Cloud usados ​​por cada equipe dos demais. Os esforços das equipes mudam frequentemente e você precisa reduzir o risco operacional e manter a visibilidade dos custos. Qual abordagem o Google recomenda?_

    :white_check_mark: One project per team.

    :black_large_square: One organization per team.

    :black_large_square: One project that contains all of each team's resources.
    
    :black_large_square: One top-level folder per team.