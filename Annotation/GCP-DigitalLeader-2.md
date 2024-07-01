# Exploring Data Transformation with Google Cloud

## 1º Módulo - O valor dos dados

- Tipos de dados:
    - **Estruturados:** São altamente organizados e bem definidos. Normalmente, eles são armazenados em uma tabela com relações entre diferentes linhas e colunas, como em uma planilha ou banco de dados.
    - Semi estruturados: Estão entre os estruturados e não estruturados. Eles são organizados em uma hierarquia, mas sem diferenciação total ou ordem específica. Os exemplos incluem e-mails, arquivos HTML, JSON e XML.
    - Não estruturados: são informações que não têm um modelo de dados predefinido ou não são organizadas de forma predefinida. As categorias incluem texto, que é mais comum, é gerado com mais frequência e é coletado de fontes como documentos, apresentações e postagens de redes sociais.

- Locais de armazenamento de dados:
    - Banco de dados: É uma coleção organizada de dados armazenados em tabelas e acessados eletronicamente em um sistema de computador.
        - Banco de dados relacional (CloudSQL e Cloud Spanner): armazenam e concedem acesso a pontos de dados relacionados entre si. Isso significa armazenar informações em tabelas, linhas e colunas que têm um esquema bem definido que representa a estrutura ou a configuração lógica do banco de dados.
        - Banco de dados não relacional (BigTable): Às vezes conhecido como banco de dados NoSQL, é menos estruturado em formato e não usa um formato tabular de linhas nem colunas como bancos de dados relacionais.
    - Data Warehouse (BigQuery): é um sistema empresarial usado para análise e relatório de dados estruturados e semiestruturados de várias origens. 
    - Data Lake (Cloud Storage): é um repositório feito para ingerir, armazenar, explorar, processar e analisar qualquer tipo ou volume de dados brutos, seja qual for a origem, como sistemas operacionais, fontes da Web, mídias sociais e Internet das Coisas (IoT).

- Dados
    - Dados próprios: são conjuntos de dados dos clientes reservados que uma empresa coleta do cliente ou de interações ou transações com o público.
    - Dados secundários: geralmente são dados próprios de outra organização, como um parceiro.
    - Dados de terceiros: que são conjuntos de dados coletados e gerenciados por organizações que não interagem diretamente com os negócios nem com os clientes de uma organização.

- Linha de dados
    - Data Genesis: é a criação inicial de uma unidade de dados.
    - Data Collection: traz essa unidade inicial de dados para a linha de montagem pela ingestão.
    - Data Processing: é onde os dados brutos coletados são convertidos para uma forma que possibilita a extração de insights.
    - Data Storage: é o local em que os dados podem ser encontrados e estão prontos para análise e ação.
    - Data Analysis: oferece orientação para ações direcionadas aos negócios.
    - Data Activation: Quando uma análise é feita, ela precisa ser enviada para os procedimentos relevantes do negócio

- Governaça de Dados: significa definir padrões internos, políticas de dados que se aplicam a forma como os dados são coletados, armazenados, processados e descartados.

<br>

### Questões

1. Qual o repositório criado para ingerir, armazenar, explorar, processar e analisar qualquer tipo ou volume de dados brutos, independentemente da origem?

    :black_large_square: Arquivo de dados

    :white_check_mark: Data lake

    :black_large_square: Banco de dados

    :black_large_square: Data warehouse

---

2. Qual opção representa os conjuntos de dados reservados que a empresa coleta das interações e transações com clientes ou público-alvo?

    :black_large_square: Dados secundários

    :black_large_square: Dados de terceiros

    :white_check_mark: Dados próprios

---

3. Novas ferramentas da nuvem ajudam a aproveitar o potencial dos dados não estruturados. Qual caso de uso abaixo melhor demonstra isso?

    :black_large_square: Analisar os valores dos históricos de vendas para prever tendências futuras

    :black_large_square: Usar coordenadas de GPS para criar um app de caronas

    :black_large_square: Criar visualizações usando dados climáticos sazonais

    :white_check_mark: Analisar postagens de redes sociais para identificar o sentimento associado a uma marca

---

