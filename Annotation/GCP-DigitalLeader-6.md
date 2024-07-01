# Scaling with Google Cloud Operations

## 1º Módulo - Financial Governance and Managing Cloud Costs

- Areas de governança financeira
    - Pessoas
    - Processos
    - Tecnologia

- Praticas recomendadas de governaça financeira
    - A primeira prática recomendada é identificar quem gerencia os custos da nuvem.
    - Além disso, o Google Cloud oferece opções flexíveis para organizar recursos e alocar custos a departamentos e equipes individuais. Um exemplo são os budgets. Notifique as principais partes interessadas com base nos custos reais ou previstos para a nuvem.
    - A segunda prática recomendada é entender qual tipo de informação pode ser encontrada em uma fatura e nas ferramentas de gestão de custos. 
    - A terceira prática recomendada está relacionada ao aumento da previsibilidade e do controle dos recursos da nuvem.

- Hierarquia de recursos do Google Cloud (de baixo para cima)
    - Level 1: Resources
    - Level 2: Projects
    - Level 3: Folder
    - Level 4: Organization

- Policy: É um conjunto de regras que definem quem pode acessar um recurso e o que a pessoa pode fazer com ele.

- Beneficios de controle de acesso a nuvem
    - Primeiro, ela fornece controle de acesso granular, o que significa que você pode atribuir funções e permissões em diferentes níveis da hierarquia, como no nível da pasta, do projeto ou de um recurso individual.
    - Segundo, como a hierarquia de recursos segue regras de herança e propagação, as permissões definidas em níveis superiores são herdadas de modo automático pelos recursos de nível inferior.
    - Terceiro, a hierarquia de recursos aumenta a segurança e a conformidade através de princípios de privilégio mínimo.
    - Por fim, a hierarquia de recursos oferece visibilidade e recursos de auditoria avançados.

- Recursos de controle de gastos
    - Rosource Quota Policies: você define limites para a quantidade de recursos que podem ser usados por um projeto ou usuário.
    - Budget threshold rules: Com elas, você define alertas para receber notificações quando os custos da nuvem excederem um determinado limite.
    - Cloud Billing reports: oferecem um método reativo para monitorar e entender o que já foi gasto nos recursos do Google Cloud e otimizar os custos.

- CUD Commited Use Discounts (Descontos por compromisso): Oferece preços com desconto em troca do compromisso de usar um nível mínimo de recursos por um período específico.

### Questões

1. Qual recurso permite definir alertas para quando os custos da nuvem excederem um determinado limite?

    :black_large_square: Relatórios de faturamento

    :white_check_mark: Regras de limite orçamentário

    :black_large_square: Previsão de custos

    :black_large_square: Recomendações de otimização de custos

---

2. Por que é benéfico que a hierarquia de recursos do Google Cloud siga regras de herança e propagação?

    :black_large_square: Recursos em níveis mais baixos podem melhorar o desempenho dos aplicativos em nuvem.

    :black_large_square: A propagação mais rápida pode simplificar uma migração para a nuvem.

    :white_check_mark: As permissões definidas em níveis superiores da hierarquia de recursos são herdadas automaticamente pelos recursos de nível inferior.

    :black_large_square: A herança na hierarquia reduz o custo geral da computação em nuvem.

---

3. Qual termo descreve um hub centralizado dentro de uma organização composto por uma parceria entre finanças, tecnologia e funções de negócios?

    :black_large_square: Centro de inovação

    :black_large_square: Centro do hub

    :white_check_mark: Centro de excelência

    :black_large_square: Centro de competência

---

4. Qual das opções abaixo oferece um método reativo de monitorar e entender o que você gastou em recursos do Google Cloud e ajuda a otimizar seus custos?

    :black_large_square: Previsão de custos

    :black_large_square: Uso de recursos

    :white_check_mark: Relatórios do Cloud Billing

    :black_large_square: Calculadora de preços do Google Cloud

---

