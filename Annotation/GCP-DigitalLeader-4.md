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
    - Cloud Function: É a plataforma para hospedar funções de propósito único, que são anexadas a eventos emitidos pela infraestrutura e serviços de nuvem.
    - Cloud Run: É um ambiente totalmente gerenciado para executar aplicativos conteinerizados.
    - App Engine: É um serviço para compilar e implantar aplicativos da Web.

### Questões

1. Qual plataforma de código aberto desenvolvida originalmente pelo Google administra serviços e cargas de trabalho conteinerizados?

    :black_large_square: TensorFlow

    :white_check_mark: Kubernetes

    :black_large_square: Go

    :black_large_square: Angular

---

2. Qual das opções abaixo se refere ao processo em que uma carga de trabalho é reospedada sem mudar nada no código ou na arquitetura da carga?

    :black_large_square: Migrar e aprimorar

    :black_large_square: Refatorar e remodelar

    :white_check_mark: Fazer uma migração lift-and-shift

    :black_large_square: Reimaginar e planejar

---

3. Qual parte de uma máquina um contêiner virtualiza?

    :black_large_square: Camadas de software acima do nível do firmware

    :white_check_mark: Camadas de software acima do nível do sistema operacional

    :black_large_square: Camadas de hardware acima do nível elétrico

    :black_large_square: Toda a máquina

---

4. Qual opção de computação provisiona automaticamente em segundo plano os recursos, como a capacidade de computação, conforme necessário?

    :black_large_square: IaaS (infraestrutura como serviço)

    :black_large_square: PaaS (plataforma como serviço)

    :black_large_square: Computação tradicional no local

    :white_check_mark: Computação sem servidor

---

5. Uma empresa de viagens está nas etapas iniciais do desenvolvimento de um novo aplicativo, e ela quer testar o app com diferentes combinações de sistemas operacionais, processadores e opções de armazenamento. Qual recurso de computação em nuvem a empresa deve usar?

    :black_large_square: Contêineres

    :white_check_mark: Instâncias de máquina virtual

    :black_large_square: Colocation

    :black_large_square: Um ambiente de desenvolvimento local

---

6. Uma empresa de manufatura está querendo migrar a infraestrutura local dela para a nuvem, mas a organização acredita que o acesso aos dados e aplicativos pode ficar indisponível em momentos importantes. A empresa quer garantir que se um data center ficar inativo, outro vai estar disponível para evitar a interrupção do serviço. O que essa empresa está buscando?

    :black_large_square: Segurança

    :white_check_mark: Confiabilidade

    :black_large_square: Custo total de propriedade

    :black_large_square: Flexibilidade

## 2º módulo - Como modernizar aplicativos na nuvem

- Beneficios de app na nuvem
    - Arquitetura
    - Custo
    - Escalonabilidade

- Google Cloud VMware Engine: Solução para re hospedar aplicativos legados. Ele migra cargas de trabalho VMware para a nuvem sem alterar aplicativos ou operações.

- Bare Metal Solution: Outra solução para re hospedar aplicativos legados. Com essa solução de infraestrutura em nuvem totalmente gerenciada, as organizações executam cargas de trabalho Oracle em servidores Bare Metal dedicados na nuvem.

- Apigee API Management: Serviço de gerenciamento de APIs do Google Cloud para operar APIs com escalonamento, segurança e automação aprimorados.

- GKE Enterprise: Nessa plataforma gerenciada e pronta para uso, é possível executar aplicativos do Kubernetes em vários ambientes de nuvem. É uma forma consistente de gerenciar clusters e aplicativos do Kubernetes e serviços executados em qualquer lugar. Solução para ambientes multicloud ou hibridos.

### Questões

1. Qual é o nome do serviço de gerenciamento de APIs do Google Cloud que pode operar APIs com mais escala, segurança e automação?

    :black_large_square: App Engine

    :white_check_mark: Apigee

    :black_large_square: Cloud API Manager

    :black_large_square: AppSheet

---

2. No desenvolvimento moderno de aplicativos na nuvem, que nome é dado aos componentes sustentáveis, escalonáveis e implantados de forma independente que podem ser usados para criar vários tipos de aplicativos?

    :black_large_square: Contêineres

    :black_large_square: Monolíticos

    :black_large_square: DevOps

    :white_check_mark: Microsserviços

---

3. Qual é o nome da plataforma do Google Cloud pronta para produção e execução de aplicativos do Kubernetes em vários ambientes de nuvem?

    :black_large_square: Knative

    :white_check_mark: GKE Enterprise

    :black_large_square: Container Registry

    :black_large_square: Google Kubernetes Engine

---

4. Qual das opções abaixo é usada com frequência para descrever uma estratégia de migração de reospedagem para uma organização que executa aplicativos legados especializados que não são compatíveis com apps nativos da nuvem?

    :black_large_square: Migrar e aprimorar

    :black_large_square: Fazer a instalação e queda

    :white_check_mark: Fazer uma migração lift-and-shift

    :black_large_square: Criar e implantar

---

5. No desenvolvimento moderno de aplicativos, qual das opções abaixo é responsável pelo gerenciamento diário da infraestrutura baseada na nuvem, como aplicar patches, lançar upgrades e fazer o monitoramento?

    :black_large_square: Segurança na nuvem

    :white_check_mark: Serviços gerenciados

    :black_large_square: Contêineres

    :black_large_square: DevOps

---

6. Qual termo descreve um conjunto de instruções que permite que programas de software diferentes se comuniquem entre si?

    :black_large_square: Interface de programação de rede

    :black_large_square: Link de comunicação de programação

    :black_large_square: Interface do link de comunicação

    :white_check_mark: Interface de programação do aplicativo

---

7. Qual das opções abaixo é uma solução de infraestrutura em nuvem totalmente gerenciada que permite que as organizações executem as cargas de trabalho da Oracle em servidores dedicados na nuvem?

    :black_large_square: App Engine

    :black_large_square: SQL Server no Google Cloud

    :black_large_square: Google Cloud VMware Engine

    :white_check_mark: Solução Bare Metal

---

8. Qual nome é dado a um ambiente em que uma organização usa mais de um provedor de nuvem pública como parte da arquitetura?

    :black_large_square: Nuvem comunitária

    :black_large_square: Nuvem híbrida

    :white_check_mark: Multicloud

    :black_large_square: Nuvem de borda

---

9. Como as organizações podem criar novas fontes de receita usando APIs?

    :black_large_square: Usando APIs para rastrear os envios dos clientes

    :white_check_mark: Cobrando aos desenvolvedores pelo acesso às APIs

    :black_large_square: Desenvolvendo novos produtos e serviços internamente

    :black_large_square: Permitindo que os desenvolvedores acessem os dados deles gratuitamente

---

10. Qual nome é dado a um ambiente que tem uma combinação de infraestrutura local ou em uma nuvem privada e serviços da nuvem pública?

    :black_large_square: Nuvem segura

    :black_large_square: Nuvem inteligente

    :black_large_square: Multicloud

    :white_check_mark: Nuvem híbrida