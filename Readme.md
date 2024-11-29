# Pipeline de dados - Engenheiro de dados  [Linkedin](www.linkedin.com/in/janatã-aruanda)


Este pipeline foi desenvolvido com o objetivo de praticar e aprimorar conhecimentos em engenharia de dados, Databricks, Azure e arquitetura de dados. Este projeto serve como um laboratório interno para experimentação e aprendizado.

Para esta atividade, foi utilizada uma conta gratuita no Azure.

Atualmente, a arquitetura não contempla etapas relacionadas à configuração de rede. Este aspecto será aprimorado em versões futuras do projeto, garantindo maior robustez e segurança.


Icone: ![](/img/Microsoft_Azure_Logo.svg.png) ![](/img/databricks.png) ![](/img/Apache_Spark_logo.svg.png)


----


# Arquiteturas

## Azure

Nessa etapa foi realizado arquitetura dos principais serviços para implementação da pipeline de dados na azure.

- Grupo de recurso

- Azure DataLake Gen2

- Azure Databricks

![](/img/arq_azure.png)


## Databricks

A solução de processamento de dados Databricks usar Azure DataLake Gen2 como data lake, com isso deixar pipeline mais robusta e ultilizando tecnologia de ponta

![](/img/arq_databricks.png)

## Pipeline de dados - ETL

# Pipeline de Dados - Arquitetura de Dados em Camadas (Medalhão)

Nesta pipeline, utilizaremos a **arquitetura em camadas Medalhão**, composta por **Bronze**, **Silver** e **Gold**, para organizar e processar os dados de forma eficiente. A arquitetura será implementada utilizando **PySpark** e **SQL**, garantindo robustez, escalabilidade e alinhamento com as melhores práticas de engenharia de dados.

## Camadas da Arquitetura

- **Camada Bronze**:
  - Responsável por armazenar os dados brutos, conforme extraídos das fontes de dados.
  - Os dados são armazenados sem qualquer tipo de transformação ou validação, preservando sua integridade original.

- **Camada Silver**:
  - Encarregada do processamento inicial e limpeza dos dados da camada Bronze.
  - Realiza transformações básicas

- **Camada Gold**:
  - Representa a camada mais refinada e otimizada para consumo.



![](/img/arq_pipeline.png)