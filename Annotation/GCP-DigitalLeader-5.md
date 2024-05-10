# Trust and Security with Google Cloud

## 1º módulo - Confiança e segurança na nuvem

- Conceitos de segurança em nuvem
    - Acessos privilegiados
    - Privilégios minimos
    - Arquitetura de confiança Zero
    - Segurança por padrão
    - Postura de segurança
    - Resiliência cibernética

- Medidas de segurança
    - Firewall
    - Criptografia
    - Descriptografia

- Aspectos de segurança (CIA)
    - Confidencialidade
    - Integridade
    - Disponibilidade

- Diferenças entre segurança da nuvem e segurança tradicional (Local)
    - Localização
    - Responsabilidade
    - Escalonabilidade
    - Manutenção e Atualização
    - Despesasa de capital

- Ameaças cibernéticas
    - Engenharia Social
    - Dano Fisico
    - Virus, Malware e Ransomware
    - Sistemas vulneraveis de terceiros
    - Erros de configuração

### Questões

1. Em qual ameaça cibernética a vítima é obrigada a pagar um resgate para reaver o acesso aos arquivos e sistemas?

(X) Ransomware

Cavalo de troia

Spyware

Vírus

2. Qual definição a seguir é a melhor descrição de um firewall?

Um modelo de segurança que pressupõe que nenhum usuário ou dispositivo é confiável.

Um software que criptografa dados para que não sejam lidos por usuários não autorizados.

(X) Um dispositivo de segurança de rede que monitora e controla o tráfego de rede que entra e sai com base em regras predefinidas.

Um conjunto de medidas de segurança criado para proteger uma rede ou um sistema de computação contra ataques cibernéticos.

3. Em qual ameaça cibernética comum os usuários são enganados para que revelem informações sensíveis ou realizem ações que comprometam a segurança?

Erro de configuração

Malware

(X) Phishing

Ransomware

4. Qual item a seguir é um benefício da segurança na nuvem em relação à segurança tradicional no local?

(X) Aumento da escalonabilidade.

As atualizações de segurança são instaladas apenas uma vez por semana.

Grande investimento inicial de capital.

Acesso físico ao hardware.

5. Quais são os três aspectos de segurança na nuvem que compõem as bases da tríade CIA?

Contêineres, infraestrutura e arquitetura

Certificados, inteligência e autenticação

Conformidade, identidade e gerenciamento de acesso

(X) Confidencialidade, integridade e disponibilidade

6. Qual princípio de segurança na nuvem está relacionado à manutenção de dados precisos e confiáveis?

Compliance

Confidencialidade

(X) Integridade

Controle

7. Qual princípio de segurança na nuvem garante que as práticas e medidas de segurança estejam alinhadas aos padrões e diretrizes estabelecidos?

(X) Compliance

Controle

Integridade

Confidencialidade

8. Qual ameaça cibernética ocorre quando são cometidos erros durante a configuração de recursos que acabam expondo dados sensíveis e sistemas a acesso não autorizado?

Phishing

Malware

Vírus

(X) Erros de configuração

9. Qual princípio de segurança defende que os usuários tenham apenas o acesso de que precisam para desempenhar suas funções?

Acesso privilegiado

Arquitetura de confiança zero

Segurança por padrão

(X) Privilégio mínimo

10. Qual é a responsabilidade do provedor de nuvem em um modelo de segurança de nuvem?

Gerenciar o acesso dos usuários do cliente.

Proteger os dados do cliente.

(X) Manter a infraestrutura do cliente.

Configurar os aplicativos do cliente.

## 2º módulo - Infraestrutura confiável do Google

- Infra confiavel
    - Arquitetura de confiança zero nos datacenters
    - Mais de 30 datacenters
    - Datacenter finlandia destaque
    - PUE - Power usage effectiveness (eficiência no uso de energia)

- KMS Cloud Key Management Service - Recurso de criptografia de dados
    - o Google criptografa os dados em repousos automaticamente sem custo adicional.

- Principal recurso utilizado pela google de criptografia é o AES (Advanced Encryption Standard)

- Google criptografa os dados em "repouso" em "transito" e em "uso"

- Os 3 A: Autenticação - Autorização e Auditoria

- IAM (Identity and Access Management): Para ter controle granular sobre quem está autorizado a acessar os recursos do Google Cloud e quais ações são permitidas neles

- Zero Trust: Recurso: BeyondCorp Entrerprise é possível implementar um modelo de segurança de confiança zero.

- Segurança de rede: Recursos: Cloud VPN e Cloud Interconnect que permitem estabelecer conexões seguras entre suas redes locais e os recursos do Google Cloud.

- Proteção de perimetro com Firewall e Virtual Private Cloud 

- Shared VPC que é como ter uma grande cerca separando cada projeto do Google Cloud para que eles possam funcionar independentemente e com segurança.

- Cloud Armor: firewall de aplicativos da Web. fornecendo uma proteção robusta contra DDoS.

