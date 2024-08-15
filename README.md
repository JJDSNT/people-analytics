# People Analytics

Este é o meu primeiro projeto de People Analytics desenvolvido com o objetivo de criar um projeto end-to-end para aprendizagem e portfólio. O projeto visa demonstrar habilidades em análise de dados, modelagem preditiva, visualização de dados e storytelling com dados.

## Objetivo

O objetivo deste projeto é construir uma solução completa de People Analytics, abrangendo desde a coleta e análise de dados até a modelagem preditiva e a visualização final. Isso incluirá a criação de uma camada semântica para facilitar o entendimento e a utilização dos dados no contexto de People Analytics.

## Dataset

- [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Visualização

Utilizar o [Apache Superset](https://superset.apache.org/) como plataforma de visualização de dados com suporte a dashboard as code.

### Dashboard de Indicadores de RH

Possiveis indicadores:

### 1. Headcount (Contagem de Empregados)
- **Descrição**: Número total de funcionários na organização.
- **Fonte de Dados**: `EmployeeCount`

### 2. Rotatividade (Attrition)
- **Descrição**: Percentual de funcionários que deixaram a empresa.
- **Fonte de Dados**: `Attrition`

### 3. Satisfação com o Trabalho
- **Descrição**: Média de satisfação dos funcionários em relação ao trabalho, ambiente e relacionamentos.
- **Fontes de Dados**:
  - `JobSatisfaction`
  - `EnvironmentSatisfaction`
  - `RelationshipSatisfaction`

### 4. Anos de Empresa
- **Descrição**: Média de tempo que os funcionários permanecem na empresa, na função atual e com o gestor atual.
- **Fontes de Dados**:
  - `YearsAtCompany`
  - `YearsInCurrentRole`
  - `YearsWithCurrManager`
  - `YearsSinceLastPromotion`

### 5. Educação e Campo de Educação
- **Descrição**: Distribuição dos funcionários por nível e campo educacional.
- **Fontes de Dados**:
  - `Education`
  - `EducationField`

### 6. Treinamento
- **Descrição**: Número médio de treinamentos recebidos pelos funcionários no último ano.
- **Fonte de Dados**: `TrainingTimesLastYear`

### 7. Horas de Trabalho e Horas Extras
- **Descrição**: Monitoramento da carga de trabalho dos funcionários, incluindo horas padrão e horas extras.
- **Fontes de Dados**:
  - `StandardHours`
  - `OverTime`

### 8. Distribuição de Idade
- **Descrição**: Distribuição etária dos funcionários.
- **Fonte de Dados**: `Age`

### 9. Promoções
- **Descrição**: Frequência de promoções entre os funcionários.
- **Fonte de Dados**: `YearsSinceLastPromotion`


## Possivel Ferramentas a utilizar

- [Apache Airflow](https://airflow.apache.org/): Orquestração de dados.
- [dbt (Data Build Tool)](https://www.getdbt.com/): Transformação de dados e criação de camadas semânticas.
- [DuckDB](https://duckdb.org/): Motor de banco de dados embutido para análise de dados.
- [Cube.js](https://cube.dev/): Camada de API de dados e analytics.
- [synmetrix](https://github.com/synmetrix/synmetrix)
- [Apache Superset](https://superset.apache.org/)
- [Droughty](https://pypi.org/project/droughty/): Ferramenta para construção de camadas semânticas.
- [Scikit-learn](https://scikit-learn.org/stable/): Biblioteca para modelagem e aprendizado de máquina.


## Referências

- [How to display a .ipynb file on github?](https://stackoverflow.com/questions/62878732/how-to-display-a-ipynb-file-on-github)

- [Running S3 Object Storage Locally with MinIO](https://simonjcarr.medium.com/running-s3-object-storage-locally-with-minio-f50540ffc239)

- [End-to-End Basic Data Engineering Tutorial (Spark, Dremio, Superset)](https://dev.to/alexmercedcoder/end-to-end-basic-data-engineering-tutorial-spark-dremio-superset-2hgi)
- [[Data Pipeline – Part. 4] Criação de dashboard com Apache Superset](https://thedataengineer.com.br/2021/01/04/data-pipeline-part-4-criacao-de-dashboard-com-apache-superset/)

- [The dbt Semantic Layer, Data Orchestration, and the Modern Enterprise Data Stack](https://blog.rittmananalytics.com/the-dbt-semantic-layer-data-orchestration-and-the-modern-enterprise-data-stack-78d9d9ed5c18)
- [Building Up a Semantic Layer with dbt Metrics, Cube, and Droughty](https://odupuis.medium.com/building-up-a-semantic-layer-with-dbt-metrics-cube-and-droughty-2a61b01517a6)
- [Introducing dbt integration with Cube](https://cube.dev/blog/introducing-dbt-integration-with-cube)