5. Qual recurso permite definir limites para a quantidade de recursos que podem ser usados por um projeto ou usuário?

    :black_large_square: Limites de faturamento

    :white_check_mark: Políticas de cotas

    :black_large_square: Relatórios de faturamento

    :black_large_square: Descontos por compromisso de uso

---

6. Qual ferramenta do Google Cloud permite estimar como as mudanças no uso da nuvem afetarão os custos?

    :black_large_square: Cloud Trace

    :white_check_mark: Calculadora de preços do Google Cloud

    :black_large_square: Cloud Monitoring

    :black_large_square: Cloud Billing

---

7. O que representa o nível mais baixo na hierarquia de recursos do Google Cloud?

    :black_large_square: Pastas

    :black_large_square: Nó da organização

    :white_check_mark: Recursos

    :black_large_square: Projetos

## 2º Módulo - Excelência operacional e confiabilidade em escala

- Unir os desenvolvedores e os operadores (DevOps)

- SRE: Engenharia de confiabilidade de site que garante a confiabilidade, a disponibilidade e a eficiência dos sistemas de software e serviços implantados na nuvem.

- Four golden signals
    - Latência: Mede o tempo que uma parte específica de um sistema leva para retornar um resultado.
    - Tráfego: Mede quantas solicitações chegam ao sistema.
    - Saturação: Mede o quão próximo um sistema está de atingir sua capacidade.
    - Erros: São eventos que medem as falhas do sistema ou outros problemas.

- Conceitos de SRE:
    - SLI (Service Level Indicators): Consistem em medidas que mostram o desempenho de um sistema ou serviço e as métricas específicas associadas, como tempo de resposta, taxa de erro ou percentual de atividade, que é a quantidade de tempo que um sistema fica disponível para uso.
    - SLO (Service Level Objective): São as metas de desempenho definidas para um sistema com base nos SLIs. Eles definem o nível de confiabilidade ou de desempenho desejado.
    - SLA (Service Level Agreements): Descrevem as promessas e garantias relativas à qualidade do serviço. Os SLAs incluem os SLOs definidos, as métricas de desempenho, as garantias de atividade e quaisquer penalidades ou soluções resultantes caso o provedor não cumpra esses compromissos.

- High availability (Alta disponibilidade): Consiste na capacidade que um sistema tem de permanecer operacional e acessível aos usuários, mesmo em caso de falhas de hardware ou software.

- Disaster Recobery (Recuperação de desastre): Se refere ao processo de restauração de um sistema para um estado funcional após uma grande interrupção ou desastre.

- Redundância: Está relacionada à duplicação de componentes ou recursos críticos a fim de fornecer alternativas de backup.

- Replicação: Envolve a criação de várias cópias de dados ou serviços e a distribuição delas em diferentes servidores ou locais.

- Regiões: Os provedores de serviços em nuvem oferecem diversas regiões ou locais de data center espalhados por diferentes áreas geográficas.

- Infra escalavel: São capazes de lidar com diversas cargas de trabalho e acomodar o aumento da demanda sem comprometer o desempenho ou a disponibilidade.

- Backups: É essencial que as organizações realizem backups regulares de dados e configurações críticas para garantir que, em caso de perda de dados, falhas de hardware ou ataques cibernéticos, seja possível restaurar os sistemas para um estado anterior.

- Observabilidade: Envolve a coleta, a análise e a visualização de dados de várias fontes em um sistema para receber insights sobre o desempenho, a integridade e o comportamento dele.

- Pacote de operações - Monitoramento GCP
    - Cloud Monitoring: Fornece uma perspectiva abrangente da infraestrutura e dos aplicativos na nuvem. Ele coleta métricas, registros e traces dos aplicativos e das infraestruturas e fornece insights sobre o desempenho, a integridade e a disponibilidade deles.
    - Cloud Logging: Coleta e armazena todos os registros de aplicativos e infraestruturas.
    - Cloud Trace: Ajuda a identificar gargalos de desempenho em aplicativos.
    - Cloud Profiler: Identifica o uso de energia de CPU, memória e outros recursos por um aplicativo.
    - Error Reporting: Conta, analisa e agrega em tempo real as falhas na execução de serviços em nuvem.

