# Innovating with Google Cloud Artificial Intelligence

## 1º módulo - Noções básicas de IA e ML

- Machine Learning: O machine learning é um subconjunto da IA que permite que uma máquina aprenda com dados sem ser explicitamente programada para isso.
- Artificial Intelligence: A inteligência artificial é um campo extenso que se refere ao uso de tecnologias para criar máquinas e computadores capazes de imitar funções cognitivas associadas à inteligência humana.

- IA Generativa

- Problemas ajustaveis com ML
    - substituir ou simplificar sistemas baseados em regras.
    - automação de processos.
    - entender dados não estruturados, como imagens, vídeos e áudio.
    - personalização.

- Qualidade dos dados
    - Integridade se refere à presença de todas as informações necessárias.
    - Exclusividade Se um modelo for treinado em um conjunto de dados com um número grande de cópias, pode ser que o modelo de ML não aprenda com precisão.
    - Pontualidade Se os dados não forem pontuais, o modelo pode fazer previsões com base em informações desatualizadas ou irrelevantes.
    - Validade significa que os dados estão em conformidade com um conjunto de padrões e definições já estabelecidos, como tipo e formato.
    - Acurácia reflete a exatidão dos dados, como a data de nascimento correta ou o número exato de unidades vendidas.
    - Consistência diz respeito à uniformidade dos dados e se eles não contêm informações contraditórias.

### Questões

1. Qual caso de uso demonstra a capacidade do ML de processar linguagem natural?

(X) Identificar o tópico e o sentimento das mensagens de e-mail dos clientes para que sejam encaminhadas ao departamento certo.

Identificar o artista, título ou gênero de músicas para criar playlists com base nos hábitos musicais do usuário.

Dividir imagens em diferentes partes ou regiões para extrair informações, como os dizeres de uma placa.

Detectar pessoas e objetos em imagens de monitoramento para usar como prova em processos criminais.

2. Os princípios de IA do Google são um conjunto de valores norteadores que ajudam a desenvolver e usar a inteligência artificial de forma responsável. Qual item a seguir é um dos princípios de IA do Google?

A IA deve criar ou reforçar um viés injusto.

A IA deve ser responsável perante outras máquinas.

A IA deve ser disponibilizada para qualquer tipo de uso.

(X) A IA deve oferecer um benefício social.

3. Enquanto assiste a um vídeo no YouTube, você recebe sugestões da plataforma de outros conteúdos que podem ser do seu interesse. Qual é solução de ML por trás desse recurso?

Detecção de clickbait

Moderação de conteúdo

(X) Recomendações personalizadas

Transcrição de vídeos

4. O Google usa a IA generativa em produtos como o Google Workspace, mas o que ela é exatamente?

Um tipo de inteligência artificial capaz de criar e manter a própria consciência.

(X) Um tipo de inteligência artificial capaz de produzir conteúdo novo, incluindo texto, áudio, imagens e dados sintéticos.

Um tipo de inteligência artificial capaz de tomar decisões e realizar ações.

Um tipo de inteligência artificial capaz de entender e responder a emoções humanas.

5. Ao medir a qualidade dos dados, qual dimensão indica que os dados estão em conformidade com um grupo de definições e padrões predefinidos, como tipo e formato?

Consistência

Acurácia

Exclusividade

(X) Validade

6. Em que aspecto a análise de dados e o Business Intelligence são diferentes da IA e do ML?

A análise de dados e o Business Intelligence usam algoritmos avançados para prever tendências futuras, enquanto a IA e o ML são focados no processamento de dados históricos.

A análise de dados e o Business Intelligence são usados apenas em pequenas empresas, enquanto a IA e o ML são usados exclusivamente por grandes corporações.

A análise de dados e o Business Intelligence usam processos automatizados de tomada de decisão, enquanto a IA e o ML exigem intervenção humana e interpretação dos dados.

(X) A análise de dados e o Business Intelligence identificam tendências em dados históricos, enquanto a IA e o ML usam dados para tomar decisões de negócios futuros.

7. Qual tecnologia usa modelos para analisar grandes volumes de dados e aprender com insights para depois fazer previsões e tomar decisões bem fundamentadas?

Robótica

Processamento de linguagem natural

Sistemas especialistas

(X) Machine learning

8. A inteligência artificial é mais indicada para substituir ou simplificar sistemas baseados em regras. Qual opção é um exemplo disso na prática?

(X) Treinar um modelo de machine learning para prever uma classificação de resultados da pesquisa.

Usar a IA para substituir decisões humanas em situações complexas, como questões de vida ou morte.

Usar um algoritmo de aprendizado por reforço para treinar drones autônomos na entrega de pacotes.

Implementar a IA para desenvolver um produto ou serviço que ainda não existe.

9. Qual opção se refere ao uso de tecnologias para criar máquinas e computadores que imitam funções cognitivas associadas à inteligência humana?

