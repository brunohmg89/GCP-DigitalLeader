# Digital Leader

Reference: <https://www.examtopics.com/exams/google/>

## Questions

1. You are migrating workloads to the cloud. The goal of the migration is to serve customers worldwide as quickly as possible According to local regulations, certain data is required to be stored in a specific geographic area, and it can be served worldwide. You need to design the architecture and deployment for your workloads. What should you do?<br>
    _Você está migrando cargas de trabalho para a nuvem. O objetivo da migração é atender clientes em todo o mundo o mais rápido possível. De acordo com as regulamentações locais, determinados dados precisam ser armazenados em uma área geográfica específica e podem ser atendidos em todo o mundo. Você precisa projetar a arquitetura e a implantação para suas cargas de trabalho. O que você deveria fazer?_

    :black_large_square: Select a public cloud provider that is only active in the required geographic area

    :black_large_square: Select a private cloud provider that globally replicates data storage for fast data access

    :white_check_mark: Select a public cloud provider that guarantees data location in the required geographic area

    :black_large_square: Select a private cloud provider that is only active in the required geographic area

    > The goal of the migration is to serve customers worldwide as quickly as possible According to local regulations, certain data is required to be stored in a specific geographic area, and it can be served worldwide" This characteristic are inherent to the public cloud provider.<br>
    _O objetivo da migração é atender clientes em todo o mundo o mais rápido possível. De acordo com as regulamentações locais, determinados dados devem ser armazenados em uma área geográfica específica e podem ser atendidos em todo o mundo" Esta característica é inerente ao provedor de nuvem pública_

---

2. Your organization needs a large amount of extra computing power within the next two weeks. After those two weeks, the need for the additional resources will end. Which is the most cost-effective approach?<br>
    _Sua organização precisará de uma grande quantidade de capacidade computacional extra nas próximas duas semanas. Após essas duas semanas, a necessidade de recursos adicionais terminará. Qual é a abordagem mais econômica?_

    :black_large_square: Use a committed use discount to reserve a very powerful virtual machine

    :black_large_square: Purch ase one very powerful physical computer

    :white_check_mark: Start a very powerful virtual machine without using a committed use discount

    :black_large_square: Purchase multiple physical computers and scale workload across them

    > When you purchase a committed use contract, you purchase Compute Engine resources—such as vCPUs, memory, GPUs, local SSDs, and sole-tenant nodes—at a discounted price in return for committing to paying for those resources for 1 year or 3 years.<br>
    _Ao adquirir um contrato de uso contínuo, você adquire recursos do Compute Engine, como vCPUs, memória, GPUs, SSDs locais e nós de locatário individual, com desconto em troca do compromisso de pagar por esses recursos por 1 ou 3 anos._

---

3. The operating systems of some of your organization's virtual machines may have a security vulnerability. How can your organization most effectively identify all virtual machines that do not have the latest security update?<br>
    _Os sistemas operacionais de algumas máquinas virtuais da sua organização podem ter uma vulnerabilidade de segurança. Como sua organização pode identificar de forma mais eficaz todas as máquinas virtuais que não possuem a atualização de segurança mais recente?_

    :white_check_mark: View the Security Command Center to identify virtual machines running vulnerable disk images

    :black_large_square: View the Compliance Reports Manager to identify and download a recent PCI audit

    :black_large_square: View the Security Command Center to identify virtual machines started more than 2 weeks ago

    :black_large_square: View the Compliance Reports Manager to identify and download a recent SOC 1 audit

    > Using the Security Command Center offers the most precise method to identify virtual machines with outdated security updates. This tool provides insights about the current security state of each machine, specifically highlighting those running vulnerable disk images. This centralized visibility and precise identification enable timely updates, boosting the overall security of your cloud infrastructure.<br>
    _Usar o Security Command Center oferece o método mais preciso para identificar máquinas virtuais com atualizações de segurança desatualizadas. Esta ferramenta fornece informações sobre o estado atual de segurança de cada máquina, destacando especificamente aquelas que executam imagens de disco vulneráveis. Essa visibilidade centralizada e identificação precisa permitem atualizações oportunas, aumentando a segurança geral da sua infraestrutura em nuvem._

