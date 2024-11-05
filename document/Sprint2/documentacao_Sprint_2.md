# Documentação SPRINT 2 IMPLEMENTAÇÃO SAP MÓDULO CONTÁBIL - Módulo 7  Inteli

## [1. Experiência do Usuário](#c1) <br>
### [1.1 Pesquisa Exploratória](#c1.1)<br>
### [1.2 Pesquisa Desk](#c1.2)<br>
### [1.3 Definição de Personas e User Stories](#c1.3)<br>

## [2. Análise de Negócios](#c2) <br>
### [2.1 Canvas Proposta de Valor](#c2.1) <br>
### [2.2 Matriz de Risco e Oportunidades](#c2.2)<br>
### [2.3 Análise Financeira](#c2.3)<br>

## [3. Desenvolvimento e Implementação](#c3)<br>
### [3.1 Desenho da Solução](#c3.1)<br>
### [3.2 Configurações Iniciais](#c3.2)<br>
### [3.3 Dados Mestres Validados](#c3.3)<br>
### [3.4 Documentação da Solução (Regras de Negócio e Diagramas)](#c3.4)<br>
### [3.5 Limpeza dos Dados](#c3.5)<br>

## [4. Testes e Validação](#c4)  <br>
### [4.1 Testes Unitários](#c4.1)  <br>
### [4.2 Testes Integrados](#c4.2)  <br>
### [4.3 Estratégia de Cut Over](#c4.3)  <br>
### [4.4 Relatórios](#c4.4)<br>

## [5. Treinamento e Suporte](#c5)  <br>
### [5.1 Treinamento de Usuários](#c5.1)  <br>
### [5.2 Suporte Pós-Implantação](#c5.2)<br>
### [5.3 Suporte parametrização](#c5.3)<br>

## [6. Referências Bibliográficas](#c6)<br>

# <a id="c1"></a>1. Experiência do Usuário  

## <a id="c1.1"></a>1.1 Pesquisa Exploratória
### 1.1.1 Introdução
&emsp;&emsp;Nessa seção, a Plus One desenvolveu uma pesquisa exploratória para a compreensão do assunto do projeto. Nesse contexto, uma pesquisa exploratória tem como função preencher as lacunas que costumam aparecer em um estudo. Segundo o artigo digital da MindMiners, "O que é pesquisa exploratória? Quais seus principais usos?", empresa que possui uma plataforma de *consumer* *insights*, as pesquisas exploratórias possuem métodos mais flexíveis e fornecem informações que ampliam a familiaridade com o assunto específico [1]. Dessa forma, a pesquisa exploratória da Plus One tem como objetivo entender a indústria e o setor de mercado da G2 Tecnologia. Além disso, busca-se compreender o serviço que a G2 Tecnologia oferece. Essa pesquisa exploratória foi construída utilizando como base as informações coletadas durante os encontros e entrevistas com o cliente, no caso, a G2 Tecnologia. Com isso, essa pesquisa foi construída com a justificativa de desenvolver o ERP da Plus One em conformidade com o cliente G2 Tecnologia, entendendo sua situação no mercado, suas dores, serviços e desafios.

### 1.1.2 A pesquisa
&emsp;&emsp;Em primeiro lugar, durante o *onboarding* com os *CEOs* da G2 Tecnologia, o sócio-fundador Gilberto, a sócia-fundadora Glaucia, e a Eduarda, gerente de projetos na área, foram obtidas algumas informações sobre a setor de consultoria. A Glaucia comentou que 87% das grandes empresas no mercado mundial utilizam SAP. Nesse sentido, durante essa reunião, foi mencionado que no mercado brasileiro a G2 Tecnologia possui aproximadamente 30% de participação, concorrendo com Oracle e Totvs.

&emsp;&emsp;Dessa maneira, focando nas informações sobre o serviço que a G2 Tecnologia oferece, os *CEOs* mencionaram durante a reunião que a ferramenta que utilizam é o SAP Business One, e que já implementaram essa ferramenta em empresas como Vivo, Havaianas, O Boticário e Beleza na Web. Dessa forma, a G2 Tecnologia possui 32 anos de existência e conta com um time de peritos em SAP. Sob esse aspecto, os serviços que a G2 Tecnologia oferece são de implementação, sustentação e venda da ferramenta SAP Business One.

&emsp;&emsp;Falando sobre os benefícios, durante o *kick-off* da empresa, momento de primeira interação com perguntas e respostas aprofundadas com o cliente, a gerente de projetos da empresa afirmou que a G2 Tecnologia destaca o valor do treinamento para os clientes, tornando-os gradualmente mais independentes. Nesse âmbito, eles oferecem suporte com uma equipe que fica à disposição, ajudam com a auditoria dos dados, testes, e serviços adicionais, como extensões do sistema. Nesse aspecto, segundo o coordenador de sistemas de informação do Instituto de Tecnologia e à Glaucia, a G2 Tecnologia, juntamente com a primeira turma de alunos de sistemas de informação do Instituto de Tecnologia e Liderança, construiu uma metodologia de implementação de ERP que oferece ao cliente um sistema aplicável em dez semanas, otimizando os processos de implementação e trazendo agilidade para o serviço.

&emsp;&emsp;Partindo para os desafios, segundo a Glaucia, pequenas empresas podem enfrentar dificuldades para operar um ERP como o SAP Business One, pois ele exige dedicação e conhecimento específico. Além disso, no *kick-off*, a gerente de projetos da G2 Tecnologia comentou que as condições de mercado, soluções mais específicas desenvolvidas para um setor específico, o preço dos addons e a dificuldade de encontrar mão de obra qualificada são desafios que a empresa enfrenta.

&emsp;&emsp;Por último, discutindo limitações e problemáticas, durante as entrevistas os colaboradores da G2 Tecnologia comentaram que trabalhar com a SAP implica em depender da empresa SAP e do seu ecossistema. Essa forte dependência da G2 Tecnologia em relação à SAP foi configurada como uma problemática da empresa pela Glaucia.

## <a id="c1.2"></a>1.2 Pesquisa Desk
  
### 1.2.1 Introdução:

&emsp;&emsp;A Pesquisa Desk, também chamada de pesquisa secundária, é uma abordagem que envolve a coleta e análise de informações a partir de documentos e fontes já existentes, com o objetivo de aprofundar o conhecimento sobre um tema específico [1]. Neste contexto, a justificativa da presente pesquisa é identificar tendências de mercado relevantes, reunir *insights* preliminares para servir como base e direcionamento para futuras pesquisas e, a partir desses dados, desenvolver uma ideação para a implantação do projeto de SAP Business One na empresa G2 Tecnologia. Através da análise de relatórios de mercado, estudos de caso e publicações especializadas, espera-se construir uma base sólida de informações que apoie a tomada de decisões estratégicas para o sucesso do projeto.

&emsp;&emsp;O objetivo é conduzir esta pesquisa utilizando o modelo Duplo Diamante, um processo de design estruturado para organizar as fases divergentes e convergentes de um projeto criativo desenvolvido pelo British Design Council em 2015 [2]. Essa metodologia é amplamente reconhecida por sua eficácia em guiar projetos desde a concepção até a implementação. O método é dividido em quatro etapas principais: Descobrir, Definir, Desenvolver e Entregar.

&emsp;&emsp;Utilizando um exemplo mais prático, ao aplicar o Duplo Diamante no projeto em que o grupo está desenvolvendo, a Pesquisa Desk estaria localizada na etapa de "Descobrir", que corresponde ao primeiro diamante do modelo. Entretanto, ao utilizar essa abordagem na própria Pesquisa Desk, não apenas se estrutura de maneira mais metódica, mas também se garante que ela esteja alinhada diretamente com os objetivos estratégicos do projeto, preparando o terreno para as fases subsequentes de definição, desenvolvimento e entrega. Essa integração do Duplo Diamante na pesquisa proporciona uma visão estratégica ao time, oferecendo clareza na condução desta pesquisa secundária.

&emsp;&emsp;Dessa forma, é possível traçar os resultados esperados dentro de cada etapa deste modelo, sendo esses:
- Descobrir: Investigar o problema central, o que inclui a pesquisa sobre a SAP, a análise de empresas semelhantes e a avaliação do mercado em que a G2 Tecnologia está inserida.
- Definir: Delimitar o escopo do projeto, com foco na implementação do SAP Business One na G2 Tecnologia, integrando a metodologia desenvolvida pelo Inteli para a G2 Tecnologia.
- Desenvolver: Elaborar uma ideação detalhada de como a implantação será realizada, incluindo planos, estratégias e recursos necessários.
- Entregar: Apresentar a solução final, detalhando a abordagem que será adotada para a implementação do SAP Business One na G2 Tecnologia.

<div align="center">
<sub>Figura 1 - Duplo Diamante</sub>
<img src="../assets/duplodiamante.png" width="100%" >
<sup>Fonte: Material produzido pelos autores com base no Duplo Diamante do British Design Council (2024)</sup>
</div>

### 1.2.2 Descobrir:

&emsp;&emsp;O primeiro passo da Pesquisa Desk envolveu uma investigação com o objetivo de entender melhor o cenário em que as empresas de ERP - Enterprise Resource Planning – traduzindo do inglês, “Planejamento dos Recursos da Empresa”, estão inseridas e identificar as melhores práticas para a implementação do SAP Business One. O grupo Plus One analisou o mercado de ERPs, incluindo a solução da SAP e a atuação de empresas similares, buscando *insights* para orientar o desenvolvimento do projeto.

&emsp;&emsp;O mercado de ERP oferece uma variedade de soluções, cada uma com características e funcionalidades específicas para diferentes tipos de negócios. Entre os principais sistemas ERP disponíveis, destacam-se o Omie, voltado para o mercado brasileiro com forte integração contábil, e o SAP S/4HANA, líder global reconhecido pela alta integração, embora de implementação complexa. Outras opções incluem o Oracle Cloud ERP, robusto e escalável, o Microsoft Dynamics 365, que se integra bem com outros produtos da Microsoft, e o NetSuite, uma solução flexível baseada em nuvem. A escolha do ERP adequado para uma empresa como a G2 Tecnologia deve considerar não apenas suas necessidades específicas e orçamento, mas também o suporte oferecido, além dos planos de treinamento e acompanhamento pós-implementação [3].

&emsp;&emsp;Além das opções proprietárias, também existem ERPs livres, cuja implantação exige adaptações devido às diferenças entre os sistemas. Embora os métodos usados em ERPs proprietários possam ser aplicados em ERPs livres, a customização e configuração são necessárias em ambos. No entanto, a implementação de ERPs livres enfrenta desafios específicos, como a escassez de profissionais qualificados nessas plataformas e o desinteresse geral em tecnologias menos conhecidas no mercado. O número reduzido de consultorias especializadas em ERP livre no Brasil também dificulta a implementação e o suporte contínuo desses sistemas [4].

&emsp;&emsp;Ainda assim, a SAP se consolidou como uma das empresas de tecnologia mais importantes no Brasil, especialmente no segmento de pequenas e médias empresas (PMEs), graças ao SAP Business One. Esta solução se destaca pela rápida implementação e custo acessível, sendo uma escolha atrativa para PMEs que buscam digitalizar suas operações. A relevância do SAP Business One no mercado brasileiro é evidente, com a SAP Brasil expandindo sua base de clientes de 3.500 para 7.600 entre 2018 e 2023. Esse crescimento foi impulsionado pela crescente demanda por soluções de ERP que facilitem a gestão empresarial, especialmente em setores como restaurantes e agronegócio [5]. O estudo "Capacidades e Atores na Gestão de Sistemas ERP: Um Estudo Exploratório entre Usuários Corporativos do ERP da SAP" explora a aplicação de gestão de sistemas ERP, com foco no SAP. A pesquisa inclui princípios como interoperabilidade, reusabilidade, preservação, proveniência, modularidade e dados vinculados, que visam garantir que dados, métodos e resultados sejam acessíveis, reutilizáveis e compreensíveis em várias plataformas. Esses princípios reforçam a posição da SAP no mercado.[6].

### 1.2.3 Definir:

&emsp;&emsp;Com base nas informações coletadas na fase de descoberta, o próximo passo é definir o escopo do projeto, focando na implementação do SAP Business One na G2 Tecnologia. Nesta etapa, utilizaremos pesquisas sobre a G2 Tecnologia e a metodologia proposta pelo Inteli e adaptadas em parceria com a G2 Tecnologia para delimitar os objetivos específicos, identificar os principais desafios e estabelecer um plano detalhado para a implantação do sistema, alinhado às necessidades e características da empresa.

&emsp;&emsp;Pensando no contexto em que a G2 Tecnologia está inserida, o setor de consultoria, a adoção de um sistema ERP pode trazer melhorias significativas na integração de dados e automação de processos, resultando em maior eficiência operacional e melhor tomada de decisões estratégicas. Um estudo recente destacou que empresas de médio porte na área de logística têm obtido vantagens substanciais com a implementação de ERPs, como a padronização e a maturidade nos processos, além da melhoria na acuracidade dos dados e na gestão de atividades específicas, como ordens de ressuprimento e monitoramento de indicadores de desempenho [7].

&emsp;&emsp;Além disso, o grupo Plus One fez um levantamento sobre a metodologia do Inteli em união com a G2 Tecnologia. O projeto foi desenvolvido por alunos do segundo ano do curso de Sistemas da Informação em 2023, em colaboração com a empresa G2 Tecnologia. A inovação proposta é uma metodologia capaz de reduzir em mais de 60% o tempo de implementação do SAP Business One, um sistema crucial para pequenas e médias empresas. Este feito destaca a eficácia do ensino orientado a projetos do Inteli e a importância das parcerias acadêmicas e industriais. A experiência prática obtida pelos alunos também evidenciou a importância de habilidades técnicas e práticas no mercado de trabalho, resultando na primeira patente dos alunos Inteli [8].


