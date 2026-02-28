Telecom X – Análise de Churn de Clientes

Descrição do Projeto

Este projeto analisa os fatores que influenciam a evasão de clientes (Churn) na Telecom X.
O objetivo é identificar perfis de clientes de maior risco e fornecer insights estratégicos que apoiem ações de retenção e otimização de receita.

Tecnologias Utilizadas

Python 3

Pandas – manipulação de dados

NumPy – cálculos numéricos

Matplotlib & Seaborn – visualização de dados

Google Colab – ambiente de execução

Estrutura do Projeto
TelecomX-Churn-Analysis/
│
├── TelecomX_Data.json       # Dados brutos
├── TelecomX_Churn.ipynb     # Notebook completo com análise
├── README.md                # Este arquivo
└── imagens/                 # Gráficos exportados (opcional)
Etapas do Projeto

Extração de Dados

Importação dos dados da API JSON da Telecom X

Limpeza e Tratamento (ETL)

Normalização do JSON

Conversão de tipos de dados

Remoção de registros nulos ou inconsistentes

Criação da coluna Contas_Diarias

Análise Exploratória de Dados (EDA)

Taxa geral de churn

Tempo médio de permanência por churn

Churn por tipo de contrato e serviço de internet

Impacto do suporte técnico

Faturamento mensal x churn

Cruzamentos críticos para identificação de perfis de risco

Visualizações Estratégicas

Boxplots e barplots para destacar padrões de churn

Heatmaps para análise segmentada

Insights e Recomendações

Segmentos de maior risco identificados

Estratégias sugeridas para reduzir evasão

Principais Insights

Clientes que cancelam têm menor tempo médio de contrato (~18 meses)

Contrato mensal apresenta alta taxa de churn (42,7%)

Fibra óptica possui churn elevado (41,9%), especialmente em contratos mensais

Ausência de suporte técnico aumenta churn (~41,6%)

Clientes com contrato mensal e sem suporte técnico possuem churn próximo de 50%

Recomendações Estratégicas

Incentivar migração de contratos mensais para anuais ou bienais

Criar programa de retenção para clientes nos primeiros 6–12 meses

Oferecer suporte técnico preventivo para clientes de fibra óptica

Revisar comunicação e percepção de valor do serviço de fibra óptica

Monitorar continuamente clientes de alto risco

Resultado Esperado

A análise fornece um perfil detalhado de risco de churn, permitindo à Telecom X tomar decisões estratégicas para aumentar a retenção, otimizar faturamento e planejar ações preventivas direcionadas.