4. Os dados brutos coletados são convertidos para uma forma que possibilita a extração de insights em qual dessas etapas da cadeia de valor dos dados?

    :black_large_square: Análise de dados

    :white_check_mark: Processamento de dados

    :black_large_square: Gênese de dados

    :black_large_square: Armazenamento de dados

---

5. Uma loja on-line usa uma ferramenta de análises inteligentes para ingerir dados de comportamento do cliente em tempo real e, com isso, mostrar sugestões aprimoradas para alguns usuários. Como o machine learning pode ajudar nisso?

    :black_large_square: O machine learning pode ser usado para recomendar os mesmos produtos para todos os usuários, independentemente das preferências ou comportamentos deles.

    :white_check_mark: Com o machine learning, cada clique do usuário aprimora a personalização da experiência no site.

    :black_large_square: O machine learning pode ajudar a identificar o comportamento do usuário em tempo real, mas não faz sugestões personalizadas com base em dados.

    :black_large_square: Com o machine learning, as transações do cartão de crédito do usuário podem ser analisadas para identificar as compras comuns.

---

6. Uma empresa de energia solar quer analisar dados meteorológicos para entender o impacto sazonal nos negócios. Em qual plataforma é possível encontrar conjuntos de dados climáticos gratuitos?

    :white_check_mark: Google Cloud Marketplace

    :black_large_square: Console do Google Cloud

    :black_large_square: Google Play

    :black_large_square: App Engine

---

7. O que é governança de dados?

    :black_large_square: É o processo de analisar dados para receber insights e tomar decisões fundamentadas

    :white_check_mark: É o processo de configurar as políticas de dados internas e garantir a conformidade com padrões externos

    :black_large_square: É o processo de coletar e armazenar dados para uso futuro

    :black_large_square: É o processo de excluir dados desnecessários para economizar espaço de armazenamento

---

8. Qual tipo de dado é altamente organizado e bem definido?

    :white_check_mark: Dados estruturados

    :black_large_square: Dados não estruturados

    :black_large_square: Dados semiestruturados

    :black_large_square: Um híbrido de dados estruturados, semiestruturados e não estruturados

---

9. Qual é a solução de armazenamento em data warehouse moderna e sem servidor do Google Cloud?

    :black_large_square: Compute Engine

    :white_check_mark: BigQuery

    :black_large_square: Cloud Storage

    :black_large_square: Vertex AI

---

10. Uma empresa de seguro para carros tem um grande banco de dados que armazena informações dos clientes, incluindo os veículos e acionamentos anteriores. A estrutura do banco de dados mostra que a informação é armazenada em tabelas, linhas e colunas. Que tipo de banco de dados é este?

    :white_check_mark: Um banco de dados relacional

    :black_large_square: Um banco de dados de objetos

    :black_large_square: Um banco de dados não relacional

    :black_large_square: Um banco de dados XML

<br>

## 2º Módulo - Soluções de gerenciamento de dados do Google Cloud

- Tipo de recursos para armazenamento de dados
    
    - Cloud Storage: que é um serviço que oferece armazenamento de objetos altamente disponível e durável a desenvolvedores e organizações de TI. (Dados não estruturados)
        - Armazenamento de objetos: É uma arquitetura de computador de armazenamento de dados que gerencia os dados como objetos, em vez de armazenamento de arquivos. Esses objetos são armazenados em formato de pacote que contém o formato binário dos dados reais e metadados associados relevantes. Esses tipos de dados são conhecidos como não estruturados. 
        
        - Tipos de armazenamento do Cloud Storage:
            - Standard Storage: Ela é considerada ideal para dados acessados frequentemente.
            - Nearline Storage: Essa opção é melhor para armazenar dados acessados com pouca frequência, como leitura ou modificação de dados em média uma vez por mês ou menos.
            - Coldline Storage: Ela também é uma opção de baixo custo para armazenamento de dados acessados com pouca frequência. destinada a leitura ou modificação de dados no máximo uma vez a cada 90 dias.
            - Archive Storage: Essa é a opção de menor custo, ideal para arquivamento de dados, backup on-line e recuperação de desastres. opção ideal para dados que você planeja acessar menos de uma vez por ano
    
    - Cloud SQL (Dados estruturados) (Disponibilidade 99,95%)
        - MySQL -> PostgreSQL -> SQL Server
    
    - Cloud Spanner (Disponibilidade 99,999%) um serviço de banco de dados relacional totalmente gerenciado que escalona horizontalmente para lidar com picos inesperados de negócios.
        - Se você não precisa de escalonamento horizontal ou de um sistema disponível globalmente, o Cloud SQL é uma solução econômica.
        - Se você ultrapassar o limite de um banco de dados relacional, fragmentar os bancos de dados para conseguir alto desempenho de capacidade de processamento, precisar de consistência transacional, dados globais e consistência forte utilize Cloud Spanner
    
    - Big Query: é um data warehouse totalmente gerenciado. Como já aprendemos, o data warehouse é um grande repositório que contém petabytes de dados coletados de uma ampla variedade de fontes dentro de uma organização e é usado para orientar decisões de gerenciamento.
    
    - Fire Store: é um banco de dados em nuvem NoSQL flexível e escalonável horizontalmente para armazenamento e sincronização de dados em tempo real.
    
    - Cloud Bigtable: o serviço de banco de dados de Big Data NoSQL do Google. Bigtable responde às solicitações com rapidez e alta capacidade de processamento, ou seja, ele pode enviar e receber grandes quantidades de dados. Se você estiver trabalhando com mais de um terabyte de dados estruturados ou semiestruturados.
    
