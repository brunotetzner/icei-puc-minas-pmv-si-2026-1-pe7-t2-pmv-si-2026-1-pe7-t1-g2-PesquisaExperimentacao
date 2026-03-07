# Introdução

O acesso ao crédito é um dos principais mecanismos que impulsionam o desenvolvimento econômico, permitindo que indivíduos e empresas realizem investimentos, adquiram bens e financiem atividades produtivas. Instituições financeiras, como bancos e fintechs, desempenham um papel fundamental nesse processo ao oferecer empréstimos e outros produtos de crédito para diferentes perfis de clientes.

Entretanto, a concessão de crédito envolve riscos, sendo a inadimplência um dos principais desafios enfrentados pelas instituições financeiras. A inadimplência ocorre quando um cliente não consegue cumprir suas obrigações de pagamento dentro do prazo estabelecido, gerando prejuízos financeiros e aumentando a incerteza no sistema de crédito.

## Problema

A concessão de crédito exige que instituições financeiras avaliem cuidadosamente o risco associado a cada cliente. Decidir se um empréstimo deve ou não ser concedido envolve analisar diversos fatores, como renda, histórico de crédito, valor solicitado e outras características financeiras do solicitante.

Quando o risco de inadimplência não é identificado corretamente, podem ocorrer dois tipos de problema. No primeiro caso, a instituição concede crédito a clientes com alto risco de inadimplência, o que pode gerar perdas financeiras. No segundo caso, clientes com bom perfil financeiro podem ter seu crédito negado, reduzindo o acesso ao sistema financeiro.

Neste projeto, o problema investigado consiste em identificar se é possível utilizar técnicas de aprendizado de máquina para prever a probabilidade de inadimplência em empréstimos com base em informações financeiras e demográficas dos clientes presentes em um dataset público. O estudo será realizado em um contexto experimental e acadêmico, utilizando ferramentas de análise de dados e modelagem de Machine Learning.

## Questão de pesquisa

Como técnicas de aprendizado de máquina podem ser utilizadas para prever a inadimplência em empréstimos financeiros a partir de dados demográficos e financeiros dos clientes?

Essa pergunta direciona a investigação realizada no projeto, buscando compreender se modelos de Machine Learning conseguem identificar padrões relevantes nos dados que permitam classificar clientes com maior risco de inadimplência.

Ao final da pesquisa, espera-se que seja possível responder a essa questão por meio da análise do desempenho dos modelos desenvolvidos e das evidências obtidas durante os experimentos.

## Objetivos preliminares

### Objetivo Geral

Experimentar e avaliar modelos de aprendizado de máquina capazes de prever a inadimplência em empréstimos financeiros utilizando dados históricos de clientes.

### Objetivos Específicos

#### Objetivo específico 1:
Realizar a análise exploratória e o pré-processamento do conjunto de dados, identificando padrões, inconsistências e possíveis fatores associados ao risco de inadimplência.

#### Objetivo específico 2:
Treinar e comparar diferentes modelos de aprendizado de máquina para classificação do risco de inadimplência, avaliando seu desempenho por meio de métricas apropriadas.

#### Objetivo específico 3:
Analisar quais variáveis do dataset possuem maior influência na previsão de inadimplência, contribuindo para uma melhor compreensão do problema de risco de crédito.

## Justificativa

Nesta seção, apresente a importância e a motivação para trabalhar com o conjunto de dados escolhido. Explique por que esse dataset é relevante e como ele se conecta ao problema identificado anteriormente.

Indique:
* Razões para a escolha dos objetivos específicos – Justifique por que decidiu aprofundar sua investigação nessas metas, relacionando-as ao potencial de solução ou melhoria para o problema.
* Relevância do estudo do problema – Mostre a importância de compreender e tratar a questão apresentada, tanto no contexto acadêmico quanto no profissional.
* Impacto social, econômico ou ambiental – Descreva como o problema afeta a sociedade ou um setor específico, buscando sempre quantificar o impacto por meio de dados reais.

**Importante:**
* Apresente números, estatísticas e informações concretas, citando as fontes (relatórios, artigos científicos, portais oficiais etc.).
* Mantenha a objetividade e a clareza, evitando argumentos genéricos.
* Construa um texto coeso que conecte o problema, os objetivos e a relevância do trabalho.

> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)

## Público-Alvo

Nesta seção, descreva quem poderá se beneficiar com a sua investigação, apresentando os diferentes perfis de pessoas ou grupos impactados.

O objetivo aqui não é definir clientes específicos ou papéis exatos dentro da aplicação, mas sim compreender o perfil dos usuários e partes interessadas. Para isso, considere:
* Conhecimentos prévios relacionados ao domínio do problema e ao uso de tecnologia;
* Nível de familiaridade com recursos digitais e possíveis barreiras de uso;
* Contexto profissional e hierárquico, quando aplicável (ex.: nível de decisão, responsabilidades, área de atuação);
* Necessidades e expectativas que podem ser atendidas pelo projeto.

**Dica:** Seja objetivo e baseie suas descrições em informações reais ou plausíveis para o contexto escolhido. Isso ajudará a manter o foco no desenvolvimento de soluções relevantes e aplicáveis.

