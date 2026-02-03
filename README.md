# Ecommerce Shipping Performance Dashboard

### Projeto: Análise de Operações e Desempenho de E-commerce com Power BI

Este projeto apresenta uma análise completa de desempenho de um e-commerce brasileiro, utilizando o dataset público da Olist. O objetivo foi transformar dados transacionais brutos em insights de negócio claros, estruturando uma narrativa analítica que conecta vendas, crescimento, operação logística e experiência do cliente.

O dashboard foi desenvolvido no Power BI e organizado em três camadas analíticas complementares. As páginas do relatório em imagem estão disponíveis na pasta `figures`.

Na Visão Geral, o foco está na saúde do negócio. São apresentados indicadores como GMV, número de pedidos entregues, ticket médio, taxa de atraso, tempo médio de entrega e avaliação média dos clientes, além do mix de pagamento e das categorias com maior contribuição de receita. Um dos principais insights dessa página é a relação direta entre atrasos logísticos e queda na satisfação do cliente.

Na página de Evolução e Tendência, a análise aprofunda o comportamento do negócio ao longo do tempo. São exploradas métricas de crescimento mensal e anual, comparação entre ano atual e ano anterior, variação mês a mês do GMV e a relação entre volume de pedidos e ticket médio. Essa camada permite identificar desacelerações, picos de crescimento e mudanças no padrão de consumo.

Por fim, a página de Operação e SLA conecta logística e resultado financeiro. A análise mostra como o percentual de pedidos atrasados evolui ao longo do tempo e como esses picos antecedem quedas no ticket médio e no GMV. Um mapa preenchido por estado evidencia regiões com maior média de dias de atraso, reforçando o impacto geográfico da operação na performance do negócio.

**Principais habilidades demonstradas no projeto:**

* Modelagem de dados em esquema estrela
* Criação de tabela calendário e uso avançado de time intelligence
* Desenvolvimento de métricas de GMV, crescimento MoM e YoY
* Análise de SLA e impacto operacional em indicadores financeiros
* Storytelling com dados e design de dashboards orientados a decisão

**Tecnologias utilizadas:**
Power BI, DAX, modelagem relacional, visualização de dados e análise exploratória.

## Fonte de dados e pipeline

Este dashboard faz parte do projeto **Ecommerce Shipping Analytics**, cujo foco inicial foi a exploração e tratamento dos dados de logística, vendas e reviews utilizando Python.

Os datasets utilizados estão disponíveis no arquivo `archive.zip` e foram obtidos no Kaggle através do link:
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)

A etapa de preparação dos dados (limpeza, análise exploratória e modelagem) foi realizada no repositório abaixo:

👉 [cidade-felipe/ecommerce-shipping-analytics](https://github.com/cidade-felipe/ecommerce-shipping-analytics)

Depois disso, estes dados foram usados para criar este dashboard no Power BI, com foco em storytelling, métricas de negócio e análise de operação (SLA).