- Lift and shift: É aqui que os bancos de dados são migrados de ambientes de nuvem no local e privados para o mesmo tipo de banco de dados hospedado por um provedor de nuvem pública, como o Google Cloud.

- Migração de dados gerenciada: permite a migração de bancos de dados do SQL Server, MySQL, PostgreSQL e outros para um banco de dados Google Cloud totalmente gerenciado.

<br>

### Questões

1. Qual estratégia define a migração de bancos de dados de ambientes locais e de nuvens privadas para o mesmo tipo de banco de dados hospedado por um provedor de nuvem pública?

    :black_large_square: Permanência no local

    :black_large_square: Refatoração

    :black_large_square: Migração de bancos de dados gerenciados

    :white_check_mark: Migração lift-and-shift

---

2. Dados em forma de vídeo, foto e gravação de áudio são os mais adequados para o armazenamento de objetos. Qual o produto ideal para armazenar esse tipo de dado?

    :black_large_square: Firestore

    :white_check_mark: Cloud Storage

    :black_large_square: Cloud SQL

    :black_large_square: BigQuery

---

3. Qual produto do Google Cloud pode ser usado para sincronizar dados entre bancos de dados, sistemas de armazenamento e aplicativos?

    :black_large_square: Pub/Sub

    :white_check_mark: Datastream

    :black_large_square: Dataproc

    :black_large_square: Dataprep

---

4. O BigQuery funciona em um ambiente multicloud. Como este recurso beneficia as organizações?

    :black_large_square: O suporte multicloud no BigQuery deve ser usado apenas em cenários de recuperação de desastres.

    :black_large_square: O BigQuery ajuda as organizações a poupar custos porque limita o número de provedores de nuvem usados.

    :white_check_mark: As equipes de dados podem eliminar os silos de dados fazendo análises em vários provedores de nuvem.

    :black_large_square: A segurança é mais eficiente quando o BigQuery é executado em ambientes locais.

---

5. Quais são os dois serviços que o BigQuery oferece?

    :black_large_square: Rede e armazenamento

    :black_large_square: Migração e análise

    :white_check_mark: Armazenamento e análise

    :black_large_square: Computação e análise

---

6. Qual é o serviço de banco de dados de Big Data do Google usado em vários dos principais serviços do Google, como Pesquisa, Analytics, Plataforma Google Maps e Gmail?

    :black_large_square: Cloud Spanner

    :black_large_square: Cloud SQL

    :black_large_square: Cloud Storage

    :white_check_mark: Cloud Bigtable

---

7. A análise de dados de uma loja on-line precisa gerar um relatório de vendas ao final de cada trimestre. Qual classe do Cloud Storage a loja precisa usar para acessar os dados a cada 90 dias?

    :black_large_square: Archive

    :black_large_square: Nearline

    :black_large_square: Standard

    :white_check_mark: Coldline

---