---

4. Your organization runs a distributed application in the Compute Engine virtual machines. Your organization needs redundancy, but it also needs extremely fast communication (less than 10 milliseconds) between the parts of the application in different virtual machines. Where should your organization locate this virtual machines?<br>
    _Sua organização executa um aplicativo distribuído nas máquinas virtuais do Compute Engine. Sua organização precisa de redundância, mas também de comunicação extremamente rápida (menos de 10 milissegundos) entre as partes do aplicativo em diferentes máquinas virtuais. Onde sua organização deve localizar essas máquinas virtuais?_

    :black_large_square: In a single zone within a single region

    :black_large_square: In different zones within a single region

    :black_large_square: In multiple regions, using one zone per region

    :white_check_mark: In multiple regions, using multiple zones per region

    > Choosing option B, placing VMs in different zones within a single region, best combines redundancy with the requirement for low latency, typically under 10 milliseconds between VMs. This setup avoids the potential latency issues that may arise with inter-regional communication in option D, which although it offers increased redundancy, may not consistently deliver the sub-10-millisecond communication required for some distributed applications.<br>
    _Escolher a opção B, colocando VMs em zonas diferentes dentro de uma única região, combina melhor a redundância com o requisito de baixa latência, normalmente abaixo de 10 milissegundos entre VMs. Esta configuração evita possíveis problemas de latência que podem surgir com a comunicação inter-regional na opção D, que embora ofereça maior redundância, pode não fornecer consistentemente a comunicação inferior a 10 milissegundos necessária para alguns aplicativos distribuídos._

---

5. An organization decides to migrate their on-premises environment to the cloud. They need to determine which resource components still need to be assigned ownership. Which two functions does a public cloud provider own? (Choose two.)<br>
    _Uma organização decide migrar seu ambiente local para a nuvem. Eles precisam determinar quais componentes de recursos ainda precisam receber propriedade. Quais são as duas funções que um provedor de nuvem pública possui? (Escolha dois.)_

    :white_check_mark: Hardware maintenance
    
    :black_large_square: Infrastructure architecture

    :black_large_square: Infrastructure deployment automation

    :white_check_mark: Hardware capacity management

    :black_large_square: Fixing application security issues

    > When it comes to public cloud services, the provider takes charge of both hardware maintenance and capacity management. Essentially, they ensure that physical servers and other hardware resources are not only up and running but also adequately scaled to meet user demands. So, there's no need for clients to worry about the nuts and bolts of hardware—they can focus on building and securing their apps!<br>
    _Quando se trata de serviços de nuvem pública, o provedor se encarrega tanto da manutenção do hardware quanto do gerenciamento da capacidade. Essencialmente, eles garantem que os servidores físicos e outros recursos de hardware não apenas estejam em funcionamento, mas também dimensionados adequadamente para atender às demandas dos usuários. Portanto, os clientes não precisam se preocupar com os detalhes básicos do hardware: eles podem se concentrar na criação e na proteção de seus aplicativos!_

---