Processamento de linguagem natural

(X) Inteligência artificial

Aprendizado profundo

Machine learning

10. Ao medir a qualidade dos dados, o que a dimensão da consistência indica?

Se um conjunto de dados está livre de valores duplicados que poderiam impedir um modelo de ML de aprender com acurácia.

(X) Se os dados são uniformes e se contêm informações contraditórias.

Se os dados estão atualizados e refletem o estado atual do fenômeno que está sendo modelado.

Se todas as informações necessárias estão presentes.

## 2º módulo - Soluções de IA e ML do Google Cloud

- Modelos de ML
    - BigQuery ML: Ele é uma ferramenta que usa consultas SQL para criar e executar modelos de machine learning no BigQuery.
    - APIs Pré treinadas (API Vision - Natural Language - Cloud Translation - Speech to text - Text to Speech - Video Intelligence):  é possível usar modelos de machine learning que foram criados e treinados pelo Google
    - AutoML: que é uma solução sem código, que permite criar modelos próprios de machine learning na Vertex AI em uma interface de apontar e clicar.
    - Custom Training: com os quais é possível programar seu próprio ambiente de machine learning

- Vertex AI: Plataforma essencial para criar modelos de machine learnings de ponta a ponta.
    - Coleta de dados -> Criação -> Implantação e monitoramento de modelo de ML
    - Tensorflow: plataforma completa de código aberto para machine learning. O TensorFlow tem um ecossistema flexível de ferramentas, bibliotecas e recursos comunitários que ajudam os pesquisadores a inovar no ML e os desenvolvedores a criar e implantar aplicativos com tecnologia de ML. Usa TPU mais rapido que CPU e GPU

- Soluções de IA:
    - Contact Center IA: fornece modelos para interagir com clientes e auxiliar agentes humanos
    - Document IA: gera insights extraindo e classificando informações de documentos não estruturados
    - Discovery IA: usa machine learning para otimizar a ordem dos produtos no site de e-commerce de um varejista quando os compradores escolhem uma categoria
    - Cloud Talent Solution IA: usa IA com recursos de pesquisa de vagas e aquisição de talentos, agiliza a correlação de candidatos com as vagas ideais 

- Considerações para escolher a melhor IA:
    - Velocidade -> Diferenciação -> Experiencia -> Esforço

### Questões

1. Qual solução de IA do Google Cloud foi criada para ajudar as empresas a melhorar o atendimento ao cliente?

(X) Contact Center AI

Cloud Talent Solution

Document AI

Discovery AI para o varejo

2. Qual é o nome do circuito integrado de aplicação específica (ASIC, na sigla em inglês) do Google usado para acelerar cargas de trabalho de machine learning?

Unidade de processamento gráfico (GPU)

Unidade de processamento central (CPU)

(X) Unidade de Processamento de Tensor (TPU)

Unidade de processamento da Vertex (VPU)

3. Uma loja on-line quer ajudar os usuários a encontrar produtos específicos com mais rapidez no site. Uma ideia é permitir que os compradores façam upload das imagens dos produtos que estão procurando. Qual API pré-treinada do Google a loja poderia usar para fazer essa melhoria?

API Natural Language

(X) API Vision

API Video Intelligence

API Speech-to-Text

4. O BigQuery ML é um serviço de machine learning que permite:

Exportar pequenas quantidades de dados para planilhas ou outros aplicativos.

Criar e avaliar modelos de machine learning no BigQuery usando Python e Java.

Conectar-se com facilidade a uma equipe de cientistas de dados para criar um modelo de ML.

(X) Criar e avaliar modelos de machine learning no BigQuery usando SQL.

5. Qual recurso da Vertex AI permite que os usuários criem e treinem modelos completos de machine learning usando uma interface gráfica do usuário (GUI), sem precisar de código?

(X) AutoML

Ambiente de ML gerenciado

Treinamento personalizado

MLOps

6. O Google Cloud oferece quatro opções para criar modelos de machine learning. Qual delas é a melhor para uma empresa que vai programar o próprio ambiente, treinamento e implantação de machine learning?

BigQuery ML

(X) Treinamento personalizado

AutoML

APIs pré-treinadas

7. Uma grande empresa de mídia quer melhorar a moderação do conteúdo on-line. Atualmente, ela conta com uma equipe de moderação humana que analisa o conteúdo quanto à adequação, mas quer aproveitar a inteligência artificial para aumentar a eficiência. Qual API pré-treinada do Google a empresa poderia usar para identificar e remover conteúdo inadequado do site e dos perfis da empresa nas redes sociais.

(X) API Natural Language

API Video Intelligence

API Speech-to-Text

API Vision

8. Qual solução de IA do Google Cloud foi criada para ajudar as empresas a automatizar o processamento de documentos?

Discovery AI para o varejo

Cloud Talent Solution

Contact Center AI

(X) Document AI