> **Links Úteis**:
> - [Público-alvo](https://blog.hotmart.com/pt-br/publico-alvo/)
> - [Como definir o público alvo](https://exame.com/pme/5-dicas-essenciais-para-definir-o-publico-alvo-do-seu-negocio/)
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)

## Estado da arte

Nesta seção, descreva abordagens da literatura que tratam problemas semelhantes ao seu. Seu objetivo é documentar métodos, dados, métricas e resultados.

### O que levantar (mínimo 5 trabalhos)
Para **cada estudo encontrado** aderente à temática do grupo, registre de forma objetiva:
* Problema e contexto: que problema o trabalho buscou resolver e em qual domínio/cenário foi aplicado.
* Dados (dataset): origem, tamanho, período, variáveis/atributos, pré-processamentos relevantes (faltantes, balanceamento, normalização).
* Abordagem/algoritmos: algoritmos utilizados e parâmetros principais (quando informados).
* Métricas de avaliação: quais e por quê (ex.: Acurácia, F1, AUC, RMSE, MAE, etc.).
* Resultados: principais números, comparações internas, limitações citadas e conclusões.

* Texto-síntese crítico (2–4 parágrafos) respondendo:
- O que os estudos concordam? Onde divergem?
- Quais lacunas permanecem (dados, métricas, cenários, limitações técnicas/éticas)?
- Como seu projeto se alinha aos estudos identificados?

**Dica:** Prefira artigos dos últimos 5 anos ou referências clássicas indispensáveis.

### Ferramentas inteligentes permitidas
Você pode utilizar: Perplexity, SciSpace, Elicit, Research Rabbit, Litmaps.
Use-as para descoberta, organização e triagem de literatura. 

**Atenção:** 
* Sempre acesse a fonte original (PDF/artigo) antes de citar; verifique números e conclusões.
* Registre DOI/URL oficial e dados bibliográficos completos.
* Evite “alucinações” das ferramentas: desconfie de referências sem DOI ou que você não consiga localizar oficialmente.
* Use as ferramentas inteligentes para mapear redes de citação (Research Rabbit), mapas de tópicos (Litmaps), filtrar por período e gerar resumos iniciais (Perplexity/SciSpace/Elicit).
* Leia os trabalhos mais promissores e descarte estudos fora de escopo.

> **Links Úteis**:
> - [Google Scholar](https://scholar.google.com/)
> - [IEEE Xplore](https://ieeexplore.ieee.org/Xplore/home.jsp)
> - [Science Direct](https://www.sciencedirect.com/)
> - [ACM Digital Library](https://dl.acm.org/)

# Descrição do _dataset_ selecionado

Nesta seção, apresente uma visão clara e objetiva do dataset selecionado, incluindo:
* Identificação e origem – Nome, link de acesso, fonte (instituição, repositório, API etc.) e licença de uso.
* Visão geral – Total de registros e atributos, período coberto e breve contextualização.
* Atributos – Tabela com nome, descrição, tipo, unidade de medida (se aplicável) e exemplos de valores.
* Qualidade dos dados – Presença de valores faltantes, inconsistências, duplicatas ou outliers.

**Dica:** Seja objetivo, mas inclua detalhes suficientes para que outra pessoa possa entender e reutilizar o conjunto de dados sem buscar informações extras.

# Canvas analítico

Nesta seção, você deverá estruturar e preencher o seu Canvas Analítico, que tem como objetivo registrar a organização das ideias e apresentar o modelo de negócio do projeto.

O Canvas deve ser preenchido integralmente, mesmo que algumas informações ainda não estejam totalmente definidas. Nessa etapa inicial, é aceitável trabalhar com hipóteses ou estimativas, desde que sejam coerentes com o problema e o contexto definidos.

**Dica:** O Canvas Analítico serve como guia visual para alinhar expectativas e direcionar o desenvolvimento. Ele poderá (e deverá) ser revisitado e atualizado ao longo do projeto.

> **Links Úteis**:
> - [Modelo do Canvas Analítico](https://github.com/ICEI-PUC-Minas-PMV-SI/PesquisaExperimentacao-Template/blob/main/help/Software-Analtics-Canvas-v1.0.pdf)

# Vídeo de apresentação da Etapa 01

Nesta etapa, o grupo deverá produzir um vídeo de 5 a 8 minutos apresentando o trabalho realizado, no qual cada integrante deve dizer seu nome e apresentar uma parte do conteúdo desenvolvido, garantindo que todos participem ativamente da gravação. A ausência de participação de qualquer membro resultará em penalização na nota final desta etapa. Recomenda-se que o grupo elabore previamente um roteiro para organizar a ordem das falas, distribuir o tempo de forma equilibrada e assegurar que todos os tópicos relevantes sejam apresentados de maneira clara e objetiva.

# Referências

Inclua todas as referências (livros, artigos, sites, etc) utilizados no desenvolvimento do trabalho utilizando o padrão ABNT.

> **Links Úteis**:
> - [Padrão ABNT PUC Minas](https://portal.pucminas.br/biblioteca/index_padrao.php?pagina=5886)