6. You are a program manager within a Software as a Service (SaaS) company that offers rendering software for animation studios. Your team needs the ability to allow scenes to be scheduled at will and to be interrupted at any time to restart later. Any individual scene rendering takes less than 12 hours to complete, and there is no service-level agreement (SLA) for the completion time for all scenes. Results will be stored in a global Cloud Storage bucket. The compute resources are not bound to any single geographical location. This software needs to run on Google Cloud in a cost-optimized way. What should you do?<br>
    _Você é gerente de programa em uma empresa de software como serviço (SaaS) que oferece software de renderização para estúdios de animação. Sua equipe precisa permitir que as cenas sejam agendadas à vontade e interrompidas a qualquer momento para reiniciar mais tarde. Qualquer renderização de cena individual leva menos de 12 horas para ser concluída e não há acordo de nível de serviço (SLA) para o tempo de conclusão de todas as cenas. Os resultados serão armazenados em um bucket global do Cloud Storage. Os recursos de computação não estão vinculados a uma única localização geográfica. Este software precisa ser executado no Google Cloud de forma econômica. O que você deveria fazer?_

    :white_check_mark: Deploy the application on Compute Engine using preemptible instances

    :black_large_square: Develop the application so it can run in an unmanaged instance group

    :black_large_square: Create a reservation for the minimum number of Compute Engine instances you will use

    :black_large_square: Start more instances with fewer virtual centralized processing units (vCPUs) instead of fewer instances with more vCPUs

    > For your SaaS company's animation rendering needs, preemptible VMs on Google Cloud present a highly cost-effective solution. These VMs offer a substantial discount compared to standard instances and are especially suitable for tasks like rendering, which can tolerate interruptions. Since each scene takes less than 12 hours and the process can be paused and resumed, using preemptible VMs allows you to manage compute costs effectively while adapting the workflow to automatically save progress and restart as needed. This setup ensures efficient use of resources and aligns perfectly with the absence of strict SLA requirements for scene completion.<br>
    _Para as necessidades de renderização de animação da sua empresa de SaaS, as VMs preemptivas no Google Cloud apresentam uma solução altamente econômica. Essas VMs oferecem um desconto substancial em comparação com instâncias padrão e são especialmente adequadas para tarefas como renderização, que podem tolerar interrupções. Como cada cena leva menos de 12 horas e o processo pode ser pausado e retomado, o uso de VMs preemptivas permite gerenciar os custos de computação de maneira eficaz e, ao mesmo tempo, adaptar o fluxo de trabalho para salvar automaticamente o progresso e reiniciar conforme necessário. Essa configuração garante o uso eficiente de recursos e se alinha perfeitamente com a ausência de requisitos rígidos de SLA para conclusão da cena._

---

7. Your manager wants to restrict communication of all virtual machines with internet access, with resources in another network, or with a resource outside Compute Engine. It is expected that different teams will create new folders and projects in the near future. How would you restrict all virtual machines from having an external IP address?<br>
    _Seu gerente quer restringir a comunicação de todas as máquinas virtuais com acesso à Internet, com recursos em outra rede ou com um recurso fora do Compute Engine. Espera-se que diferentes equipes criem novas pastas e projetos em um futuro próximo. Como você impediria que todas as máquinas virtuais tivessem um endereço IP externo?_

    :white_check_mark: Define an organization policy at the root organization node to restrict virtual machine instances from having an external IP address

    :black_large_square: Define an organization policy on all existing folders to define a constraint to restrict virtual machine instances from having an external IP address

    :black_large_square: Define an organization policy on all existing projects to restrict virtual machine instances from having an external IP address

    :black_large_square: Communicate with the different teams and agree that each time a virtual machine is created, it must be configured without an external IP address

---

8. Your multinational organization has servers running mission critical workloads on its premises around the world. You want to be able to manage these workloads consistently and centrally, and you want to stop managing infrastructure. What should your organization do?<br>
    _Sua organização multinacional possui servidores que executam cargas de trabalho de missão crítica em suas instalações ao redor do mundo. Você deseja gerenciar essas cargas de trabalho de forma consistente e centralizada e deseja parar de gerenciar a infraestrutura. O que sua organização deve fazer?_

    :white_check_mark: Migrate the workloads to a public cloud

    :black_large_square: Migrate the workloads to a central office building

    :black_large_square: Migrate the workloads to multiple local co-location facilities

    :black_large_square: Migrate the workloads to multiple local private clouds

    > Choosing to migrate the workloads to a public cloud perfectly addresses the goals of managing the workloads centrally and consistently while eliminating the need to manage physical infrastructure. This shift not only streamlines management practices across various geographies but also enhances operational efficiency by leveraging cloud technologies. This option is most in line with the desire to decrease direct oversight over hardware and physical systems.<br>
    _A escolha de migrar as cargas de trabalho para uma nuvem pública atende perfeitamente aos objetivos de gerenciamento das cargas de trabalho de forma centralizada e consistente, ao mesmo tempo que elimina a necessidade de gerenciar a infraestrutura física. Esta mudança não só simplifica as práticas de gestão em várias geografias, mas também aumenta a eficiência operacional ao alavancar tecnologias de nuvem. Esta opção está mais alinhada com o desejo de diminuir a supervisão direta sobre hardware e sistemas físicos._

