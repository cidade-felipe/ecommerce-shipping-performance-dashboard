```mermaid
flowchart LR
    A[**Fonte**<br/>● Kaggle (kagglehub)<br/>● Dataset Brazil Students Scholarship Prouni] --> B[**Ingestão**<br/>● Leitura do CSV com Pandas]

    B --> C[**Pré-processamento**<br/>● Renomeia colunas (padroniza nomes)<br/>● Remove nulos (dropna)<br/>● Remove colunas sensíveis (CPF, nascimento, código e-MEC)<br/>● Filtra idade (15–90)]

    C --> D[**Saída limpa**<br/>● Salva em data/prouni_2005_2019_processed.csv]

    C --> E[**Carregamento**<br/>● Lê CSV processado]

    E --> F[**Transformações**<br/>● Renomeia colunas legíveis<br/>● Remove “BOLSA COMPLEMENTAR 25%”<br/>● Cria “FAIXA DE IDADE”]

    F --> G[**Visualizações**<br/>● Plotly + ipywidgets<br/>● Sexo x tipo, Raça x tipo, Crescimento por período<br/>● Mapa por UF (GeoJSON local)]

    G --> H[**Exportação**<br/>● Salva gráficos em `figures/`]

```