8. Qual é a melhor opção de armazenamento com base em SQL para cargas de trabalho transacionais que precisam de escalabilidade global?

    :black_large_square: Cloud Bigtable

    :black_large_square: Cloud SQL

    :white_check_mark: Cloud Spanner

    :black_large_square: Firestore

---

9. Qual característica vale para todas as classes do Cloud Storage?

    :black_large_square: Limite máximo de armazenamento

    :white_check_mark: Redundância geográfica se os dados forem armazenados em um local multirregional ou birregional

    :black_large_square: Acessibilidade em apenas uma região

    :black_large_square: Latência alta e baixa durabilidade

---

10. Qual é a melhor opção de armazenamento com base em SQL para cargas de trabalho transacionais que precisam de escalonabilidade local ou regional?

    :black_large_square: Cloud Bigtable

    :black_large_square: Cloud Storage

    :white_check_mark: Cloud SQL

    :black_large_square: Cloud Spanner

<br>

## 3º Módulo - Como ter dados eficientes e acessíveis

- Looker: é uma plataforma de Business Intelligence do Google Cloud projetada para ajudar pessoas e equipes a analisar, visualizar e compartilhar dados.

- Streaming Analytics: para analisar dados em tempo real e fornecer insights sobre uma ampla variedade de atividades, como medição, atividade do servidor, geolocalização de dispositivos ou cliques para acessar o site. Os casos de uso incluem e-commerce.

- O Google Cloud oferece dois produtos principais de análise de streaming para ingerir, processar, e analisar streams de eventos em tempo real, o que deixa os dados mais úteis e acessíveis desde o momento em que são gerados.
    - Pub/Sub: é um serviço de distribuição que pode receber mensagens de vários streams de dispositivos, como eventos de jogos, dispositivos IoT e aplicativos.
    - Dataflow: cria um pipeline para processar dados tanto de streaming quanto em lote. Nesse caso, "processar" significa as etapas para extrair, transformar e carregar dados, às vezes chamadas de ETL. Uma solução conhecida para o design de pipelines é o Apache Beam.

<br>

### Questões

1. Qual plataforma de Business Intelligence do Google Cloud foi projetada para ajudar usuários e equipes a analisar, visualizar e compartilhar dados?

    :black_large_square: Dataplex

    :white_check_mark: Looker

    :black_large_square: Dataflow

    :black_large_square: Cloud Storage

---

2. A análise de streaming é o processamento e a análise de registros de dados continuamente, em vez de em lotes. Qual dessas opções é uma fonte de dados de streaming?

    :black_large_square: Endereços de e-mail do cliente

    :black_large_square: Registros de folhas de pagamento

    :black_large_square: Resultados de exames médicos

    :white_check_mark: Sensores de temperatura

---

3. No contexto do processamento de dados, o que significa ETL?

    :white_check_mark: Extract, transform, and load (Extração, transformação e carregamento)

    :black_large_square: Enhanced transaction logic (Lógica de transação aprimorada)

    :black_large_square: Enrichment, tagging, and labeling (Aprimoramento, marcação e rotulagem)

    :black_large_square: Event-time logic (Lógica de hora do evento)

---

4. Qual é o serviço de mensagens distribuídas do Google Cloud que pode receber mensagens de vários streams de dispositivos, como eventos de jogos, dispositivos da Internet das Coisas (IoT) e streams de aplicativos?

    :black_large_square: Dataplex

    :black_large_square: Dataproc

    :black_large_square: Looker

    :white_check_mark: Pub/Sub

---

5. Qual afirmação sobre o Dataflow é verdadeira?

    :black_large_square: É um data warehouse baseado na nuvem usado para armazenar e analisar dados de streaming e em lote.

    :black_large_square: É um serviço para receber mensagens de vários streams de dispositivos.

    :black_large_square: Facilita a limpeza e a transformação de dados usando ferramentas visuais e sugestões baseadas em machine learning.

    :white_check_mark: Cuida da configuração e da manutenção da infraestrutura para pipelines de processamento.

---

6. Qual recurso do Looker facilita a integração com fluxos de trabalho atuais e o compartilhamento com várias equipes de uma organização?

    :black_large_square: Cria visualizações fáceis de entender.

    :black_large_square: Tem suporte para mais de 60 bancos de dados de SQL.

    :black_large_square: É econômico.

    :white_check_mark: É 100% baseado na Web.