---

9. Your organization stores highly sensitive data on-premises that cannot be sent over the public internet. The data must be processed both on-premises and in the cloud. What should your organization do?<br>
    _Sua organização armazena dados altamente confidenciais localmente que não podem ser enviados pela Internet pública. Os dados devem ser processados ​​localmente e na nuvem. O que sua organização deve fazer?_

    :black_large_square: Configure Identity-Aware Proxy (IAP) in your Google Cloud VPC network

    :black_large_square: Create a Cloud VPN tunnel between Google Cloud and your data center

    :white_check_mark: Order a Partner Interconnect connection with your network provider

    :black_large_square: Enable Private Google Access in your Google Cloud VPC network

    > After the service provider provisions your connection, you can start passing traffic between your networks by using the service provider's network.<br>
    _Depois que o provedor de serviços provisionar sua conexão, você poderá começar a transmitir o tráfego entre suas redes usando a rede do provedor de serviços._

---

10. Your company's development team is building an application that will be deployed on Cloud Run. You are designing a CI/CD pipeline so that any new version of the application can be deployed in the fewest number of steps possible using the CI/CD pipeline you are designing. You need to select a storage location for the images of the application after the CI part of your pipeline has built them. What should you do?<br>
    _A equipe de desenvolvimento da sua empresa está criando um aplicativo que será implantado no Cloud Run. Você está projetando um pipeline de CI/CD para que qualquer nova versão do aplicativo possa ser implantada no menor número de etapas possível usando o pipeline de CI/CD que você está projetando. Você precisa selecionar um local de armazenamento para as imagens do aplicativo depois que a parte CI do pipeline as tiver criado. O que você deveria fazer?_

    :black_large_square: Create a Compute Engine image containing the application

    :white_check_mark: Store the images in Container Registry

    :black_large_square: Store the images in Cloud Storage

    :black_large_square: Create a Compute Engine disk containing the application

    > Pushing (uploading) and pulling (downloading) images are two of the most common Container Registry tasks. This document focuses on pushing and pulling images with Docker.<br>
    _Enviar (carregar) e extrair (baixar) imagens são duas das tarefas mais comuns do Container Registry. Este documento se concentra em enviar e extrair imagens com Docker._

---

11. Each of the three cloud service models - infrastructure as a service (IaaS), platform as a service (PaaS), and software as a service (SaaS) - offers benefits between flexibility and levels of management by the cloud provider and the customer. Why would SaaS be the right choice of service model?<br>
    _Cada um dos três modelos de serviço em nuvem – infraestrutura como serviço (IaaS), plataforma como serviço (PaaS) e software como serviço (SaaS) – oferece benefícios entre flexibilidade e níveis de gerenciamento por parte do provedor de nuvem e do cliente. Por que o SaaS seria a escolha certa de modelo de serviço?_

    :black_large_square: You want a balance between flexibility for the customer and the level of management by the cloud provider.

    :white_check_mark: You want to minimize the level of management by the customer.

    :black_large_square: You want to maximize flexibility for the customer.

    :black_large_square: You want to be able to shift your emphasis between flexibility and management by the cloud provider as business needs change.

    > Benefits of SaaS - The main benefit of SaaS is that it offloads all infrastructure and application management to the SaaS vendor.<br>
    _Benefícios do SaaS - O principal benefício do SaaS é que ele transfere toda a infraestrutura e gerenciamento de aplicativos para o fornecedor de SaaS._

---

12. As your organization increases its release velocity, the VM-based application upgrades take a long time to perform rolling updates due to OS boot times. You need to make the application deployments faster. What should your organization do?<br>
    _À medida que sua organização aumenta a velocidade de lançamento, as atualizações de aplicativos baseados em VM demoram muito para realizar atualizações contínuas devido aos tempos de inicialização do sistema operacional. Você precisa tornar as implantações de aplicativos mais rápidas. O que sua organização deve fazer?_

    :black_large_square: Migrate your VMs to the cloud, and add more resources to them

    :white_check_mark: Convert your applications into containers

    :black_large_square: Increase the resources of your VMs

    :black_large_square: Automate your upgrade rollouts

