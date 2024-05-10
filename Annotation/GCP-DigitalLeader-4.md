# Modernize Infrastructure and Applications with Google Cloud

## 1º módulo - Como modernizar a infraestrutura na nuvem

- Termos comuns da modernização
    - Workload (Cargas de trabalho)
    - Retired (Retirada/Remoção)
    - Retained (Retenção)
    - Rehosted (Re hospedar -> Lift and Shift mandar do jeito que está)
    - Replatform (Reinstalar)
    - Refactored (Refatorar código)
    - Reimagined (Reimaginar app)

- TCO - Total Cost of Ownership

- Beneficios da nuvem
    - Organização
    - Escalonabilidade
    - Confiabilidade
    - Flexibilidade
    - Segurança
    - Abstração

- Compute Engine - Maquinas virtuais
    - Preemptible VMS or Spot VMs (máquinas prontas para uso, redução de custo)
    - Descontos são aplicados quanto mais usar as VMs
    - Desconto por compromisso de 1 ou 3 anos

- API: Application Programming Interface: é um conjunto de instruções para que diferentes softwares se comuniquem entre si.

- Containers: (Kubernetes, desenvolvido pelo google e hoje em código aberto realiza a orquestração de containers)

- GKE Autopilot - um modo com gerenciamento completo da infraestrutura do cluster e pagamento por pod

- Cloud Run: Ferramenta para executar aplicativos conteinerizados. é uma plataforma sem servidor e totalmente gerenciada para implantar e executar aplicativos conteinerizados sem se preocupar com a infraestrutura.

- Opções Serverless
    - Cloud Function: que é a plataforma para hospedar funções de propósito único, que são anexadas a eventos emitidos pela infraestrutura e serviços de nuvem.
    - Cloud Run: um ambiente totalmente gerenciado para executar aplicativos conteinerizados.
    - App Engine: um serviço para compilar e implantar aplicativos da Web.

### Questões

1. Qual plataforma de código aberto desenvolvida originalmente pelo Google administra serviços e cargas de trabalho conteinerizados?

    - [ ] TensorFlow

    - [x] Kubernetes

    - [ ] Go

    - [ ] Angular

2. Qual das opções abaixo se refere ao processo em que uma carga de trabalho é reospedada sem mudar nada no código ou na arquitetura da carga?

    - [ ] Migrar e aprimorar

    - [ ] Refatorar e remodelar

    - [x] Fazer uma migração lift-and-shift

    - [ ] Reimaginar e planejar

3. Qual parte de uma máquina um contêiner virtualiza?

    - [ ] Camadas de software acima do nível do firmware

    - [x] Camadas de software acima do nível do sistema operacional

    - [ ] Camadas de hardware acima do nível elétrico

    - [ ] Toda a máquina

4. Qual opção de computação provisiona automaticamente em segundo plano os recursos, como a capacidade de computação, conforme necessário?

    - [ ] IaaS (infraestrutura como serviço)

    - [ ] PaaS (plataforma como serviço)

    - [ ] Computação tradicional no local

    - [x] Computação sem servidor

5. Uma empresa de viagens está nas etapas iniciais do desenvolvimento de um novo aplicativo, e ela quer testar o app com diferentes combinações de sistemas operacionais, processadores e opções de armazenamento. Qual recurso de computação em nuvem a empresa deve usar?

    - [ ] Contêineres

    - [x] Instâncias de máquina virtual

    - [ ] Colocation

    - [ ] Um ambiente de desenvolvimento local

6. Uma empresa de manufatura está querendo migrar a infraestrutura local dela para a nuvem, mas a organização acredita que o acesso aos dados e aplicativos pode ficar indisponível em momentos importantes. A empresa quer garantir que se um data center ficar inativo, outro vai estar disponível para evitar a interrupção do serviço. O que essa empresa está buscando?

    - [ ] Segurança

    - [x] Confiabilidade

    - [ ] Custo total de propriedade

    - [ ] Flexibilidade

## 2º módulo - Como modernizar aplicativos na nuvem

- Beneficios de app na nuvem
    - Arquitetura
    - Custo
    - Escalonabilidade

