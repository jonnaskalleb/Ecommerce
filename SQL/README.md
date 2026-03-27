##Estrutura das Views:

O modelo foi organizado seguindo o conceito de Star Schema (Modelo Estrela):

Tabelas fato: pedidos e itens
Tabelas dimensão: clientes, produtos e vendedores

Essa estrutura melhora a performance das análises e facilita a criação de métricas no Power BI.

#Principais técnicas utilizadas:
- LEFT JOIN → integração entre tabelas
- ISNULL → tratamento de valores nulos
- CASE WHEN → criação de regras de negócio
- DATEDIFF → cálculo de tempo e atraso
- AS → padronização e clareza nos nomes das colunas
- WHERE → filtragem de dados inválidos


#Resultado>> As views criadas transformam dados brutos em uma base de dados para analisar, permitindo:

- Análise de receita e performance comercial
- Avaliação da eficiência logística
- Entendimento do comportamento do cliente
- Suporte à tomada de decisão baseada em dados