---

13. Your organization uses Active Directory to authenticate users. Users' Google account access must be removed when their Active Directory account is terminated. How should your organization meet this requirement?<br>
    _Sua organização usa o Active Directory para autenticar usuários. O acesso à conta Google dos usuários deverá ser removido quando a conta do Active Directory for encerrada. Como sua organização deve atender a esse requisito?_

    :black_large_square: Configure two-factor authentication in the Google domain

    :black_large_square: Remove the Google account from all IAM policies

    :black_large_square: Configure BeyondCorp and Identity-Aware Proxy in the Google domain

    :white_check_mark: Configure single sign-on in the Google domain

---

14. Your company has recently acquired three growing startups in three different countries. You want to reduce overhead in infrastructure management and keep your costs low without sacrificing security and quality of service to your customers. How should you meet these requirements?<br>
    _Sua empresa adquiriu recentemente três startups em crescimento em três países diferentes. Você deseja reduzir as despesas gerais no gerenciamento da infraestrutura e manter seus custos baixos sem sacrificar a segurança e a qualidade do serviço aos seus clientes. Como você deve atender a esses requisitos?_

    :black_large_square: Host all your subsidiaries' services on-premises together with your existing services.

    :white_check_mark: Host all your subsidiaries' services together with your existing services on the public cloud.

    :black_large_square: Build a homogenous infrastructure at each subsidiary, and invest in training their engineers.

    :black_large_square: Build a homogenous infrastructure at each subsidiary, and invest in hiring more engineers.

---

15. What is the difference between Standard and Coldline storage?<br>
    _Qual é a diferença entre armazenamento Standard e Coldline?_

    :black_large_square: Coldline storage is for data for which a slow transfer rate is acceptable.

    :black_large_square: Standard and Coldline storage have different durability guarantees.

    :black_large_square: Standard and Coldline storage use different APIs.

    :white_check_mark: Coldline storage is for infrequently accessed data.

---

16. What would provide near unlimited availability of computing resources without requiring your organization to procure and provision new equipment?<br>
    _O que proporcionaria disponibilidade quase ilimitada de recursos computacionais sem exigir que sua organização adquirisse e fornecesse novos equipamentos?_

    :white_check_mark: Public cloud

    :black_large_square: Containers

    :black_large_square: Private cloud

    :black_large_square: Microservices

---

17. You are a program manager for a team of developers who are building an event driven application to allow users to follow one another's activities in the app. Each time a user adds himself as a follower of another user, a write occurs in the real-time database. The developers will develop a lightweight piece of code that can respond to database writes and generate a notification to let the appropriate users know that they have gained new followers. The code should integrate with other cloud services such as Pub/Sub, Firebase, and Cloud APIs to streamline the orchestration process. The application requires a platform that automatically manages underlying infrastructure and scales to zero when there is no activity. Which primary compute resource should your developers select, given these requirements?<br>
    _Você é gerente de programa de uma equipe de desenvolvedores que está criando um aplicativo orientado a eventos para permitir que os usuários acompanhem as atividades uns dos outros no aplicativo. Cada vez que um usuário se adiciona como seguidor de outro usuário, ocorre uma gravação no banco de dados em tempo real. Os desenvolvedores desenvolverão um código leve que pode responder às gravações do banco de dados e gerar uma notificação para informar aos usuários apropriados que ganharam novos seguidores. O código deve ser integrado a outros serviços de nuvem, como Pub/Sub, Firebase e APIs de nuvem, para agilizar o processo de orquestração. O aplicativo requer uma plataforma que gerencie automaticamente a infraestrutura subjacente e escale até zero quando não houver atividade. Qual recurso de computação principal seus desenvolvedores devem selecionar, considerando esses requisitos?_

    :black_large_square: Google Kubernetes Engine

    :white_check_mark: Cloud Functions

    :black_large_square: App Engine flexible environment

    :black_large_square: Compute Engine

    > Cloud Functions gives developers access to Firebase and Google Cloud events, along with scalable computing power to run code in response to those events. While it's expected that Firebase apps will use Cloud Functions in unique ways to meet their unique requirements.<br>
    _O Cloud Functions oferece aos desenvolvedores acesso a eventos do Firebase e do Google Cloud, além de poder de computação escalonável para executar código em resposta a esses eventos. Embora seja esperado que os aplicativos do Firebase usem o Cloud Functions de maneiras exclusivas para atender aos seus requisitos exclusivos_