### 1.2.4 Desenvolver:

&emsp;&emsp;Na etapa de desenvolvimento, o objetivo é criar uma ideação detalhada para a implantação do SAP Business One na empresa G2 Tecnologia. Esta fase envolve a elaboração de um plano que abrange análise de necessidades, cronograma, metodologias e estratégias para garantir a execução bem-sucedida do projeto. Faz-se relevante nesse momento citar que o grupo Plus One é o responsável pela área de Contábil entre as áreas divididas pelos alunos.
- **Análise das Necessidades da G2:** Com base nas informações coletadas nas fases anteriores e nas entrevistas com os *stakeholders* que se disponibilizarão no Inteli, o grupo mapeará as necessidades específicas da empresa e como o SAP Business One pode ser configurado para atendê-las. Isso inclui analisar os processos atuais da G2 Tecnologia, identificar áreas a serem otimizadas e determinar quais funcionalidades do SAP Business One serão mais benéficas.
- **Desenvolvimento de um Cronograma:** Foi desenvolvido um cronograma detalhado para mapear as etapas do projeto, desde a configuração inicial do sistema até o treinamento dos usuários. Este cronograma foi desenvolvido em conjunto entre a diretora acadêmica, o coordenador do curso, o professor orientador e os professores, junto a uma gerente de projetos e dois consultores da G2 Tecnologia. O cronograma inclui marcos principais, prazos para entrega de tarefas e períodos de revisão e feedback para o que foi desenvolvido pelos alunos.
- **Utilização de Metodologias Ágeis:** O grupo Plus One, assim como toda a sala, adotou metodologias ágeis adaptadas para o ambiente educacional. Será utilizado uma adaptação de *Scrum* e *Product Owner*, com *dailys*, *sprint plannings* e *sprint reviews*, incluindo a validação dos *Stakeholders*.
- **Plano de Treinamento:** Será desenvolvido um plano de treinamento para garantir que os usuários da G2 Tecnologia estejam capacitados a utilizar o SAP Business One de forma eficiente. O treinamento será conduzido com o auxílio dos professores e orientador.

### 1.2.5 Entregar:

&emsp;&emsp;Na etapa de entrega da Pesquisa Desk serão retomadas as informações levantadas, facilitando no processo de implementação do SAP Business One na G2 Tecnologia. Esta fase é crucial para assegurar que todas as descobertas e recomendações sejam integradas em um plano coeso e aplicável para o desenvolvimento do projeto.

&emsp;&emsp;Esse processo envolve uma revisão detalhada das informações coletadas durante as fases de Descobrir, Definir e Desenvolver. Esse processo é fundamental para garantir que todas as descobertas estejam alinhadas com os objetivos estratégicos e operacionais da empresa, assim como com as expectativas de todos os integrantes do grupo.

&emsp;&emsp;Por fim, as pesquisas indicam que a escolha do sistema ERP certo é essencial para a eficiência empresarial. Embora os ERPs livres representem uma alternativa econômica, eles podem carecer de suporte especializado no Brasil. Contudo, com investimento em capacitação interna, esses sistemas podem se tornar viáveis.

&emsp;&emsp;Em relação ao mercado, o SAP Business One se destaca quando implantado em pequenas e médias empresas no Brasil, apresentando um crescimento no número de clientes da SAP desde 2018 devido à sua rápida implementação e custo acessível. Para uma gestão eficaz, é crucial que os ERPs sigam princípios como interoperabilidade e modularidade, assegurando a integridade dos dados.

&emsp;&emsp;No ano de 2023, a parceria entre o Inteli e a G2 Tecnologia resultou em uma metodologia patenteada que reduz em mais de 60% o tempo de implementação do SAP Business One.

&emsp;&emsp;Por fim, a etapa de Entregar sintetiza todas as descobertas e recomendações das fases anteriores, proporcionando uma base sólida para a implementação do SAP Business One na G2 Tecnologia. 

## <a id="c1.3"></a>1.3 Definição de Personas e User Stories

### 1.3.1 Personas
### 1.3.1.1 Introdução:
&emsp;&emsp;Uma persona é uma representação fictícia e detalhada de um usuário típico ou ideal de um produto, serviço ou sistema. Criada a partir de pesquisas, dados e suposições bem fundamentadas, a persona ajuda a identificar e entender as necessidades, comportamentos, objetivos e desafios dos usuários. Ao criar personas, as empresas podem adotar uma abordagem mais centrada no cliente, orientando suas estratégias de design, marketing e desenvolvimento de produtos de maneira a atender melhor ao público-alvo.

&emsp;&emsp;As personas permitem que as equipes de trabalho visualizem e empatizem com seus usuários, ajudando a tomar decisões mais assertivas e alinhadas às expectativas dos clientes. Elas servem como um guia para o desenvolvimento de soluções mais personalizadas e eficazes, garantindo que os produtos ou serviços atendam às necessidades reais dos usuários e, ao mesmo tempo, criem uma conexão mais significativa com eles. A criação de uma persona é um passo essencial no processo de desenvolvimento de qualquer projeto voltado ao cliente, pois proporciona clareza e foco ao longo de todo o processo.


 <div align="center">
<sub>Figura 2 - Persona</sub>
<img src="../assets/PersonaMariana.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

### 1.3.2 User Stories
#### 1.3.2.1 Introdução
  &emsp;&emsp; User Stories são uma técnica central no desenvolvimento ágil, focada em capturar as necessidades dos usuários de forma clara e direcionada. Elas descrevem funcionalidades do ponto de vista do usuário final, ajudando a equipe a manter o foco na entrega de valor. No contexto da G2 Tecnologia, as User Stories foram elaboradas para atender às demandas específicas da área contábil, assegurando que as soluções desenvolvidas reflitam diretamente as necessidades de precisão e eficiência nos processos financeiros.
  
&emsp;&emsp; Cada User Story segue o formato "Como [tipo de usuário], eu quero [funcionalidade/ação] para [benefício/valor]", o que facilita a comunicação entre todos os envolvidos no projeto. Além disso, essas histórias são pequenas e gerenciáveis, permitindo que sejam priorizadas, estimadas e entregues de forma incremental, garantindo que o sistema contábil da G2 esteja sempre alinhado às melhores práticas e pronto para responder às demandas do mercado.

&emsp;&emsp; Ao longo do processo, as User Stories ajudam a guiar o desenvolvimento, assegurando que as funcionalidades implementadas não só atendam às necessidades imediatas, mas também preparem o sistema para futuras melhorias. Com isso, a equipe consegue garantir a qualidade e a eficiência do trabalho, entregando valor de forma contínua e estratégica.

#### 1.3.2.2 User Story 1
&emsp;&emsp; A User Story US01 descreve a necessidade de um gerente contábil para revisar e conciliar os balancetes mensais, garantindo que todas as entradas e saídas estejam devidamente registradas. O objetivo é assegurar a precisão dos registros financeiros, refletindo fielmente a situação contábil da G2 Tecnologia.

| **Atributo**         | **Descrição**                                                                 |
|----------------------|-------------------------------------------------------------------------------|
| **Título**           | US01                                                        |
| **Descrição**        | Como gerente contábil, eu quero revisar e conciliar os balancetes mensais para garantir que todas as entradas e saídas estejam devidamente registradas. |
| **Independent**      | A User Story pode ser implementada independentemente, pois a revisão e conciliação de balancetes não depende de outras funcionalidades específicas do sistema|
| **Negotiable**       | O escopo pode ser ajustado conforme necessário, como incluir filtros adicionais ou personalizações na visualização dos balancetes.|
| **Valuable**         | A User Story entrega valor ao usuário final ao permitir que o gerente contábil assegure a exatidão dos registros financeiros, promovendo uma melhor tomada de decisão.|
| **Estimable**        | A User Story pode ser estimada em termos de tempo e esforço, considerando a complexidade da revisão e conciliação dos registros contábeis.|
| **Small**            | Sim. A User Story é pequena o suficiente para ser concluída em 1 hora, desde que o escopo não se expanda com requisitos adicionais complexos.|
| **Testable**         | A User Story pode ser testada através da verificação da precisão dos registros e da conciliação correta dos balancetes.                     |
| **Critérios de Aceite** | 1.Os balancetes mensais são revisados e conciliados corretamente, com todas as entradas e saídas registradas de forma precisa. <br> 2. Os registros revisados estão em conformidade com as práticas contábeis da G2 e as normas contábeis exigidas.|
| **Notas/Comentários** | Certificar-se de que o SAP Business One está configurado corretamente para suportar a revisão e conciliação dos balancetes mensais, garantindo que os dados sejam atualizados e refletidos com precisão.|

&emsp;&emsp;A User Story US01 visa permitir que o gerente contábil utilize o SAP Business One para revisar e conciliar os balancetes mensais, garantindo a integridade dos dados financeiros. A implementação dessa funcionalidade é independente, sem depender de outras partes do sistema. O escopo da User Story é flexível e pode ser ajustado para incluir filtros adicionais ou critérios específicos de conciliação, conforme necessário.

&emsp;&emsp;Essa funcionalidade é fundamental para garantir a exatidão dos registros financeiros da empresa, auxiliando na tomada de decisões estratégicas e assegurando conformidade com as práticas contábeis. A complexidade da conciliação e revisão dos balancetes permite uma estimativa precisa do tempo e esforço necessários para sua conclusão. A User Story é pequena o suficiente para ser implementada em um único sprint, desde que o escopo permaneça gerenciável e sem expansões significativas.

&emsp;&emsp;Para garantir a eficácia da implementação, é essencial testar se os balancetes foram revisados e conciliados corretamente, e se os registros resultantes estão em conformidade com as normas contábeis da G2. Além disso, é crucial assegurar que o SAP Business One esteja configurado de forma adequada, permitindo que os dados sejam sempre atualizados e precisos.

#### 1.3.2.3 User Story 2
| **Atributo**         | **Descrição**                                                                 |
|----------------------|-------------------------------------------------------------------------------|
| **Título**           | US02                                                                          |
| **Descrição**        | Como gerente contábil, eu quero criar e personalizar relatórios de desempenho financeiro no SAP Business One para monitorar métricas-chave e apoiar decisões estratégicas. |
| **Independent**      | A User Story pode ser implementada independentemente, pois a criação de relatórios customizados é uma funcionalidade autônoma que não depende de outras partes do sistema. |
| **Negotiable**       | O escopo pode ser ajustado para incluir diferentes tipos de métricas e visualizações nos relatórios, conforme as necessidades da empresa e as preferências dos usuários finais. |
| **Valuable**         | A User Story entrega valor ao usuário final ao fornecer relatórios detalhados e personalizados, que são essenciais para o acompanhamento de metas financeiras e a tomada de decisões informadas. |
| **Estimable**        | A User Story pode ser estimada em termos de tempo e esforço, considerando as opções de customização e a necessidade de integração com os dados financeiros existentes no SAP Business One. |
| **Small**            | A User Story é pequena o suficiente para ser concluída em um sprint, desde que o escopo seja limitado à personalização básica dos relatórios, sem necessidade de desenvolvimento extensivo. |
| **Testable**         | A User Story pode ser testada verificando-se a exatidão dos dados apresentados nos relatórios customizados e sua conformidade com as métricas financeiras estabelecidas. |
| **Critérios de Aceite** | 1. Relatórios de desempenho financeiro são criados e personalizados conforme as especificações do gerente contábil. <br> 2. Relatórios gerados refletem dados financeiros precisos e são formatados de acordo com as normas internas da empresa. |
| **Notas/Comentários** | Garantir que o SAP Business One esteja configurado corretamente para suportar a customização de relatórios e que os dados financeiros sejam atualizados regularmente para garantir a precisão. |

&emsp;&emsp;A User Story US02 tem como objetivo permitir que o gerente contábil crie e personalize relatórios de desempenho financeiro no SAP Business One, facilitando o monitoramento de métricas-chave e o apoio à tomada de decisões estratégicas. Essa funcionalidade é independente, não necessitando de integração com outras partes do sistema. O escopo da User Story pode ser ajustado para incluir diferentes tipos de métricas e visualizações conforme as necessidades da empresa.

&emsp;&emsp;Essa funcionalidade agrega valor ao fornecer relatórios detalhados e personalizados, essenciais para o acompanhamento de metas financeiras e decisões informadas. A complexidade da customização de relatórios permite uma estimativa precisa do tempo e esforço necessários para sua implementação, sendo pequena o suficiente para ser concluída em um sprint.

&emsp;&emsp;Para garantir a eficácia da implementação, é crucial testar se os relatórios foram criados e personalizados conforme as especificações e se os dados financeiros apresentados são precisos e formatados de acordo com as normas internas da empresa. Além disso, é necessário assegurar que o SAP Business One esteja configurado corretamente para suportar essas customizações e que os

#### 1.3.2.4 User Story 3

| **Atributo**           | **Descrição**                                                                                           |
|------------------------|---------------------------------------------------------------------------------------------------------|
| **Título**             | US03 - Automação da Emissão de Faturamentos no SAP Business One |
| **Descrição**          | Como gerente contábil da G2 Tecnologia, eu quero automatizar a emissão de faturamentos no SAP Business One, para reduzir erros manuais e aumentar a eficiência no processo de faturamento. |
| **Independente**       | A User Story pode ser implementada de forma autônoma, pois a automação da emissão de faturamentos não depende de outros sistemas. |
| **Negociável**         | A implementação da automação pode ser ajustada para diferentes tipos de faturamentos conforme necessário. |
| **Valuable**           | A User Story entrega valor significativo ao reduzir o tempo e os erros associados ao processo de faturamento manual. |
| **Estimable**          | A User Story pode ser estimada em termos de tempo, recursos e custo, considerando a simplicidade da automação dentro do SAP Business One. |
| **Small**              | A User Story é pequena o suficiente para ser concluída em uma hora. |
| **Testable**           | A User Story pode ser testada ao emitir um conjunto de faturamentos automatizados e verificar a precisão dos resultados. |
| **Critérios de Aceite** | 1. Emissão automatizada de faturamentos para pelo menos uma categoria de cliente.<br> 2. Redução de erros manuais no processo de faturamento. |
| **Notas/Comentários**  | Este projeto deve ser realizado em colaboração com a equipe de TI para garantir que a automação seja integrada corretamente no SAP Business One. |

