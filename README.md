Este projeto apresenta uma análise exploratória dos dados do `Censo Demográfico 2022`, realizado pelo Instituto Brasileiro de Geografia e Estatística (IBGE). O Censo é a principal fonte de dados sobre a vida da população brasileira, oferecendo um retrato detalhado de quem somos, como vivemos e como o país mudou na última década.

Para esta análise, utilizamos os `Agregados por Municípios`, que consolidam informações socioeconômicas e demográficas das 5.570 cidades brasileiras. O foco principal é explorar a relação entre infraestrutura básica, educação e perfis demográficos, utilizando ferramentas de ponta em análise de dados.

## Objetivos Técnicos
Seguindo os padrões de rigor da Certificação Google Advanced Data Analytics, este notebook percorre o ciclo completo de análise:

- **ETL (Extração, Transformação e Carga)**: Processamento de arquivos brutos (.csv), tratamento de codificações e manipulação de grandes tabelas.

- **Data Wrangling**: Cruzamento de datasets temáticos (Merge) e renomeação técnica de variáveis com base em dicionários oficiais.

- **Análise Exploratória (EDA)**: Identificação de padrões, correlações e tratamento de valores ausentes (null values).

- **Visualização de Dados**: Criação de gráficos claros e informativos para comunicar insights geográficos e sociais.

## Estrutura PACE
**Para estruturar esse projeto utilizaremos a ESTRUTURA PACE (Plan, Analyze, Construct, Execute)**

### 1. Planejar (Plan)
**Foco:** Definição do escopo do projeto e as perguntas específica que queremos responder ao longo do projeto.
- Evolução demográfica por região. (Qual região teve maior crescimento vegetativo?) (O que indica determinado crescimento em determinada região?)
- Acesso à educação por estado. (Como a taxa de alfabetização varia entre diferentes regiões e tamanhos de municípios?)
- Relação entre Renda per capita x IDH. (Qual a relação entre Renda per capita e IDH?)
- Comparação entre as diferentes regiões do Brasil. (O que difere região X de região Y?)
- Existe correlação entre a infraestrutura domiciliar (rede de água e esgoto) e a densidade demográfica local?
- Qual o perfil de idade e sexo predominante nas regiões que mais cresceram desde o último Censo?
> O trabalho aqui será transformar esses temas amplos em perguntas de pesquisa específicas e factíveis com os dados que temos.

### 2. Analisar (Analyze)
**Foco:** Coleta, preparação e análise dos dados (Análise Exploratória de Dados - EDA)
- Importação de dados
- Limpeza
- reorganização
> O objetivo é avaliar a qualidade dos dados e descobrir padrões interessantes para o propósito do projeto.

### 3. Construir (Construct)
**Foco:** Criação de algoritmos de Machine Learning e Estatística
- Testes de hipóteses
- Modelos de Regressão Linear
> Realização de testes de hipótese para verificar se diferenças demográficas entre duas regiões são estatisticamente significativas ou apenas obra do acaso
> Construção de modelos de regressão linear para investigar a relação entre Renda per capita e IDH

### 4. Executar (Execute)
**Foco:** Entrega e apresentação dos resultados obtidos (Data Storytelling e Dashboards)
- Contar a história através dos números
- Dataviz utilizando **Power BI**, **Tableau**
- Dataviz usando IA e visualização usando Excel
> Apoiar decisões de negócios baseados nos dados

**Em resumo:**
- **Plan (Planejar)** → Define escopo, metas e necessidades do negócio.
- **Analyze (Analisar)** → Coleta, limpeza e EDA (Análise Exploratória).
- **Construct (Construir)** → Modelagem de Machine Learning e inferência estatística.
- **Execute (Executar)** → Apresentação de resultados e recomendações aos stakeholders.

## Link do conjunto de dados
[Conjuntos de dados IBGE - Censo 2022](https://www.ibge.gov.br/estatisticas/sociais/saude/22827-censo-demografico-2022.html?=&t=downloads)

## Proposta de Projeto
[Proposta-de-Projeto_Analise-Demografica-e-Socioeconomica-Censo-IBGE-2022 .pdf](https://github.com/user-attachments/files/26226102/Proposta-de-Projeto_Analise-Demografica-e-Socioeconomica-Censo-IBGE-2022.pdf)