- SecOps - Security Operation
    - Vulnerability Management: é o processo de identificar e corrigir vulnerabilidades de segurança em aplicativos e infraestruturas na nuvem
        - Security Command Center (SCC) oferece uma visão centralizada da sua postura de segurança.
    Log Management
        - Cloud Logging: um serviço para coletar e analisar registros de segurança de todo o seu ambiente do Google Cloud.
    - Incidente Response
    - Educação dos usuários

### Questões

1. Qual item a seguir é um potente algoritmo de criptografia em que governos e empresas do mundo todo confiam?

(X) Padrão de criptografia avançada (AES)

Criptografia isomórfica (IE)

Criptografia baseada em reticulados (LBC)

Criptografia pós-quântica (PQC)

2. Selecione a afirmação correta sobre o Identity and Access Management (IAM).

O IAM é um serviço em nuvem que criptografa dados em repouso e em trânsito baseados na nuvem.

O IAM é um sistema que detecta tráfego malicioso e impede que ele entre em uma rede da nuvem.

O IAM é uma solução para gerenciamento de eventos e informações de segurança na nuvem que coleta e analisa dados de registro de dispositivos e aplicativos de segurança na nuvem.

(X) O IAM fornece controle granular de quem tem acesso aos recursos do Google Cloud e o que é possível fazer com esses recursos.

3. O Google Cloud criptografa dados em vários estados. Qual estado indica que os dados estão sendo processados ativamente por um computador?

Dados em trânsito

Dados em repouso

(X) Dados em uso

Data lake

4. Qual prática envolve uma combinação de processos e tecnologias que ajudam a reduzir o risco de vazamento de dados, interrupções no sistema e outros incidentes de segurança na nuvem?

Gerenciamento de postura de segurança na nuvem (CSPM)

Segurança de confiança zero

(X) Operações de segurança (SecOps)

Engenharia de confiabilidade do site (SRE)

5. Qual recurso de segurança adiciona uma camada extra de proteção nos sistemas baseados na nuvem?

(X) Verificação em duas etapas (2SV)

Prevenção contra perda de dados (DLP)

Firewall como serviço (FaaS)

Gerenciamento de eventos e informações de segurança (SIEM)

6. Qual aspecto do Gerenciamento de identificação do Cloud verifica a identidade de usuários e sistemas?

Autorização

Auditoria

(X) Autenticação

Accounting

7. Qual produto do Google Cloud fornece proteção robusta contra ataques distribuídos de negação de serviço (DDoS)?

(X) Google Cloud Armor

Cloud Load Balancing

Cloud IAM

Cloud Monitoring

8. Qual métrica do Google Cloud mede a eficiência dos data centers para alcançar as metas de economia de custos e reduzir a pegada de carbono?

Custo total de propriedade (TCO)

Proporção de eficiência energética (EER)

(X) Eficiência no uso de energia (PUE)

Eficiência da infraestrutura do data center (DCiE)

## 3º Módulo - Compliance e princípios de confiança do Google Cloud

- Principios do google
    - Primeiro: os dados são seus, e não do Google.
    - Segundo: o Google não vende os dados dos clientes a terceiros.
    - Terceiro: o Google Cloud não usa dados dos clientes em publicidade.
    - Quarto: todos os dados dos clientes são criptografados por padrão.
    - Quinto: oferecemos proteção contra o acesso interno aos seus dados.
    - Sexto: nunca damos a entidades governamentais acesso "backdoor" aos seus dados.
    - Sete: Nossas práticas de privacidade são auditadas de acordo com padrões internacionais.

- Data sovereignty: refere-se ao conceito legal de que os dados estão sujeitos às leis e regulamentações do país onde eles residem.

- Data residency: se refere ao local físico onde os dados são armazenados ou tratados.

- Compliance Resource Center: Esse hub abrangente fornece informações detalhadas sobre as certificações e padrões de conformidade que atendemos.

- Compliance Reports Manager: uma ferramenta potente à sua disposição. Essa plataforma intuitiva oferece acesso fácil e sob demanda a recursos críticos de conformidade, sem custo financeiro adicional.

### Questões

1. Qual item é um dos sete princípios de confiança do Google Cloud?

(X) Todos os dados dos clientes são criptografados por padrão.

O Google dá acesso backdoor a entidades governamentais mediante solicitação.

O Google Cloud usa os dados dos clientes para publicidade.

O Google vende os dados dos clientes a terceiros.

2. Qual termo descreve o conceito de que os dados estão sujeitos às leis e regulamentações do país onde residem?

(X) Soberania de dados

Redundância de dados

Residência dos dados

Consistência de dados

3. Onde estão os detalhes sobre as certificações e os padrões de compliance que o Google Cloud cumpre?

Marketplace

(X) Central de recursos de compliance

Console do Google Cloud

Bibliotecas de cliente do Cloud Storage

4. Que tipo de relatório é uma forma de o Google Cloud compartilhar dados sobre como as políticas e ações de governos e corporações afetam a privacidade, a segurança e o acesso à informação?

Relatórios de compliance

(X) Relatórios de transparência

Relatórios de segurança

Relatórios de faturamento

5. Qual recurso do Google Cloud permite aos usuários controlar a localização física dos dados?

Áreas

(X) Regiões

Distritos

Lugares