&emsp;&emsp;A User Story US03 tem como objetivo automatizar a emissão de faturamentos no SAP Business One para o gerente contábil da G2 Tecnologia. Com essa automação, busca-se reduzir os erros manuais e aumentar a eficiência no processo de faturamento, otimizando o fluxo de trabalho da equipe contábil.

&emsp;&emsp;A implementação dessa funcionalidade é independente e pode ser realizada de forma isolada, sem necessidade de outras integrações no sistema. O escopo é flexível, permitindo ajustes para incluir diferentes tipos de faturamentos, conforme as necessidades da empresa.

&emsp;&emsp;Essa funcionalidade é essencial para assegurar maior precisão nos dados financeiros e garantir conformidade fiscal, além de liberar a equipe contábil de tarefas repetitivas. A tarefa é pequena o suficiente para ser concluída em uma hora, desde que seja mantido o foco em um único tipo de faturamento.

&emsp;&emsp;Para garantir a eficácia da implementação, será necessário testar se os faturamentos são gerados corretamente, seguindo os padrões fiscais exigidos. A colaboração com a equipe de TI é crucial para garantir que a automação seja integrada corretamente ao SAP Business One, evitando qualquer impacto negativo em outras funcionalidades do sistema.

#### 1.3.2.5 User Story 4

&emsp;&emsp;A User Story US04 descreve a necessidade de um gerente contábil para utilizar o SAP Business One na emissão de faturamentos fiscais do último mês. O objetivo é que essa funcionalidade permita a análise detalhada das movimentações monetárias da G2 Tecnologia.

| **Atributo**         | **Descrição**                                                                 |
|----------------------|-------------------------------------------------------------------------------|
| **Título**           | US04                                                      |
| **Descrição**        | Como gerente contábil, eu quero, através da utilização do SAP Business One, emitir faturamentos fiscais do último mês para analisar as movimentações monetárias da G2 Tecnologia. |
| **Independent**      | A User Story pode ser implementada independentemente, pois o fluxo contábil que gera a emissão de faturamentos fiscais não depende de outras funcionalidades específicas do sistema.        |
| **Negotiable**       |  O escopo pode ser ajustado conforme necessário, como incluir filtros adicionais ou personalizações na emissão dos faturamentos.         |
| **Valuable**         | A User Story entrega valor ao usuário final ao permitir que a gerente contábil analise as movimentações monetárias da empresa, facilitando uma tomada de decisões financeiras mais assertiva.                        |
| **Estimable**        | A User Story pode ser estimada em termos de tempo e esforço, considerando a complexidade da emissão de documentos fiscais e a integração com o SAP Business One.           |
| **Small**            | A User Story é pequena o suficiente para ser concluída em menos de uma hora. |
| **Testable**         | A User Story pode ser testada através da verificação da emissão correta de faturamentos fiscais e a análise dos dados gerados.            |
| **Critérios de Aceite** | 1. Os faturamentos fiscais do último mês são gerados corretamente através do SAP Business One. <br> 2.  Os faturamentos fiscais gerados devem estar em conformidade com o formato de dados exigidos em uma nota fiscal válida, de acordo com as normas fiscais externas ao SAP Business One.                     |
| **Notas/Comentários** | Certificar-se de que o SAP Business One está configurado corretamente para a emissão de faturamentos fiscais e que os dados são atualizados e refletidos corretamente.    |

&emsp;&emsp;A User Story US04 visa permitir que o gerente contábil utilize o SAP Business One para emitir faturamentos fiscais do último mês, facilitando a análise das movimentações monetárias da G2 Tecnologia. A implementação dessa funcionalidade é independente e não depende de outras partes do sistema, o que permite sua realização isolada. O escopo da User Story é flexível e pode ser ajustado para incluir filtros adicionais ou personalizações, conforme necessário. 

&emsp;&emsp;Essa funcionalidade é essencial, pois contribui para a análise financeira e colabora para assegurar a conformidade fiscal. A complexidade envolvida na emissão dos documentos fiscais e sua integração com o SAP Business One permite uma estimativa precisa do esforço necessário. A User Story é suficientemente pequena para ser concluída em um sprint, desde que não sejam adicionados requisitos extensivos.

&emsp;&emsp;Para garantir a eficácia da implementação, é fundamental testar se os faturamentos fiscais são gerados corretamente e atendem aos padrões exigidos pelas normas fiscais externas ao SAP Business One. Além disso, é crucial assegurar que o sistema esteja configurado corretamente e que os dados estejam atualizados e precisos.

#### 1.3.2.6 Conclusão
&emsp;&emsp;As User Stories que desenvolvemos para a G2 foram projetadas para entregar soluções práticas, focadas no usuário e alinhadas aos objetivos da empresa. Cada história foi cuidadosamente elaborada para ser independente, valiosa e testável, o que facilita sua implementação e validação dentro do ciclo ágil.

&emsp;&emsp;Ao priorizar a entrega de valor e a flexibilidade, garantimos que as funcionalidades atendam às necessidades da G2 e estejam preparadas para se adaptar rapidamente às mudanças do ambiente de negócios. A abordagem ágil adotada por nossa equipe permite ajustes contínuos, assegurando que o sistema contábil da G2 se mantenha eficiente, preciso e em conformidade com as melhores práticas do mercado.

&emsp;&emsp;Essas User Stories também preparam o terreno para futuras melhorias, estabelecendo uma base sólida para o desenvolvimento contínuo da empresa. Através dessas histórias, reforçamos o compromisso com a excelência nos processos contábeis e o alinhamento estratégico da G2.

&emsp;&emsp;Em resumo, essas User Stories não só atendem às necessidades atuais da G2, mas também posicionam a empresa para continuar evoluindo de forma eficaz e ágil.


# <a id="c2"></a>2. Análise de Negócios  

# <a id="c2.1"></a> 2.1 Canvas Proposta de Valor

### 2.1.1 Introdução
<p align="justify"> 
&emsp;&emsp;O Value Proposition Canvas é uma ferramenta de análise de negócios que ajuda a entender como um projeto pode gerar valor para os clientes. Ele é composto por duas partes: o segmento de clientes e a proposta de valor.

No segmento de clientes, identificamos os benefícios que o cliente espera obter, os problemas que deseja evitar e as atividades que precisa realizar. Este perfil oferece uma visão detalhada das necessidades e desejos do cliente. A seção de tarefas do cliente descreve as atividades que ele precisa executar para alcançar seus objetivos, que podem ser funcionais, sociais, emocionais ou relacionadas a necessidades básicas. Essas tarefas também podem envolver diferentes papéis, como comprador, co-criador e transferidor.

Na proposta de valor, apresentamos os aliviadores de dores e os criadores de benefícios. Os aliviadores de dores mostram como o projeto pode resolver os problemas do cliente, enquanto os criadores de benefícios destacam como o projeto pode gerar vantagens para o cliente. A seção de produtos e serviços lista todos os produtos e serviços que compõem a proposta de valor, que podem ser tangíveis, digitais/virtuais, intangíveis ou financeiros.


### 2.1.2 Canvas Proposta de Valor
<div align="center">
<sub>Figura X - Título</sub>
<img src="../assets/CanvasVPC.png" width="100%" >
<sup>Fonte: Material produzido pelos autores com base no Canvas Proposta de Valor do Dr Alexander Osterwalder (2024)</sup>
</div>

### 2.1.3 Conclusão
<p align="justify"> 
&emsp;&emsp;Value Proposition Canvas é uma ferramenta fundamental para empresas que desejam compreender e satisfazer melhor as necessidades de seus clientes. Ele possibilita uma análise detalhada do perfil do cliente e da proposta de valor, assegurando que ambos estejam em harmonia. Ao identificar as dores e os benefícios esperados pelos clientes, além de propor soluções que aliviem essas dores e proporcionem ganhos, é possível desenvolver produtos e serviços que não apenas atendam, mas superem as expectativas dos clientes. Ademais, ao considerar os diferentes papéis do cliente e os diversos tipos de produtos e serviços, essa ferramenta oferece uma visão completa e diversificada do valor que um projeto pode oferecer. Assim, o Value Proposition Canvas é indispensável para qualquer negócio que almeje criar valor significativo para seus clientes.

# <a id="c2.2"></a> 2.2 Matriz de Risco e Oportunidades
<p align="justify"> 
&emsp;&emsp;A implementação de um sistema ERP, como o SAP Business One, é um processo complexo que envolve a integração de diversas áreas da empresa, desde a TI até o departamento financeiro. Durante esse processo, é essencial identificar os riscos potenciais que possam impactar o cronograma, a qualidade da entrega e a satisfação dos usuários. Além disso, é igualmente importante reconhecer as oportunidades que podem surgir durante a implementação, possibilitando melhorias operacionais e estratégicas. Esta sessão apresenta uma análise detalhada dos principais riscos e oportunidades, bem como o plano de ação correspondente para garantir o sucesso do projeto.

### 2.2.1 Matriz de Risco e Oportunidades
<div align="center">
<sub>Figura X - Título</sub>
<img src="../assets/Matriz-de-Risco.png" width="100%" > 
<sup>Fonte: Material produzido pelos autores com base na matriz de risco popularizada pelo Project Management Institute (PMI) através do seu guia de boas práticas, o "PMBOK Guide" (1987)</sup>
</div>

### 2.2.2 Plano de Resposta para Riscos e Oportunidades

&emsp;&emsp;Através da identificação e análise cuidadosa dos riscos e oportunidades, desenvolvemos um plano de resposta que permite mitigar os impactos negativos e aproveitar as vantagens potenciais da implementação do SAP Business One. Com ações claras e responsáveis definidos, o projeto está bem posicionado para alcançar seus objetivos, promovendo uma gestão mais eficiente e decisões mais assertivas.

### Metodologia de Cálculo de Risco vs Impacto

Para determinar a posição de cada risco e oportunidade na matriz de risco, adotamos uma abordagem quantitativa que envolve a avaliação da probabilidade e do impacto de cada item.

**1. Estimativa de Probabilidade:**
   - A probabilidade foi calculada com base na frequência esperada de ocorrência de cada risco ou oportunidade. Isso foi estimado em termos percentuais, representando a chance de cada evento ocorrer. Por exemplo, uma probabilidade de 90% indica que o risco tem uma alta chance de ocorrer.

**2. Estimativa de Impacto:**
   - O impacto foi avaliado em uma escala de 1 a 5, onde 1 representa um impacto muito baixo e 5 representa um impacto muito alto. Essa avaliação considerou os potenciais efeitos financeiros, operacionais e qualitativos que o risco ou oportunidade poderia ter no projeto.

**3. Cálculo da Pontuação do Risco:**
   - A pontuação de cada risco ou oportunidade foi calculada multiplicando a probabilidade pelo impacto, isso resultou em uma pontuação que ajudou a posicionar cada risco e oportunidade na matriz, de acordo com sua criticidade.

Esta metodologia permitiu uma análise sistemática e objetiva dos riscos e oportunidades, ajudando a equipe a focar nos itens mais críticos para o sucesso do projeto.

### Ameaças

1. **Resistência à mudança por parte dos usuários finais**
   - **Descrição:** Os usuários finais podem resistir à adoção do novo sistema devido à incerteza ou falta de compreensão das mudanças.
   - **Estratégia:** Mitigar
   - **Ação:** Entregar uma documentação completa como forma de auxílio e orientação. Realizar workshops e sessões de treinamento interativos.
   - **Justificativa:** Facilitar a adaptação ao novo sistema e reduzir a resistência.
   - **Responsável:** Equipe de Treinamento e Comunicação.
   - **Probabilidade:** 90%
   - **Impacto:** 5 (Muito Alto)
   - **Pontuação do Risco:** 0.9 * 5 = 4.5

2. **Indisponibilidade de recursos de infraestrutura**
   - **Descrição:** A falta de recursos de infraestrutura, como servidores ou redes, pode causar atrasos no projeto.
   - **Estratégia:** Mitigar
   - **Ação:** Estabelecer acordos com fornecedores e criar planos de contingência para garantir a disponibilidade dos recursos necessários.
   - **Justificativa:** Garantir que os recursos estejam disponíveis para evitar atrasos.
   - **Responsável:** Gerente de Infraestrutura.
   - **Probabilidade:** 50%
   - **Impacto:** 4 (Alto)
   - **Pontuação do Risco:** 0.5 * 4 = 2.0

3. **Falta de conhecimento técnico da equipe no SAP Business One**
   - **Descrição:** A equipe pode não ter o conhecimento técnico necessário para lidar com a complexidade do SAP Business One, resultando em erros e atrasos.
   - **Estratégia:** Mitigar
   - **Ação:** Certificar durante as entregas que o projeto está sendo desenvolvido com clareza e obter feedbacks. Implementar um programa de treinamento contínuo e designar mentores especializados para suporte durante a implementação.
   - **Justificativa:** Assegurar que a equipe esteja bem preparada para evitar erros.
   - **Responsável:** Líder Técnico do Projeto.
   - **Probabilidade:** 70%
   - **Impacto:** 5 (Muito Alto)
   - **Pontuação do Risco:** 0.7 * 5 = 3.5

