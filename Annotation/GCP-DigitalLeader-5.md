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
    - Despesas de capital (CapEx)

- Ameaças cibernéticas
    - Engenharia Social
    - Dano Fisico
    - Virus, Malware e Ransomware
    - Sistemas vulneraveis de terceiros
    - Erros de configuração

### Questões

1. Em qual ameaça cibernética a vítima é obrigada a pagar um resgate para reaver o acesso aos arquivos e sistemas?

    :white_check_mark: Ransomware

    :black_large_square: Cavalo de troia

    :black_large_square: Spyware

    :black_large_square: Vírus

---

2. Qual definição a seguir é a melhor descrição de um firewall?

    :black_large_square: Um modelo de segurança que pressupõe que nenhum usuário ou dispositivo é confiável.

    :black_large_square: Um software que criptografa dados para que não sejam lidos por usuários não autorizados.

    :white_check_mark: Um dispositivo de segurança de rede que monitora e controla o tráfego de rede que entra e sai com base em regras predefinidas.

    :black_large_square: Um conjunto de medidas de segurança criado para proteger uma rede ou um sistema de computação contra ataques cibernéticos.

---

3. Em qual ameaça cibernética comum os usuários são enganados para que revelem informações sensíveis ou realizem ações que comprometam a segurança?

    :black_large_square: Erro de configuração

    :black_large_square: Malware

    :white_check_mark: Phishing

    :black_large_square: Ransomware

---

4. Qual item a seguir é um benefício da segurança na nuvem em relação à segurança tradicional no local?

    :white_check_mark: Aumento da escalonabilidade.

    :black_large_square: As atualizações de segurança são instaladas apenas uma vez por semana.

    :black_large_square: Grande investimento inicial de capital.

    :black_large_square: Acesso físico ao hardware.

---

5. Quais são os três aspectos de segurança na nuvem que compõem as bases da tríade CIA?

    :black_large_square: Contêineres, infraestrutura e arquitetura

    :black_large_square: Certificados, inteligência e autenticação

    :black_large_square: Conformidade, identidade e gerenciamento de acesso

    :white_check_mark: Confidencialidade, integridade e disponibilidade

---

6. Qual princípio de segurança na nuvem está relacionado à manutenção de dados precisos e confiáveis?

    :black_large_square: Compliance

    :black_large_square: Confidencialidade

    :white_check_mark: Integridade

    :black_large_square: Controle

---

7. Qual princípio de segurança na nuvem garante que as práticas e medidas de segurança estejam alinhadas aos padrões e diretrizes estabelecidos?

    :white_check_mark: Compliance

    :black_large_square: Controle

    :black_large_square: Integridade

    :black_large_square: Confidencialidade

---

8. Qual ameaça cibernética ocorre quando são cometidos erros durante a configuração de recursos que acabam expondo dados sensíveis e sistemas a acesso não autorizado?

    :black_large_square: Phishing

    :black_large_square: Malware

    :black_large_square: Vírus

    :white_check_mark: Erros de configuração

---

9. Qual princípio de segurança defende que os usuários tenham apenas o acesso de que precisam para desempenhar suas funções?

    :black_large_square: Acesso privilegiado

    :black_large_square: Arquitetura de confiança zero

    :black_large_square: Segurança por padrão

    :white_check_mark: Privilégio mínimo

---

10. Qual é a responsabilidade do provedor de nuvem em um modelo de segurança de nuvem?

    :black_large_square: Gerenciar o acesso dos usuários do cliente.

    :black_large_square: Proteger os dados do cliente.

    :white_check_mark: Manter a infraestrutura do cliente.

    :black_large_square: Configurar os aplicativos do cliente.

## 2º módulo - Infraestrutura confiável do Google

- Infra confiavel
    - Arquitetura de confiança zero nos datacenters
    - Mais de 30 datacenters
    - Datacenter finlandia destaque
    - PUE - Power usage effectiveness (eficiência no uso de energia)

- KMS Cloud Key Management Service - Recurso de criptografia de dados
    - O Google criptografa os dados em repouso automaticamente sem custo adicional.

- Principal recurso utilizado pela google de criptografia é o AES (Advanced Encryption Standard)

- Google criptografa os dados em "repouso" em "transito" e em "uso"

- Os 3 "A"
    - Autenticação
    - Autorização
    - Auditoria

- IAM (Identity and Access Management): Para ter controle granular sobre quem está autorizado a acessar os recursos do Google Cloud e quais ações são permitidas neles

- Zero Trust
    - BeyondCorp Entrerprise: É possível implementar um modelo de segurança de confiança zero.

- Segurança de rede
    - Cloud VPN e Cloud Interconnect que permitem estabelecer conexões seguras entre suas redes locais e os recursos do Google Cloud.

- Proteção de perimetro com Firewall e Virtual Private Cloud 

- Shared VPC: É como ter uma grande cerca separando cada projeto do Google Cloud para que eles possam funcionar independentemente e com segurança.

- Cloud Armor: Firewall de aplicativos da Web, fornecendo uma proteção robusta contra DDoS.

- SecOps - Security Operation
    - Vulnerability Management: É o processo de identificar e corrigir vulnerabilidades de segurança em aplicativos e infraestruturas na nuvem.
        - Security Command Center (SCC): Oferece uma visão centralizada da sua postura de segurança.
    - Log Management
        - Cloud Logging: Um serviço para coletar e analisar registros de segurança de todo o seu ambiente do Google Cloud.
    - Incidente Response
    - Educação dos usuários

### Questões

1. Qual item a seguir é um potente algoritmo de criptografia em que governos e empresas do mundo todo confiam?

    :white_check_mark: Padrão de criptografia avançada (AES)

    :black_large_square: Criptografia isomórfica (IE)

    :black_large_square: Criptografia baseada em reticulados (LBC)

    :black_large_square: Criptografia pós-quântica (PQC)