- Google Cloud Customer Care:
    - Basic: O Suporte Básico é gratuito para todos os clientes do Google Cloud. Ele dá acesso à documentação, ao Suporte da comunidade e do Cloud Billing e às recomendações do Active Assist.
    - Standard: O Suporte Padrão é recomendado para cargas de trabalho em desenvolvimento. É possível começar a usar a nuvem com acesso ilimitado ao suporte técnico, o que permite solucionar problemas, fazer testes e conhecer os recursos.
        - Casos P2: Quatro horas
        - Casos P3: Oito horas
        - Casos P4: Oito horas
        - Respostas durante o horário comercial em dias úteis para problemas de alto impacto
        - Atendimento somente em inglês
    - Enhanced: O Suporte Avançado foi pensado para cargas de trabalho em produção. Ele conta com tempos de resposta rápidos e serviços adicionais para otimizar sua experiência com um suporte robusto e de alta qualidade.
        - Casos P1: Uma hora
        - Casos P2: Quatro horas
        - Casos P3: Oito horas
        - Casos P4: Oito horas
        - Respostas 24 horas para problemas de alto impacto e impacto crítico
        - Inglês, japonês, mandarim, coreano e francês
    - Premium: O Suporte Premium foi feito para empresas com cargas de trabalho essenciais. Ele tem os menores tempos de resposta, suporte baseado no cliente e um Gerente técnico de contas exclusivo.
        - Casos P1: 15 minutos
        - Casos P2: Duas horas
        - Casos P3: Quatro horas
        - Casos P4: Oito horas
        - Respostas 24 horas para problemas de alto impacto e impacto crítico
        - Inglês, japonês, mandarim, coreano e francês

- Abertura de cases: Menos no Basic

### Questões

1. O pacote de operações do Google Cloud oferece um conjunto abrangente de ferramentas de monitoramento, geração de registros e diagnóstico. Qual ferramenta coleta dados de latência de aplicativos e fornece insights sobre o desempenho deles?

    :black_large_square: Cloud Profiler

    :black_large_square: Cloud Logging

    :black_large_square: Cloud Monitoring

    :white_check_mark: Cloud Trace

---

2. O que a ferramenta Cloud Profiler faz?

    :white_check_mark: Ela identifica quanta energia, memória e outros recursos de CPU um aplicativo usa.

    :black_large_square: Ela conta, analisa e agrega as falhas na execução de serviços em nuvem em tempo real.

    :black_large_square: Ela fornece uma perspectiva abrangente da sua infraestrutura e aplicativos em nuvem.

    :black_large_square: Ela coleta e armazena todos os registros de aplicativos e infraestrutura.

---

3. Um dos quatro sinais de ouro é a latência. O que a latência mede?

    :black_large_square: As falhas do sistema ou outros problemas.

    :black_large_square: Quantas solicitações chegam a um sistema.

    :black_large_square: A proximidade de um sistema da capacidade.

    :white_check_mark: Quanto tempo leva para uma parte específica de um sistema retornar um resultado.

---

4. Como a replicação ajuda no projeto de infraestrutura e processos resilientes e tolerantes a falhas em um ambiente de nuvem?

    :black_large_square: Ela monitora e controla o tráfego de rede que entra e sai com base em regras de segurança predefinidas.

    :black_large_square: Ela duplica componentes ou recursos críticos para fornecer alternativas de backup.

    :white_check_mark: Ela cria várias cópias de dados ou serviços e as distribui em diferentes servidores ou locais.

    :black_large_square: Ela dimensiona a infraestrutura para lidar com diversas cargas de trabalho e acomodar o aumento da demanda.

---

5. Qual métrica mostra o desempenho de um sistema ou serviço?

    :white_check_mark: Indicadores de nível de serviço

    :black_large_square: Contratos de nível de serviço

    :black_large_square: Acordos de nível de serviço

    :black_large_square: Objetivos de nível de serviço