4. **Atraso na disponibilização dos dados mestres pelo cliente**
   - **Descrição:** O cliente pode não fornecer os dados mestres no prazo acordado, impactando o cronograma do projeto.
   - **Estratégia:** Mitigar
   - **Ação:** Definir prazos claros com o cliente e criar um plano de contingência que utilize dados simulados para prosseguir com o desenvolvimento.
   - **Justificativa:** Evitar que a falta de dados atrase o cronograma do projeto.
   - **Responsável:** Gerente de Projeto.
   - **Probabilidade:** 50%
   - **Impacto:** 5 (Muito Alto)
   - **Pontuação do Risco:** 0.5 * 5 = 2.5

5. **Falha na migração de dados para o novo sistema**
   - **Descrição:** Erros na migração de dados podem levar à perda de dados ou à inconsistência no sistema novo.
   - **Estratégia:** Mitigar
   - **Ação:** Realizar migração em fases e testes de validação em cada etapa, incluindo backups antes de cada fase de migração.
   - **Justificativa:** Garantir que a migração seja feita corretamente, minimizando o risco de perda de dados.
   - **Responsável:** Especialista em Migração de Dados.
   - **Probabilidade:** 30%
   - **Impacto:** 4 (Alto)
   - **Pontuação do Risco:** 0.3×4=1.2

6. **Escopo mal definido ou mudanças frequentes de escopo**
   - **Descrição:** Um escopo mal definido ou mudanças frequentes podem causar desvios no cronograma e no orçamento.
   - **Estratégia:** Mitigar
   - **Ação:** Implementar um controle rigoroso de mudanças e revisões periódicas do escopo, com documentação detalhada e aprovação formal para cada alteração.
   - **Justificativa:** Manter o projeto dentro do escopo original para evitar desvios.
   - **Responsável:** Gerente de Projeto.
   - **Probabilidade:** 50%
   - **Impacto:** 3 (Moderado)
   - **Pontuação do Risco:** 0.5 * 3 = 1.5

7. **Sobrecarga da Equipe de Desenvolvimento**
   - **Descrição:** A equipe de desenvolvimento pode ficar sobrecarregada devido ao acúmulo de tarefas ou prazos apertados, o que pode levar a erros, atrasos, e diminuição da qualidade do trabalho.
   - **Estratégia:** Mitigar
   - **Ação:** Monitorar constantemente a carga de trabalho da equipe e implementar um sistema de gestão de tarefas que permita priorizar atividades críticas. Considerar a contratação temporária de pessoal adicional ou a redistribuição de tarefas para aliviar a pressão sobre a equipe.
   - **Justificativa:** Reduzir a possibilidade de erros e atrasos causados por sobrecarga, garantindo que a equipe trabalhe em um ritmo sustentável e que a qualidade do trabalho seja mantida.
   - **Responsável:** Gerente de Projeto e Líder de Equipe.
   - **Probabilidade:** 30%
   - **Impacto:** 3 (Moderado)
   - **Pontuação do Risco:** 0.3 * 3 = 0.9

8. **Problemas na parametrização das regras de negócio**
   - **Descrição:** A parametrização incorreta das regras de negócio pode resultar em falhas operacionais significativas.
   - **Estratégia:** Mitigar
   - **Ação:** Realizar testes detalhados e obter validação do cliente para cada configuração, garantindo que todas as parametrizações estejam alinhadas com os requisitos de negócio.
   - **Justificativa:** Assegurar que as regras de negócio estejam configuradas corretamente.
   - **Responsável:** Analista de Negócios.
   - **Probabilidade:** 70%
   - **Impacto:** 4 (Alto)
   - **Pontuação do Risco:** 0.7 * 4 = 2.8

9. **Problemas legais relacionados à conformidade com regulamentações**
   - **Descrição:** O não cumprimento de regulamentações pode resultar em multas e penalidades legais para a empresa.
   - **Estratégia:** Mitigar
   - **Ação:** Consultar especialistas jurídicos para garantir que todas as regulamentações aplicáveis sejam cumpridas durante o desenvolvimento e implementação do projeto.
   - **Justificativa:** Evitar riscos legais que possam prejudicar o projeto ou a empresa.
   - **Responsável:** Consultor Jurídico.
   - **Probabilidade:** 10%
   - **Impacto:** 5 (Muito Alto)
   - **Pontuação do Risco:** 0.1 * 5 = 0.5

10. **Falhas na integração entre módulos do ERP**
      - **Descrição:** Problemas na integração entre diferentes módulos do ERP podem levar a inconsistências nos dados e interrupções nas operações.
      - **Estratégia:** Mitigar
      - **Ação:** Utilizar ambientes de teste para simular a integração entre módulos e identificar possíveis problemas antes da implantação no ambiente de produção.
      - **Justificativa:** A integração entre módulos é crucial para o funcionamento eficiente de um ERP. Qualquer falha nesse processo pode resultar em interrupções significativas.
      - **Responsável:** Equipe de Integração de Sistemas.
      - **Probabilidade:** 60%
      - **Impacto:** 4 (Alto)
      - **Pontuação do Risco:** 0.6 * 4 = 2.4

## 2.2.3 Plano de Resposta para Oportunidades

### Oportunidades

1. **Criação de uma Patente para a Solução Desenvolvida**
   - **Descrição:** A solução desenvolvida possui potencial inovador que pode ser patenteado, gerando exclusividade e vantagens competitivas para a empresa.
   - **Estratégia:** Explorar
   - **Ação:** Realizar uma análise detalhada da solução para identificar elementos que podem ser patenteados. Consultar especialistas em propriedade intelectual para assegurar que todos os aspectos legais sejam cumpridos e submeter a patente.
   - **Justificativa:** Garantir exclusividade e potencial de retorno financeiro através da proteção da propriedade intelectual.
   - **Responsável:** Departamento Jurídico e Equipe de P&D.
   - **Probabilidade:** 70%
   - **Impacto:** 4 (Alto)
   - **Pontuação do Risco:** 0.7 * 4 = 2.8

2. **Abertura de Novos Mercados com a Solução Inovadora**
   - **Descrição:** A solução desenvolvida pode ser introduzida em novos mercados, ampliando o alcance da empresa e gerando novas fontes de receita.
   - **Estratégia:** Explorar
   - **Ação:** Realizar estudos de mercado para identificar regiões ou segmentos onde a solução possa ser implementada com sucesso. Desenvolver estratégias de marketing específicas para esses novos mercados.
   - **Justificativa:** Expandir a presença da empresa e diversificar as fontes de receita.
   - **Responsável:** Equipe de Marketing e Desenvolvimento de Negócios.
   - **Probabilidade:** 50%
   - **Impacto:** 4 (Alto)
   - **Pontuação do Risco:** 0.5 * 4 = 2.0

3. **Estabelecimento de Parcerias para Comercialização da Tecnologia**
   - **Descrição:** A solução desenvolvida pode ser licenciada ou comercializada através de parcerias com outras empresas, aumentando o potencial de receita e ampliando a base de usuários.
   - **Estratégia:** Explorar
   - **Ação:** Identificar empresas potenciais para parcerias estratégicas e negociar termos de licenciamento ou co-comercialização. Estabelecer acordos que beneficiem ambas as partes.
   - **Justificativa:** Aumentar o alcance da solução e gerar novas oportunidades de receita através de parcerias estratégicas.
   - **Responsável:** Equipe de Parcerias e Alianças Estratégicas.
   - **Probabilidade:** 30%
   - **Impacto:** 4 (Alto)
   - **Pontuação do Risco:** 0.3 * 4 = 1.2

<p align="justify"> 
&emsp;&emsp;Através da identificação e análise cuidadosa dos riscos e oportunidades, desenvolvemos um plano de resposta que permite mitigar os impactos negativos e aproveitar as vantagens potenciais da implementação do SAP Business One. Com ações claras e responsáveis definidos, o projeto está bem posicionado para alcançar seus objetivos, promovendo uma gestão mais eficiente e decisões mais assertivas. A conclusão bem-sucedida desse projeto não só atenderá às necessidades imediatas da empresa, como também abrirá novas possibilidades de crescimento e inovação no futuro.

## <a id="c2.3"><a/>2.3 Análise Financeira

&emsp;*[Conteúdo adicionado nas próximas sprints.]*

# <a id="c3"></a> 3. Desenvolvimento e Implementação

## <a id="c3.1"></a>3.1 Desenho da Solução

### 3.1.1 Introdução

O presente documento tem como objetivo apresentar o mapeamento, documentação e detalhamento dos macroprocessos, processos e subprocessos relacionados às áreas contábil, financeira, de vendas, compras e estoque no contexto da implementação do sistema ERP SAP Business One na empresa G2 Tecnologia. A escolha pelo SAP Business One visa a melhoria da eficiência operacional, a integração das diferentes áreas da empresa e a garantia de maior controle e visibilidade sobre os processos de negócio.

Os processos aqui descritos foram identificados a partir de entrevistas com stakeholders e análises dos formulários de Business Blue Print fornecidos pelo cliente. Cada processo foi documentado com detalhes sobre as entradas, saídas, atividades realizadas e responsáveis, visando assegurar uma implementação eficaz e alinhada com as expectativas da empresa.

### 3.1.2 Visão Geral dos Macroprocessos

A seguir, apresenta-se a representação gráfica dos macroprocessos mapeados para a implementação do SAP Business One, abrangendo as áreas de Compras, Vendas, Estoque, Financeiro e Contábil.

<div align="center">
<sub>Figura 1 - Fluxo de Trabalho </sub>
<img src="../assets/WorkflowDiagram.jpeg" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

### 3.1.3 Detalhamento dos Macroprocessos

### 3.1.4 Macroprocesso Compras

##### 3.1.4.1 Processo 1: Início do Processo de Compras
- **Atividade:** Definir e selecionar fornecedores.
- **Responsável:** Equipe de Compras.
- **Entrada:** Necessidade de compra ou reposição de estoque.
- **Saída:** Fornecedores selecionados.

##### 3.1.4.2 Processo 2: Emissão de Pedidos de Compra
- **Atividade:** Gerar e emitir o pedido de compra para o fornecedor.
- **Responsável:** Equipe de Compras.
- **Entrada:** Fornecedores selecionados.
- **Saída:** Pedido de compra emitido.

#### 3.1.5 Macroprocesso Vendas

##### 3.1.5.1 Processo 1: Início do Processo de Vendas
- **Atividade:** Definição da lista de preços.
- **Responsável:** Equipe de Vendas.
- **Entrada:** Informações de mercado e custos de produtos.
- **Saída:** Lista de preços definida.

##### 3.1.5.2 Processo 2: Emissão de Pedidos de Venda
- **Atividade:** Receber pedido do cliente e emitir ordem de venda.
- **Responsável:** Equipe de Vendas.
- **Entrada:** Solicitação do cliente.
- **Saída:** Pedido de venda emitido.

#### 3.1.3 Macroprocesso Estoque

##### 3.1.3.1 Processo 1: Cadastro e Definição de Itens
- **Atividade:** Cadastro de novos produtos e definição dos itens no estoque.
- **Responsável:** Equipe de Estoque.
- **Entrada:** Novos produtos ou itens a serem cadastrados.
- **Saída:** Itens cadastrados no sistema.

##### 3.1.3.2 Processo 2: Definição de Método de Avaliação de Custo
- **Atividade:** Seleção e implementação do método de avaliação de custo (FIFO, LIFO, Custo Médio, etc.).
- **Responsável:** Equipe de Estoque e Contábil.
- **Entrada:** Políticas de contabilidade e requisitos fiscais.
- **Saída:** Método de avaliação de custo implementado e aplicado.

##### 3.1.3.3 Processo 3: Movimentação de Entrada e Saída de Estoque
- **Atividade:** Controle de entrada e saída de mercadorias no estoque.
- **Responsável:** Equipe de Estoque.
- **Entrada:** Produtos recebidos ou vendidos.
- **Saída:** Estoque atualizado.

#### 3.1.4 Macroprocesso Financeiro

##### 3.1.4.1 Processo 1: Projeção de Caixa
- **Atividade:** Projeção de fluxos de caixa futuro.
- **Responsável:** Equipe Financeira.
- **Entrada:** Dados financeiros e de vendas.
- **Saída:** Projeção de fluxo de caixa.

##### 3.1.4.2 Processo 2: Controle de Contas a Pagar e Receber
- **Atividade:** Gerenciamento das contas a pagar e a receber.
- **Responsável:** Equipe Financeira.
- **Entrada:** Faturas e notas fiscais.
- **Saída:** Pagamentos realizados e recebimentos processados.

##### 3.1.4.3 Processo 3: Reconciliação Bancária
- **Atividade:** Verificar e ajustar saldos de contas bancárias.
- **Responsável:** Equipe Financeira.
- **Entrada:** Extratos bancários.
- **Saída:** Saldos bancários reconciliados.

### 3.1.5 Macroprocesso Contábil

##### 3.1.5.1 Processo 1: Reconciliação Contábil
- **Atividade:** Reconciliar contas contábeis com o sistema financeiro.
- **Responsável:** Equipe Contábil.
- **Entrada:** Relatórios financeiros.
- **Saída:** Contas contábeis reconciliadas.

##### 3.1.5.2 Processo 2: Lançamentos Contábeis
- **Atividade:** Registrar lançamentos contábeis no sistema.
- **Responsável:** Equipe Contábil.
- **Entrada:** Dados financeiros e contábeis.
- **Saída:** Lançamentos contábeis realizados.

##### 3.1.5.3 Processo 3: Determinação de Contas Contábeis
- **Atividade:** Determinar as contas contábeis apropriadas para cada operação financeira.
- **Responsável:** Equipe Contábil.
- **Entrada:** Informações financeiras e operacionais.
- **Saída:** Contas contábeis determinadas.

### 3.1.6 Fluxo de Processo Integrado: Gestão Contábil e Fiscal