- Google CLoud VMware Engine: Solução para re hospedar aplicativos legados. que migra cargas de trabalho VMware para a nuvem sem alterar aplicativos ou operações.

- Bare Metal Solution: Outra solução para re hospedar aplicativos legados. Com essa solução de infraestrutura em nuvem totalmente gerenciada, as organizações executam cargas de trabalho Oracle em servidores Bare Metal dedicados na nuvem.

- Apigee API Management: serviço de gerenciamento de APIs do Google Cloud para operar APIs com escalonamento, segurança e automação aprimorados.

- GKE Enterprise: Nessa plataforma gerenciada e pronta para uso, é possível executar aplicativos do Kubernetes em vários ambientes de nuvem. É uma forma consistente de gerenciar clusters e aplicativos do Kubernetes e serviços executados em qualquer lugar. Solução para ambientes multicloud ou hibridos.

### Questões

1. Qual é o nome do serviço de gerenciamento de APIs do Google Cloud que pode operar APIs com mais escala, segurança e automação?

    - [ ] App Engine

    - [x] Apigee

    - [ ] Cloud API Manager

    - [ ] AppSheet

2. No desenvolvimento moderno de aplicativos na nuvem, que nome é dado aos componentes sustentáveis, escalonáveis e implantados de forma independente que podem ser usados para criar vários tipos de aplicativos?

    - [ ] Contêineres

    - [ ] Monolíticos

    - [ ] DevOps

    - [x] Microsserviços

3. Qual é o nome da plataforma do Google Cloud pronta para produção e execução de aplicativos do Kubernetes em vários ambientes de nuvem?

    - [ ] Knative

    - [x] GKE Enterprise

    - [ ] Container Registry

    - [ ] Google Kubernetes Engine

4. Qual das opções abaixo é usada com frequência para descrever uma estratégia de migração de reospedagem para uma organização que executa aplicativos legados especializados que não são compatíveis com apps nativos da nuvem?

    - [ ] Migrar e aprimorar

    - [ ] Fazer a instalação e queda

    - [x] Fazer uma migração lift-and-shift

    - [ ] Criar e implantar

5. No desenvolvimento moderno de aplicativos, qual das opções abaixo é responsável pelo gerenciamento diário da infraestrutura baseada na nuvem, como aplicar patches, lançar upgrades e fazer o monitoramento?

    - [ ] Segurança na nuvem

    - [x] Serviços gerenciados

    - [ ] Contêineres

    - [ ] DevOps

6. Qual termo descreve um conjunto de instruções que permite que programas de software diferentes se comuniquem entre si?

    - [ ] Interface de programação de rede

    - [ ] Link de comunicação de programação

    - [ ] Interface do link de comunicação

    - [x] Interface de programação do aplicativo

7. Qual das opções abaixo é uma solução de infraestrutura em nuvem totalmente gerenciada que permite que as organizações executem as cargas de trabalho da Oracle em servidores dedicados na nuvem?

    - [ ] App Engine

    - [ ] SQL Server no Google Cloud

    - [ ] Google Cloud VMware Engine

    - [x] Solução Bare Metal

8. Qual nome é dado a um ambiente em que uma organização usa mais de um provedor de nuvem pública como parte da arquitetura?

    - [ ] Nuvem comunitária

    - [ ] Nuvem híbrida

    - [x] Multicloud

    - [ ] Nuvem de borda

9. Como as organizações podem criar novas fontes de receita usando APIs?

    - [ ] Usando APIs para rastrear os envios dos clientes

    - [x] Cobrando aos desenvolvedores pelo acesso às APIs

    - [ ] Desenvolvendo novos produtos e serviços internamente

    - [ ] Permitindo que os desenvolvedores acessem os dados deles gratuitamente

10. Qual nome é dado a um ambiente que tem uma combinação de infraestrutura local ou em uma nuvem privada e serviços da nuvem pública?

    - [ ] Nuvem segura

    - [ ] Nuvem inteligente

    - [ ] Multicloud

    - [x] Nuvem híbrida

