# Clusterizacao-Clientes

> https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering

Este projeto tem como objetivo segmentar clientes com base em comportamento de compra e características demográficas, utilizando técnicas de clusterização não supervisionada (K-Means). O foco foi identificar perfis distintos de clientes e gerar insights estratégicos para ações de marketing e retenção.

### Objetivos:
- Identificar segmentos de clientes com comportamentos semelhantes  
- Entender padrões de consumo e engajamento  
- Apoiar estratégias de marketing direcionado  
- Gerar insights acionáveis para retenção e monetização

## Resultado:
``k = 4`` --> escolha orientada a estratégica de negócios

| Cluster | Perfil |
|--------|-------|
| VIP Ativo | Alto valor e alta frequência |
| Baixo Valor Ativo | Engajados, porém com baixo gasto |
| Baixo Valor Inativo | Clientes com baixa atividade recente |
| VIP Inativo | Alto valor histórico, mas com risco de churn |

<img width="866" height="548" alt="1126ab4d-afc5-4145-85df-7486d7502ce0" src="https://github.com/user-attachments/assets/d3a8d233-225f-4948-b740-ca6f2121b3b7" />
___________________________________

### Dicionário de Dados:
| Coluna               | Tipo de Dado | Descrição |
|---------------------|-------------|----------|
| ID                  | Numérico    | Identificador único do cliente |
| Year_Birth          | Numérico    | Ano de nascimento do cliente |
| Education           | Categórico  | Nível de escolaridade |
| Marital_Status      | Categórico  | Estado civil |
| Income              | Numérico    | Renda anual do cliente |
| Kidhome             | Numérico    | Número de crianças no domicílio |
| Teenhome            | Numérico    | Número de adolescentes no domicílio |
| Dt_Customer         | Data        | Data de cadastro do cliente |
| Recency             | Numérico    | Dias desde a última compra |
| MntWines            | Numérico    | Valor gasto em vinhos |
| MntFruits           | Numérico    | Valor gasto em frutas |
| MntMeatProducts     | Numérico    | Valor gasto em carnes |
| MntFishProducts     | Numérico    | Valor gasto em peixes |
| MntSweetProducts    | Numérico    | Valor gasto em doces |
| MntGoldProds        | Numérico    | Valor gasto em produtos premium |
| NumDealsPurchases   | Numérico    | Número de compras com desconto |
| NumWebPurchases     | Numérico    | Número de compras online |
| NumCatalogPurchases | Numérico    | Número de compras via catálogo |
| NumStorePurchases   | Numérico    | Número de compras em loja física |
| NumWebVisitsMonth   | Numérico    | Número de visitas ao site por mês |
| AcceptedCmp1        | Binário     | Aceitou campanha 1 (1 = Sim, 0 = Não) |
| AcceptedCmp2        | Binário     | Aceitou campanha 2 (1 = Sim, 0 = Não) |
| AcceptedCmp3        | Binário     | Aceitou campanha 3 (1 = Sim, 0 = Não) |
| AcceptedCmp4        | Binário     | Aceitou campanha 4 (1 = Sim, 0 = Não) |
| AcceptedCmp5        | Binário     | Aceitou campanha 5 (1 = Sim, 0 = Não) |
| Complain            | Binário     | Cliente fez reclamação (1 = Sim, 0 = Não) |
| Z_CostContact       | Constante   | Custo fixo de contato com cliente |
| Z_Revenue           | Constante   | Receita fixa associada a campanhas |
| Response            | Binário     | Respondeu à campanha atual (1 = Sim, 0 = Não) |