#### 3.1.6.1 Introdução

Este tópico descreve o fluxo de processo integrado da gestão contábil e fiscal, enfatizando como a contabilidade interage com as áreas de compras, vendas, estoque e financeiro no contexto da implementação do sistema ERP SAP Business One. A integração entre essas áreas é essencial para garantir a precisão nos registros contábeis, a apuração correta de impostos, e a geração de relatórios contábeis e fiscais que reflitam a realidade financeira da empresa.

#### 3.1.6.2 Visão Geral do Fluxo de Processo

O diagrama a seguir ilustra o fluxo de processo integrado para a gestão contábil e fiscal, mostrando como as áreas de Compras, Vendas, Estoque e Financeiro se inter-relacionam com a Contabilidade.

<div align="center">
<sub>Figura 2 - Diagrama de trabalho area contabil</sub>
<img src="../assets/Workflow Diagram (1).jpg" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>


### 3.1.7 Subprocessos e Integrações

#### 3.1.7.1 Compras
- **Registro de Transações:** As transações de compra são registradas conforme os bens e serviços são adquiridos.
- **Registro de Compras:** Documentação e contabilização dos itens adquiridos, incluindo dados de fornecedores e condições de pagamento.
- **Apuração dos Impostos:** Cálculo de impostos relacionados às compras realizadas, como ICMS e IPI.
- **Relatórios Contábeis/Fiscais:** Geração de relatórios que consolidam as transações e impostos associados às compras.
- **Conciliação a Pagar:** Verificação e reconciliação das contas a pagar, assegurando que os valores das compras estejam corretos e correspondam aos registros contábeis.

#### 3.1.7.2 Vendas
- **Registro de Transações:** Todas as transações de venda são registradas quando produtos ou serviços são vendidos aos clientes.
- **Registro de Vendas:** Documentação detalhada das vendas, incluindo o valor total, impostos e termos de pagamento.
- **Apuração dos Impostos:** Cálculo dos impostos sobre as vendas, como ICMS, ISS, entre outros.
- **Relatórios Contábeis/Fiscais:** Relatórios que consolidam as vendas realizadas e os impostos devidos.
- **Conciliação a Receber:** Verificação e reconciliação das contas a receber, garantindo que os valores das vendas sejam devidamente registrados e conciliados com as contas contábeis.

#### 3.1.7.3 Estoque
- **Registro de Transações:** Movimentação de estoque é registrada conforme produtos são adicionados ou retirados.
- **Movimentação de Estoque:** Controle de entradas e saídas de produtos no estoque, assegurando que os níveis de estoque estejam atualizados.
- **Apuração dos Impostos:** Cálculo de impostos relacionados às movimentações de estoque.
- **Relatórios Contábeis/Fiscais:** Relatórios que refletem as movimentações de estoque e o impacto fiscal dessas operações.
- **Conciliação de Inventário:** Reconciliação do inventário físico com os registros contábeis para garantir a precisão dos dados de estoque.

#### 3.1.7.4 Financeiro
- **Registro de Transações:** Todas as transações financeiras, como pagamentos e recebimentos, são registradas no sistema.
- **Movimentações Financeiras:** Documentação das entradas e saídas de recursos financeiros, incluindo operações bancárias.
- **Apuração dos Impostos:** Cálculo de impostos sobre as movimentações financeiras, como IOF.
- **Relatórios Contábeis/Fiscais:** Relatórios financeiros que consolidam as movimentações financeiras e os impostos aplicáveis.
- **Conciliação Bancária:** Reconciliação dos saldos bancários com os registros contábeis para assegurar que todas as transações financeiras estejam devidamente registradas.

### 3.1.8 Conclusão

O fluxo de processo integrado descrito neste tópico evidencia como a gestão contábil e fiscal está profundamente interligada com as áreas de Compras, Vendas, Estoque e Financeiro. A correta execução desse fluxo garante que os dados contábeis sejam precisos, os impostos sejam devidamente apurados, e os relatórios gerados estejam em conformidade com as normas fiscais e contábeis. A conciliação final em cada área é crucial para assegurar a consistência dos dados e a preparação adequada para auditorias e revisões financeiras.

## <a id="c3.2"></a> 3.2 Configurações Iniciais

### 3.2.1 Introdução

Esta seção reúne uma documentação detalhada de imagens extraídas do SAP Business One, onde cada captura de tela reflete as configurações realizadas, acompanhadas dos dados mestres que já foram validados. O objetivo é assegurar que as configurações estejam em conformidade com as especificações definidas no Business Blueprint (BBP) e garantir a precisão e a integridade do ambiente configurado. 

### 3.2.2  Documentação de Configuração do SAP Business One

#### 3.2.2.1 Configurações Iniciais

<div align="center">
<sub>Figura 1 - Tela Inicial do SAP Business One</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420630/SAPprints/urtke0xa9z3chqbcnldr.png)

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420631/SAPprints/amlyexglz5l05ydds57n.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela inicial do SAP Business One, onde os menus principais são acessados. A barra de menus na parte superior permite que você navegue para diferentes módulos, como Administração, Finanças, Vendas, etc.  
&emsp;&emsp;**Contexto:** Esse é o ponto de partida para acessar as diferentes configurações e módulos necessários para a implementação do sistema.  
&emsp;&emsp;**O que observar:** Verifique se você tem acesso a todos os módulos necessários, pois as permissões podem variar dependendo do seu perfil de usuário.

<div align="center">
<sub>Figura 2 - Configuração de Administrar Custo de Item por Depósito</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420634/SAPprints/gjepnuevr5jg4hb7ff95.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela de configuração de detalhes da empresa no SAP Business One, especificamente a aba "Inicialização Básica". Aqui, você pode marcar a opção "Administrar custo de item por depósito".  
&emsp;&emsp;**Contexto:** Essa configuração é crucial para controlar o custo dos itens em diferentes depósitos da empresa, algo vital para a precisão dos relatórios de estoque e financeiros.  
&emsp;&emsp;**O que observar:** Ao marcar esta opção, o sistema começará a gerenciar os custos dos itens individualmente por depósito, e essa ação é irreversível.

<div align="center">
<sub>Figura 3 - Detalhes de Empresa</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420634/SAPprints/dh3r3pyjaf2vpqqqxp9d.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a configuração de gerenciamento de estoque por depósito. Na aba "Geral" dentro das configurações do sistema, você pode marcar "Administrar estoque por depósito".  
&emsp;&emsp;**Contexto:** Esta configuração permite que o estoque seja gerido separadamente por cada depósito, essencial para empresas que têm múltiplos armazéns ou locais de estocagem.  
&emsp;&emsp;**O que observar:** Certifique-se de que essa configuração reflete as operações reais da sua empresa, pois ela terá impacto direto no controle de estoque.

<div align="center">
<sub>Figura 4 - Configuração de Recursos de Múltiplas Filiais</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420630/SAPprints/wcdyq6wsahkkrmzxbdcu.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem é uma instrução caso de algum erro na ativação de recursos de múltiplas filiais.
&emsp;&emsp;**Contexto:** Poderia ser algo importante que deve ser mencionado ou revisado, como uma configuração específica ou uma documentação adicional.  
&emsp;&emsp;**O que observar:** Verifique o contexto desta nota para garantir que todas as informações necessárias sejam incluídas no seu documento final.

<div align="center">
<sub>Figura 5 - Nota para Revisão ou Citação</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420634/SAPprints/dh3r3pyjaf2vpqqqxp9d.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** A imagem mostra a configuração para ativar recursos de múltiplas filiais. Esta configuração está na aba "Inicialização Básica", onde você pode ativar o recurso de múltiplas filiais.  
&emsp;&emsp;**Contexto:** Esta configuração é essencial para empresas que operam com mais de um CNPJ ou que desejam gerenciar diferentes filiais dentro do SAP Business One.  
&emsp;&emsp;**O que observar:** Ativar este recurso é uma ação irreversível; certifique-se de que sua empresa necessita dessa configuração antes de prosseguir.

<div align="center">
<sub>Figura 6 - Ativação da Determinação Avançada de Conta do Razão</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420634/SAPprints/uplgub56iszukweh28da.png)
  
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem exibe a tela onde você pode ativar a determinação avançada de conta do Razão.  
&emsp;&emsp;**Contexto:** Ativar a determinação avançada de conta do Razão é importante para empresas que necessitam de uma contabilidade mais detalhada e automatizada, onde diferentes transações podem ser associadas automaticamente a contas específicas.  
&emsp;&emsp;**O que observar:** Confirme que a sua empresa requer essa funcionalidade, pois ela afeta diretamente a forma como as contas são geridas no SAP.

<div align="center">
<sub>Figura 7 - Configuração do Método de Avaliação de Grupos de Itens</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420633/SAPprints/eswdjvugncswfhsxmma5.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela de configuração do método de avaliação de grupos de itens. Aqui, você pode escolher entre Preço Médio Móvel, Padrão, e FIFO.  
&emsp;&emsp;**Contexto:** O método de avaliação selecionado terá um impacto direto no valor dos itens no estoque e nos relatórios financeiros.  
&emsp;&emsp;**O que observar:** Escolha o método de avaliação que melhor se adequa às práticas contábeis da sua empresa.

<div align="center">
<sub>Figura 8 - Configuração das Informações Bancárias da Empresa</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420634/SAPprints/bp6yfve5of4jswgkv3xe.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela onde você define informações bancárias da empresa.  
&emsp;&emsp;**Contexto:** Configurar corretamente as informações bancárias é essencial para garantir que todas as transações financeiras sejam corretamente refletidas nos relatórios e no sistema.  
&emsp;&emsp;**O que observar:** Certifique-se de que os dados bancários estejam corretos e que estejam devidamente associados às contas relevantes.

<div align="center">
<sub>Figura 9 - Configuração da Filial Padrão</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420631/SAPprints/dixbftg7oiwqesmemzcr.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela mostra a configuração da filial padrão da empresa no SAP Business One.  
&emsp;&emsp;**Contexto:** Definir a filial padrão é importante para que todas as operações financeiras e de estoque sejam corretamente atribuídas à unidadeda empresa.  
&emsp;&emsp;**O que observar:** Escolha a filial correta como padrão, especialmente se a empresa opera com várias filiais.

#### 3.2.2.2 Configurações Específicas

<div align="center">
<sub>Figura 10 - Configuração das Restrições de Atividade do Cliente</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420631/SAPprints/amlyexglz5l05ydds57n.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a configuração das restrições de atividade do cliente, como limites de crédito e compromissos.  
&emsp;&emsp;**Contexto:** Configurar corretamente essas restrições é vital para garantir que a empresa não enfrente problemas de inadimplência ou excesso de compromissos financeiros.  
&emsp;&emsp;**O que observar:** Valide com o cliente se essas restrições estão configuradas conforme as políticas financeiras da empresa.

<div align="center">
<sub>Figura 11 - Configuração de Comissões no SAP Business One</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420631/SAPprints/dp7sonfeslqlabftj0dq.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela exibe a configuração de comissão dentro do SAP Business One.  
&emsp;&emsp;**Contexto:** Configurar as comissões corretamente é importante para que o sistema calcule automaticamente os valores devidos a vendedores ou representantes, conforme as vendas realizadas.  
&emsp;&emsp;**O que observar:** Verifique se todos os grupos e valores de comissão estão configurados de acordo com as práticas da empresa.

<div align="center">
<sub>Figura 12 - Configurações Gerais</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420630/SAPprints/rvuvilcjbvgpzsh4ozaq.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Aqui, temos a configuração de condições de pagamento no SAP Business One.  
&emsp;&emsp;**Contexto:** As condições de pagamento determinam os termos sob os quais a empresa recebe ou faz pagamentos, sendo crucial para a gestão do fluxo de caixa.  
&emsp;&emsp;**O que observar:** Assegure-se de que todas as condições de pagamento, tanto para clientes quanto para fornecedores, estejam corretamente configuradas.

<div align="center">
<sub>Figura 13 - Exibir Configurações Gerais</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420631/SAPprints/hut9wzqpohejj5i623hn.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela de preferência de pagamento, onde você define as condições padrão de pagamento para clientes e fornecedores.  
&emsp;&emsp;**Contexto:** É importante definir essas preferências para que as transações sejam processadas corretamente, evitando problemas com prazos e métodos de pagamento.  
&emsp;&emsp;**O que observar:** Certifique-se de que as preferências de pagamento refletem os acordos reais com clientes e fornecedores.

<div align="center">
<sub>Figura 14 - Exibir Configurações Gerais Data e Hora</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420631/SAPprints/hut9wzqpohejj5i623hn.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela permite configurar o formato de data e hora no SAP Business One.  
&emsp;&emsp;**Contexto:** Configurar corretamente o formato de data e hora garante que todos os registros no sistema sejam consistentes e compreensíveis para todos os usuários.  
&emsp;&emsp;**O que observar:** Escolha os formatos que estão de acordo com as práticas locais e a necessidade da empresa.

<div align="center">
<sub>Figura 15 - Configuração de Exibição de Casas Decimais</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420630/SAPprints/bnmy8prigx5i6linheid.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem exibe a configuração de exibição de casas decimais para diferentes tipos de valores no SAP Business One.  
&emsp;&emsp;**Contexto:** Definir corretamente as casas decimais é importante para garantir a precisão dos relatórios financeiros e operacionais.  
&emsp;&emsp;**O que observar:** Assegure-se de que as casas decimais estão configuradas conforme os requisitos contábeis e operacionais da empresa.

