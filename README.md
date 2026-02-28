# Telecom X – Análise de Churn de Clientes

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12.2-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.1-red)

## Descrição do Projeto

Este projeto realiza uma análise detalhada da **evasão de clientes (Churn)** na Telecom X. O objetivo é identificar perfis de clientes de maior risco e fornecer insights estratégicos que possam ser utilizados para reduzir cancelamentos e aumentar a retenção.

A análise foi conduzida utilizando **Python**, com foco em **ETL, análise exploratória de dados (EDA)** e visualizações estratégicas.

## Tecnologias e Ferramentas

* **Python 3** – linguagem de programação
* **Pandas** – manipulação de dados
* **NumPy** – cálculos numéricos
* **Matplotlib & Seaborn** – visualização de dados
* **Google Colab** – ambiente de execução

## Estrutura do Repositório

```text
TelecomX-Churn-Analysis/
│
├── TelecomX_Data.json       # Dados brutos
├── TelecomX_Churn.ipynb     # Notebook completo com análise
├── README.md                # Este arquivo
└── imagens/                 # Gráficos exportados (opcional)
```

## Etapas do Projeto

1. **Extração de Dados**

   * Importação dos dados da API JSON da Telecom X.

2. **Limpeza e Tratamento (ETL)**

   * Normalização do JSON em formato tabular
   * Conversão de tipos de dados
   * Remoção de registros inconsistentes
   * Criação da coluna `Contas_Diarias` para análise diária do faturamento

3. **Análise Exploratória de Dados (EDA)**

   * Taxa geral de churn
   * Tempo médio de permanência por churn
   * Churn por tipo de contrato e serviço de internet
   * Impacto do suporte técnico
   * Faturamento mensal x churn
   * Cruzamentos críticos para identificação de perfis de risco

4. **Visualizações Estratégicas**

   * Gráficos de barras, boxplots e heatmaps destacando padrões de churn

5. **Insights e Recomendações**

   * Segmentos de maior risco identificados
   * Estratégias sugeridas para redução de evasão

## Principais Insights

* Clientes que cancelam possuem menor tempo médio de contrato (~18 meses)
* Contratos mensais apresentam alta taxa de churn (42,7%)
* Fibra óptica apresenta churn elevado (41,9%), especialmente em contratos mensais
* Ausência de suporte técnico aumenta churn (~41,6%)
* Clientes com contrato mensal e sem suporte técnico apresentam churn próximo de 50%

## Recomendações Estratégicas

1. Incentivar migração de contratos mensais para anuais ou bienais
2. Criar programa de retenção para clientes nos primeiros 6–12 meses
3. Oferecer suporte técnico preventivo para clientes de fibra óptica
4. Revisar comunicação e percepção de valor do serviço de fibra óptica
5. Monitorar continuamente clientes de alto risco

## Visualizações

As principais visualizações estão disponíveis no notebook, incluindo:

* Distribuição geral de churn
* Tempo de permanência por churn
* Churn por tipo de contrato
* Churn por tipo de internet
* Churn por suporte técnico
* Heatmap de proporção de contratos por tipo de internet

## Resultado Esperado

A análise fornece um perfil detalhado de risco de churn, permitindo à Telecom X tomar decisões estratégicas para aumentar a retenção de clientes e otimizar receita, priorizando ações nos segmentos mais críticos.