---

6. De quem é a função de garantir a confiabilidade, disponibilidade e eficiência dos sistemas e serviços de software implantados na nuvem?

    :black_large_square: Engenheiro de segurança em nuvem

    :black_large_square: Cloud Architect

    :white_check_mark: Engenheiro de confiabilidade do site

    :black_large_square: Engenheiro de DevOps

---

7. Quais destas medidas devem ser automatizadas com frequência e armazenadas em locais geograficamente separados para permitir a rápida recuperação de desastres ou falhas?

    :black_large_square: Arquivos de registro

    :black_large_square: Patches de segurança

    :white_check_mark: Backups

    :black_large_square: Dados de inventário

---

8. Por que encaminhar um tíquete de suporte para um supervisor nem sempre é o melhor a se fazer para tentar resolver um problema?

    :black_large_square: Isso pode diminuir o número de máquinas virtuais disponíveis.

    :black_large_square: Isso pode aumentar o custo mensal dos planos de suporte.

    :white_check_mark: Isso pode atrapalhar o fluxo de trabalho da equipe de atendimento ao cliente e atrasar a resolução de outros casos.

    :black_large_square: Isso pode resultar no aumento do consumo de energia, impactando a neutralidade de carbono.

---

9. Qual nível de suporte do Google Cloud Customer Care foi desenvolvido para empresas com cargas de trabalho críticas e apresenta o tempo de resposta mais rápido?

    :black_large_square: Suporte Avançado

    :black_large_square: Suporte Básico

    :white_check_mark: Suporte Premium

    :black_large_square: Suporte Padrão

## 3º módulo - Sustentabilidade com o Google Cloud

- Primeiro data center a receber a certificação ISO 14001 (Trata-se de um padrão que define a estrutura para que uma organização melhore seu desempenho ambiental aumentando a eficiência no uso dos recursos e reduzindo o desperdício.)

- Na primeria década da fundação do Google ela foi a primeira grande empresa a se tornar neutra em carbono.

- Em 20 anos, fomos a primeira empresa a usar energia 100% renovável.

- Até 2030, pretendem ser a primeira grande empresa a operar sem carbono.

### Questões

1. Os data centers do Google foram os primeiros a conquistar a certificação ISO 14001. Qual é o propósito deste padrão?

    :black_large_square: É uma estrutura de compras sustentáveis, que é o processo de aquisição de bens e serviços minimizando os impactos ambientais e sociais.

    :black_large_square: É uma estrutura para identificar, prever e avaliar os impactos ambientais de um projeto proposto.

    :black_large_square: É uma estrutura relacionada à pegada de carbono que calcula a quantidade total de emissões de gases de efeito estufa associadas a um produto, serviço ou organização.

    :white_check_mark: Ele representa uma estrutura para uma organização melhorar o próprio desempenho ambiental aprimorando a eficiência dos recursos e reduzindo resíduos.

---

2. Qual meta de sustentabilidade o Google pretende alcançar até 2030?

    :black_large_square: Ser a primeira grande empresa a gerir a própria usina eólica.

    :black_large_square: Ser a primeira grande empresa a alcançar 100% de energia renovável.

    :white_check_mark: Ser a primeira grande empresa a operar totalmente livre de carbono.

    :black_large_square: Ser a primeira grande empresa a ser neutra em carbono.

---

3. Kaluza é uma solução de carregamento inteligente para veículos elétricos. Como ela usa o BigQuery e o Looker Studio?

    :black_large_square: Ela usa o BigQuery e Looker Studio para conteinerizar cargas de trabalho.

    :black_large_square: Ela usa o BigQuery e Looker Studio para criar e implantar modelos de machine learning.

    :white_check_mark: Ela usa o BigQuery e Looker Studio para criar painéis com insights operacionais granulares.

    :black_large_square: Ela usa o BigQuery e Looker Studio para cumprir regulamentações governamentais.