<div align="center">
<sub>Figura 16 - Configuração do Método de Administração de Itens</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420631/SAPprints/tnzemjg8ejbw4rzx2mg6.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela mostra a configuração do método de administração de itens, onde se define quando o número de série deve ser solicitado.  
&emsp;&emsp;**Contexto:** Este método é importante para a gestão de itens que requerem um acompanhamento rigoroso, como produtos seriados ou loteados.  
&emsp;&emsp;**O que observar:** Escolha a configuração que melhor se alinha ao processo de gestão de estoque da empresa.

<div align="center">
<sub>Figura 17 - Configuração de Adição Automática a Depósitos</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420633/SAPprints/cdkhqlj9glim6itfivdn.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** A imagem exibe a tela de adição automática de itens a depósitos específicos no SAP Business One.  
&emsp;&emsp;**Contexto:** Esta configuração facilita a alocação de itens em depósitos automaticamente, simplificando a gestão de estoque.  
&emsp;&emsp;**O que observar:** Verifique se os depósitos estão corretamente configurados para cada tipo de item.

<div align="center">
<sub>Figura 18 - Configuração da Determinação de Conta do Razão</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420630/SAPprints/krut77mqy2gp6mp8jlsn.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a configuração da determinação de conta do Razão, importante para a associação automática de transações financeiras a contas específicas.  
&emsp;&emsp;**Contexto:** Essa configuração é vital para a automação e precisão da contabilidade.  
&emsp;&emsp;**O que observar:** Verifique se todas as contas estão corretamente associadas para evitar inconsistências nos relatórios financeiros.

<div align="center">
<sub>Figura 19 - Configuração de Dimensões na Contabilidade de Custo</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420633/SAPprints/wvh3hx8kyyvif4symicw.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela exibe a configuração de contabilidade de custo, especificamente a definição de dimensões.  
&emsp;&emsp;**Contexto:** As dimensões são usadas para rastrear custos em diferentes áreas ou departamentos dentro da empresa.  
&emsp;&emsp;**O que observar:** Configure as dimensões de acordo com a estrutura de custo da empresa.

<div align="center">
<sub>Figura 20 - Configuração de Centros de Custo</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420632/SAPprints/vqznqaqqcvacltlcgys4.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Aqui, temos a configuração de centros de custo, que são usados para alocar despesas e receitas a diferentes departamentos ou projetos.  
&emsp;&emsp;**Contexto:** Configurar centros de custo corretamente é crucial para a análise financeira detalhada por departamento ou projeto.  
&emsp;&emsp;**O que observar:** Verifique se os centros de custo estão configurados conforme a estrutura organizacional da empresa.

<div align="center">
<sub>Figura 21 - Configuração de Despesas de Importação</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420632/SAPprints/jmoo172axcfpuxuuswec.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a configuração de despesas de importação, onde são registrados os custos associados às operações de importação.  
&emsp;&emsp;**Contexto:** É importante para garantir que todas as despesas sejam refletidas corretamente no custo final dos produtos.  
&emsp;&emsp;**O que observar:** Certifique-se de que todas as despesas relacionadas à importação estão corretamente cadastradas.

<div align="center">
<sub>Figura 22 - Configuração de Despesas Adicionais</sub>
  
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420632/SAPprints/gfeye6e6omh6epywp7h2.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela exibe a configuração de despesas adicionais, onde custos extras associados a diferentes operações são registrados.  
&emsp;&emsp;**Contexto:** Esses custos adicionais podem impactar o preço final dos produtos ou serviços e devem ser bem gerenciados.  
&emsp;&emsp;**O que observar:** Verifique se todas as despesas adicionais estão devidamente cadastradas e associadas aos itens corretos.

<div align="center">
<sub>Figura 23 - Configuração de Depósitos no SAP Business One</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420632/SAPprints/scyh5dcu9n5mq0rsmhye.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a definição de depósitos no SAP Business One, onde são cadastrados os locais de armazenamento dos produtos.  
&emsp;&emsp;**Contexto:** É essencial para empresas com múltiplos depósitos ou armazéns, garantindo que o estoque seja gerido corretamente.  
&emsp;&emsp;**O que observar:** Verifique se todos os depósitos estão corretamente cadastrados e se os itens estão associados aos depósitos corretos.

<div align="center">
<sub>Figura 24 - Configuração de Grupos de Itens</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420633/SAPprints/zw7q5nl7ddycfmkblrih.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** A imagem exibe a configuração de grupos de itens, onde são categorizados os produtos que a empresa vende.  
&emsp;&emsp;**Contexto:** A categorização correta dos itens é fundamental para a gestão de estoque e para a criação de relatórios precisos.  
&emsp;&emsp;**O que observar:** Assegure-se de que todos os itens estão corretamente categorizados em seus respectivos grupos.

<div align="center">
<sub>Figura 25 - Definição de Cartões de Crédito</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420633/SAPprints/gg65euwmokqefua5ztye.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela de definição de cartões de crédito no SAP Business One. Aqui, você pode configurar o nome do cartão de crédito, associar uma conta do Razão e identificar a empresa relacionada.  
&emsp;&emsp;**Contexto:** A definição correta dos cartões de crédito é fundamental para a gestão financeira, permitindo que as transações sejam associadas corretamente à conta e empresa responsáveis.  
&emsp;&emsp;**O que observar:** Certifique-se de que todos os cartões de crédito utilizados pela empresa estão corretamente configurados e associados às contas relevantes.

<div align="center">
<sub>Figura 26 - Definição de Usuários</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420633/SAPprints/wfqh9unxaqv6yh8ypnlu.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem exibe a tela de definição de usuários no SAP Business One. Aqui, você pode configurar as informações dos usuários, incluindo nome, e-mail, telefone, e atribuição de filial.  
&emsp;&emsp;**Contexto:** Configurar os usuários corretamente é essencial para garantir que eles tenham acesso às funcionalidades adequadas no sistema, de acordo com suas responsabilidades na empresa.  
&emsp;&emsp;**O que observar:** Verifique se as informações dos usuários estão atualizadas e se as permissões e atribuições estão alinhadas com as funções de cada um na empresa.

<div align="center">
<sub>Figura 27 - Definição de Territórios</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420630/SAPprints/mhhdipqjfes24exdmugr.png)

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420631/SAPprints/cxu9xjwpyx3vei4lgbpx.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela mostra a definição de territórios no SAP Business One, onde são configuradas as áreas geográficas nas quais a empresa opera.  
&emsp;&emsp;**Contexto:** A configuração de territórios é importante para a gestão de vendas e operações em diferentes regiões, permitindo uma análise mais detalhada do desempenho em cada área.  
&emsp;&emsp;**O que observar:** Certifique-se de que todos os territórios relevantes estão devidamente configurados, com os nomes e hierarquias corretos.

<div align="center">
<sub>Figura 28 - Definição de Vendedores/Compradores</sub>
<img src="../assets/Screenshot 2024-08-22 at 18.27.05.png" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela de definição de vendedores ou compradores no SAP Business One. Aqui, é possível configurar os nomes dos vendedores, associar grupos de comissões e definir a porcentagem de comissão para cada vendedor.  
&emsp;&emsp;**Contexto:** A configuração de vendedores e suas comissões é fundamental para garantir que as vendas sejam corretamente associadas aos responsáveis, permitindo uma gestão eficaz de comissões.  
&emsp;&emsp;**O que observar:** Verifique se todos os vendedores estão corretamente cadastrados e se as comissões atribuídas correspondem às políticas da empresa.

<div align="center">
<sub>Figura 29 - Definição dos Níveis de Oportunidade</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420633/SAPprints/gjwia39x7gm6sbza3sze.png)

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela exibe a definição dos níveis de oportunidade dentro do SAP Business One. Aqui, é possível configurar as etapas de oportunidades, atribuindo porcentagens finais e indicando em quais áreas (vendas, compras) as etapas se aplicam.  
&emsp;&emsp;**Contexto:** Configurar corretamente os níveis de oportunidade é essencial para o gerenciamento de vendas e negociações, ajudando a rastrear o progresso das oportunidades ao longo das diferentes etapas.  
&emsp;&emsp;**O que observar:** Certifique-se de que todas as etapas e porcentagens refletem corretamente o ciclo de vendas da empresa.

<div align="center">
<sub>Figura 30 - Definição de Grupos de Clientes</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420632/SAPprints/glhcxvndygnr5radrpig.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela de definição de grupos de clientes no SAP Business One. Cada grupo de clientes pode ser associado a listas de preços e grupos de descontos específicos.  
&emsp;&emsp;**Contexto:** A configuração de grupos de clientes permite personalizar listas de preços e descontos para diferentes segmentos de clientes, otimizando as condições comerciais e o atendimento ao cliente.  
&emsp;&emsp;**O que observar:** Verifique se todos os grupos de clientes estão configurados conforme as necessidades comerciais da empresa, garantindo que os descontos e listas de preços aplicáveis sejam corretamente associados.

<div align="center">
<sub>Figura 31 - Definição de Grupos de Fornecedores</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420632/SAPprints/illqjasoiuuzxtz2rddi.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta tela exibe a definição de grupos de fornecedores, onde são configurados os fornecedores de acordo com listas de preços e grupos de descontos específicos.  
&emsp;&emsp;**Contexto:** A configuração adequada dos grupos de fornecedores ajuda na gestão eficiente dos fornecedores, facilitando a negociação e o controle de preços e descontos.  
&emsp;&emsp;**O que observar:** Certifique-se de que os grupos de fornecedores estão devidamente configurados, com listas de preços e descontos que reflitam os acordos comerciais estabelecidos.

<div align="center">
<sub>Figura 32 - Definição de Tipos de Envio</sub>

![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1724420632/SAPprints/vpg95qgfndkpuhf1sfpr.png )

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

&emsp;&emsp;**Descrição:** Esta imagem mostra a tela de definição de tipos de envio no SAP Business One. Cada tipo de envio pode ser associado a um site específico e ativado conforme necessário.  
&emsp;&emsp;**Contexto:** Configurar os tipos de envio é importante para garantir que os produtos sejam enviados corretamente de acordo com as preferências e necessidades dos clientes.  
&emsp;&emsp;**O que observar:** Verifique se todos os tipos de envio estão configurados de acordo com as operações logísticas da empresa e se estão associados aos canais corretos.

### 3.2.3 Conclusão

Cada configuração documentada tem um papel crucial na operação do SAP Business One, desde a gestão de custos por depósito até a definição de centros de custo e métodos de avaliação de estoque. As imagens fornecem uma referência visual que facilita a verificação e validação das configurações, assegurando que o sistema atenda às necessidades específicas do projeto.

O processo de validação dos dados mestres é essencial para garantir a integridade das informações que serão utilizadas no sistema. A estrutura da documentação é organizada de forma a cobrir tanto as configurações iniciais, que são críticas para o funcionamento do sistema, quanto as configurações específicas, que atendem a necessidades particulares. As imagens servem como um guia prático para os usuários, permitindo uma compreensão clara das configurações realizadas e fornecendo uma base para futuras auditorias e manutenções do sistema.

## <a id="c3.3"></a>3.3 Dados Mestres Validados

### 3.3.1 Caminhos de Acesso

#### 3.3.1.1 **Configuração Geral de Contas Contábeis**:
   - `Modules > Administration > Setup > Financials > G/L Account Determination`
   - **Imagem relacionada**: 
   ![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826569/G_L_Account_Determination_y8glnb.png)

#### 3.3.1.2 **Plano de Contas**:
   - `Modules > Financials > Chart of Accounts`
   - **Imagem relacionada**: 
   ![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826569/ChartsOfAccounts_hffwsy.png)

#### 3.3.1.3 **Cadastro de Parceiros de Negócio**:
   - `Modules > Business Partners > Business Partner Master Data`
   - **Imagem relacionada**: 
   ![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826569/BusinessPartnerMasterData_czvmoe.png)

Esses caminhos são utilizados para acessar e configurar as principais funcionalidades contábeis e de relacionamento com parceiros de negócio no sistema ERP. Eles são fundamentais para garantir que todas as transações financeiras sejam corretamente registradas e classificadas, de acordo com as normas contábeis e as necessidades da empresa.

### 3.3.2 Configuração de Contas Contábeis

##### 3.3.2.1 G/L Account Determination**

No menu de **G/L Account Determination**, as contas são configuradas para associar corretamente as transações contábeis com suas respectivas contas do plano de contas. As categorias configuradas incluem:

- **Sales (Vendas)**: Contas relacionadas às receitas da empresa, como contas a receber e transações de vendas.
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826568/Sales_dz7l6p.jpg)

- **Purchasing (Compras)**: Contas utilizadas para registrar as despesas e os passivos com fornecedores.
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826568/Purchasing_to65in.jpg)

- **General (Geral)**: Contas usadas em diversas transações contábeis, como ajustes de câmbio e despesas bancárias.
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826568/General_fsrgyf.jpg)


Estas configurações garantem que as operações de venda e compra sejam refletidas corretamente nos registros contábeis, facilitando a análise financeira e o cumprimento das obrigações fiscais.

**Links relacionados**:
- [Template_Cadastro de PNs](https://docs.google.com/spreadsheets/d/1Fu7bksMk16OEEnd63v69Hf_TjznEZWxD/edit?gid=118738051#gid=118738051)
- [Template_Cadastro de Itens](https://docs.google.com/spreadsheets/d/1XsjWydshiP71Lpk5bymCmZoehQmGfNCe/edit?gid=1598150342#gid=1598150342)

#### 3.3.3 Plano de Contas

No menu de **Chart of Accounts**, visualizamos e editamos o plano de contas da empresa. Este menu exibe uma estrutura hierárquica das contas contábeis, onde cada conta é categorizada sob grupos maiores como **Ativo**, **Passivo**, **Receita**, **Despesa**, etc.

**Exemplo de Contas Configuradas**:
- **1.01.01 - CIRCULANTE**
  - **1.01.01.01 - CAIXA**
    - **1.01.01.01.01 - Caixa Geral**
    - **1.01.01.01.02 - Valores Transitórios**
  - **1.01.01.02 - BANCOS**
    - **1.01.01.02.01 - Banco A**
  - **1.01.01.03 - APLICAÇÕES FINANCEIRAS**
    - **1.01.01.03.01 - Aplicação Financeira**

**Imagem relacionada**:
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826568/ChartOfAccounts1_k6bxza.jpg)
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826568/ChartOfAccounts2_mhpxdh.jpg)