---

18. Your organization is developing an application that will capture a large amount of data from millions of different sensor devices spread all around the world. Your organization needs a database that is suitable for worldwide, high-speed data storage of a large amount of unstructured data. Which Google Cloud product should your organization choose?<br>
    _Sua organização está desenvolvendo um aplicativo que irá capturar uma grande quantidade de dados de milhões de dispositivos sensores diferentes espalhados por todo o mundo. Sua organização precisa de um banco de dados adequado para armazenamento mundial e em alta velocidade de uma grande quantidade de dados não estruturados. Qual produto do Google Cloud sua organização deve escolher?_

    :black_large_square: Firestore

    :black_large_square: Cloud Data Fusion

    :black_large_square: Cloud SQL

    :white_check_mark: Cloud Bigtable

--- 

19. Your organization needs to build streaming data pipelines. You don't want to manage the individual servers that do the data processing in the pipelines. Instead, you want a managed service that will automatically scale with the amount of data to be processed. Which Google Cloud product or feature should your organization choose?<br>
    _Sua organização precisa construir pipelines de dados de streaming. Você não deseja gerenciar os servidores individuais que fazem o processamento de dados nos pipelines. Em vez disso, você deseja um serviço gerenciado que seja dimensionado automaticamente de acordo com a quantidade de dados a serem processados. Qual produto ou recurso do Google Cloud sua organização deve escolher?_

    :black_large_square: Pub/Sub

    :white_check_mark: Dataflow

    :black_large_square: Data Catalog

    :black_large_square: Dataprep by Trifacta

    > Dataflow is a fully-managed service for strongly consistent, parallel data-processing pipelines. It provides an SDK for Java with composable primitives for building data-processing pipelines for batch or continuous processing. This service manages the life cycle of Compute Engine resources of the processing pipeline(s). It also provides a monitoring user interface for understanding pipeline health.<br>
    _O Dataflow é um serviço totalmente gerenciado para pipelines de processamento de dados paralelos e altamente consistentes. Ele fornece um SDK para Java com primitivos combináveis ​​para construir pipelines de processamento de dados para processamento em lote ou contínuo. Este serviço gerencia o ciclo de vida dos recursos do Compute Engine dos pipelines de processamento. Ele também fornece uma interface de usuário de monitoramento para compreender a integridade do pipeline._

---

20. Your organization is building an application running in Google Cloud. Currently, software builds, tests, and regular deployments are done manually, but you want to reduce work for the team. Your organization wants to use Google Cloud managed solutions to automate your build, testing, and deployment process. Which Google Cloud product or feature should your organization use?<br>
    _Sua organização está criando um aplicativo em execução no Google Cloud. Atualmente, compilações, testes e implantações regulares de software são feitos manualmente, mas você deseja reduzir o trabalho da equipe. Sua organização quer usar soluções gerenciadas do Google Cloud para automatizar o processo de criação, teste e implantação. Qual produto ou recurso do Google Cloud sua organização deve usar?_

    :black_large_square: Cloud Scheduler

    :black_large_square: Cloud Code

    :white_check_mark: Cloud Build
    
    :black_large_square: Cloud Deployment Manager

    > Deploy your application to App Engine using the gcloud app deploy command. This command automatically builds a container image by using the Cloud Build service and then deploys that image to the App Engine flexible environment.<br>
    _Implante seu aplicativo no App Engine usando o comando gcloud app deploy. Este comando cria automaticamente uma imagem de contêiner usando o serviço Cloud Build e, em seguida, implanta essa imagem no ambiente flexível do App Engine._