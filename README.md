## 📊 Dashboard de Gestão de Vendas

https://github.com/RyanSfernandes/Dasboard-vendas/blob/main/imagem_2026-02-24_120144299.png

Este projeto consiste em um dashboard interativo de gestão de vendas desenvolvido para acompanhar o desempenho comercial de uma empresa fictícia. O objetivo é fornecer uma visão clara e dinâmica sobre faturamento, formas de pagamento, análise de produtos e sazonalidade.

##🚀 Funcionalidades e Indicadores
O dashboard permite uma análise aprofundada através dos seguintes pontos:

Faturamento por Loja: Comparativo de desempenho entre Matriz e Filiais.

Faturamento por Forma de Pagamento: Representatividade de Cartão de Crédito vs. Transferência/PIX.

Análise por Produto: Tabela detalhada com faturamento e percentual de participação por item.

Faturamento por Período: Visão mensal do faturamento ao longo do ano, permitindo identificar sazonalidades.

Métricas Chave: Cálculo de faturamento total, comissões e ticket médio.

##🛠️ Processamento e Tratamento dos Dados (Power Query)
Antes da visualização, os dados brutos passaram por um processo de transformação e limpeza utilizando o Power Query (Editor do Power BI) para garantir a qualidade e consistência das informações:

Ajustes de Tabelas: Estruturação e padronização das tabelas de vendas, produtos e lojas para o modelo de dados.

Limpeza de Dados: Remoção de registros com dados nulos ou inconsistentes que poderiam comprometer as análises.

Padronização de Nomes: Correção e uniformização dos nomes de produtos, lojas e formas de pagamento para garantir a correta categorização.
##📐 Medidas e Cálculos (DAX)
Foram criadas medidas personalizadas em DAX (Data Analysis Expressions) para calcular os principais indicadores de negócio:

Faturamento Total: Soma do valor total das vendas.
Faturamento por Loja: Medida que permite segmentar o faturamento total por unidade.
Comissão: Cálculo da comissão sobre as vendas (exemplo: 5% do faturamento).
Ticket Médio: Valor médio gasto por venda.
##📈 Visualizações e Insights
O layout do dashboard foi pensado para facilitar a leitura rápida dos dados:

Gráfico de Barras: Comparativo de faturamento entre as lojas (Matriz, Filial 1, Filial 2).

Gráfico de Rosca/ Pizza: Proporção do uso de Cartão de Crédito vs. Transferência/PIX (61% vs 39%).

Tabela de Detalhamento: Listagem de produtos com faturamento e percentual, destacando os mais vendidos (ex: Bolsa com 33,48%).

Gráfico de Linhas/Área: Evolução do faturamento mensal, mostrando o comportamento das vendas ao longo do ano.

##🧰 Ferramentas Utilizadas
Power BI Desktop: Criação do dashboard, modelagem de dados e aplicação da lógica com DAX.

Power Query: Processo de ETL (Extração, Transformação e Carga) e limpeza dos dados.

Base de Dados: Conjunto de dados fictícios gerados para fins de estudo e portfólio.
