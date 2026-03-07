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

A inadimplência representa um dos principais desafios enfrentados pelo setor financeiro. De acordo com dados do Banco Central do Brasil, o nível de inadimplência no sistema financeiro pode impactar diretamente a estabilidade do mercado de crédito, afetando tanto instituições financeiras quanto consumidores.

Quando níveis elevados de inadimplência ocorrem, os bancos tendem a aumentar as taxas de juros ou restringir a concessão de crédito, o que pode dificultar o acesso ao financiamento para consumidores e empresas. Dessa forma, melhorar a capacidade de prever o risco de inadimplência pode contribuir para decisões de crédito mais eficientes e equilibradas.

O uso de técnicas de aprendizado de máquina tem se mostrado uma abordagem promissora nesse contexto, pois permite identificar padrões complexos em grandes volumes de dados que seriam difíceis de detectar por métodos tradicionais de análise estatística. Esses modelos podem apoiar o processo de análise de crédito, reduzindo riscos financeiros e aumentando a eficiência na concessão de empréstimos.

O dataset escolhido para este projeto contém diversas informações relevantes sobre solicitantes de empréstimos, como características demográficas, financeiras e histórico de crédito. Esse conjunto de dados permite investigar como diferentes variáveis podem influenciar a probabilidade de inadimplência e avaliar a eficácia de diferentes algoritmos de aprendizado de máquina na solução desse problema.

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

* Loan Default Dataset, https://www.kaggle.com/datasets/yasserh/loan-default-dataset, kaggle.com
* 149 mil registros com 34 colunas no periodo de 2019 contemplando valores e caracteristicas do emprestimo como possibilidade de amortização, inadimplencia, dados do devedor como sexo, garantia, motivo do emprestimo, entre outros.<br>
| titulo | descrição | dados faltante |<br>
|----------|----------|----------|<br>
| ID | Identificador único da solicitação de empréstimo | 0 |<br>
| year | Ano em que o empréstimo foi solicitado | 0 |<br>
| loan_limit | Indica se o empréstimo segue normas padrão (cf) ou não (ncf) | 3344 |<br>
| Gender | Gênero do solicitante (masculino, feminino, conjunto, não informado). | 0 |<br>
| approv_in_adv | Indica se houve pré-aprovação do empréstimo (pre) ou não (nopre). | 908 |<br>
| loan_type | Categoria do tipo de empréstimo (type1, 2, 3). | 0 |<br>
| loan_purpose | Motivo do empréstimo (p1, p2, p3, p4). | 134 |<br>
| Credit_Worthiness | Solvência/idoneidade de crédito (l1, l2). | 0 |<br>
| open_credit | Indica se o solicitante possui contas de crédito abertas (opc) ou não (nopc). | 0 |<br>
| business_or_commercial | Finalidade do empréstimo: Comercial (ob/c) ou pessoal (nob/c). | 0 |<br>
| loan_amount | Valor solicitado no empréstimo. | 0 |<br>
| rate_of_interest | Taxa de juros aplicada ao empréstimo. | 36.4K |<br>
| Interest_rate_spread | Diferença entre a taxa de juros do empréstimo e uma taxa de referência (benchmark). | 36.6K |<br>
| Upfront_charges | Taxas iniciais cobradas para liberar o crédito. | 39.6k |<br>
| term | Prazo para pagamento do empréstimo (em meses). | 41 |<br>
| Neg_ammortization | Indica se permite amortização negativa (quando a dívida aumenta mesmo pagando). | 121 |<br>
| interest_only | Indica se há opção de pagar apenas juros (sem abater o principal). | 0 |<br>
| lump_sum_payment | Indica se exige pagamento de uma parcela única final (balão). | 0 |<br>
| property_value | Valor do imóvel usado como garantia. | 15.1 |<br>
| construction_type | Tipo de construção (sb: construído no local, mh: casa pré-fabricada). | 0 |<br>
| occupancy_type | Tipo de ocupação (residência principal, secundária ou investimento). | 0 |<br>
| Secured_by | Tipo de garantia real (ex: casa, terreno). | 0 |<br>
| total_units | Quantidade de unidades no imóvel financiado (1U, 2U, etc.). | 0 |<br>
| income | Renda anual do solicitante. | 9150 |<br>
| credit_type | Bureau de crédito consultado (CIB, CRIF, EXP, EQUI). | 0 |<br>
| Credit_Score | Pontuação de crédito do solicitante. | 0 |<br>
| co-applicant_credit_type | Bureau de crédito do co-requerente (se houver). | 0 |<br>
| age | Idade do solicitante. | 200 |<br>
| submission_of_application | Forma de submissão (via instituição ou não). | 0 |<br>
| LTV | Loan-to-Value: Relação entre o valor do empréstimo e o valor do imóvel. | 15.1k |<br>
| Region | Região geográfica do imóvel. | 0 |<br>
| Security_Type | Tipo de segurança/garantia (direta ou indireta). | 0 |<br>
| Status | Status do empréstimo Em inadimplência (1) ou adimplente (0). | 0 |<br>
| dtir1 | Debt-to-Income Ratio: Relação entre dívidas e renda mensal. | 24.1K |<br>
|----------|----------|----------|
# Canvas analítico

<img width="1086" height="714" alt="image" src="https://github.com/user-attachments/assets/9b1f375c-d4e9-43aa-9621-489581c5c642" />


> **Links Úteis**:
> - [Modelo do Canvas Analítico](https://github.com/ICEI-PUC-Minas-PMV-SI/PesquisaExperimentacao-Template/blob/main/help/Software-Analtics-Canvas-v1.0.pdf)

# Vídeo de apresentação da Etapa 01

Nesta etapa, o grupo deverá produzir um vídeo de 5 a 8 minutos apresentando o trabalho realizado, no qual cada integrante deve dizer seu nome e apresentar uma parte do conteúdo desenvolvido, garantindo que todos participem ativamente da gravação. A ausência de participação de qualquer membro resultará em penalização na nota final desta etapa. Recomenda-se que o grupo elabore previamente um roteiro para organizar a ordem das falas, distribuir o tempo de forma equilibrada e assegurar que todos os tópicos relevantes sejam apresentados de maneira clara e objetiva.

# Referências

Inclua todas as referências (livros, artigos, sites, etc) utilizados no desenvolvimento do trabalho utilizando o padrão ABNT.

> **Links Úteis**:
> - [Padrão ABNT PUC Minas](https://portal.pucminas.br/biblioteca/index_padrao.php?pagina=5886)