### 3.3.4 Cadastro de Parceiros de Negócio

No menu **Business Partner Master Data**, são gerenciados os dados mestres dos parceiros de negócios, incluindo clientes e fornecedores. Este cadastro é essencial para a gestão das relações comerciais e financeiras.

**Campos Relevantes**:
- **Code, Name, Foreign Name (Código, Nome, Nome Estrangeiro)**: Identificadores e nome do parceiro de negócios.
- **Currency (Moeda)**: Moeda utilizada nas transações com o parceiro.
- **Payment Terms (Condições de Pagamento)**: Detalha as condições acordadas para pagamento.
- **Industry, Type of Business (Indústria, Tipo de Negócio)**: Classificações que podem influenciar a tributação e outros aspectos contábeis.

**Imagem relacionada**:
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826568/BuisnessPartnerMasterData1_lwh0lb.jpg)
![image](https://res.cloudinary.com/di57ql5yx/image/upload/v1723826568/BuisnessPartnerMasterData2_llt3ju.jpg)

### 3.3.5 Importância para a Contabilidade

A configuração adequada dessas contas contábeis e a correta atribuição no plano de contas garantem que todas as transações sejam registradas com precisão, refletindo a real situação financeira da empresa. O cadastro de parceiros de negócios é vital para a correta gestão das contas a pagar e a receber, além de assegurar que todas as interações comerciais sejam documentadas e rastreáveis.

Com essa estrutura, o sistema ERP permite que a empresa mantenha um controle financeiro rigoroso, assegurando a conformidade com as normas contábeis e facilitando auditorias e análises financeiras.

## <a id="c3.4"></a> 3.4 Documentação da Solução (Regras de Negócio e Diagramas)

### 3.4.1 Introdução

Este documento descreve o processo detalhado de configuração inicial no SAP Business One, essencial para o funcionamento adequado do sistema dentro da organização. As configurações gerais abrangem uma série de etapas críticas que determinam como os processos financeiros, logísticos e comerciais serão gerenciados. A precisão nestas configurações é fundamental para assegurar a integridade dos dados e a eficiência das operações empresariais.

### 3.4.2 Diagrama
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725230444/Diagrama_atualizado.drawio_dto5yg.png) 

#### 3.4.2.1 Configurações Gerais
- **Descrição:** Esta etapa envolve a configuração inicial do sistema SAP, onde são definidas as principais parametrizações que impactam todo o funcionamento do sistema. Configurações como moeda padrão, método de contabilização e definições globais da empresa são realizadas aqui.

#### 3.4.2.2 Determinação de Conta Contábil
- **Descrição:** Aqui são determinadas as contas contábeis que serão usadas pelo sistema, vinculando-as aos processos financeiros da empresa, como vendas, compras e estoque. É essencial que todas as contas estejam configuradas corretamente para evitar erros contábeis.

#### 3.4.2.3 Configuração de Centros de Custo
- **Descrição:** Consiste na criação e parametrização dos centros de custo, que são essenciais para a contabilidade gerencial, permitindo à empresa alocar despesas e receitas conforme suas áreas de atuação.

#### 3.4.2.4 Configuração de Depósitos
- **Descrição:** Nesta etapa, são configurados os depósitos de estoque da empresa, vinculados às filiais. Cada depósito precisa ser configurado corretamente para garantir o controle do estoque e o correto funcionamento do processo logístico.

#### 3.4.2.5 Configuração de Grupos de Itens
- **Descrição:** Esta configuração agrupa itens semelhantes para facilitar a gestão e a aplicação de regras contábeis. Também é útil para a geração de relatórios e análises detalhadas.

#### 3.4.2.6 Informações Básicas da Empresa
- **Descrição:** Inclui o cadastro de informações essenciais sobre a empresa, como nome, CNPJ, endereço, e outros dados fundamentais para a operação dentro do SAP Business One.

#### 3.4.2.7 Configuração de Moedas
- **Descrição:** Aqui são configuradas as moedas que serão utilizadas nas transações financeiras, tanto para compras quanto para vendas. É possível definir moedas correntes e sistemas.

#### 3.4.2.8 Cadastro de Vendedores/Compradores
- **Descrição:** Esta etapa consiste no registro dos vendedores e compradores da empresa no sistema, permitindo o controle e a análise das operações realizadas por cada um.

#### 2.2.2.9 Níveis de Oportunidades
- **Descrição:** Nessa etapa, são configurados os níveis de oportunidades que serão utilizados no processo de funil de vendas ou compras. Isso permite um controle mais granular das etapas de negociação com clientes ou fornecedores.

#### 2.2.2.10 Conclusão

A correta configuração das parametrizações iniciais no SAP Business One é um passo crítico que afeta diretamente a eficácia e a precisão dos processos empresariais em toda a organização. Seguir este guia de configuração não apenas facilita a implementação do sistema, mas também assegura que a empresa esteja preparada para responder de forma ágil e precisa às demandas do mercado e aos requisitos regulatórios. Esta documentação deve servir como uma referência central para garantir que todas as configurações necessárias sejam realizadas de forma abrangente e correta.

### 3.4.3 Regras de Negocío

Este documento é uma apresentação detalhada das principais regras de negócio desenvolvidas especificamente para fortalecer e aprimorar a gestão contábil dentro da organização. Abordamos estratégias meticulosamente projetadas para aperfeiçoar não apenas a geração, mas também a análise e o monitoramento de relatórios contábeis essenciais. Essas regras são fundamentais para garantir uma administração financeira eficiente e transparente, proporcionando uma base sólida para decisões estratégicas bem-informadas e conformidade regulatória rigorosa.

#### 3.4.3.1 Principais Relatórios Contábeis
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725232498/Screenshot_2024-09-01_at_19.51.34_hkrgch.png) 
**Descrição:**  
Configuração dos parâmetros necessários para a geração de relatórios contábeis críticos, como DRE, Balanço, Balancete e Razão, facilitando a análise financeira e a conformidade regulatória.

#### 3.4.3.2 Controles Contábeis
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725232499/Screenshot_2024-09-01_at_19.50.47_bgj9e9.png) 
**Descrição:**  
Monitoramento e controle de desvios orçamentários para identificar e corrigir variações significativas, garantindo que as operações permaneçam dentro dos limites orçamentários estabelecidos.

#### 3.4.3.3 Centro de Custos
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725232498/Screenshot_2024-09-01_at_19.50.17_clx4wv.png) 
**Descrição:**  
Adequada atribuição e monitoramento de despesas e receitas aos centros de custos apropriados, proporcionando uma visão clara sobre a utilização dos recursos financeiros.

#### 3.4.3.4 Orçamento
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725232496/Screenshot_2024-09-01_at_19.49.33_bvcmnx.png) 
**Descrição:**  
Estabelecimento de um orçamento anual detalhado, envolvendo todas as unidades de negócio para alinhar os gastos às estratégias e objetivos da empresa.

#### 3.4.3.5 Conclusão 
A implementação destas regras de negócio é essencial para manter a integridade financeira e promover uma gestão eficiente dos recursos. Com processos claros e bem definidos, a organização pode melhorar sua capacidade de planejamento e execução financeira, além de garantir a conformidade com as normativas vigentes. A seguir, serão detalhadas as DMNs (Decisões de Modelagem de Negócios) que suportam cada uma dessas regras.

### 3.4.4 DMN's