---

2. Selecione a afirmação correta sobre o Identity and Access Management (IAM).

    :black_large_square: O IAM é um serviço em nuvem que criptografa dados em repouso e em trânsito baseados na nuvem.

    :black_large_square: O IAM é um sistema que detecta tráfego malicioso e impede que ele entre em uma rede da nuvem.

    :black_large_square: O IAM é uma solução para gerenciamento de eventos e informações de segurança na nuvem que coleta e analisa dados de registro de dispositivos e aplicativos de segurança na nuvem.

    :white_check_mark: O IAM fornece controle granular de quem tem acesso aos recursos do Google Cloud e o que é possível fazer com esses recursos.

---

3. O Google Cloud criptografa dados em vários estados. Qual estado indica que os dados estão sendo processados ativamente por um computador?

    :black_large_square: Dados em trânsito

    :black_large_square: Dados em repouso

    :white_check_mark: Dados em uso

    :black_large_square: Data lake

---

4. Qual prática envolve uma combinação de processos e tecnologias que ajudam a reduzir o risco de vazamento de dados, interrupções no sistema e outros incidentes de segurança na nuvem?

    :black_large_square: Gerenciamento de postura de segurança na nuvem (CSPM)

    :black_large_square: Segurança de confiança zero

    :white_check_mark: Operações de segurança (SecOps)

    :black_large_square: Engenharia de confiabilidade do site (SRE)

---

5. Qual recurso de segurança adiciona uma camada extra de proteção nos sistemas baseados na nuvem?

    :white_check_mark: Verificação em duas etapas (2SV)

    :black_large_square: Prevenção contra perda de dados (DLP)

    :black_large_square: Firewall como serviço (FaaS)

    :black_large_square: Gerenciamento de eventos e informações de segurança (SIEM)

---

6. Qual aspecto do Gerenciamento de identificação do Cloud verifica a identidade de usuários e sistemas?

    :black_large_square: Autorização

    :black_large_square: Auditoria

    :white_check_mark: Autenticação

    :black_large_square: Accounting

---

7. Qual produto do Google Cloud fornece proteção robusta contra ataques distribuídos de negação de serviço (DDoS)?

    :white_check_mark: Google Cloud Armor

    :black_large_square: Cloud Load Balancing

    :black_large_square: Cloud IAM

    :black_large_square: Cloud Monitoring

---

8. Qual métrica do Google Cloud mede a eficiência dos data centers para alcançar as metas de economia de custos e reduzir a pegada de carbono?

    :black_large_square: Custo total de propriedade (TCO)

    :black_large_square: Proporção de eficiência energética (EER)

    :white_check_mark: Eficiência no uso de energia (PUE)

    :black_large_square: Eficiência da infraestrutura do data center (DCiE)

## 3º Módulo - Compliance e princípios de confiança do Google Cloud

- Principios do google
    - Primeiro: Os dados são seus, e não do Google.
    - Segundo: O Google não vende os dados dos clientes a terceiros.
    - Terceiro: O Google Cloud não usa dados dos clientes em publicidade.
    - Quarto: Todos os dados dos clientes são criptografados por padrão.
    - Quinto: Oferecemos proteção contra o acesso interno aos seus dados.
    - Sexto: Nunca damos a entidades governamentais acesso "backdoor" aos seus dados.
    - Sétimo: Nossas práticas de privacidade são auditadas de acordo com padrões internacionais.

- Data Sovereignty (Soberania): Refere-se ao conceito legal de que os dados estão sujeitos às leis e regulamentações do país onde eles residem.

- Data Residency: Se refere ao local físico onde os dados são armazenados ou tratados.

- Compliance Resource Center: Esse hub abrangente fornece informações detalhadas sobre as certificações e padrões de conformidade que atendemos.

- Compliance Reports Manager: Uma ferramenta potente à sua disposição. Essa plataforma intuitiva oferece acesso fácil e sob demanda a recursos críticos de conformidade, sem custo financeiro adicional.

### Questões

1. Qual item é um dos sete princípios de confiança do Google Cloud?

    :white_check_mark: Todos os dados dos clientes são criptografados por padrão.

    :black_large_square: O Google dá acesso backdoor a entidades governamentais mediante solicitação.

    :black_large_square: O Google Cloud usa os dados dos clientes para publicidade.

    :black_large_square: O Google vende os dados dos clientes a terceiros.

---

2. Qual termo descreve o conceito de que os dados estão sujeitos às leis e regulamentações do país onde residem?

    :white_check_mark: Soberania de dados

    :black_large_square: Redundância de dados

    :black_large_square: Residência dos dados

    :black_large_square: Consistência de dados

---

3. Onde estão os detalhes sobre as certificações e os padrões de compliance que o Google Cloud cumpre?

    :black_large_square: Marketplace

    :white_check_mark: Central de recursos de compliance

    :black_large_square: Console do Google Cloud

    :black_large_square: Bibliotecas de cliente do Cloud Storage

---

4. Que tipo de relatório é uma forma de o Google Cloud compartilhar dados sobre como as políticas e ações de governos e corporações afetam a privacidade, a segurança e o acesso à informação?

    :black_large_square: Relatórios de compliance

    :white_check_mark: Relatórios de transparência

    :black_large_square: Relatórios de segurança

    :black_large_square: Relatórios de faturamento

---

5. Qual recurso do Google Cloud permite aos usuários controlar a localização física dos dados?

    :black_large_square: Áreas

    :white_check_mark: Regiões

    :black_large_square: Distritos

    :black_large_square: Lugares