### 3.4.4.1 Principais Relatórios Contábeis
#### 3.4.4.1.1 Diagrama de Decisões
![Imagem](https://res.cloudinary.com/dccieesr9/image/upload/v1725236773/diagramadrd_as9pby.jpg)

**Descrição:**
O diagrama acima representa a interdependência entre os principais relatórios contábeis. Ele ilustra a criação e auditoria desses relatórios.

#### 3.4.4.1.2 Configuração de Parâmetros de Relatórios
![Imagem](https://res.cloudinary.com/dccieesr9/image/upload/v1725236692/decis%C3%A3o1_xsm0yl.jpg)

**Descrição:**
Esta decisão trata da configuração dos parâmetros de relatórios financeiros. O cliente deve ser orientado caso as configurações dos relatórios DRE, Balanço, Balancete e Razão estejam corretas, garantindo que os relatórios sejam gerados adequadamente. Se as configurações não estiverem corretas, é necessário orientar o cliente para ajustar os parâmetros e assegurar a conformidade dos relatórios.

#### 3.4.4.1.3 Treinamento para Geração de Relatórios
![Imagem](https://res.cloudinary.com/dccieesr9/image/upload/v1725236773/decis%C3%A3o2_dsiktw.jpg)

**Descrição:**
Esta decisão trata do treinamento necessário para a geração de relatórios. Usuários responsáveis pela contabilidade que já estão treinados não precisam de sessões adicionais. No entanto, se o usuário não tiver treinamento prévio, é necessário oferecer sessões de treinamento e documentação detalhada para assegurar que os relatórios sejam gerados corretamente.

#### 3.4.4.1.4 Suporte Para a Personalização de Relatórios
![Imagem](https://res.cloudinary.com/dccieesr9/image/upload/v1725236773/decis%C3%A3o3_ld7odz.jpg)

**Descrição:**
Esta decisão trata do suporte para a personalização de relatórios. Quando as solicitações de customização de relatórios estão ativas, é necessário fornecer suporte técnico para garantir a personalização e a geração adequada dos relatórios. Se as solicitações de customização não estiverem ativas, não é necessário fornecer suporte técnico para essa atividade.

### 3.4.4.2 Controle Contábeis

#### 3.4.4.2.1 Diagrama de Decisões
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725230417/Screenshot_2024-09-01_at_19.37.38_thnsc4.png)

**Descrição:**
O diagrama acima representa a interdependência entre as decisões de verificação, auditoria e revisão dentro do controle contábil. Ele ilustra como as transações contábeis são processadas e gerenciadas para garantir que todos os procedimentos contábeis sejam seguidos de maneira correta e eficiente.

#### 3.4.4.2.2 **Verificação de Determinações Contábeis**
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725230400/Screenshot_2024-09-01_at_19.39.54_znhz13.png)

**Descrição:**  
Esta decisão trata da verificação da validade das transações contábeis. Uma transação é considerada válida se as configurações de determinação de contas contábeis estão corretas, permitindo que prossiga sem atrasos. Se inválida, é necessário corrigir a configuração das contas para garantir a conformidade e precisão contábil.

#### 3.4.4.2.3 **Auditoria de Transações Contábeis**
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725230418/Screenshot_2024-09-01_at_19.38.24_srcdgl.png)

**Descrição:**  
Baseado no risco associado às transações contábeis, esta decisão determina a necessidade de uma auditoria. Transações com alto risco exigem uma auditoria imediata para mitigar possíveis problemas financeiros ou legais. Transações de baixo risco são programadas para auditorias trimestrais, otimizando recursos sem comprometer a segurança.

#### 3.4.4.2.4 **Revisão de Contas de Razão**
![Imagem](https://res.cloudinary.com/di57ql5yx/image/upload/v1725230418/Screenshot_2024-09-01_at_19.38.40_e1ujow.png)

**Descrição:**  
Esta decisão foca na revisão das contas de razão com base no cenário fiscal atual. Contas que estão em um cenário fiscal válido prosseguem sem intervenções, enquanto cenários fiscais inválidos requerem uma revisão das regras fiscais e ajustes nas contas para alinhar com as normas vigentes.

### 3.4.4.3 Centro de Custos

#### 3.4.4.3.1 Diagrama de Decisões
![Imagem](https://res.cloudinary.com/dp4liildh/image/upload/v1725240331/qnhdxmb8kkpfeftkjv4c.png)

**Imagem Descrição Geral:** O diagrama abaixo representa a interdependência entre as principais decisões de monitoramento de despesas, rateio de custos e atribuição de centros de custos. Ele ilustra como essas decisões são conectadas e impactam a gestão financeira dentro da organização.

#### 3.4.4.3.2 Atribuição de Centros de Custos
![Imagem](https://res.cloudinary.com/dp4liildh/image/upload/v1725240331/mljxn3avvy62lw2zcaov.png)

**Descrição:** Esta decisão trata da atribuição de centros de custos com base nas transações operacionais. Se a transação for uma receita, o sistema atribui o centro de receita correspondente. Para despesas, a atribuição ocorre de acordo com regras específicas do centro de custo de despesas.

#### 3.4.4.3.3 Rateio de Custos
![Imagem](https://res.cloudinary.com/dp4liildh/image/upload/v1725240331/upcsfxi5olb7b7obv6pg.png)

**Descrição:** Esta decisão estabelece os critérios para o rateio de custos, diferenciando entre custos indiretos e compartilhados. Dependendo do tipo de custo, o sistema aplica o critério de rateio apropriado, seja por departamento ou por projeto.

#### 3.4.4.3.4 Monitoramento de Despesas
![Imagem](https://res.cloudinary.com/dp4liildh/image/upload/v1725240331/bhthnrzvmm6hvwekupn8.png)

**Descrição:** Esta decisão trata do monitoramento das despesas com base nos relatórios mensais. O sistema aprova o relatório se ele estiver dentro do orçamento. Caso contrário, é gerado um alerta de excesso para indicar que as despesas ultrapassaram os limites estabelecidos.

### 3.4.4.4 Orçamento

#### 3.4.4.4.1 Diagrama de Orçamento
![Imagem](https://res.cloudinary.com/djzw4o0tp/image/upload/v1725243070/z1dsxaxk4fa4aktuotfm.png)

**Descrição:** Este diagrama DMN ilustra o fluxo sistemático e a interdependência das decisões cruciais no processo de gestão orçamentária. Ele detalha como o planejamento orçamentário é iniciado, monitorado e ajustado com base em desvios significativos, assegurando que o orçamento da organização seja mantido dentro dos parâmetros estabelecidos e que as práticas contábeis sejam rigorosamente seguidas para a sustentabilidade financeira. 

#### 3.4.4.4.2 Definição de Orçamento
![Imagem](https://res.cloudinary.com/djzw4o0tp/image/upload/v1725243083/oocvjfmcqvbrffaga5cz.png)

**Descrição:** Baseada no início do ciclo anual de planejamento, esta decisão direciona o processo de criação de cenários de orçamento. Se o ciclo estiver ativo, os cenários são criados e submetidos para aprovação; se não, o processo de criação de cenários é interrompido. Esta abordagem assegura que o planejamento orçamentário ocorra somente dentro do período designado, otimizando a preparação para o novo ano fiscal.


#### 3.4.4.4.3 Monitoramento de Execução Orçamentária
![Imagem](https://res.cloudinary.com/djzw4o0tp/image/upload/v1725243110/n2j64iagwb1auokelxzp.png)

**Descrição:** Baseada na disponibilidade de relatórios mensais de desempenho, esta decisão determina a necessidade de gerar relatórios detalhados. Relatórios disponíveis desencadeiam a geração de análises e ajustes orçamentários, enquanto a ausência de relatórios impede ações adicionais, otimizando o uso de recursos e focando em dados concretos para a tomada de decisões.

#### 3.4.4.4.4 Monitoramento de Despesas
![Imagem](https://res.cloudinary.com/djzw4o0tp/image/upload/v1725243119/ltco2omnbktud5g7oyv9.png)

**Descrição:** Esta decisão automatiza a resposta aos desvios orçamentários, baseando-se no seu impacto percentual no orçamento aprovado. Desvios acima de 10% resultam em análises detalhadas e potencial aprovação de ajustes, enquanto desvios menores não exigem ações imediatas, permitindo uma gestão de recursos mais eficiente e focada.

#### 3.4.5 Conclusão Geral 
A implementação dessas decisões de modelagem de negócios assegura uma gestão contábil rigorosa e eficiente. Por meio desses processos detalhados, a organização mantém um alto padrão de precisão e conformidade, essencial para a saúde financeira e a sustentabilidade a longo prazo.

## <a id="c3.5"></a>3.5 Limpeza dos Dados

## 3.5.1 Introdução

Essa seção tem como objetivo detalhar as alterações realizadas em cinco planilhas que passaram por processo de limpeza e padronização para serem implementadas como dados mestres na plataforma SAP Business One. O objetivo deste processo é garantir a integridade e consistência dos dados. A ferramenta Data Transfer Workbench (DTW) facilita a migração e a operação eficiente com SAP Business One. A limpeza de dados é uma etapa importante para evitar erros de importação e garantir que seu sistema esteja operando de acordo com os padrões exigidos por sua organização.

Durante o processo de limpeza, foi necessário cadastrar diversos bancos no SAP Business One para garantir que as operações financeiras pudessem ser gerenciadas corretamente. Os bancos cadastrados foram:

- Banco Bradesco
- Banco BS2
- Banco BTG Pactual
- Banco C6
- Banco Cooperativo do Brasil - BANCOOB
- Banco Cooperativo Sicredi
- Cooperativa Central de Crédito - AILOS
- Cora Sociedade de Crédito Direto
- Itaú Unibanco
- Mercado Pago
- Pagseguro

### 3.5.2 Planilhas Limpeza e Ajustes

#### 3.5.2.1 OCRB (Dados Bancários)
- Remover colunas desnecessárias: Os campos irrelevantes para o SAP Business One são removidos e apenas as informações necessárias são importadas.
- Ajustes nas informações bancárias: Os campos “BankCode”, “Branch” e “AccountName” são padronizados para se adequarem ao formato exigido pelo SAP Business One. Além disso, os bancos acima mencionados estão registrados na plataforma para garantir transações tranquilas. 

#### 3.5.2.2 CRD7 (Dados Fiscais e Endereços)
- Colunas irrelevantes removidas: campos como "CNAECode",  pois não são necessários para implementação no SAP Business One.
- Padronização e Ajuste de Identificador Fiscal: O campo “TaxId” é revisado e padronizado para garantir que os dados atendam às exigências fiscais do sistema.

#### 3.5.2.3 CRD1 (Dados de Endereços)
- Padronização de endereços: as colunas "AddressName", "City", "ZipCode" foram revisadas e adaptadas para atender aos padrões do SAP Business One.
- Remover campos redundantes: Remova dados que não serão utilizados no sistema, simplificando planilhas e facilitando a importação.

#### 3.5.2.4 OCRD (Dados Cadastrais de Clientes e Fornecedores)
- As configurações dos campos de cadastro: “CardName”, “EmailAddress”, “SalesPersonCode” são padronizadas e adaptadas às necessidades do SAP Business One.
- Excluir campos não utilizados: exclua campos da planilha que não são necessários para operações no SAP Business One.


#### 3.5.2.5 Itens (Cadastro de Itens)
- Padronização de classificação de materiais: Campos como "InventoryItem", "ItemClass", "ItemName" foram revisados ​​e ajustados para garantir a classificação correta de materiais no SAP Business One.
- Ajustes no código tributário: "U_SKILL_CEST" e códigos similares foram modificados para garantir o cumprimento fiscal e facilitar a administração tributária no sistema.
- Simplificação da planilha: Retire campos que não serão utilizados na plataforma, garantindo um processo de importação mais eficiente.
  
### 3.5.3 Processo de upload de dados no DTW:
Importe dados limpos e padronizados para o SAP Business One usando a ferramenta Data Transfer Workbench (DTW). O DTW é uma ferramenta poderosa para migração de dados em lote para SAP Business One, permitindo carregar grandes quantidades de informações com eficiência e precisão.

#### 3.5.3.1 **Preparação dos Arquivos CSV**:
 - Exportar planilhas limpas e ajustadas em formato CSV conforme layout exigido pelo SAP Business One.
- Verifique a estrutura do arquivo CSV para garantir que os dados estejam formatados corretamente e prontos para importação.

#### 3.5.3.2 **Configuração do DTW**:
   - Abra o Data Transfer Workbench.

<div align="center">
<sub>Figura X - Print SAP DTW 1</sub>
<img src="../assets/SAPprint6.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

   - Selecione a opção de "Add New Data" e "Master Data" para iniciar o processo de importação dos dados.

<div align="center">
<sub>Figura X - Print SAP DTW 2</sub>
<img src="../assets/SAPprint4.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

<div align="center">
<sub>Figura X - Print SAP DTW 3</sub>
<img src="../assets/SAPprint5.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

   - Escolha o tipo de masterdata que será importado (por exemplo, Contas Bancárias, Clientes, Itens, etc.).

   <div align="center">
<sub>Figura X - Print SAP DTW 4</sub>
<img src="../assets/SAPprint3.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

#### 3.5.3.3 **Mapeamento dos Dados**:
   - Importe os arquivos CSV no DTW.
   - Mapeie as colunas do CSV com os campos correspondentes no SAP Business One.
   - Revise o mapeamento para garantir que todos os dados serão importados corretamente.

<div align="center">
<sub>Figura X - Print SAP DTW 5</sub>
<img src="../assets/SAPprint2.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

#### 3.5.3.4 **Simulação da Importação**:
   - Execute a simulação do processo de importação.
   - Monitore o progresso da importação para identificar e resolver quaisquer erros ou inconsistências que possam surgir.
   - Revise os logs de importação para confirmar que todos os registros foram carregados corretamente.

<div align="center">
<sub>Figura X - Print SAP DTW 6</sub>
<img src="../assets/SAPprint1.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

<div align="center">
<sub>Figura X - Print SAP DTW 7</sub>
<img src="../assets/SAPprint8.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

<div align="center">
<sub>Figura X - Print SAP DTW 8</sub>
<img src="../assets/SAPprint7.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

#### 3.5.3.5 **Execute a importação**:
   - Após a conclusão da simulação, execute a importação dos dados

<div align="center">
<sub>Figura X - Print SAP DTW 9</sub>
<img src="../assets/SAPprint10.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

<div align="center">
<sub>Figura X - Print SAP DTW 10</sub>
<img src="../assets/SAPprint9.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

<div align="center">
<sub>Figura X - Print SAP DTW 11</sub>
<img src="../assets/SAPprint11.jpg" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

<div align="center">
<sub>Figura X - Print SAP DTW 12</sub>
<img src="../assets/SAPprint7.png" width="100%" >
<sup>Fonte: Material produzido pelos autores</sup>
</div>

#### 3.5.4 Conclusão

Para garantir que os dados sejam importados para o SAP Business One de um jeito eficiente e livre de erros, é importante  limpar e padronizar planilhas e cadastrar os bancos necessários. Utilizar  o Data Transfer Workbench (DTW) como  ferramenta de migração para uma migração tranquila e segura. A transferência de dados garante que o banco de dados do SAP Business One esteja completo e consistente. Cumprir os requisitos do sistema é fundamental para o bom funcionamento das operações. O registro dessas alterações garante a rastreabilidade e a integridade dos processos executados.


# <a id="c4"></a>4. Testes e Validação

## <a id="c4.1"></a>4.1 Testes Unitários

&emsp;*[Conteúdo adicionado nas próximas sprints.]*

## <a id="c4.2"></a>4.2 Testes Integrados

&emsp;*[Conteúdo adicionado nas próximas sprints.]*

## <a id="c4.3"></a>4.3 Estratégia de Cut Over

&emsp;*[Conteúdo adicionado nas próximas sprints.]*

## <a id="c4.4"></a>4.4 Relatórios

&emsp;*[Conteúdo adicionado nas próximas sprints.]*

# <a id="c5"></a>5. Treinamento e Suporte

## <a id="c5.1"></a>5.1 Treinamento de Usuários

&emsp;*[Conteúdo adicionado nas próximas sprints.]*

## <a id="c5.2"></a>5.2 Suporte Pós-Implantação

&emsp;*[Conteúdo adicionado nas próximas sprints.]*

## <a id="c5.3"></a>5.3 Suporte parametrização

&emsp;*[Conteúdo adicionado nas próximas sprints.]*

# <a id="c6"></a>6. Referências

Referências Bibliográficas Pesquisa Desk
MEDIUM. Desk research: o que é e como efetuar uma pesquisa secundária. Disponível em: https://medium.com/aela/desk-research-o-que-é-e-como-efetuar-uma-pesquisa-secundária-784ee064c10b. Acesso em: 13 ago. 2024.

MEDIUM. Double Diamond: o que aprendi sobre cada etapa desse processo de design. Disponível em: https://medium.com/ladies-that-ux-br/double-diamond-o-que-aprendi-sobre-cada-etapa-desse-processo-de-design-b8f1054ae992. Acesso em: 13 ago. 2024.

OMIE. Conheça os melhores sistemas ERP e saiba como escolher. Disponível em: https://blog.omie.com.br/conheca-os-melhores-sistemas-erp-e-saiba-como-escolher/. Acesso em: 13 ago. 2024.

ADOÇÃO, SELEÇÃO E IMPLANTAÇÃO DE UM ERP LIVRE. Disponível em: https://www.scielo.br/j/prod/a/sCmkgcJCpM97PxpVCcmd3fj/. Acesso em: 13 ago. 2024.

EXAME. Brasil é mais importante para a SAP Business One. Exame. Disponível em: https://exame.com/pme/brasil-mais-importante-sap-business-one/. Acesso em: 13 ago. 2024.

CAPACIDADES E ATORES NA GESTÃO DE SISTEMAS ERP: UM ESTUDO EXPLORATÓRIO ENTRE USUÁRIOS CORPORATIVOS DO ERP DA SAP. Disponível em: https://www.scielo.br/j/jistm/a/gJRtCmbCLQbd8RPYMJvqtPH/. Acesso em: 13 ago. 2024.

SOUZA DE JESUS, S.; GOMES, F.; SANTANA, A.; PIMENTA, I. A importância do ERP em empresas de logística, o caso de uma organização de médio porte. Revista Sapientiae, v. 8, n. 2, p. 253-267, 2023.

INTELI. Inteli registra patente desenvolvida por alunos que reduz tempo de implementação do SAP Business One. Disponível em: https://www.inteli.edu.br/inteli-registra-patente-desenvolvida-por-alunos-que-reduz-tempo-de-implementacao-do-sap-business-one/. Acesso em: 13 ago. 2024.

Referências Bibliográficas Pesquisa Exploratória
MINDMINERS. O que é pesquisa exploratória? Quais seus principais usos? MindMiners Blog, 07 ago. 2023. Disponível em: https://mindminers.com/blog/o-que-e-pesquisa-exploratoria/. Acesso em: 16 ago. 2024.

Referências Bibliográficas Canvas Proposta de Valor
TERA BLOG. Canvas de proposta de valor: para que serve e como preencher. Disponível em:  https://blog.somostera.com/product-management/canvas-de-proposta-de-valor. Acesso em: 14 ago. 2024.

Referências Bibliográficas Personas
MINDMINERS. O que é persona? Definindo o consumidor ideal da sua marca. Disponível em:  https://mindminers.com/blog/o-que-e-persona/. Acesso em: 27 ago. 2024.

Referências Bibliográficas User Stories
Programmers. A importância de uma boa User Story. Disponível em:  https://www.programmers.com.br/blog/a-importancia-de-uma-boa-user-story/. Acesso em: 28 ago. 2024.











